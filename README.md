# RHEL Web Server Deployment

This project documents the deployment of an Apache HTTP server on a Red Hat Enterprise Linux (RHEL) instance hosted on AWS.

## Objectives
- Deploy a RHEL server on AWS EC2.
- Install and configure the Apache HTTP server.
- Ensure the web server is accessible over the internet.

## Steps Performed
1. Launched an EC2 instance with the RHEL operating system.
2. Updated the system packages.
3. Installed the `httpd` package.
4. Started and enabled the Apache service.
5. Configured security groups to allow HTTP/HTTPS traffic.

## Results
The web server was successfully deployed and the default Red Hat test page is now visible.

## How to Automate
You can use the provided `setup_webserver.sh` script to automate the installation process:
```bash
chmod +x setup_webserver.sh
./setup_webserver.sh
