# Software Design Methodologies

## 1. What do we mean by coupling and cohesion when discussing structured design?

Cohesion refers to how much properties in a class 'truly' belong together. A highly cohesive module would be a module that is made up of properties that a tightly related to eachother in purpose.

Coupling refers to how dependent a module is to another module. Loosely coupled modules are desired as they are easier to change and more modular to test.

## 2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

With a top down approach an overview of the system is created and the finer details are refined until the entire system is planned. An advantage of this approach is that it means that planning can progress quickly in the early stages because you don't get bogged down by implementation details.

With a bottom-up design approach fleshing out the details of the systems modules is prioritised. And then these detailed modules are put together for the final system. An advantage of this is that your code will be more modular as a circumstance leading to easier testing.

## 3. In which design methodology would a class diagram be most useful?

Class diagram is most useful for object oriented design.

## 4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

**Encapsulation** - Binding together data and the functions that manipulate them, can lead to data abstraction and looser coupling.

**Abstraction** - Only displaying the essential information and higind the details. Achieved by using predefined interfaces to interact with objects.

**Polymorphism** - Functions and operators can take many forms. Function overloading is multiple functions have the same name but have different input arguments. Operator overloading when operators are used differently depending on the data types, for example '+' can be used to add to numbers or concatenate 2 strings.

**Inheritance** - This is the capability of a class to inherit properties and methods from another class.

## 5. What is the strategy pattern? How would its implementation differ between a functional and object oriented system?

Behaviour of an application is dynamically selected at runtime depending on the specific context. 

In object oriented design this can be achieved by creating a strategy superclass, which has a number of subclasses that have the same signature and method signature but differing internal logic. And creating a context object which is what the user will be interacting with. The context objects uses a strategy object that is dynamically selected.

In functional programming it is similar except that higher order functions will be used instead of classes.

## 6. Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision.

I would suggest using the MVC design pattern. The SQL database can be used to store the different sales/orders with the relevant columns such as (sale_price, item_type). The models will interact with the database and will need litte knowledge of how the database operates internally. The controller will hanlde the requests from the front end users and the view will be the portal the user uses to complete their payments. The advantages of this design pattern are that it maintains single responsibility and code modularity, and if you wanted to add items from a different sector it would be simple and the system is loosely coupled.
