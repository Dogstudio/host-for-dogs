# HOSTDOG 

> Test your hosting for Dogstudio CMS

To test if your hosting is compatible with our CMS <strong>Emulsion</strong>, we have coded a small script that make some validations for you.

## Getting started

* To use it, you need to **download the script**, 
* place the file in your **web root folder**.
* and **access your site** using your configured domain.

> Direct download.

## Test results

The script make the following tests (and some others) :

* The PHP version
* Some PHP parameters like : `max_execution_time`, `memory_limit`.
* The domain configuration : is your site accessible with your domain.
* The write acces on directories and files fr the web user.
* The database access _(you must enter the connexion parameters, manually)_.
* If the server can send email.

When the test is performed, you'll see a result page like this.

![Screenshot of test results in development](https://raw.githubusercontent.com/Dogstudio/hosting-for-dogs/master/docs/images/test-pass.png)

The green ones meet the needs of our CMS while the reds need your attention.
You can click on each one to obtain more informations.