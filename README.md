<b>Gmail Python OAuth Client:</b>

This is a simple python module that authenticates with Gmail using OAuth and sends a message.

<b>Usage is as follows:</b>
	On the first use, run gmail.configure(), this is an interactive tool allows you to set the location of your client_secret.json file.
	Afterwards, you can use it to send messages.
	<i>Example:</i>
		gmail.sendMail(body, recipient, sender, subject)
		
More feautures to come soon such as attachements.

