# netcup-ddns-for-mikrotik
This Script is for using the netcup API for DynDNS on Mikrotik Routers
<br>
## Important note !
1. The script is only working with subdomains in the moment!
2. The subdomain must exist in the netcup CCP (Customer Control Panel)

<br>
## How the script works
Checks the IP of the Internet connection against the IP in the DNS Record on the netcup API,
<br>
when the IP is different it starts the update process to the new IP.

## How to set it up
1. set up you subdomain record in the netcup CCP (Customer Control Panel)
2. set the TTL to 300 (5min) in the nectup CCP
3. copy the content of the file into a new script on Mikrotik RouterOS.
4. change the variables to yours from your netcup account
5. set the script permissions on RouterOS to "read" and "test"
6. set a new schedule for the script and let it run every 15mins or so

<!-- <p> -->
<br>
<!-- <p> -->
special thanks to rextended from the mikrotik forums for the "ID extraction function" in this script

