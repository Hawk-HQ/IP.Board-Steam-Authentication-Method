Thank you for downloading my Sign in through Steam plugin for IP.Board

This plugin will allow new users to sign into your forum through the steam openid authentication system

-----------------

Installation: 

Step 1:
First upload the files in the upload folder to your forum directory

Step 2:
Go to your ACP and click Log In Management. Look at the bottom and install Steam login method by clicking the + Icon to it's side.

Step 3:
Enable the Steam Authentication Method by clicking the red Disabled text on the right of it

Step 4:
Click Manage Hooks. Browse for and import the supplied 'Steam_Login.xml' hook.

Step 5:
Enjoy your day as all should be well!

*note if your site is running https, make sure to turn on the 'login with https' setting otherwise this plugin will have issues. It is an OpenID erorr if you send wrong addresses by leaving this setting off.

-----------------

Updrading:

Step 1 (Skip to Step 2 if you are upgrading from 1.0.4):
First upload the files in the upload folder to your forum directory

Step 2:
Go to your ACP and Click Manage Hooks. Browse for and import the supplied 'Steam_Login.xml' hook.

Step 3:
There is no step 3, your done :P

-----------------

Need Support? Post in the support topic for this plugin, or email me at adam@lavoaster.co.uk

-----------------

Want to send me a donation? https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=LGZ5JV53BC9XW

-----------------

Are you a developer? The users steam id is stored in the members table, the column name is steamid.

You can pull interesting stuff just by loading http://steamcommunity.com/profiles/<users steam id>?xml=1

For instance my steam community page is http://steamcommunity.com/profiles/76561198010571702?xml=1
