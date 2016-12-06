## What Are Tests?
Tests are ways of testing our code to see if they are performing the way we have intended it behave.

# Example
 For example, lets say we wanted to create a program that models an orange tree.  Well, what defines an orange tree to us? Is it safe to say that we need at least two objects, an orange object and a tree object? Can our tree mature and bear more fruit at a certain age? Could our oranges ripen and fall from the tree?  Sounds like the list can become lengthy right? Lets stop here for a few minutes and see what we need to fulfill these user stories.  

# What We Need To Test?
* Remember that we need to model an orange and a tree, so we know that there are two objects that needs to be created.
* We could say that the tree will not bare fruit until it matures at one year of age and then it well bare an X amount of oranges.  We would need a test to test if the tree ages and a test to see if the tree has created an X amount of oranges once it has matured.
* How do we determine if an orange is ripe? Well, we can have oranges age and if it is at least 30 days old, then it will fall from the tree.  We would need to write a test to check for ripeness and a test to check if it falls at ripeness.

# Now That We Have Tests
You could think of tests as a requirement list.  Every time a change is made we want to test to see if our code still meets those requirements. For example, as our program becomes increasingly complex and we want to have our tree to have a certain lifespan, would it make sense for our tree to continue to create oranges after exceeding that lifespan?   

# Why Is It Important That We Test?
For situations like our tree's lifespan is a prime example of why tests are important.  As our program become more complex over time the tests tells us that a basic requirement is not fulfilled and needs to be addressed.  Can you imagine looking at pages and pages of code that was written by someone else or many years ago without a way to trace exactly where the bug is?  Tests can help!
