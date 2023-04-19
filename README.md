<!DOCTYPE html>

<html>

<head>

	<title>Sign Up</title>	<style>

		body {

			background-color: black;

			color: white;

		}

	</style>

</head>

<body>

	<h1>Sign Up</h1>

	<form>

		<label for="name">Name:</label>

		<input type="text" id="name" name="name"><br><br>

		

		<label for="gmail">Gmail:</label>

		<input type="email" id="gmail" name="gmail"><br><br>

		

		<label for="profile-pic">Profile Picture:</label>

		<input type="file" id="profile-pic" name="profile-pic"><br><br>

		

		<label for="password">Password:</label>

		<input type="password" id="password" name="password"><br><br>

		

		<label for="country">Country:</label>

		<select id="country" name="country">

			<option value="Bangladesh">Bangladesh</option>

			<option value="China">China</option>

			<option value="India">India</option>

			<option value="Indonesia">Indonesia</option>

			<option value="Japan">Japan</option>

			<option value="Malaysia">Malaysia</option>

			<option value="Philippines">Philippines</option>

			<option value="Russia">Russia</option>

			<option value="South Korea">South Korea</option>

			<option value="Thailand">Thailand</option>

			<option value="Vietnam">Vietnam</option>

		</select><br><br>

		

		<label for="message">Message:</label><br>

		<textarea id="message" name="message" rows="10" cols="50"></textarea><br><br>

		

		<input type="submit" value="Submit">

	</form>

</body>

</html>
