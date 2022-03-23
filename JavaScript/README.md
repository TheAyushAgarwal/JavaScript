```JavaScript
// 1. Ways to print in JavaScript
console.log("hello world");
alert("me");
docoment.write("this is document write");

// 2. java Script Console API
console.log("Hello World", 4+6, "Another log");
console.warn("this is warning");
console.error("this is Error");

//3. JavaScript Variables
// what are Varibales ? -- Containers to store data Values
var number1= 34;
var number2= 56;
console.log(number1+number2);

// 4. Data Types in Java Script
// Numbers
var num1= 455;
var num2= 56.76;

// Strings
var str1= "this is a Strings";
var str2= "This is also a string";

//Objects
var marks= {
    ravi: 34,
    subham: 78,
}

//Booleans
var a =true;
var b= false;
console.log(a,b);

// var und = undefined;
var und;
console.log(und);

// null
var n= null;
console.log(n);


/* At a very high level, there are two types of dta types in JavaScript
1. Primitive data types: undefind, null, numbers, string, boolean, symbol
2. Reference data types: Arrays and Objects
*/

// Arrays 
var arr=[1,2,3,4,5]


//Operators In JavaScript
// Arithmetic Operators
var a= 34;
var b= 56;
console.log("The value of a+b is ", a+b);
console.log("the value of a-b is", a-b);
console.log("the value of a*b is", a*b);
console.log("the value of a/b is", a/b);

// Assignment Operators
var c=b;
c+= 2;// c= c+2
c-= 2;// c= c-2
c*= 2;// c= c*2
c/= 2;// c= c/2

console.log(c);


//Logical Operators
    // logical And
 console.log(true && true)
 console.log(true && false)
 console.log(false && true)
 console.log(false && false)
    // Logical OR
 console.log(true || true)
 console.log(true || false)
 console.log(false || true)
 console.log(false || false)
  
    // Logical Another
console.log(!false);
console.log(!true);


// Function in Java Script
    function avg(a,b)
    {
        return(a+b)/2;
        
    }
    c= avg(4,6);
    console.log(c);
    
    
// Conditions on JavaScript
var age= 34;
if(age>8)
{
    console.log('you are not a kid');
}
else{
    console.log("you are not a kid");
}
```
