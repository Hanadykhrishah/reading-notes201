# Domain modeling:

**is the process of creating a conceptual model in code for a specific problem.**

* The new keyword instantiates (i.e. creates) an object.
* The constructor function initializes properties inside that object using the this variable.
* The object is stored in a variable for later use.

> summary: When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.

> Model its attributes with a constructor function that defines and initializes properties.

> Create instances using the new keyword followed by a call to a constructor function.

> Store the newly created object in a variable so you can access its properties and methods from outside.

> Use the this variable within methods so you can access the object's properties and methods from inside.

___

# Table :

**A table represents information in a grid format.**

Basic Table Structure :

* table tag.
* table row You indicate the start of each row using the opening <tr> tag.
* table data.

![](https://cdn.educba.com/academy/wp-content/uploads/2019/10/Create-Tables-in-HTML.png)
___


#  CREATING OBJECTS USING CONSTRUCTOR SYNTAX:

![](https://miro.medium.com/max/3108/1*EmDT5rILBeTia4yPy0JyYw.png)

**On the right, an empty object called hote 1 is created using the constructor function. Once it has been created, three properties and a method are then assigned to the object. 
(If the object already had any of these properties, this would overwrite the values in those properties.) To access a property of this object, you can use dot notation, 
just as you can with any object. For example, to get the hotel's name you could use: 
hotel .name Similarly, to use the method, you can use the object name followed by the method name:hotel.checkAvailability()**

### THIS (IT IS A KEYWORD) 
The keyword this is commonly used inside functions and objects. 
Where the function is declared alters what this means. It always refers 
to one object, usually the object in which the function operates.


![](https://fireship.io/courses/javascript/img/js-object-props.png)















