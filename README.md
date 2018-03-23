# Murmur_Vagrant
Murmur Server with a Client on the same Network.

The Vagrant File will create two VMs. One is named murmur and is the Servers and the other is called Mumble which is the Client
Both of these VMs are in the Same Private Network which gets created in the Setup Process.

The Server has the following Ports forwarded:

80 for Http

64738 for Mumble

The Server will import the mumble-server.ini, which is used as a config for Mumble, from the synced folder.
The File is Used to configure the Mumble Server itself.

The Client VM has a GUI because the Mumble Client is not available without a gui

After start up from Both Server and Client, connect the Client by starting the Mumble Program and adding the server with the IP 192.168.10.20

A Guide on how to do this, you can find here https://www.mumble.com/support/how-to-connect-to-a-mumble-server.php
