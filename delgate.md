# Delegates in c#

what is  *Delegates *:its a function pointer its a type safe function which means  

1. when you invoke the delegate you invoke the function

Q1)why we dont call the delgate function dirictly?

A)flexibllity by pointing to a function and invoking it

Q2)WHAT is the syntax of delegate?

A) `accsses modfier delegate return type name of function ( type  params)`

### example on Delegates 

 ` public delegate void helloworld(string message)` it will point to any function that will have a void and string as parameters

 Q3)How we invoke the delegate function?

 A)By creating an instance from the delegate and pointing it to spesfic function with the same params

 ### example on invoking  Delegates 

 helloworld fun=new helloworld(hello)=> hello is predefined function

 Q4)what does mean safe in delegate ?

 A)means that the signture syntax  of the delegate  is matching the invoked function