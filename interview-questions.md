# Scala Interview Questions

## General
1. What do you like about Scala?  What do you dislike?

2. Functional programming values mutability.  Why is this a good thing?  Are there any cases where being immutable is ok or prefered?

## Functions
1. Scala is functional/OO hybrid language.  One of the most important ideas of a functional langauge is that a function is a "first class citizen".  What does that mean?

2. What is a higher-order function?

3. There are two methods for composing functions.  What are they?
  1. How are they different?

4. What is a Partial Function?
  1.  What happens when you 'lift' a partial function?

5. What is a Partially Applied Function?

6. What is currying?

## Data Structures

1. There a two primary ways to create an immutable List in Scala, what are they?

2. Scala has the datatype `Option`.  What is it used for?  Why is it better than null?


## Design and Language Constructs
1. What is the difference between a `trait` and a `class`?

2. What is a `sealed trait`?  When would you use one?

3. In Scala, when we refer to pattern matching, what does that mean?

4. In Scala, there is a construct known as a "for comprehension" which can be used to loop over a collection.  However, it is far more powerful than that. What is its use outside of iteration.


## Functional Paradigms
1. Many data structures in Scala have a `map` function. What does `map` do from a general standpoint?

2. Many of the structures that have a `map` function also have a `flatmap` function as well.  What does `flatmap` do?  How is it different than `map`?

3. The structures with both `map` and `flatmap` have a special term that describes them relative to functional programming.  What is that term?

4. What is a type class?  Give me an example of a good use of a type class.

## Specific frameworks
1. ScalaZ has the concept of the `\/` sometimes refered to as a disjunction.  What data structure in Scala is disjunction analagous too?  What makes the disjunction different from its Scala conterpart?

2. What is the primary data structure of the Akka framework?

3. Are Akka Actors presently type safe?
