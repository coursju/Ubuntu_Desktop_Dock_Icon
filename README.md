# Ubuntu_Desktop_Dock_Icon
***Code to show an app icon on the ubuntu dock from custom app***

sudo nano /usr/share/applications/yourapp.desktop

***Paste the following content:***

#!/usr/bin/env xdg-open

[Desktop Entry]

Version=1.0

Type=Application

Terminal=false

Exec=/path/to/yourapp

Name=YourApp

Comment=Description of YourApp

Icon=/path/to/yourapp.png


***Replace yourapp with your application and save by pressing Ctrl+O, Enter and Ctrl+X.***




***(optional, works without), Make this file executable:***
sudo chmod +x /usr/share/applications/yourapp.desktop
