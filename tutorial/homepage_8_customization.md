# Customizing the Homepage

One of the key reasons why Bootstrap has been so successful is the fact that it is easily customizable. What we will be doing is adding a bit of spacing to our home page and making it look just like we want.

## Customizing the Sections

1. Open your ```portfolio.css``` file located in the ```css``` folder.
2. Write the following: 
```
	section {
		padding-bottom: 20px;
	}
```
3. This will add a little bit of space after every section on our page.
4. Lets also bring the line and the section header closer together.
```
	section > h2 {
		margin-bottom: 0px;
	}

	section > hr {
		margin-top: 0px;
	}
```
5. And while we are at it, let's also make the line a little bit darker
```
	section > hr {
		margin-top: 0px;
		border-top: 2px solid #aaa;
	}
```

## Customizing the Footer

1. Next let's add a bit of space before our footer.
```
	footer {
		padding-bottom: 20px;
	}
```
2. And let's change the background color of the footer and add a bit of space between the text and the edge of the div
```
	footer > p {
		padding: 15px;
		background-color: #eeeeee;
	}
```