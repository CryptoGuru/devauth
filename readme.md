DevAuth Split Identity Sign-In with Device Authentication
=========================================================

Passwordless allows users to sign up and log in by first entering password on a registered device and then accessing the 
wordpress account by only entering the username. The username has to be an email address. It is based on patent pending concept developed by Gurudatt Shenoy [here](http://www.devauth.com).

This plugin orginally created by hel.io has been modified to incorporate split Identity Sign-In with device authentication 
ensuring that both the pieces of authentication are not entered on same device and thus secured from hackers.

I hope it will be of use to others but it might break things. Please use it with caution and at your own risk. 


**Login process**

DevAuth allows your site's users to log in first using their password on a registered device. After successfuly verifying the password, the user then proceeds to access their account on any device only
using their username. 

**New users**

New users will have to first register their account information with DevAuth by entering their username and password.

**Login page**

The plugin changes the login page URI to `example.com/login` from the default `example.com/wp-login.php`. If permalinks are disabled the login page will instead be `example.com/?login`.

The page can be customized using some of the same filters and action hooks that the original login page used. If a total overhaul of the page is desired, placing a `login.php` template file in the currently active theme directory will override the plugin's login page.

##Installation

**Requirements**

The plugin requires WordPress 3.4 or higher.

**Installation**

- Download the plugin from http://www.devauth.com/wordpress/devauth/DevAuth.zip
- Upload the plugin to the `/wp-contents/plugins/` folder.
- Activate the plugin from the 'Plugins' menu in WordPress.


## Changelog

**1.0**
- Initial release
