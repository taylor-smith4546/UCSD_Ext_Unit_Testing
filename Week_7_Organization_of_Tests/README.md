# UCSD Extension: Unit Testing: Supporting Modern Software Development Methods

## Videos: 

[Lecture 7: Organization of Tests](URL link here)

## Assignment/Classwork:

Quiz #7 (Canvas)

Exercise #1:

Test Data Builder

The listing below shows the Transaction class. It is a simple POJO with no logic but only getters
and setters methods (which have been omitted in the listing to make it shorter).

Transaction Class:
```java
public class Transaction {
 private long id;
 private State state;
 //There are four possible values of the state field - PROCESSING, OK, CANCELLED, ERROR.
 private boolean retryAllowed;
private String message;
 private String billingId;
 // getters and setters omitted
 ...
}
 ```
 
 Write a test which creates a number of objects of the Transaction class using the Test Data Builder
 pattern. Compare the result with the "normal" approach of creating objects directly within your test
 code (using their constructor and setters).
 


## Topics Covered: 

o	Package for test classes

o	Naming tests consistently

o	BDD: ‘Given’, ‘When’, ‘Then’

o	Writing maintainable tests


## Supplementary Items (Please Read!)

[Getting more out of your units tests](https://www.slideshare.net/wakaleo/junit-kung-fu-getting-more-out-of-your-unit-tests)

[Mockito - How to write good tests](https://github.com/mockito/mockito/wiki/How-to-write-good-tests)

[Mockito annotations](https://www.baeldung.com/mockito-annotations)

[ObjectMother Patterns - Martin Fowler](https://www.martinfowler.com/bliki/ObjectMother.html)

[Factory Patterns](https://www.tutorialspoint.com/design_pattern/factory_pattern.html)

[Test Data Builders](https://projectlombok.org/features/Builder)




