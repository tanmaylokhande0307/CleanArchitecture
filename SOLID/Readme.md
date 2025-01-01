## SOLID

### S - Single Responsibility Principle
Single-responsibility principle (SRP) states that "There should never be more than one reason for a class to change." In other words, every class should have only one responsibility.  

### O - Open Closed Principle
A software artifact should be open for extension but closed for modification
Higher level comoponents in the hierarchy are protected from the changes made to lower level components

### L - Liskov Substitution Principle
If for each object o1 of type S there is an object o2 of type T such that for all Programs P defined in terms of T, the behaviour of P is unchanged when o1 is substituted with o2 then S is the subtype of T
subclasses can replace their superclasses without altering the program's behavior or introducing errors

### I - Interface Segeration Principle
clients should not be forced to depend upon interfaced that they do not use

### D - Dependency Inversion Principle
Most flexible systems are those in which the source code depenedencies refer only to the abstractions and not on concretions
