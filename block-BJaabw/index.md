/*function mintosec(min){

let second = min*60
return second;
}
mintosec(); 

function calcbmi(weight,height){
let bmi = weight/(height*height);
if (bmi < 18.5){
    return underweight;
} else if (bmi>=18.5 && bmi <=24.9){
    return normalweight
}else if(bmi>=25 && bmi<=29.9){
    return overweight
}else{
    return obese
}
}
let weight = 65;
let height = 1.75;
let result = calcbmi(weight,height);
console.log("bmi:", result); 

function approdrink(age){

    if (age<14 ){
        return "drink fruit juice"
    }else if (age => 14 && age<18){
        return "drink soda";
    }else if (age>18 && age<21 ){
        return "drink fruit flavoured beer";
    }else{
        return "drink throat piercing vodka";
    }
}
approdrink();

function numorstring(input1,input2){
if(typeof input1 === "number" || typeof input2 === "number"){
    return input1 + input2
}else if(typeof input1 === "string" || typeof input2 === "string"){
    return input1+ input2
}


}
numorstring();


