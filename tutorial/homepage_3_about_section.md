# Building the "Who Am I" section

![](../../images/homepage_section_who_am_i.png)

Now that we have our header built, we can start putting in the "meat" of our website, starting with the "Who Am I" section.

This section will give our web site's visitors a glimpse into us and will direct them to the "About Me" page.

# Coding the section

1. In HTML, different tags indicate different things; and in our site we will be using the ```<section>``` tag to separate out our sections
2. After the end of the header ```div``` add in the following code:
   3. ```
	<!-- WHO AM I SECTION -->
	<section id="who-am-i">
		<h2>Who Am I?</h2>
		<hr>
		<p>
			My name is <strong>John</strong> and I am a made up person for this tutorial. I am 14 years old and have a blue shirt.
			<a href="" class="btn btn-primary pull-right">Read More About Me</a>
		</p>
	</section>
```
4. And just like that, our site should look something like this: ![](../../images/homepage_section_who_am_i_screenshot_1.png)
5. Hmm, the text seems a bit too spread out
6. We will learn how to fix that in the next page.