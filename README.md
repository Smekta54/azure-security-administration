# Azure Web Application and Security Administration

## Overview

This academic project for the Security Administration module involved deploying a small Flask web application on a Microsoft Azure virtual machine and configuring its supporting infrastructure and security controls.

The application provided a login page and user profile displaying information stored in Azure SQL Database.

## Technologies and tools

- Microsoft Azure: Virtual Machines, Virtual Network, Network Security Groups, Azure SQL Database and Private Endpoint
- Ubuntu Linux
- Python and Flask
- SQL and sqlcmd
- UFW, Fail2Ban and SSH
- Bash
- HTTPS with a self-signed certificate for the lab environment

## My work

- Created an Azure resource group, virtual network, subnets and network security groups.
- Configured an Ubuntu virtual machine and connected it to Azure SQL Database using a private endpoint.
- Created database tables and integrated the database with a Flask application.
- Adapted login and profile templates and configured the application to display user information and photos.
- Configured firewall rules, SSH key-based authentication and disabled remote root login.
- Set up Fail2Ban, automatic security updates and log rotation.
- Created a Bash script to automate basic Fail2Ban installation and setup.
- Configured HTTPS using a self-signed certificate for testing.

## Challenges and outcome

During setup, I investigated database connectivity and permission issues before successfully connecting from the virtual machine and creating the required tables. I also updated the user table after the profile template required additional fields.

The resulting application displayed a login page and user profile connected to the cloud database. The project gave me experience combining Azure networking, Linux administration, application deployment and security configuration.
