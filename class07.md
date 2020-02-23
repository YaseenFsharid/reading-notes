# Domain modeling 
_Is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. **An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model_.**

A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams._

**Here's some tips to follow when building your own domain models.**
1. _When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors._
2. _Model its attributes with a constructor function that defines and initializes properties._
3. _Model its behaviors with small methods that focus on doing one job well._
4. _Create instances using the new keyword followed by a call to a constructor function._
5. _Store the newly created object in a variable so you can access its properties and methods from **outside**._
6. _Use the this variable within methods so you can access the object's properties and methods from **inside**._


## tables
_table is a way to display content in grid format example about table sports result_

To create table we have three tages:
+ < table> </ table> is used to create a table and the content of the table is written row by row. 
+ < tr> < /tr> it stands for table row and its used to create a new row in the table
+ < td > </ td> is used to create a table coloumn and its stand for table data once the first row ends another one will filled vertically
+ we can merger to rows by using rowspan proparity and we can also using colspan to marge the table data in one cell of the table.
+ **we have < thead > table head that contains the header information**
+ **we have also < tbody> tag that contains the main vlaues data in the middle of the table**
+ **another thing is < tfooter> stands for table footer and it contains the final result of the table like score**
_we can use the borders in the table and control the desgin of the table by it_



## objects 
+ _objects in java script is used to create an entity that have its own proparited and methods_
+ _proparites is the actual status of the object ( which means what that object do )_
+ _Methods are a function proparity that is used to excute some inststuction that we want to make_
+ _Fuction helps us to make some event in the web pages_

_actually the access of the proparites done by . notaion_
_we need an object call to access the object and this is done by object.proparityname=something_

