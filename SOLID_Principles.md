### SOLID Principles

The SOLID principle was introduced by <b>Robert C. Martin</b>, also known as Uncle Bob.(not king Bob !😂)

#### S -> Single Responsibility Principle (SRP)
#### O -> Open/Closed Principle
#### L -> Liskov’s Substitution Principle (LSP)
#### I -> Interface Segregation Principle (ISP)
#### D -> Dependency Inversion Principle (DIP)

The SOLID principle helps in reducing tight coupling. Loosely coupled classes minimize changes in your code, helps in making code more reusable, maintainable, flexible and stable.

S -> One class should have one purpose. <br />
O -> Entities can be open for extension but closed for modification. <br />
L -> Child class could be replaced in place of parent class.(parent - rectangle, child - square [rectangle with equal edges]) <br />
I -> Only required functionality of interface should be present in a class, interfaces should only have single purpose. <br />
D -> High Level modules should not depened on low level modules, it makes it tightly coupled, tv remove is depenedent on battery but not on brand of battery. <br />

Tight Coupling Leads to :-
- Extra Time to implement any new requirements, feature or bug fixes and may result to unknown issues.
- Duplicate Code, Code which is not testable, Fixing old bug result in new bug, unknown issue.

Things Needed for creating a successful application
1. Architechture
2. Design Patterns
3. Design Principle (SOLID)
