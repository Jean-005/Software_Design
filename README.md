# Software Design Methodologies

## Structured 
## Function oriented design
## Object oriented design

_What do we mean by coupling and cohesion when discussing structured design?_

Coupling describes the relationships between modules, more specifiacally the degree of interdependence between different software modules. There are two levels of coupling: high and low.

**High coupling**: This is when modules are tightly intertwined,any change in one module can shave a significant impact on another. Thus makeing the system fragile and difficult to modify.

**Low coupling**: This is when modules are independent of each other and rely on well-defined interfaces to interact. Any change in one module has minimal impact on another thereby promoting modularity and maintainability.

Cohesion, on the other hand, describes the relationships within the modules. This is the degree to which elements that are within a single module relate and work together towards a specific goal.
There are also two levels of cohesion: high and low.

**High cohesion**: This is when elements within a module are tightly focused and perform a single and well-defined task thereby making the module easier to understand, test, and maintain.

**Low cohesion**: This is when elements within a module are loosely related and perform unrelated tasks. This is something that can lead to confusion, difficulty in testing, and increased complexity.

In conclusion, a well-designed system will strive for low coupling and high cohesion.


_What is the difference between top-down and bottom-up design? Which best describes a function oriented design?_

Top-down and bottom-up design are two contrasting approaches to problem-solving and system development software engineering. These approaches differ in their starting point and overall direction.

**The top-down** mainly focuses on high-level planning and decision-making. It starts with a high-level overview of the system/problem then it breaks this down into smaller, well-defined and more manageable components. 

**The bottom-up** approach, on the other hand, focuses on the implementation and execution of individual tasks. It starts with individual components/building blocks and it intergrates these to form a more complex system.

**Top-down design** describes a function oriented design more closely given that it also emphasises breaking down a problem into smaller and well-defined functions that perform specific tasks.


_In which design methodology would a class diagram be most useful?_

A class diagram would be most useful in the object-oriented design methodology especially given that classes are the fundamental building blocks in object-oriented design.

_What are the four pillars of object oriented programming? Give a single-sentence description of each_

**1. Abstraction:** Principle focuses on hiding unnecessary details and showing only essential details of an object to the user.

**2. Encapsulation:** Principle involves the bundling together of data (attributes) and methods (functions) within a class. 

**3. Inheritance** Principle allows the creation of new classes (subclasses) that inherit properties and behaviors from existing classes (parent classes).

**4. Polymorphism:** Principle allows objects of different classes to respond diffferently to the same method call. 

_What is the strategy pattern? How would its implementation differ between a functional and object oriented system?_

**The strategy pattern** also referred to as the policy pattern is a behavioral software design pattern that allows for the selection of an algorithm at runtime. Instead of implementing a single algorithm directly, the code receives run-time instructions as to which in a family of algorithms to use based on specific conditions.

**Its implementation would differ between an object oriented system and a functional** in that in an object-oriented system strategies are implemented as separate classes inheriting from the common strategy interface whereas in a functional system strategies are implemented as separate functions with the same signature.

While both systems (object oriented and functional) achieve the same outcome of dynamically choosing and using algorithms - they differ in their implementation. The object-oriented system relies on classes and inheritance to define and select strategies whereas the functional system leverages functions and higher-order functions for strategy implementation and selection.


_Imagine your is creating a new online payment system. In order to gain maximum market share it can't be tied to a particular sector - it needs to work just as well when ordering a takeaway as when buying a new coat. Which design methodology would you suggest following? Give some justification for your decision._

I believe that **object-oriented design** would be the most suitable choice for creating a new online payment system that can be applied in several different sectors. The reasons for this are as follows:

1. The object-oriented design methodology allows modeling entities like customers, orders, and transactions as objects, making it easier to represent and manage diverse payment scenarios across various sectors. 

2. It also enables the reuse of code through inheritance and polymorphism - crucial for functionalities such as payment processing, user authentication, and transaction management. These can be implemented in reusable classes that can be extended for specific sector needs through subclasses. 

3. In addition,the object-oriented design methodology encourages the encapsulation of data and methods within objects leading to well-organised and maintainable code, important for when the system has to expand to handle new sectors.

4. Finally, the object-oriented design methodology facilitates scalability by allowing the addition of new functionalities and integrations through inheritance and composition of existing objects. This would allow the payment system to adapt to diverse sectoral requirements without major code restructuring.




