function sayhello(name){
alert("hello!")
sayhello();
}


function getfullname(firstname,lastname){
return `${firstname} ${lastname}`;
}
getfullname("john","snow"); 


function addtwonumbers(firstnum,secondnum){
  if(typeof firstnum !== "number" || typeof secondnum !== "number"){

   alert("please enter a valid input(number)");
   return;
  }


return firstnum + secondnum;
}
addtwonumbers();
 

function calc(numa,numb,operation ){
if(typeof numa !=='number' ||typeof numb !== 'number'){
   alert("Enter valid input");
   return;
}

{
switch(operation) {

case "add" :
   return numa+numb

   case"sub":
   return numa - numb 

   case"mul":
   return numa*numb;

   case "div":
      return numa/numb;
}

}

