# Customizing the About Page

1. Open ```portfolio.css``` from the ```css``` folder.
2. Let's add a little bit of space between all of the rows in our page
```
	#about-page .row {
		padding-bottom: 50px;
	}
```
	3. Here we are only selecting the ```row``` class inside of the ```about-page``` id
4. Next, let's make the text in the biography section a little bit bigger
```
	#about-page #bio {
		font-size: large;
	}
```
5. And finally, let's make it so that whenever you hover over a list item, it changes the background color!
```
	#about-page .list-group-item:hover {
		background-color: #BCF3EE;
	}
```

## One last step
1. In ```index.html```, change the link for the about page from ```#``` to ```pages/about.html```
```
	<li><a href="pages/about.html">About Me</a></li>
```