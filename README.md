# linodeVPN
Scripts for setting up the Tinc server and client reverse proxy

## Required Parameters

- `netname`: Netname for Tinc VPN
- `client alias`: Client Alias
- `server alias`: Server Alias
- `server hostname`: Server Hostname
- `username`: Username for connecting to Server
- `address`: Ip address type used for the connection
- `client ip`: Local Client Ip for Tinc
- `server ip`: Local Server Ip for Tinc
- `gateway`: Local Gateway for Tinc

## Note
* Run the `server.sh` script before running the `client.sh` script.
* Make sure that the **client** has the proper SSH keys setup for password less authentication to the **server**.
* Once both scripts are run in the client and server **Reboot** the servers.
