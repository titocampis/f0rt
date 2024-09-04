# Ansible Role: f0rt

## Introduction
Welcome to **f0rt**! 🛡️ Your go-to Ansible role for effortlessly securing your servers against the wild world of cyber threats. With **f0rt**, you can kick back and relax as it takes care of all the heavy lifting—deploying and configuring **Fail2Ban** to keep those pesky intruders at bay by automatically detecting and blocking malicious activity. 

It also installs and configures **Firewalld**, setting up robust firewall rules that act like a fortress around your server, keeping unwanted traffic out while ensuring your services run smoothly.

## Requirements
### Ansible Collections
- ansible.posix
- community.general

### Other Requirements
- Root access, so either run it in a playbook with a global become: true.
- Include the role in your playbook and run it using the correct --tags for each task you want to perform.

## Tags
| **Tags**              | **Description**                                                 |
|-----------------------|-----------------------------------------------------------------|
| `f0rt`                | Full Role                                                       |
| `f0rt_firewalld`      | Ensure firwalld installed and configured for your necessities   |
