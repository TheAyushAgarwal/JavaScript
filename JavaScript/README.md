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
// Loops in Java Script
var arr= [1,2,3,4,5,6,7];
console.log(arr);
    // for loop
for(var i=0;i<arr.length;i++)
{
    console.log(arr[i])
}
    // while loop
while(j<arr.length){
    console.log(arr[j]);
    j++;
}

    // do while
do
{
    console.log(arr[j]);
    j++;
    
}while(j<arr.length);

// break and continue

var arr= [1,2,3,4,5,6,7];
    
for(var i=0;i<arr.length;i++)
{
    if(i=2)
    {
        break;
        //here it will break the for loop
    }
 console.log(arr[i])
}
for(var i=0;i<arr.length;i++)
{
    if(i=2)
    {
        continue;
        // here it will just break the current condition but excutes all codes except it
    }
    console.log(arr[i])
}
// Methods On Array
var myArr=["fan","camera",null,34,true];

console.log(myArr.length);
myArr.pop();
myArr.push("ayush");
myArr.shift();
myArr.unshift();
// here pop means it will remove last element in the array, 
// here push means it  will add one index with value at the end of the array,
// here shift menas it will remove first index from the array,
// here unshift means it  will add one index with value at the starting of the array.

// String Methods in javaScript
let mylovelyString="he is a good boy";
console.log(mylovelyString.length);
// it will findout the length of the array
console.log(mylovelyString.indexOf("good");
// it will findout the index of the Array

console.log(mylovelyString.lastIndexOf("good");
// it will print the last index position of the Array

console.log(mylovelyString.slice(1,3);
// it will print only value of index which we want to print
myLovelyString.replace("he","rohit");
// it will replace he, and add rohit.




// Dates ond time in javaScript
let myDate= new Date();
console.log(my.Date.getTime());
console.log(my.Date.getFullYear());
console.log(my.Date.getDay());
console.log(my.Date.getMinutes());
console.log(my.Date.getHours());

// it will print current date, year, day, minutes, hours.

// DOM Manipulation
let elem = document.getElementById('click');
// console.log(elem);

let elemClass = document.getElementsByClassName("container")
// console.log(elemClass);
// elemClass[0].style.background = "yellow";
elemClass[0].classList.add("bg-primary")
elemClass[0].classList.add("text-success")
// console.log(elem.innerHTML);
// console.log(elem.innerText); 

// console.log(elemClass[0].innerHTML);
// console.log(elemClass[0].innerText); 
tn = document.getElementsByTagName('div')
// console.log(tn)
createdElement = document.createElement('p');
createdElement.innerText = "This is a created para";
tn[0].appendChild(createdElement);
createdElement2 = document.createElement('b');
createdElement2.innerText = "This is a created bold";
tn[0].replaceChild(createdElement2, createdElement);
// removeChild(element); ---> removes an element
 
// Selecting using Query
// sel = document.querySelector('.container')
// console.log(sel)
// sel = document.querySelectorAll('.container')
// console.log(sel)

// function clicked(){
//     console.log('The button was clicked')
// }
// window.onload = function(){
//     console.log('The document was loaded')

// }
// Events in JavaScript
// firstContainer.addEventListener('click', function(){
//     document.querySelectorAll('.container')[1].innerHTML = "<b> We have clicked</b>"
//     console.log("Clicked on Container")
// })

// firstContainer.addEventListener('mouseover', function(){
//     console.log("Mouse on Container")
// })

// firstContainer.addEventListener('mouseout', function(){
//     console.log("Mouse out of Container");
// })

// let prevHTML = document.querySelectorAll('.container')[1].innerHTML;
// firstContainer.addEventListener('mouseup', function(){
//     document.querySelectorAll('.container')[1].innerHTML = prevHTML;
//     console.log("Mouse up when clicked on Container");
// })

// firstContainer.addEventListener('mousedown', function(){
//     document.querySelectorAll('.container')[1].innerHTML = "<b> We have clicked</b>"
//     console.log("Mouse down when clicked on Container");
// })


// Arrow Functions
// function summ(a, b){
//     return a+b;
// }
summ = (a,b)=>{
    return a+b;
}

logKaro = ()=>{
    document.querySelectorAll('.container')[1].innerHTML = "<b> Set interval fired</b>"
    console.log("I am your log")
}
// SetTimeout and setinterval
// clr = setTimeout(logKaro, 5000);
// clr = setInterval(logKaro, 2000);
// use clearInterval(clr)/clearTimeout(clr) to cancel setInterval/setTimeout

// JavaScript localStorage
// localStorage.setItem('name', 'harry') 
// localStorage 
// localStorage.getItem('name')
// localStorage.removeItem('name')
// localStorage.clear();

// Json 
// obj = {name: "harry", length: 1, a: {this: 'tha"t'}}
// jso = JSON.stringify(obj);
// console.log(typeof jso)
// console.log(jso)
// parsed = JSON.parse(`{"name":"harry","length":1,"a":{"this":"that"}}`)
// console.log(parsed);

// Template literals - Backticks
a = 34;
console.log(`this is my ${a}`)


```
