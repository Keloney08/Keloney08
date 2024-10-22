HTML

<!DOCTYPE html>
<html>
<head>

<title>For Loop</title>

    <link rel= "stylesheet" type = "text/css" href = "customize" ></link>
    
    <script src = "javascript.js" ></script>

</head>
<body>

<p id = "firstpart">

    <label id = "lblgradenum" >Enter the amount of grades that you would like to average: </label>
    <input type = "text"  id = "txtgradenum "  autofocus></input>
    
    <button type = "button" id = "btnenter">ENTER</button>
    
    <input type = "text" id = "txtgrade1" ></input>
    
</p>


</body>
</html>





JAVASCRIPT


window.addEventListener("load", addListener)
var grade1, grade2, grade3, grade4, grade5, grade6, grade7;

function addListener()
{
	document.getElementById("btnenter").addEventListener("click",Average)
	document.getElementById("txtgrade1").disabled = true;
}

function Average()
{
	alert("hi");
}




