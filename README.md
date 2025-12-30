# Android Dev Handbook

## Kotlin

### What is Kotlin ? 
→ Kotlin is statically type programming language and runs on the JVM. Kotlin provides null-safety feature, which is helping to avoid common programming errors realted to null value.

### What is data class ?
→ A data class is used to hold the data and the compiler will auto genrates `equals()`, `hashCode()`,`toString()` and `copy()`. 

### What is sealed class ?
→ The sealed class represent restricted class hierarchies. So all direct subclasses must be defined within the same module and allowing the compiler to know all possible options at compile-time.
→ We can define a constructor in sealed calss.

### What is Extension Function ?
→ Extension function allows you to add a new function to an existing class, without modifying the class.
#### Example of extension function
<img width="463" height="367" alt="Screenshot 2025-12-30 at 4 54 37 PM" src="https://github.com/user-attachments/assets/1a164094-599c-40a3-84a9-8d45206a80ee" />


<img width="496" height="356" alt="Screenshot 2025-12-30 at 4 54 55 PM" src="https://github.com/user-attachments/assets/96534ca1-3bf9-4e2e-a07e-af460c957894" />

### What is Inline Function ?
→ An Inline function copies its function body directly where it is called. Therefore no extra lambad object is created and improve the performance.

### What is Non Inline Functions ?
→ It is a normal function, where the code will executed by calling the function.

### What is Scope Functions ?
→ A Scope function allows you to execute the block of code on an object.
 ##### List of scope functions
   - `let`
     - `let` is ued to execute the code only, if the object is not null.
     - `let` will return `it` as Context Type.
     - `let` will use for Null checks.
---
     
   - `apply`
   - `run`
   - `with`
   - `also`

### Kotlin Null Safety Operators
