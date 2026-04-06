###Deployment Notes: Web Server Migration

This documents shows how our web application's structure is build 
from apache to nginx server and how a frontend of webapp is organized.

####File Structure

* index.html : This is the main page for the webapp.
* about.html : This is the second supplement page for providing information about the project.
* css.style : This presents the visual layout and design for webapp.
* nginx.conf : This is the primary file for the web server. It defines the listening ports, root directory of our static files.
* apache.conf : This file is same as nginx but works differently in production.
* .gitignore : This prevents temporary files and sensitive environment variables from being pushed to github.


