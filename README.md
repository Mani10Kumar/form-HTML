# form-HTML
company form in html css
<!DOCTYPE html>
<html>
<head>
	<title>REGISTRATION</title>
</head>
<style>
	body{
		background-color: #C0C0C0
	}
input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=datetime-local], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
h2{text-align:center;
}
</style>
<body>
<h2>WELCOME TO BEL</h2>

<div>
  <form action="/action_page.php">
    <label for="fname">First Name</label>
    <input type="text" id="fname" name="firstname" placeholder="Your name..">

    <label for="lname">Last Name</label>
    <input type="text" id="lname" name="lastname" placeholder="Your last name..">

    <label for="etime">Entry Time</label>
    <input type="datetime-local">

    <label for="lsttime">Exit Time</label>
    <input type="datetime-local">

    <label for="field">Field</label>
    <select id="field" name="field">
      <option value="HRD">HRD</option>
      <option value="APPARENTIS">APPARENTIS</option>
    </select>
  
    <input type="submit" value="Submit">
  </form>
</div>

</body>
</html>
