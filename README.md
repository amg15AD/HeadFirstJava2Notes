# HeadFirstJava2Notes
Objects live in the heap while methods & local variables live in the stack.
Instant variables live within the object they belong to, on the heap.

If you want a no-arg constructor, and you've already put in a constructor with arguments, you'll have to build the no-arg constructor yourself. Always try to provide one to make it easy for programmers to make a working object.
Overloaded constructors mean you have more than one constructor in your class.
You cannot have two constructors with the same argument lists. An argument list includes the order and/or type of arguments.
Instance variables are assigned a default value, even when you don't explicitly assign one. The default values are 0/0.0/false for primitives, and null for references.
when inheriting a parent constructor you must always pass super as the first statement.
When you set a reference to null you are deprogramming the reference 

Static methods can't use nonstatic instant variables and they can't use nonstatic methods either
Static final variables are constants
public static final double PI = 3.141592653589793;
final variable can't change its value 
final method can't be overridden
final class means you cant extend, make a sub-class

If you have a class with only static methods, and you do not want the class to be instantiated, you can mark the constructor private.
