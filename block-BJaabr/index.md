/* function declaration

function convertTostring (n){
    return String(n)

}
convertTostring();
*/


/* Function expression

let convertTostring = function(n){

    return String(n)
}
convertTostring(); */

/* arrow function*/

/*
let convertTostring = (n) => {
  return  String(n);
}*/
/*
let convertTostring = (n) => String(n) */

/*function declaration

function addone(n){
    return(n+1)
}
addone();*/

/*function expression
let addone = function(n){
    return(n+1)
}
addone(); */

/* arrow function without curly brackets

let addone = (n) => (n+1); */

 /*arrow function with curly brackets

let addone = (n) =>{
    return(n+1)
}
addone(); */

/*function expression*
function sum(numa,numb){
    return(numa+numb)
}
sum();*/

/*function expression

let sum = function(numa,numb){
    return(numa+numb)
}
sum();
*/ 

/* arrow function without curly brackets 

let sum = (numa,numb) => (numa+numb); */

/*arrow function with curly brackets 
 let sum = (numa,numb) =>{
    return(numa+numb)
 }
 sum();*/

 /* function declaration

function isGreater(x,y){
if(x>y)
return "true"
else 
return"false"
}
isGreater();*/

/* function expression 

let isGreater = function(x,y){
    if(x>y)
return "true"
else 
return"false"
}
isGreater();
*/

/* arrow function without curly function 
let isGreater = (x,y) => (x>y) ; true ,false*/


/* arrow function with curly brackets 
let isGreater =(x,y) =>{
    if(x>y)
    return true ; 
    else
    return false; }
isGreater(); */

/* function declaration 
function oddeven(num){
    if (num %2 === 0 )
    return "number is even"
    else if ( num %2 != 0 )
    return "number is odd"
}
oddeven(); */

/* function expression 
 let oddeven = function(num){
    if(num %2 ===0 )
    return "number is even"
    if(num %2 !==0 )
    return "number is odd"
 }
 oddeven(); */

 /* arrow function  without curly brackets 

 let oddeven = (num) => "if"(num %2 === 0) "the number is even ";  if(num %2 !==0) "number is odd" */

 /* arrow function with curly brackets */

 let oddeven = (num) => {
    if(num %2 === 0 )
    return"number is even "
    else 
    return "number is odd"
 }
 oddeven(); 
