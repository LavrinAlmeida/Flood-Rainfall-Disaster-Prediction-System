Approach:->
Disaster response is the second phase of the disaster Management cycle. It consists of a number of elements, for example, warning, evacuation, search and rescue, providing immediate assistance, assessing damage, continuing assistance and the immediate restoration. So among all, we have worked upon warning system for floods. In this, we have provided a user interface to the common public to check the level of water flow in rivers in future and have a provided a mechanism of notification if there is any possibility of flood due to any river in nearby future(12 months). Along with that users can also see the historical trends of rivers flow and can visualize the rainfall patterns also in their Sub-Division(Area). So with that much information beforehand and knowing the chances of the flood in any region we can prepare ourselves and alert the local public so that loss would be minimum.

STEPS TAKEN IN THE PROCESS:->
CONNECTION TO HTML:
A user issues a request for a domain's root URL / to go to its index page
main.py maps the URL / to a Python function
The Python function finds a web template living in the templates/ folder.
A web template will look in the static/ folder for any images, CSSfiles it needs as it renders to HTML
Rendered HTML is sent back to main.py
main.py sends the HTML back to the browser
URL IN THE BROWSER AND BACKEND CONNECTION:
First. we imported the Flask class and a function render template.
Next, we created a new instance of the Flask class.
We then mapped the URL / to the function index(). Now, when someone visits this URL, the function index() will execute.
The function index() uses the Flask function render template() to render the index.html template we just created from the templates/ folder to the browser.
Finally, we use run() to run our app on a local server.
We'll set the debug flag to true, so we can view any applicable error messages if something goes wrong, and so that the local server automatically reloads after we've made changes to the code.
When we visited http://127.0.0.1:5000/, main.py had code in it, which mapped the URL / to the Python function index().
index() found the web template index.html in the templates/ folder, rendered it to HTML, and sent it back to the browser, giving us the screen above.
