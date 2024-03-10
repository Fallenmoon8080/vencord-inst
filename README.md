# Vencord-inst
Everytime a new discord app version releases for linux, you have to download the files yourself off of the website, and apply any patches each and every time you reinstall.  
Or do you?

Vencord-inst is a script that will download the latest and greatest discord, and will automatically patch it with vencord without *any* user interaction!
Please note that this script will install the **stable** discord app, and only works on debian-based distros.
## Requirements
 - sudo (and permissions to use it)
 - wget
 - Internet connection
Do not run this script as root, as that will mess things up! Instead, just run it as a normal user that has sudo privileges.

## How to use
To get the script, you can either download it directly, or you can the following command  
`cd; wget https://raw.githubusercontent.com/LucRtheL/vencord-inst/main/vencord_inst`  
Once you've downloaded the script, navigate to its containing directory, and run  
`chmod +x vencord_inst`  
Finally to execute the script, simply run  
`./vencord_inst`  
Enter your password when prompted and you should be all set!  
If you wish to make vencord_inst easier to use and find, run  
`sudo mv vencord_inst /usr/local/bin`  
This will put it in your $PATH so you can simply tab autocomplete to use it!
