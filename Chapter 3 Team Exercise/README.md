# This folder is corresponding to the exercises done at the final of chapter 3.. #


## The following are the written answers to the first two exercises. ##

1. Why do testers automate tests? What are the limitations of automation?

>The main reason of why testers use automated methods is quite easy, and that is because manual testing takes a lot of hours of work whilst automation can turn those thousands of hours in something as simple as clicking a single button. 
Even though automated testing is something that makes the general testing of a program simple, it comes with certain caveats. The first of this is that of the development time, meaning that for testing a program, the tester needs to build a system, or code a program that tests all the possible results that the original program has. Another reason can be that sometimes tests can fail, which turns out to be a bigger problem than not doing testing at all because wrong testing can confuse the developers and throw a wrench into the development.

2. Give a one-to-two paragraph explanation for how the **inheritance** hierarchy can affect controllability and observability.

>In Object oriented programming, inheritance is the mechanism in charge of having an object or class being based up of other object or class. This means that one class or object takes most of the details, of the other. This can cause issues with controllability and observability. This can be said because these two methods are based on seeing in how the code is done and how it runs and inheriting sometimes makes things more hidden or confusing.

3. Develop JUnit tests for the *BoundedQueue* class. A compilable version is available on the book website in the file *BoundedQueue.java*. Make sure your tests check every method, but we will not evaluate the quality of your test designs and do not expect you to satisfy any test criteria. Turn in a printout of your JUnit tests and either a printout or a screen shot showing the results of each test.

> BoundedQueue class can be found in this repo.

4. Delete the explicit throw of *NullPointerException* in the Min program (Figure 3.2). Verify that the JUnit test for a list with a single null element now fails.

> When using MinTest.java class to test Min.java as it was in Figure 3.1 (Without removing any line), one can notice how Min successfully runs through all the tests. However, when the explicit NullPointerException throw in line 13 is removed, Min class fails to complete the testForSoloNullElement test. 

> ![alt text](https://raw.githubusercontent.com/ferpart/WeAreHungry/master/Chapter%203%20Team%20Exercise/src/junitTests/mintest%20success.PNG "Success Test") ![alt text](https://raw.githubusercontent.com/ferpart/WeAreHungry/master/Chapter%203%20Team%20Exercise/src/junitTests/mintest%20failure.PNG "testForSoloNullElement Failure test") 

