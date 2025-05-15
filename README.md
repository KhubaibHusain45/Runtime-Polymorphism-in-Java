My code is a perfect example of Run-Time Polymorphism in Java.

Animal is the parent class with a method sound().
Dog and Cat are child classes that override the sound() method with their own behavior.

Even though the reference type is Animal, Java decides at runtime which sound() method to call based on the actual object (Dog or Cat).
This is runtime polymorphism (a.k.a. dynamic method dispatch).

My code demonstrates:
1-Method Overriding
2-Upcasting
3-Runtime Polymorphism
