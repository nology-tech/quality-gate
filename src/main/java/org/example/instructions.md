# Java Assessment Questions

## Question 1: Warm-up - WarmUp Class

Write a simple Java program that declares an array of 10 integers, populates it with numbers from 1 to 10, and then prints them out in reverse order.  This can be done in the Main class.

## Question 2: Vehicle Class, Car Class & Bicycle Class

Create a simple class hierarchy:

- A Vehicle superclass with properties like speed and color.
- Two subclasses: Car and Bicycle.
- Car should have additional properties like numberOfDoors and a method honk().
- Bicycle should have an additional property like numberOfGears and a method ringBell().
- Instantiate objects of Car and Bicycle, set their properties, and call their respective methods.

## Question 3: VehicleUtility Class

Given a List of Vehicle objects (both Car and Bicycle), write a function that:

- Filters out all Bicycles.
- Sorts Car objects based on their speed in descending order.
- Returns the sorted list.

## Question 4: Exception Handling - Create your own

Extend the above code by adding functionality where:

- Setting a negative speed for any vehicle throws a custom exception named InvalidSpeedException.
- The main function should catch this exception and print a user-friendly message without terminating.

## Question 5: - Discussion 

Briefly explain the difference between == and equals() in Java. Demonstrate a short example showcasing this difference.

## Question 6: JUnit & Testing - 

You will be provided with a basic Vehicle utility class outline. Your task is to select three methods from the provided list, write JUnit tests for them first, and then implement the methods to make the tests pass.

- getFastestVehicle:
    - Description: This method should take a list of vehicles and return the vehicle with the highest speed.
    - Edge Cases to Test: Empty list, multiple vehicles with the same top speed.

## Question 7: Feedback and Q&A 

Allow the developer to ask any questions or clarify any doubts. This session also provides insight into their thought process and how they approach problem-solving.
