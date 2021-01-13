# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

The word comes from the Greek words 'poly' meaning 'many' and 'morph' meaning 'change'. When we talk about something being 'polymorphic' we mean it can have many forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
One example would be a class which could be a term for many classes but are still a type of that single class - e.g a student and instructor are both people.


3. What can we use to implement polymorphism in Java?
We can use polymorphism in Java by using an abstract class and creating a super class which all the classes we want to treat as being the same can inherit from.

4. How many 'forms' can an object take when using polymorphism?
As many as we want to define in the code.

5. Give an example of when you could use polymorphism.

When we have an abstract 'Vehicle' super class which contains a colour and make of a type of car. This would then be inherited by the subclasses (eg. motorbike, car etc.)



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
Composition is where an object is made up of one or more other objects.

7. When would you use composition? Provide a simple example in Java.
When describing if something 'has a' something and is composed of other objects, each with their own state and behaviour. eg. a car has a gearbox

8. What is/are the advantage(s) of using composition?
Using composition means that we can change the behaviour of an object, simply by swapping one component for another. For example, we can change the behaviour of the Car's start method simply by swapping a Car's engine for a different engine with a different start method.

9. When an object is destroyed, what happens to all the objects it is composed of?

The composed objects can still exist.

