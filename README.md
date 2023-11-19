# Ex.05 Design a Website for Server Side Processing
## Date:05/10/2023

## AIM:
To design a website to find total surface area of a square prism in server side.

## FORMULA:
Total Surface Area = 2b<sup>2</sup> + 4bh
<br>b --> Base of Square Prism
<br>h --> Height of Square Prism

## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Create python programs for views and urls to perform server side processing.

### Step 5:
Create a HTML file to implement form based input and output.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```html
<html>
<head>
<meta charset='utf-8'>
<meta http-equiv='X-UA-Compatible' content='IE=edge'>
<title>Total surface area of a square prism</title>
<meta name='viewport' content='width=device-width, initial-scale=1'>
<style type="text/css">
body 
{
background-color:red;
}
.edge {
width: 1440px;
margin-left: auto;
margin-right: auto;
padding-top: 250px;
padding-left: 300px;
}
.box {
display:block;
border: Thick dashed lime;
width: 500px;
min-height: 300px;
font-size: 20px;
background-color:blue;
}
.formelt{
color:orange;
text-align: center;
margin-top: 7px;
margin-bottom: 6px;
}
h1
{
color:rgb(255, 0, 179);
text-align: center;
padding-top: 20px;
}
</style>
</head>
<body>
<div class="edge">
<div class="box">
<h1>Total surface area of a square prism</h1>
<form method="POST">
{% csrf_token %}
<div class="formelt">
Length : <input type="text" name="length" value="{{l}}"></input>(in m)<br/>
</div>
<div class="formelt">
Breadth : <input type="text" name="breadth" value="{{b}}"></input>(in m)<br/>
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


## HOMEPAGE:
<img width="825" alt="Screenshot 2023-11-19 at 11 35 14 PM" src="https://github.com/Andrewvarghese653/MathServer/assets/145822115/be50fbda-83a0-4748-986b-1d6a471e68ff">
<img width="831" alt="Screenshot 2023-11-19 at 11 36 09 PM" src="https://github.com/Andrewvarghese653/MathServer/assets/145822115/148e9240-0001-4bb9-909a-321f8320dc56">




## RESULT:
The program for performing server side processing is completed successfully.
