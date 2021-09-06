# C# Fundamentals


**1.** What is the purpose of a `namespace`?
<!-- enter you answer in the space below -->
```
It's a way of organizing and easily accessing code.
```
**2.** What is the difference between a `class` and a `struct`?
<!-- enter you answer in the space below -->
```
Class defines the reference types and stored in the heap and struct defines the value types and is stored in the stack.
```
**3.** What is the method that returns an instance of a class, yet it has no return type?
<!-- enter you answer in the space below -->
```
constructor
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
public
```
**6.** In the example what is `string` an indication of?
<!-- enter you answer in the space below -->
```
return type
```
**7.** In the example what is `abstract` preventing?
<!-- enter you answer in the space below -->
```
It prevents the class from being instantiated on its own.
```
**8.** In the example what is the purpose of `virtual`?
<!-- enter you answer in the space below -->
```
It can be overridden by a derived class at runtime.
```
**9.** Name four access modifiers:
<!-- enter you answer in the space below -->
```
public, private, internal, protected
```
**10.** If you set a class or method to private, what can access it?
<!-- enter you answer in the space below -->
```
code in the same class/struct
```