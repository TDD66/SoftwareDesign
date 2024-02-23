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

