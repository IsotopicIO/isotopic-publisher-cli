# isotopic-publisher-cli
Publish content to the Isotopic Store using your command line. Windows & UNIX 

# How to Use:
- Download files
- (UNIX only) Add executabe permission to iso-publish.exe (e.g ``chmod +x iso-publish.exe``)
- run iso-publish.exe and pass the required arguments.

# Command Syntax
``./iso-publish.exe <build-path> -u <username> -p <password> -app <app_id> -zip <zip-destination>``

-u   : Isotopic Account Username<br>
-p   : Isotopic Account Password<br>
-app : Isotopic App ID , the name of App (find in URL of your game's page, e.g /?game=MyApp_243)<br>
-zip : The zip file name. if this parameter is set, build-path is the directory which should zip.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;otherwise build must be the the full path of zip file name.
