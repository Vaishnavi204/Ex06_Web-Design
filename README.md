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
    alert("No Grade");
}
}
</script>
</head>
<body>
<h1 onclick="student()">
Click here to Find Grade Result of a Student
</h1>
</body>
</html>
```


## OUTPUT
![Screenshot (19)](https://github.com/Vaishnavi204/Ex06_Web-Design/assets/167157596/8f04a77d-fcbd-43d3-90b3-80b871d37f90)
![Screenshot (20)](https://github.com/Vaishnavi204/Ex06_Web-Design/assets/167157596/9cb12b72-9223-464b-be79-2e6f78a88db3)
![Screenshot (21)](https://github.com/Vaishnavi204/Ex06_Web-Design/assets/167157596/c72f0fc8-551f-40b3-b0f5-c9deba558fad)
![Screenshot (22)](https://github.com/Vaishnavi204/Ex06_Web-Design/assets/167157596/e74dca0b-be92-402d-a490-cb3e235c2306)
![Screenshot (23)](https://github.com/Vaishnavi204/Ex06_Web-Design/assets/167157596/fad9ebef-a64c-4092-8409-85c82ab5f249)
![Screenshot (24)](https://github.com/Vaishnavi204/Ex06_Web-Design/assets/167157596/46e864a5-e54c-4e8b-9f6d-94a0437b48dc)







## RESULT
  Student result using JavaScript is created successfully.
