# MMP-Webserver
Webserver app that uses built in httpd for Miyoo Mini Plus running OnionOS.

Warning: This won't work if using the built in HTTP file server (without workaround)

Installing:

1. Unzip release file
2. Edit HTTP/index.html to your website files (Server root is SDCARD/HTTP)
3. Copy App and HTTP folders to the root of the SD card and press merge

Workaround to use both HTTP file server and custom server:

1. Go to SDCARD/App/WebServer
2. Edit the port variable in launch.sh to a custom port (Not port 80)
3. Acess your webserver at http://IP:Port and File server as normal

Note: Every reboot requires restarting the webserver with the app

