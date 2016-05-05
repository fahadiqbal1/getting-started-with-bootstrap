# Starting Template

Now that we have all the folders made and starting files generated, we can start working on a base template. This template is what we will use on every single future page, so that our entire site looks cohesive and well built.

## Design

Before we can start code, we need to figure out what will be present in every single page on our website. For the purposes on this tutorial, here is what every page in our site will have:

* Navigation bar at the top
* Contents of the page
* Footer at the bottom with links

## Coding the Template

 1. Open ```template.html``` in your text editor (Sublime Text, Notepad++, etc)
 2. Copy this code:
   3. ```
  <!DOCTYPE html>
  <html>
  <head>
      <meta charset="utf-8">
      <meta http-equiv="X-UA-Compatible" content="IE=edge">
      <title>John Doe Personal Site</title>
      <link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
      <link rel="stylesheet" href="css/portfolio.css">
  </head>
  <body>
      <!-- This is where our page's content will go -->

      <!-- Our Javascript Files -->
      <script type="text/javascript" src="https://code.jquery.com/jquery-2.2.3.min.js"></script>
      <script type="text/javascript" src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
  </body>
  </html>
  ```
   This is the absolute barebone version of our template. What we are doing here is loading the Bootstrap **CSS** and **JS** files
 3. T