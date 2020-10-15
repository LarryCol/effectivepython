## Chapter 1: Pythonic Thinking
The Python community has come to use the adjective Pythonic to describe code that follows a particular style. 
The idioms of Python have emerged over time 
through experience using the language and working with others. 
his chapter covers the best way to do the most common things in Python.

  1 Know Which Version of Python You’re Using
  
  2 Follow the PEP 8 Style Guide
  
  3  Know the Differences Between bytes and str
   
   4 Prefer Interpolated F-Strings Over C-style Format Strings and str.format
  
  5 Write Helper Functions Instead of Complex Expressions
   
   6 Prefer Multiple Assignment Unpacking Over Indexing
   
   7 Prefer enumerate Over range
   
   8 Use zip to Process Iterators in Parallel
  
  9 Avoid else Blocks After for and while Loops 
  
   10 Prevent Repetition with Assignment Expressions
## Chapter 2: Lists and Dictionaries
In Python, the most common way to organize information is in a sequence of values stored in a list. A list‘s natural complement is the dict that stores 
lookup keys mapped to corresponding values. 
This chapter covers how to build programs with these versatile building blocks.

   11 Know How to Slice Sequences
   
   12 Avoid Striding and Slicing in a Single Expression
    
   13 Prefer Catch-All Unpacking Over Slicing
    
   14 Sort by Complex Criteria Using the key Parameter
    
   15 Be Cautious When Relying on dict Insertion Ordering
    
   16 Prefer get Over in and KeyError to Handle Missing Dictionary Keys
    
   17 Prefer defaultdict Over setdefault to Handle Missing Items in Internal State
    
   18 Know How to Construct Key-Dependent Default Values with __missing__
## Chapter 3: Functions
Functions in Python have a variety of extra features that make a programmer’s life easier. Some are similar to capabilities 
in other programming languages, but many are unique to Python. 
This chapter covers how to use functions to clarify intention, promote reuse, and reduce bugs.

   18 Never Unpack More Than Three Variables When Functions Return Multiple Values
    
   19 Prefer Raising Exceptions to Returning None
    
   20 Know How Closures Interact with Variable Scope
    
   21 Reduce Visual Noise with Variable Positional Arguments
    
   22 Provide Optional Behavior with Keyword Arguments
    
   23 Use None and Docstrings to Specify Dynamic Default Arguments
    
   24 Enforce Clarity with Keyword-Only and Position-Only Arguments
    
   25 Define Function Decorators with functools.wraps
## Chapter 4: Comprehensions and Generators
Python has special syntax for quickly iterating through lists, dictionaries, and sets to generate derivative data structures. 
It also allows for a stream of iterable values to be incrementally returned by a function. 
This chapter covers how these features can provide better performance, reduced memory usage, and improved readability.

  26 Use Comprehensions Instead of map and filter
  
  27 Avoid More Than Two Control Subexpressions in Comprehensions
  
  28 Avoid Repeated Work in Comprehensions by Using Assignment Expressions
  
  29 Consider Generators Instead of Returning Lists
  
  30 Be Defensive When Iterating Over Arguments
  
  31 Consider Generator Expressions for Large List Comprehensions
  
  32 Compose Multiple Generators with yield from
  
  33 Avoid Injecting Data into Generators with send
  
  34 Avoid Causing State Transitions in Generators with throw
  
  35 Consider itertools for Working with Iterators and Generators
## Chapter 5: Classes and Interfaces
Python is an object-oriented language. Getting things done in Python often requires writing new classes and 
defining how they interact through their interfaces and hierarchies. 
This chapter covers how to use classes to express your intended behaviors with objects.

  36 Compose Classes Instead of Nesting Many Levels of Built-in Types
  
  37 Accept Functions Instead of Classes for Simple Interfaces
    
  38 Use @classmethod Polymorphism to Construct Objects Generically
    
  39 Initialize Parent Classes with super
    
  40 Consider Composing Functionality with Mix-in Classes
    
  41 Prefer Public Attributes Over Private Ones
    
  42 Inherit from collections.abc for Custom Container Types


