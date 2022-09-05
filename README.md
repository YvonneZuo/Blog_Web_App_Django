# Blog_Web_App_Django
<h3>A full-featured Web App built with python Django, where different users can register, login, make blog posts, and update posts</h3><br>                                                                                                                                                              
1. Created database tables using Django models; Used the Django ORM to query the database and filter through results.<br> 
2. Used forms and validated user input by creating a user registration page and applied Crispy Form to make the forms match a modern style.<br> 
3. Created an authentication system for the application so that users can login and logout; Restricted certain pages so that users must be logged-in in order to access the page.<br> 
4. Extended the built-in Django User model to create user profiles; Created a receiver function for a Django single that will make sure profiles are created when a user first registers.<br> 
5. Utilized class-based views to create, update, and delete posts; Used pagination to only load a select number of items at a time so that the application does not get bogged down.<br> 
6. Deployed the application to a Linux Server using Nginx and Gunicorn, and tightened its security with SSH keys and firewalls.<br> 
7. Set up the custom domain name for the application using NameCheap as the domain registrar and Linode to host the server.<br> 
8. Enabled HTTPS on the web server with a free SSL/TLS certificate using Let’s Encrypt.<br> 
9. Set up AWS S3 to host the media files from that service instead of my local filesystem; Deployed the application to Heroku.<br> 
