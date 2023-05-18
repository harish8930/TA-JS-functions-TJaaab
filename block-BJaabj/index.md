function sayhello ()
{

alert("hello World !");


}
sayhello();*/

function fullname(){

let firstname = prompt("enter your first name");
let lastname = prompt("enter your lastname");
fullname = firstname+lastname ;

alert( `${ fullname }`)

}
fullname();


function addtwonumber(){
   let firstnum =Number(prompt("Enter the first number"))
   let secondnum =Number(prompt("Enter the second number"))
let sum = firstnum+secondnum;{



alert(`${sum}`)

}
}

addtwonumber(); 

function getTable(){

let num = Number(prompt("Enter the number"))
console.log(num*1,num*2,num*3,num*4,num*5,num*6,num*7,num*8,num*9,num*10);

}
getTable();


function isLeapyear()
{

let year = prompt("Enter the year");
if(year %4==0 )
alert("year is a leap year");
else 
alert("year is not a leap year")
}

isLeapyear();  

function getFactorial()
{

   let number = Number(prompt("Enter a number"))

  let factorial  =  number(number-1)

alert (`factorial of number is ${factorial}` )

}

getFactorial();

