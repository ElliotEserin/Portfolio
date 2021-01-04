---
layout: default
---

# contact

You can contact me through my e-mail: ellioteserin@gmail.com or using the form below.

<div class="container">
      <section id="main_content">
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
					<input type="submit" value="Submit" class="button-success pure-button">
				</p>
			</form>
		</fieldset>
      </section>
    </div>
