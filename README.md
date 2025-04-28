// Abstract class
abstract class Animal {
    // Abstract method
    public abstract void makeSound();
}

// Derived class Dog
class Dog extends Animal {
    @Override
    public void makeSound() {
        System.out.println("Dog barks: Woof Woof!");
    }
}

// Derived class Cat
class Cat extends Animal {
    @Override
    public void makeSound() {


output-Dog barks: Woof Woof!
Cat meows: Meow Meow!
