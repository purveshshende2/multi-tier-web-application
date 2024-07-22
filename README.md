# Multi-Tier Web Application Setup (Locally)

## About the Project
This project aims to set up a multi-tier web application locally on your laptop or desktop. It helps you automate the setup of any project locally, making it repeatable and efficient, perfect for research and development purposes.

## Scenario
When working on a project, various services power your project runtime, such as SQL services and application services. Typically, setting up these services locally can be complex, time-consuming, and not easily repeatable. To address these issues, we propose an automated local setup using Infrastructure as Code (IaC) principles.

## Problem
- Uncomfortable making changes on real servers
- Local setup is complex
- Time-consuming
- Not repeatable

## Solution
We can automate the local setup, making it repeatable using Infrastructure as Code (IaC). This approach allows you to set up the entire stack locally multiple times, enabling you to perform as much research and development (R&D) as needed on your local machine.

## Tools
- **Hypervisor**: Oracle VM VirtualBox
- **Automation**: Vagrant
- **CLI**: Git Bash
- **IDE**: Visual Studio Code (VS Code)

## Objectives
- Automate VM setup locally
- Set up a real-world project locally for R&D purposes

## Architecture of Project Services
1. **NGINX**: A high-performance web server and reverse proxy server for serving web content, load balancing, and handling HTTP, HTTPS, and mail protocols.
2. **TOMCAT**: An open-source Java servlet container and web server used to deploy and serve Java applications and dynamic web content.
3. **RABBITMQ**: A robust message broker that facilitates communication between distributed systems and applications through message queuing.
4. **MEMCACHED**: An in-memory key-value store used for caching data to accelerate web applications by reducing database load.
5. **MYSQL**: A widely-used open-source relational database management system for storing, managing, and retrieving structured data efficiently.

## Use Cases
1. **NGINX**: Serve web content, load balancing, handle HTTP, HTTPS, and mail protocols.
2. **TOMCAT**: Deploy and serve Java applications and dynamic web content.
3. **RABBITMQ**: Facilitate communication between distributed systems and applications through message queuing.
4. **MEMCACHED**: Cache data to accelerate web applications by reducing database load.
5. **MYSQL**: Store, manage, and retrieve structured data efficiently.

## Architecture of Automated Setup
- **Vagrant**
- **VirtualBox**
- **Git Bash**

## Overview
In summary, we are setting up a website and web application. This web app is a social networking site written by developers in the Java language. The setup will be automated to ensure it is repeatable and efficient for R&D purposes.

---

## Getting Started

### Prerequisites
- Install [Oracle VM VirtualBox](https://www.virtualbox.org/)
- Install [Vagrant](https://www.vagrantup.com/)
- Install [Git Bash](https://git-scm.com/)
- Install [Visual Studio Code (VS Code)](https://code.visualstudio.com/)

### Installation

 **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
