# OOPs-Essentials
## Classes and Objects

Before a BMW car was made, a blueprint was designed and given to factories. All vehicles were produced based on that blueprint. In this analogy, the **object** is each vehicle produced in the factory, and the **blueprint** is the **class**.

Similarly, in programming, an object represents an entity, and the class is the instruction to design that object. Functions defined within a class are called **methods**.

`Class` is a user-defined data type which defines its properties and its functions. Class is the only logical representation of the data. For example, Human being is a class. The body parts of a human being are its properties, and the actions performed by the body parts are known as functions. The class does not occupy any memory space till the time an object is instantiated.

`Object` is a run-time entity. It is an instance of the class. An object can represent a person, place or any other item. An object can operate on both data members and member functions.

- Class names start with an uppercase letter.
- Object names start with a lowercase letter.
```
class Pen {                      //class
    String color;
    Integer cost;
     public void write () {
        System.out.print("Write something");
     }
}

{
    public static void main(String [] args)
        {
            Pen pen1 = new Pen (); //object
            pen1.color = "blue";
            pen1.cost = 20;

            pen1.write();
        }
}
```
