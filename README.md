# Ex.06 JavaScript - Student Result
## AIM
  To write a program in JavaScript for displaying the result of a student.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to generate the result grade.

### STEP-3
  Using branching statements analyze the grade achieved.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<title>Javascript program to display result of a student</title>
<script type="text/javascript">
function student()
{
var mark1,mark2,mark3,total,percentage;
mark1=parseInt(prompt("Enter Subject-1 Marks"))
mark2=parseInt(prompt("Enter Subject-2 Marks"))
mark3=parseInt(prompt("Enter Subject-3 Marks"))
mark4=parseInt(prompt("Enter Subject-4 Marks"))
mark5=parseInt(prompt("Enter Subject-5 Marks"))
total=mark1+mark2+mark3+mark4+mark5
percentage=total/5;
if((percentage>=91)&&(percentage<=100))
{
alert("O Grade");
}
else if((percentage>=81)&&(percentage<=90))
{
    alert("A+ Grade");
}
else if((percentage>=71)&&(percentage<=80))
{
    alert("A Grade");
}
else if((percentage>=61)&&(percentage<=70))
{
    alert("B+ Grade");
}
else if((percentage>=51)&&(percentage<=60))
{
    alert("B Grade");
}
else
{
    alert("RA Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click me to Find Grade Result of a Student
</h1>
</body>
</html>
```

## OUTPUT
![subject-1](https://github.com/Kiruthigamoorthi/Ex06_Web-Design/assets/127816726/5e484939-3508-4fd5-8b88-860f445eb33c)

![subject-2](https://github.com/Kiruthigamoorthi/Ex06_Web-Design/assets/127816726/b78fcd47-8bbb-4f5f-93fc-e6c23cf1265f)
![subject-3](https://github.com/Kiruthigamoorthi/Ex06_Web-Design/assets/127816726/299014b7-d009-4de5-b72f-94f89519be3a)
![subject-4](https://github.com/Kiruthigamoorthi/Ex06_Web-Design/assets/127816726/a153d3b8-fe8e-4a7a-9d8e-465ed7c7acfa)
![subject-5](https://github.com/Kiruthigamoorthi/Ex06_Web-Design/assets/127816726/e36da7a4-6fb9-474e-abfa-c30aba0d277f)
![last page](https://github.com/Kiruthigamoorthi/Ex06_Web-Design/assets/127816726/12b99e54-8032-4757-b757-525a3cdf92e9)

## RESULT
  Student result using JavaScript is created successfully.
