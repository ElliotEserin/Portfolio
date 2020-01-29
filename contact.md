---
layout: default
---

<html>
	<head>
		<meta charset="utf-8">
		
		<link rel="stylesheet" href="https://unpkg.com/purecss@1.0.1/build/pure-min.css" integrity="sha384-oAOxQR6DkCoMliIh8yFnu25d7Eq/PHS21PClpwjOTeU2jRSq11vu66rf90/cZr47" crossorigin="anonymous">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<title>contact</title>
	</head>

	<body>
		<fieldset>
			<form   action="https://formspree.io/mzbegebe"
  					method="POST" 
				  	class="pure-form pure-form-stacked">
				<legend>Comment form</legend>
				<p>
					Title:
					<select name="title" id="" required>
						<option value="Mr">Mr</option>
						<option value="Mrs">Mrs</option>
						<option value="Ms">Ms</option>
						<option value="Dr">Dr</option>
						<option value="Other">Other</option>
					</select>
				</p>
				<p>
					<label for="firstname">First Name:</label>			
					<input type="text" name="firstname" id="firstname" required>
				</p>
				<p>
					<label for="lastname">Last Name:</label>	
					<input type="text" name="lastname" id="lastname" required>
				</p>
				<p>
					<label for="_replyto">Email:</label>
					<input type="email" name="_replyto" id="_replyto" required>
				</p>
				<p>
					<label for="message">Comment:<br></label>
					<textarea name="message" id="message" cols="" rows="5" required></textarea>
				</p>
				<p>
					<input type="checkbox" name="checkbox" id="checkbox" required> You agree to the terms and conditions
				</p>
				<p>
					<input type="submit" value="Submit" class="button-success pure-button">
				</p>
			</form>
		</fieldset>
	</body>
</html>
