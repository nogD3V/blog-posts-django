# SIMPLE DJANGO BLOG

<p>In this repo there's a simple django blog with some technologies.</p>
<p>The goal here was to know how django works, We didn't prioritize appearance here.</p>
<p>LINK: https://nogd3v.pythonanywhere.com</p>
</br>

<h3>BACKEND STACK:</h3>

<p><i>- Language: Python with framework Django.</i></p>
<p><i>- Database: SQLITE3 (Django native database).</i></p>

<h3><b>FRONTEND STACK: </b></h3>

<p><i>- Markup language: HTML5.</i></p>
<p><i>- Style Language: CSS3 WITH BOOTSTRAP.</i></p>

<h3><b>DEPLOY:</b></h3>
<p><i>- We used <b>GIT</b> to version the code, <b>GITHUB</b> to store and <b>PYTHONANYWHERE</b> to deploy the WEB APP using git.</i></p>

<h3><b>GOAL WITH THIS REPO:</b></h3>
<p><i>The real goal with this web app is to understand how django works, how to link templates with views, how to use a database, how to create a folder/files structure using 
  Django. the knowledge gained here will be used in a much larger project!</i></p>
<hr/>
</br>

# ERRORS

### We had this problem that were resolved with a alternative:

<pre>erro: nogd3v.pythonanywhere.com/:1 Refused to apply style from 'https://nogd3v.pythonanywhere.com/static/css/blog.css'
because its MIME type ('text/html') is not a supported stylesheet MIME type, and strict MIME checking is enabled.</pre>

<h3>EXPLANATION:</h3>

<pre>For some reason, deploying the web app was crashing the link of CSS file.
I looked for some solutions, but no one helped:</pre>

- Edditing settings.py
- Adding libraries on virtual environment.
- And others solutions proposed by stackoverflow, etc.

<h3>ALTERNATIVE SOLUTION: </h3>


<pre>The solution for now:
We tried to style the .html without using a external CSS file.
So, when the link was removed and we insert the tag style directly on .html, It worked.

fyi: The error did not occur on the local machine! 
It might be a limitation deploying the app.
I'm not sure if PYTHONANYWHERE was the problem, 'cause I didn't test in another server.</pre>
