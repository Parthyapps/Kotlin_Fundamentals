# Kotlin Overview
Kotlin is a statically typed programming language that runs on the Java Virtual Machine (JVM).
It was developed by JetBrains, the same company behind IntelliJ IDEA, Kotlin's preferred IDE.

# Kotlin Fundamentals
- **1.Conciseness**: Kotlin reduces boilerplate code compared to Java. It achieves this through features like type inference, smart casts, data classes, and more.
- **2.Null Safety**: Kotlin's type system distinguishes between nullable and non-nullable types, helping to eliminate the dreaded NullPointerException. You must explicitly specify when a variable can hold a null value.
- **3.Extension Functions**: Kotlin allows you to add new functions to existing classes without modifying their source code. This feature enhances code readability and reusability.
- **4.Interoperability**: Kotlin is fully interoperable with Java. You can use Kotlin code in existing Java projects and vice versa, which makes adoption easier, especially in legacy codebases.
- **5.Coroutines**: Kotlin provides first-class support for coroutines, which are lightweight threads that help manage asynchronous code. Coroutines simplify complex asynchronous programming tasks, making code more readable and maintainable.
- **6.Data Classes**: Kotlin's data classes automatically generate equals(), hashCode(), toString(), copy(), and componentN() methods based on properties defined in the primary constructor. This feature is especially useful for modeling immutable data.
- **7.Functional Programming**: Kotlin supports functional programming paradigms, including higher-order functions, lambdas, and immutable data structures. These features enable concise and expressive code.
- **8.Smart Casts**: Kotlin's compiler performs automatic type casts when certain conditions are met. This feature eliminates the need for explicit type checks and casts in many situations, leading to cleaner code.
- **9.Ranges**: Kotlin provides a built-in range type that represents a sequence of numbers. Ranges are commonly used in loops, conditions, and collections to express a range of values concisely.
- **10.Companion Objects**: Kotlin allows you to define a companion object within a class, which is similar to static methods and fields in Java. Companion objects can access private members of their enclosing class and serve as a replacement for static utility classes.
  
# Variables and Data Types:
- Immutable using val keyword
- Mutable using var keyword
- Kotlin has various data types such as `Int`, `Long`, `Float`, `Double`, `Boolean`, `Char`, `String`, etc.
- Scope of a variable – A variable exists only inside the block of code( {………….} ) where it has been declared. You can not access the variable outside the loop. Same variable can be declared inside the nested loop – so if a function contains an argument x and we declare a new variable x inside the same loop, then x inside the loop is different than the argument. Naming Convention – Every variable should be named using lowerCamelCase.

```kotlin
val name: String = "Kotlin"
var age: Int = 5
