# OOPs-Essentials
## Classes and Objects

Before a BMW car was made, a blueprint was designed and given to factories. All vehicles were produced based on that blueprint. In this analogy, the **object** is each vehicle produced in the factory, and the **blueprint** is the **class**.

Similarly, in programming, an object represents an entity, and the class is the instruction to design that object. Functions defined within a class are called **methods**.

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
