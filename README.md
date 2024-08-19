# 4.1 PiggyBank

## Java Documentation
[Classes and Objects](https://docs.oracle.com/javase/8/docs/api/java/lang/Class.html)

## Java Tutorials
[Classes and Objects](https://runestone.academy/ns/books/published/apcsareview/JavaBasics/toctree.html)

## Assignment:
1. Create your own PiggyBank class. This class will be used to create PiggyBank objects;
therefore, everyone can have their own piggy bank! When your personal bank is created
(instantiated), it may be stuffed with a certain number of pennies, nickels, dimes, and
quarters. You will be able to access the number of each type of coin deposited into the bank as
well as the bank’s total dollar value. You will also need to create methods that will allow the
piggy bank to receive coins and update the appropriate values.


Here are some thoughts about what your class needs:
- An instance variable for each of the following coins: pennies, nickels, dimes and
quarters.
- Constructors. There should be a default constructor that can create a brand new piggy
bank without anything in it as well as a constructor that can accept initial values of
each coin denomination. Would there be any other constructors that could come in
handy?
- Getter methods for returning the number of each type of coin currently in the bank.
- A method or methods that will receive more coins and add them to the total. Think
about the easiest way for your client to input the values. Would it be easiest to have
one method that inputs all the values at once? What if the client only has a bunch of
nickels? Or nickels and quarters? Keep these thoughts in mind when designing your
methods.
- A method to calculate the total value of the coins currently in the bank. Should this
method print the value directly, or should it simply return the value and let the client
deal with the data?
