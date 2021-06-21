![](https://learninfinity.info/wp-content/uploads/2017/05/Utilizing-browser-local-storage-for-client-site-script-in-any-web-application-1200x675.jpg)
___

# HISTORY OF LOCAL STORAGE:
> In the beginning, there was only Internet Explorer. Or at least, that’s what Microsoft wanted the world to think. To that end, as part of the First Great Browser Wars, Microsoft invented a great many things and included them in their browser-to-end-all-browser-wars, Internet Explorer. One of these things was called DHTML Behaviors, and one of these behaviors was called userData.

> userData allows web pages to store up to 64 KB of data per domain, in a hierarchical XML-based structure. (Trusted domains, such as intranet sites, can store 10 times that amount. And hey, 640 KB ought to be enough for anybody.) IE does not present any form of permissions dialog, and there is no allowance for increasing the amount of storage available.

> In the meantime, Brad Neuberg and others continued to hack away on dojox.storage to provide a unified interface to all these different plugins and APIs. By 2009, dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.

___
## what is HTML5 Storage:

> Simply put, it’s a way for web pages to store named key/value pairs locally, within the client web browser. Like cookies, this data persists even after you navigate away from the web site, close your browser tab, exit your browser, or what have you. Unlike cookies, this data is never transmitted to the remote web server (unless you go out of your way to send it manually). Unlike all previous attempts at providing persistent local storage, it is implemented natively in web browsers, so it is available even when third-party browser plugins are not.


### HTML5 STORAGE SUPPORT:

* IE 8.0+
* FIREFOX 3.5+
* SAFARI 4.0+
* CHROME 4.0+
* OPERA 10.5+
* ANDROID 2.0+

![](https://sites.google.com/site/azswiki/_/rsrc/1286362842741/html5-localstorage/localstorage_browser_support.jpg)

### USING HTML5 STORAGE:
> HTML5 Storage is based on named key/value pairs. You store data based on a named key, then you can retrieve that data with the same key. The named key is a string. The data can be any type supported by JavaScript, including strings, Booleans, integers, or floats. However, the data is actually stored as a string. If you are storing and retrieving anything other than strings, you will need to use functions like parseInt() or parseFloat() to coerce your retrieved data into the expected JavaScript datatype.

### HTML5 STORAGE IN ACTION:

> it uses the localStorage object to save whether there is a game in progress (gGameInProgress, a Boolean). If so, it iterates through the pieces (gPieces, a JavaScript Array) and saves the row and column number of each piece. Then it saves some additional game state, including which piece is selected (gSelectedPieceIndex, an integer), whether the piece is in the middle of a potentially long series of hops (gSelectedPieceHasMoved, a Boolean), and the total number of moves made so far (gMoveCount, an integer).

# FURTHER READING:

**HTML5 storage:**
* HTML5 Storage specification.
* Introduction to DOM Storage on MSDN.
* Web Storage: easier, more powerful client-side data storage on Opera Developer Community.
* DOM Storage on Mozilla Developer Center. (Note: most of this page is devoted to Firefox’s prototype implementation of a globalStorage object, a non-standard precursor to localStorage. Mozilla added support for the standard localStorage interface in Firefox 3.5.)

* Unlock local storage for mobile Web applications with HTML5, a tutorial on IBM DeveloperWorks.

**Early work by Brad Neuberg et. al. (pre-HTML5):**
* Internet Explorer Has Native Support for Persistence?!?! (about the userData object in IE)
* Dojo Storage, part of a larger tutorial about the (now-defunct) Dojo Offline library
* dojox.storage.manager API reference
* dojox.storage Subversion repository



![](https://www.kirupa.com/things_to_do_with_data/images/object_144.png)