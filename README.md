Ansible Role: apache2_role
Overview
This Ansible role, is designed to automate the installation and configuration of Apache2. This document provides an overview of the Apache2 setup within this role.

Role Name
Role: apache2_role
Author: Mangesh Shrestha
Description: Roles to install Apache2.
Features
Installs Apache2 using the package manager.
Ensures Apache2 is enabled to start on boot.
Requirements
Ansible 2.9 or higher
A compatible Linux distribution (e.g., Debian, Ubuntu)
Supported Platforms
This role is compatible with the following platforms:

Debian: All versions
Ubuntu: All versions
Usage
To use this role in your Ansible playbook, include it as follows:

- hosts: your_target_hosts
  become: yes
  roles:
    - 
