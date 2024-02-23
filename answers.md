# Software Design Methodologies

## 1. What do we mean by coupling and cohesion when discussing structured design?

Cohesion refers to how much properties in a class 'truly' belong together. A highly cohesive module would be a module that is made up of properties that a tightly related to eachother in purpose.

Coupling refers to how dependent a module is to another module. Loosely coupled modules are desired as they are easier to change and more modular to test.

## 2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

With a top down approach an overview of the system is created and the finer details are refined until the entire system is planned. An advantage of this approach is that it means that planning can progress quickly in the early stages because you don't get bogged down by implementation details.

With a bottom-up design approach fleshing out the details of the systems modules is prioritised. And then these detailed modules are put together for the final system. An advantage of this is that your code will be more modular as a circumstance leading to easier testing.
