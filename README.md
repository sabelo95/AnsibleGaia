# Hello Gagia Deployment with Ansible and Docker

This project automatically deploys a basic web application on an AWS EC2 instance using **Ansible**, executed from a **Docker** container.

## 🧱 Technologies Used

- Docker
- Ansible
- AWS EC2 (Ubuntu 20.04)
- Nginx

## 🚀 What Does This Project Do?

Using an Ansible playbook, it performs the following steps:

1. Installs **Nginx** on a remote EC2 instance.
2. Creates an `index.html` file with the message `Hello Gagia`.
3. Ensures that the **Nginx** service is running and enabled on boot.




