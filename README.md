# netcup-ddns-for-mikrotik
This Script is for using the netcup API for DynDNS on Mikrotik Routers


## Functions
- checks the IP of the Internet connection against the IP in the DNS Records on the netcup API
- when the IP is different it starts the update process to the new IP


## How to set it up
1. copy the content of the file into a new script on Mikrotik RouterOS.
2. change the variables to yours from your netcup account
3. set the script permissions on RouterOS to "read" and "test"
4. set a new schedule for the script and let it run every 15mins or so


## Important note
The script is only working with subdomains in the moment!
