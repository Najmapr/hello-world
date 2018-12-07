<html>
<head>
<meta charset="ISO-8859-1">
<title>Pizza delivery</title>
<link rel="stylesheet" href="bootstrap-3.3.7-dist/css/bootstrap.min.css">
<script src="js\pizza.js"></script>
<style type="text/css">
table, th, td{
border:2px solid black;
box-sizing:content-box;
border-collapse:collapse;
}

.b{
position:relative;
top:35px;
left:10px;
}

.tab{
background-color:fuchsia;
}

h1{
color:navy;
font-size: large;
font-style: Cooper Black;
}

</style>
</head>
<body background="img\pizza-wallpers.jpg" width="100%">
<div align="center" class="container">
<h1 style="color:navy; font-size: 50px; font-style: Cooper Black;">Pizza Shop</h1>
<table class="tab">
<tr>
<th>Name</th>
<td><form class="form-inline">
<div class="form-group">
<input type="text" class="form-control" id="exampleInputName2" placeholder="name">
</div>
</form></td>
</tr>

<tr>
<th>Pizza Topping</th>
<td>
<div class="radio">
<label><input type="radio" name="optionsRadios" id="otionsRadios1" value="supreme">Supreme</label>
</div>
<div class="radio">
<label><input type="radio" name="optionsRadios" id="otionsRadios2" value="vegetarian">Vegetarian
</label>
</div>
<div class="radio disabled">
<label><input type="radio" name="optionsRadios" id="otionsRadios3" value="Hawaiian">Hawaiian
</label>
</div>
</td>
</tr>

<tr>
<th>Pizza sauce</th>
<td><select name="sauce" id="s1">
<option value="tomato">Tomato</option>
<option value="Barbeque">Barbeque</option>
<option value="mayonnaise">mayonnaise</option>
</select></td>
</tr>

<tr>
<th>Optional Extras</th>
<td><label class="checkbox-inline">
<input type="checkbox" id="inlineCheckbox1" value="Extrea Cheese">Extra Cheese
</label>
<label class="checkbox-inline">
<input type="checkbox" id="inlineCheckbox2" value="glutten free base">Glutten Free Base
</label></td>
</tr>
</table>
<div class="b">
<input class="btn btn-success" type="button" value="place order" onclick="getName();">
</div>

</div>
</body>
</html>
