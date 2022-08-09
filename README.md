# 177



jQuery helps to
reduce the JavaScript code.
That means we have to
write very less code
compared to the JavaScript
code.



jQuery is “write less, do more”
JavaScript library.
jQuery also makes web applications
load a lot faster than JavaScript.


steps:
======
● Browser sends an HTTP
request.

● Server responds and sends
back the requested HTML file.

● Browser begins to render
HTML.

● Browser then sends additional
requests for objects present in
the HTML file (CSS files,
images, JavaScript, etc.).

The faster all steps are completed, the
faster the web page will be loaded!
------------------------------------------------------------------------------------------
millions of people using the
browser at the same time, how is this
possible for Google to give such fast
results?

Well the Google Chrome browser is
built on one of the very powerful

technologies used in the web
application, that is, AJAX.
AJAX is Asynchronous JavaScript and
XML.
In simple terms, this technique helps
to load/update the specific portion of
the page, instead of loading the whole
page again and again.


______________________________________________________________________________________________________

For example, in our Mad Libs game,
when we click on the Submit button
the result should be updated without
reloading the page again!

That means only the result section
should be updated!

lets learn
how to use the jQuery ajax() method to
show the score when the user clicks
on the submit button for a particular
Mad Libs story.
--------------------------------------------------------------------------------------
Flask is a Python’s
Framework to create APIs.


we converted
our HTML’s page into a Flask App.(boilerplate code)

how to run flask apps
1. Create a Virtual
Environment.
2. Activate the Virtual
Environment.
3. Install
Modules/Dependenci
es.
4. Run the server.

-------------------------------------
First we will go to the project directory
through terminal or command prompt.
-----------------------------------------------------------------------------------------------------------------


Then, we’ll create a virtual
environment first -


python3.8 -m venv venv


venv\Scripts\activate.bat

pip install flask

Finally, we can run the server -

python app.py

If we go to localhost:5000 on the
browser, we can see our app:
-----------------------------------------------------------------------------
Here, we know that our main APIs and
Flask App is in app.py.


Flask
has some special words reserved for
folders that have special meaning

Our .gitignore file contains the
files/folders we want GitHub to ignore.
What are the templates and static
folders?

“templates” folder is where Flask
looks for HTML files when a function
render_template is called.


We can see here that we have created
a route “/” where we are calling the
render_template() function and
passing “index.html” into it.
What this means is that on the route
localhost:5000/

We are rendering a template
“index.html” with a
render_template() function.
When the render_template() function
is called, it looks for the HTML file only
in a folder named templates like we
have.
==================================================================================


Next, we have a “static” folder. Inside
this folder, we have our CSS,
JavaScript files and Images that we
are using in an assets folder



Now Flask creates a URL endpoint of
“/static” by default, which contains all
the static data

This is because Flask has “static” as
a special folder we can create to hold
our static data and we can access this
data with the help of a URL.


You will see the image from the
Group.png image in the browser -


-----------------------------------------------

● “static” folder: We have our
static assets and files

● “templates” folder: Our HTML
templates.

● “app.py” file: We have our
APIs.

-------------------------------------------------------------

To begin with, we are going to create a
<div> tag showing the Mad Libs result
on the page below the Word Bank.
  
  =======================================
  But the “Result” is visible on the page
all the time, even though we have not
clicked on the “Submit” button.
The result must be visible only after
Submit is clicked.
  
  Let’s take “hidden” as our own class
name and assign it to the row <div>
and set its initial display property as
none in the style sheet.

  ==============================================================
  
  Ajax requests are similar to that!
When we make a request to a server
to get or post some data, conventional
JavaScript methods redirect(sends
requests) to the next route (or we can
say next page) after the request is
completed or the same page will be
reloaded again.
But using jQuery ajax() method for
making server requests the result is
updated on the same page without
reloading the whole page again.

  
  There are many possible values for
the name:value parameters in the
ajax() method. We are going to use a
few in our AJAX request:
● url: URL of the page where we
want to send the request;
  
● type: type of the request, GET
or POST;
  
● data: actual data that needs to
be sent to the server;
  
● dataType: datatype of the
response;
  
● contentType: type of the
content used while sending a
request to the server;
  
● success: a function after the
request is successful; and
  
● error: a function after the
request fails.

 g the url
parameter: This will help us to
call the API.

