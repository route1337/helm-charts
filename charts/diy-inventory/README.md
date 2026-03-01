DIY Inventory
=============
A basic helm chart for creating a simple DIY Inventory system using MariaDB and [NocoDB](https://nocodb.com/)

Configuration
-------------
The chart is pretty self-explanatory.

You can create the `NC_AUTH_JWT_SECRET` with `openssl rand -hex 32`  
As usual the MySQL password works better without special characters

Network Policy
--------------
By default, the NetworkPolicies are enabled. One restricts DB access just to the NocoDB application.  
The other permits only Cloudflared and Ingress NginX in to the NocoDB service.
