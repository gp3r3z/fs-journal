# C# Fundamentals

**1.** What is the purpose of a `namespace`?

<!-- enter you answer in the space below -->

```
  Provides a scoped area of like data .
```

**2.** What is the difference between a `class` and a `struct`?

<!-- enter you answer in the space below -->

```
 Classes are references types and struct is a value type.
```

**3.** What is the method that returns an instance of a class, yet it has no return type?

<!-- enter you answer in the space below -->

```
  A void method has no return type. 
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
 The access modifier is public 
```

**6.** In the example what is `string` an indication of?

<!-- enter you answer in the space below -->

```
 The value keyword 'string' indicates the value being assigned 
```

**7.** In the example what is `abstract` preventing?

<!-- enter you answer in the space below -->

```
The abstract additional is the process to prevent the internal data shown and only allow access to functionality. 
```

**8.** In the example what is the purpose of `virtual`?

<!-- enter you answer in the space below -->

```
 The Virtual keyword is used to allow modification by the child class. 
```

**9.** Name four access modifiers:

<!-- enter you answer in the space below -->

```
   The four most common are : 
    + Public 
    + Private
    + Protected 
    + internal 
```

**10.** If you set a class or method to private, what can access it?

<!-- enter you answer in the space below -->

```
Only code in the same class or a class that is derived from that class. 

```
