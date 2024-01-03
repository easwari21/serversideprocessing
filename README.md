# Design a Website for Server Side Processing

## AIM:
To design a website to perform mathematical calculations in server side.

## DESIGN STEPS:

### Step 1:

Clone the repository from GitHub

### Step 2:

Create Django Admin project.

### Step 3:

Create a New App.

### Step 4:

Create python programs for views and urls.

### Step 5:

Create a HTML file of forms.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
```
<html> 
<head> 
<meta charset='utf-8'> 
<meta http-equiv='X-UA-Compatible' content='IE=edge'> 
<title>Area of Square Prism</title> 
<meta name='viewport' content='width=device-width, initial-scale=1'> 
<style type="text/css"> 
body  
{ 
background-color:rgb(149, 255, 0); 
} 
.edge { 
width: 1080px; 
margin-left: auto; 
margin-right: auto; 
padding-top: 200px; 
padding-left: 300px; 
} 
.box { 
display:block; 
border: Thick dashed rgb(22, 22, 22); 
width: 500px; 
min-height: 300px; 
font-size: 20px; 
background-color: rgb(180, 82, 141); 
} 
.formelt{ 
color: rgb(10, 10, 10); 
text-align: center; 
margin-top: 5px; 
margin-bottom: 5px; 
} 
h1 
{ 
color: rgb(16, 16, 15); 
text-align: center; 
padding-top: 20px; 
} 
</style> 
</head> 
<body> 
<div class="edge"> 
<div class="box"> 
<h1>Area of Square Prism</h1> 
<form method="POST">  
<div class="formelt"> 
Side : <input type="text" name="side" value="{{s}}"></input>(in m)<br/> 
</div> 
<div class="formelt"> 
Height : <input type="text" name="height" value="{{h}}"></input>(in m)<br/> 
</div> 
<div class="formelt"> 
<input type="submit" value="Calculate"></input><br/> 
</div> 
<div class="formelt"> 
Area : <input type="text" name="area" value="{{area}}"></input>m<sup>2</sup><br/> 
</div> 
</form> 
</div> 
</div> 
</body> 
</html> 
```
## OUTPUT:
![Screenshot 2024-01-03 153209](https://github.com/easwari21/serversideprocessing/assets/131534979/b4e27e83-c16f-43f1-91cc-e96d841512a3)


## Result:

The program for implementing server side processing is completed successfully.
