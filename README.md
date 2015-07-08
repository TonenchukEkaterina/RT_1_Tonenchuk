# RT_1_Tonenchuk
<!DOCTYPE HTML> 
<html> 
<head> 
<title>Лабораторная 1</title> 
</head> 
<body>
<script> 
var a;
var b;
var c;
var chislo1 = prompt('Введите a', ''); 
var chislo2 = prompt('Введите b', ''); 
var chislo3 = prompt('Введите c', ''); 
a= parseInt(chislo1);
b= parseInt(chislo2);
c= parseInt(chislo3);
var a2 = Math.pow(a,2);
var b2 = Math.pow(b,2);
var c2 = Math.pow(c,2);
if  (a + b > c && a + c > b && b + c > a && a > 0 && b>0 && c>0 ) 
{ 
document.write("Треугольник существует" + "<br>" );
if (a2 < b2 + c2 && b2 < a2 + c2 && c2 < a2 + b2)
{
document.write("Треугольник остроугольный" + "<br>" );
}
else 
{
document.write("Треугольник прямоугольный или тупоугольный" + "<br>" );
}
}
else
{
document.write("Треугольник не существует" + "<br>" );
}
</script>
</body> 
</html> 
