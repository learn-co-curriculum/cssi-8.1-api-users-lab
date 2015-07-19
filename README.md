# Python API Users Lab 

## Concept

This lab sets up a simple use for the App Engine Users api. You will be building a login page that says "hello" to the user and tracks their status.  

## Objectives

+ Use the App Engine Users API to log people into your site
+ Use the API to access data about the user

## Directions

1. Import `users` from `google.appengine.api`
2. Fill out the get handler so it uses the users API to get the current user
	a. If there is a user, output "Welcome [nickname]" to the template and append a logout url.
	b. If there isn't a user create a link so they can login
3. Pass the greeting to the index.html page using the jinja2 template.


## Stretch

+ What other information can we access using the users API? Add some of that to the page.
+ How could we make the website more intuitive?
+ Can we mimic the login UI of other sites you've seen before?