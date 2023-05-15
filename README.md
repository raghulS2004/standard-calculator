# Design of a Standard Calculator

## AIM:

To design a web application for a standard calculator.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Clone the github repository and create Django admin interface.

### Step 3:
Use CSS for creating attractive colors.

### Step 4:
Write JavaScript program for implementing five different operations.

### Step 5:
Run the Server using "python3 manage.py runserver 0:8000" command.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
<!DOCTYPE html>
<html>
<head>
<title>SEC Demo on Calculator</title>
<style type="text/css">
table{
border: 1px solid black;
margin-left: auto;
margin-right: auto;
}
input[type="text"]{
border: 1px solid black;
padding: 20px 30px;
font-size: 24px;
font-weight: bold;
border-radius: 2px;
}
input[type="button"]{
width: 100%;
padding: 20px 40px;
background-color:greenyellow;
border-radius: 2px;
}
</style>
</head>
<body>
<form name="form1" onload="result.value=''">
<h1 style="text-align: center;color:blue;">Simple Calculator</h1>
<table id="calc">
<tr>
<td colspan="4">
<input type="text" id="result">
</td>
</tr>
<tr>
<td><input type="button" value="1"
onclick="result.value+='1'"/></td>
<td><input type="button" value="2"
onclick="result.value+='2'"/></td>
<td><input type="button" value="3"
onclick="result.value+='3'"/></td>
<td><input type="button" value="+"
onclick="result.value+='+'"/></td>
</tr>
Firefox https://github.com/Jayakrishnan22003251/standard-calculator/blob/ma...
3 of 6 15-05-2023, 08:56
OUTPUT:
SERVER OUTPUT:
<tr>
<td><input type="button" value="4"
onclick="result.value+='4'"/></td>
<td><input type="button" value="5"
onclick="result.value+='5'"/></td>
<td><input type="button" value="6"
onclick="result.value+='6'"/></td>
<td><input type="button" value="-" onclick="result.value+='-
'"/></td>
</tr>
<tr>
<td><input type="button" value="7"
onclick="result.value+='7'"/></td>
<td><input type="button" value="8"
onclick="result.value+='8'"/></td>
<td><input type="button" value="9"
onclick="result.value+='9'"/></td>
<td><input type="button" value="*"
onclick="result.value+='*'"/></td>
</tr>
<tr>
<td><input type="button" value="/" onclick="result.value+='/'"
/></td>
<td><input type="button" value="0"
onclick="result.value+='0'"/></td>
<td><input type="button" value="."
onclick="result.value+='.'"/></td>
<td><input type="button" value="="
onclick="result.value=eval(result.value)"/></td>
</tr>
<tr>
<td colspan="4">
<input type="button" value="clearall" id="clear"
onclick="result.value=''">
</td>
</tr>
</table>
</form>
</body>
</html>
```
## OUTPUT:
# SERVER OUTPUT:
![image](https://github.com/raghulS2004/standard-calculator/assets/122069938/d21b3a36-9749-47ca-9878-0e876f8c7920)

![image](https://github.com/raghulS2004/standard-calculator/assets/122069938/e020d2c2-97cb-43ed-ade1-8614edd55b1d)

# HTML VALIDATOR:
![image](https://github.com/raghulS2004/standard-calculator/assets/122069938/39091d55-750f-45be-9107-130ba53d1c55)


## Result:
The program for designing a simple calculator using JavaScript is executed successfully.
