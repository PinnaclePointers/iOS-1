Categories
==========

Objective-C allows programmers to dynamically augment the capability of compiled classes at run-time by using categories. 

Categories allow a programmer to dynamically mix-in new methods to an object at run-time. 

These methods have full access to all instance variables of the objects.

Categories do not, however, allow the programmer to dynamically add new instance variables. To do this, the class in question must be subclassed.

The NSString+Reverse class provides a simple demonstration of how to use categories in Objective-C.
