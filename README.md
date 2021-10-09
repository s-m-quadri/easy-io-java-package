# Documentation:

## Download:
Download this repository, unzip it and add into your project directory.
```
https://github.com/shaikhmudassir/EasyIO-package/archive/refs/heads/main.zip
```

## Import 
Import following statement, it is must to add **static** keyword. 
```
import static EasyIO.EasyIO.*;
```

## Printing Methods:

1. These methods will print what ever is written within circular brackets.
2. String must be Written with Double Quotes(" ").
3. " + " Operator is used to concatenate String and to Separate Variables.
4. If user wants Next print Statement within a same line so,he can Enable(true) By writing "true" as second argument.Example,

```
print("One line ",true);
print("Second line");
```
Output:
>Oneline Second


## Inserting Methods:

1. All of these methods used to accept input from front end user.
2. User can give description.It is the guidelines for the user.
3. If user wants Description and input in a single line then he can Enable(true)the Single line method. 

```
String str = insert() ;

String age = insertInt("Enter your age");
```

## Type Casting:
1. All Type casting Methods has first Letter Capital. 
2. Type casting is done with String,Integer,Double,Long,Float data types. 

```
int age = Int(args[1]);
```
