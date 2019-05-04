<html>
<head>
<style>
      input {padding :2px;
	       border:1px solid green;
		   align:center;
		   color:blue;
		   }
		body{background-color:dodgerblue;
		  margin-top:3cm;
		  margin-left:10cm;
		  margin-right:5cm;
		  margin-bottom:10 pcm;
		      }
</style>
</head>
<body>
enter number to get the fibonacci series:<input type ="text" id="id1">
<button onclick = "fun()"> click </button>
<p id = "demo1"> </p>
 <p id = "demo"> </p>
 <script>
 function fun() {
 var i;
 var a = 0;
 var b = 1;
  var n =document.getElementById("id1").value;
  
      document.write(a+" <br>");
	  if (n <0) {
	 document.getElementById("demo").innerHTML =  "the number" +" "+n+" "+"is not valid" +" ."+"please enter a valid number"; 
}
  else {	  
	  for(i= 1;i<=n;i++) {
	   c=a+b;
	   a=b;
	   b=c;
	   
	   document.write(c+"<br>");
	   }
	   }
	   
	   }
	   </script>
	   </body>
	   </html>
