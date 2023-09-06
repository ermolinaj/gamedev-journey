## Functions
Declare with the `func` keyword, then by a name and parameters between `( )` and function body starts with the `:` character after a name is given to the function.
Functions content have to be indented when inside a function body.
You can use the `pass` keyword if you want to declare a function without content.
### Return values
Using the `return` keyword you can return a value when the function finishes executing.
When the function is called this value can be used by, for example, assigning it to a variable or as an argument.
A `void` return type means a function doesn't return anything.

---
### Parameters / Arguments
Parameters can be created on definition by putting their names between `,`s.
On function call Arguments are passed between `( )` separated by `,`s.
Beware of infered types and operations made inside functions if type isn't required, GDScript is an interpreted language.

If a parameters has a value assigned on declaration it means it is optional parameter and if not present in argument list it will have the default value.

---
## Comments 
Single line comments are written with the `#` character.

---
## Math operators
![[Pasted image 20230903182039.png]]
** = power of

When dividing you need to assign presission of values used in operation (if ypu want a result in float presission use float values when operating with `/`)

---
## Data Types
Basic Data Types
- Integer
- Float
- String
- Boolean
---
## Variables
To declare a value we use the `var` keyword. It is followed by a variable name.
Value assignation is optional.
Assignment is made post declaration using the variable name and the `=` sign followed by the variable new value.

### Scopes
This variable scope is global for the script
![[Pasted image 20230904022552.png]]
If a variable its defined inside a function or code block (for example an if statement) once the function or de code block finishes executing the variable is disposed.

### Exports
By using the `@export` keyword the defined variable is visible on the script´s assigned node Inspector, allowing you to modify ins value from the inspector:
![[Pasted image 20230905021121.png]]
![[Pasted image 20230905021147.png]]

---
## If statements
`if + [boolean expression] + :` 
![[Pasted image 20230904005107.png]]
If expression equals true code block inside is executed.

If its false else statement will be executed:
![[Pasted image 20230904005207.png]]

Before else you can define an `elif` statement that executes in case if expression equals false and can execute another boolean expression:
![[Pasted image 20230904005359.png]]

---
## Comparison Operators
![[Pasted image 20230904004807.png]]

---
## Naming Conventions
In GDScript we use `snake_case` for naming conventions.

``
