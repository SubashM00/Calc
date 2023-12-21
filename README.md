# Ex.08 Design of a Standard Calculator
## Date:21.12.2023

## AIM:
To design a web application for a standard calculator with minimum five operations.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
calculator.html

<!DOCTYPE html>  
<html lang = "en">  
<head>  
<title> Calculator </title>  
  
<style>  
h1 {  
    text-align: center;  
    padding: 23px;  
    background-color: rgb(227, 100, 10);  
    color: rgb(7, 7, 7);  
    }  
  
#clear{  
width: 270px;  
border: 3px solid yellow;  
    border-radius: 3px;  
    padding: 20px;  
    background-color: rgb(9, 238, 219);  
}  
  
.formstyle  
{  
width: 290px;  
height: 600px;  
margin: auto;  
border: 5px solid rgb(14, 14, 12);  
border-radius: 5px;  
padding: 50px;  
}  
  
  
  
input  
{  
width: 20px;  
background-color: rgb(9, 238, 219); ;  
color: rgb(14, 14, 13);  
border: 3px solid  yellow;  
    border-radius: 5px;  
    padding: 25px;  
    margin: 5px; 
    font-size: 25px;  
}  
  
  
#calc{  
width: 250px;  
border: 5px solid yellow;  
    border-radius: 3px;  
    padding: 20px;  
    margin: auto;  
}  
  
</style>  
  
</head>  
<body>  
<h1> SUBASH  M  23014070 </h1>  
<div class= "formstyle">  
<form name = "form1">  
     
  <input id = "calc" type ="text" name = "answer"> <br> <br>    
  <input type = "button" value = "1" onclick = "form1.answer.value += '1' ">  
  <input type = "button" value = "2" onclick = "form1.answer.value += '2' ">  
  <input type = "button" value = "3" onclick = "form1.answer.value += '3' ">  
   <input type = "button" value = "+" onclick = "form1.answer.value += '+' ">  
  <br> <br>  
    
  <input type = "button" value = "4" onclick = "form1.answer.value += '4' ">  
  <input type = "button" value = "5" onclick = "form1.answer.value += '5' ">  
  <input type = "button" value = "6" onclick = "form1.answer.value += '6' ">  
  <input type = "button" value = "-" onclick = "form1.answer.value += '-' ">  
  <br> <br>  
    
  <input type = "button" value = "7" onclick = "form1.answer.value += '7' ">  
  <input type = "button" value = "8" onclick = "form1.answer.value += '8' ">  
  <input type = "button" value = "9" onclick = "form1.answer.value += '9' ">  
  <input type = "button" value = "*" onclick = "form1.answer.value += '*' ">  
  <br> <br>  
    
    
  <input type = "button" value = "/" onclick = "form1.answer.value += '/' ">  
  <input type = "button" value = "0" onclick = "form1.answer.value += '0' ">  
    <input type = "button" value = "%" onclick = "form1.answer.value += '%' ">  
    <!-- When we click on the '=' button, the onclick() shows the sum results on the calculator screen. -->  
  <input type = "button" value = "=" onclick = "form1.answer.value = eval(form1.answer.value) ">  
  <br>   
  <!-- Display the Cancel button and erase all data entered by the user. -->  
  <input type = "button" value = "Clear All" onclick = "form1.answer.value = ' ' " id= "clear" >  
  <br>   
    
</form>  
</div>  
</body>  
</html>

```

## OUTPUT:
![Alt text](<Screenshot (63).png>)
![Alt text](<Screenshot (64).png>)

## RESULT:
The program for designing a standard calculator using HTML and CSS is executed successfully.
