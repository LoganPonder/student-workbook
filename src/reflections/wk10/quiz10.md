# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
Namespace's provide scope to the identifiers inside a region of a program. Organizing code and preventing collisions.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Structs are light versions of classes. Structs are value types while classes are reference types. Structs can not inherit from another struct/class, structs cannot be the base of another class
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
You can use VOID as a return type as it doesn't return a value.
```
## Example 1
```c#
abstract class Car
{
  ...
  public virtual string Start()
  {
    return "Vroooom";
  }
}
```
**5.** In the example what is the access modifier of the `Start()` method?
<!-- enter you answer in the space below -->
```
Public, meaning it can be accessed by other code
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
It indicates what data type will be returned 
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
An abstract class prevents the class from being instantiated.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
A virtual can be changed by an overriding member in a derived class
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, protected, internal
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
If private, it can only be accessed by code in the same class/struct
```