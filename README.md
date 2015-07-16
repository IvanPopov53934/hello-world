<html>
<head>
</head> 
<body> 
<script>
 var i = ""; 
var o = 0;
for(a =0;a<50;a++)
{ 
if(a>=3 && a<=7)
{
 o = parseFloat(o)+parseFloat(a);
}
if (a < 2) 
{ 
i = i+" "+"0"; 
} 

else 
{ 
i = i +" " + a; 
} 

} alert(i);alert(o);
</script> 
</body> 
</html>
