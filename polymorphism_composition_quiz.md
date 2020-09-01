# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
- It means having 'many forms', and occurs when there are mulitple classes that are related to each other 

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
- When a parent class reference is used to refer to a child class object. 

3. What can we use to implement polymorphism in Java?
- We can use interfaces to implement polymorphism in Java.

4. How many 'forms' can an object take when using polymorphism?
- Two forms

5. Give an example of when you could use polymorphism.
- When creating an Array list of related types. For example, if we wanted to create an array list of vehicles (car, motorbikes etc),  we could do that using polymorphism by creating a parent class called vehicle, then sub-classes of vehicle (car, motorbike etc).


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
- Composition referes to an is-a-part-of relationship where an object is made up, or composed of one or more other objects

7. When would you use composition? Provide a simple example in Java.
- If there was a class called House, it might be made up of other class objects such as Roof. This roof object is part of the House class and cannot exist without the house.

8. Give a difference between composition and aggregation?
- Aggregation is similiar to composition but with aggregation, objects can exist independently from each other. It refers to a has-a relationship. where an object has other objects.

9. What is/are the advantage(s) of using composition/aggregation?
- More flexibility than inheritance. Can only extend one class in Java but can do this with composition. it also increases the re-usability of the code.


10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
- All objects that it owns, or is composed of, are also destroyed along with it

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
- When the owning object is destroyed, the objec tthat it 'owned' will still exist