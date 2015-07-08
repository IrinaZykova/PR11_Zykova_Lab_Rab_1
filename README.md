# PR11_Zykova_Lab_Rab_1
<!DOCTYPE HTML>
<html>
<head>
<title>Пример11</title>
</head>
<body>

<button onclick="task1()">а)</button>
<button onclick="task2()">б)</button>
<button onclick="task3()">в)</button>
<button onclick="task4()">г)</button>
<button onclick="task5()">д)</button>
<button onclick="task6()">е)</button>
<button onclick="task7()">ж)</button>

<script>
{
function task1()
{

var x = prompt('Введите x', '');
var y = prompt('Введите y', '');
var z = prompt('Введите z', '');

var a=(Math.sqrt(Math.abs(x-1)))/(1+Math.pow(x,2)/2+Math.pow(y,2)/4);
var b=x*((Math.atan(z)/(Math.PI/180))+Math.exp(-x-3));

document.write(a + "<br>");
document.write(b + "<br>");
}
function task2()
{
var x = prompt('Введите x', '');
var y = prompt('Введите y', '');
var z = prompt('Введите z', '');

var a = (3+Math.exp(y-1))/(1+Math.pow(x,2)*Math.abs(y-(Math.tan(z))/(Math.PI/180)));
var b = (1+Math.abs(y-x)+(Math.pow((y-x),2))/2+Math.pow(Math.abs(y-x),3)/3);

document.write(a + "<br>");
document.write(b + "<br>");
}
function task3()
{
var x = prompt('Введите x', '');
var y = prompt('Введите y', '');
var z = prompt('Введите z', '');

var a = (1+y)*((x+y)/(Math.pow(x,2)+4))/((Math.exp(-x-2)+1)/(Math.pow(x,4)+4));
var b = (1+(Math.cos(y-2))/(Math.PI/180))/(Math.pow(x,4)/(2+Math.pow(Math.sin(z),2)));

document.write(a + "<br>");
document.write(b + "<br>");
}
function task4()
{
var x = prompt('Введите x', '');
var y = prompt('Введите y', '');
var z = prompt('Введите z', '');

var a = y+ x/(Math.pow(y,2)+Math.abs(Math.pow(x,2)/(y+Math.pow(x,3)/3)));
var b = (1+Math.pow(Math.tan(x/2),2));

document.write(a + "<br>");
document.write(b + "<br>");
}
function task5()
{
var x = prompt('Введите x', '');
var y = prompt('Введите y', '');
var z = prompt('Введите z', '');

var a = (2*Math.cos(x-Math.PI/6))/(1/2+Math.pow(Math.sin(y),2));
var b = 1+(Math.pow(z,2))/(3+Math.pow(z,2)/5);

document.write(a + "<br>");
document.write(b + "<br>");
}
function task6()
{
var x = prompt('Введите x', '');
var y = prompt('Введите y', '');
var z = prompt('Введите z', '');

var a=x+(1+Math.pow(Math.sin(x+y)/(Math.PI/180),2))/(2+Math.abs(x-(2*x)/(1+Math.pow(x,2)*Math.pow(y,2))));
var b = Math.pow(Math.cos(Math.atan(1/z)/(Math.PI/180)/(Math.PI/180)),2);

document.write(a + "<br>");
document.write(b + "<br>");
}
function task7()
{
var x = prompt('Введите x', '');
var y = prompt('Введите y', '');
var z = prompt('Введите z', '');

var a = Math.log(Math.abs((y-Math.sqrt(Math.abs(x)))*(x-(y/(z+Math.pow(x,2)/4)))));
var b = x-Math.pow(x,2)/2/3+Math.pow(x,5)/2/3/4/5;

document.write(a + "<br>");
document.write(b + "<br>");
}
}


</script>
</body>
</html>
