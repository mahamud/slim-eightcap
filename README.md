# slim-demo-project-one

Notes:
-----
Framework Used : Slim3

**#logs folder should be writeable**

Installation Instructions:
-------------------------

1. Need to setup a virtual Host to run the app.
2. Set Environment Variables for DB on /app/config/config.dev.php
2. Run Composer
3. Please look in to app/config/config.dev.php for required environmental variables that require to be configured
4. Routes are under /app/routes.php


Sample Url Requests:
--------------------
1. https://{virtual_host}/posts/
2. https://{virtual_host}/details/{post_id}

** Please be careful about trailing slashes. The first url has a slash at the end while the second doesn't have one. 


