# Nginx Installation Playbook

An Ansible playbook for automated Nginx installation and configuration on Ubuntu servers.

## Playbook Details

- File: `nginx.yml`
- Purpose: Install and configure Nginx web server
- Target: Ubuntu servers

## Features

- Installs latest Nginx package
- Automatically updates package cache
- Starts Nginx service immediately
- Enables Nginx to start on system boot

## Usage

```bash
ansible-playbook -i inventory nginx.yml

## Requirements
- Ansible installed on control node
- Ubuntu target servers
- SSH access with sudo privileges

# LAMP Stack Playbook

An Ansible playbook for automated LAMP (Linux, Apache, MySQL, PHP) stack installation on Ubuntu servers.

## Playbook Details

- **File**: `lamp.yml` 
- **Purpose**: Complete LAMP stack deployment
- **Target**: Ubuntu servers

## Features

- Installs and configures Apache2 web server
- Installs MySQL database server  
- Installs PHP and essential extensions
- Automatically starts and enables all services

## Usage

```bash
ansible-playbook -i inventory lamp.yml

## Requirements
- Ansible installed on control node
- Ubuntu target servers
- SSH access with sudo privileges
