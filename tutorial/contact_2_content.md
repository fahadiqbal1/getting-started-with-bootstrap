# Building the Contact Page

1. Make a copy of ```template.html``` and paste it in the ```pages``` directory as ```contact.html```
2. Find header links to Home and About and replace them with 
```
	<li><a href="../index.html">Home</a></li>
	<li><a href="about.html">About Me</a></li>
```
3. Next, find the line ```<link rel="stylesheet" href="css/portfolio.css">``` and replace it with 
```
	<link rel="stylesheet" href="../css/portfolio.css">
```
4. Find ```<!-- This is where our page's content will go -->``` and replace it with
```
	<div id="contact-page">
		<div id="contact-page">
			<iframe id="contact-form" src="https://hello.typeform.com/to/Mkg0Tc" width="100%" height="750"></iframe>
		</div>
	</div>
```
5. Update the links to the Contact page in both the Home page and the About page
