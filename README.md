# A dynamic site built with node js where the api retrieves student profile information from a RESTFUL web service(json file) provided by a website and displays the profile information on searching for various students.

start the server using node app.js in the terminal and run http://localhost:3000 in the browser to get the site running .

app.js is the entry point .

router.js file includes route function to route to both the user page and search page.

render.js handles all the views including header, footer , search and profile .It helps in loading the view files in html when 

triggering various events in router.js .

profile.js uses https module to retrieve treehouse api using GET method.
