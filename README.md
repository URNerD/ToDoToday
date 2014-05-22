# To Do Today

This file can be found at http://github/URNerD/ToDoToday

## 22 May 2014

Make sure you have completed the items from yesterday. You should be able to go to the URL: __http://_your-user-name_.github.io__ and see a page that looks something like the example below. You should absolutely not see the GitHub 404 (page not found) error page.

![foo](basic-index-html.jpg)

Once you have the basics from yesterday working, add links for your HTML, CSS, and JavaScript portfolio pages.
To do this you'll edit your index.html and modify the unordered list (the ```<ul>```) to create working links.
The new code will look something like this:

```
  <ul>
    <li><a href="static.html">Static HTML</a></li>
    <li><a href="static-plus-css.html">CSS</a></li>
    <li><a href="and-now-with-javascript.html">JavaScript</a></li>
  </ul>
```

The only difference between this and the code from yesterday is that you've replaced the empty ```href=""``` attributes with ones that refer to actual files. These files will be in the same repository (folder) with your
index.html so the attribute is just the plain name of the file.

Your links should now work and take you to an error page – it should be a 404. This is fine for now, since the files don't exist and we know why.

Now create the three files (if you don't already have them). You don't have to use my names… You can start by making bare bones files like your index.html – but put something different in them so that you can tell that you're getting to your new pages when you follow the links.

## 21 May 2014

If you haven't done these things, do them __today:__

* Setup your GitHub account and e-mail me your user name.
* Verify your e-mail address with GitHub.
* Create a repository named: _your-user-name_.github.io and mark the checkbox to initialize it with a README before you click the Create Repository button.
* Add a file called index.html, make it look like the example below.
* Commit the changes.
* Check your e-mail for build errors.
* Check out your page at _your-user-name_.github.io.

![foo](github-verify.jpg)

You can use this as a basic template for your index.html file:

```
<!doctype html>
<html>
<head>
  <title>your name here</title>
</head>
<body>
  <h1>your name here too</h1>
  <ul>
    <li><a href="">Static HTML</a></li>
    <li><a href="">CSS</a></li>
    <li><a href="">JavaScript</a></li>
  </ul>
</body>
</html>
