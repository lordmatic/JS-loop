# JS-loop
<!DOCTYPE html>
<html lang="en">
<head>
     <meta charset="utf-8">
	<title> Anto and Liberty intro </title>
</head>
<body>
	<h3> Working with operators in JS</h3>
	<P id ="demo"> This is a replacement methods</P>

 <script>
        var  sisters = ["Emilia", "Elisha", "Marry", "Hannah", "Monica"];
		var i = 0
		var text = ""; 
		
		
		while (sisters[i]){
		
		 text += sisters[i] + "<br>";
		 i++;
		 
		                   }
  
  </script>
	   <button type="button"
		onclick = "document.getElementById('demo').innerHTML = text">
	   Click Me </button>
	   
</body>
