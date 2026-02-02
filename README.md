# Static Website Hosting on Microsoft Azure

## Project Overview
This project demonstrates how a static frontend website can be hosted on Microsoft Azure using Azure Blob Storage's Static Website feature. The goal is to provide a serverless, scalable, and cost-effective hosting solution without using virtual machines or traditional web servers.

## What is a Static Website?
A static website contains only frontend files such as HTML, CSS.
- No backend logic
- No database
- Content is served directly to users

## Problem Statement
Traditional hosting methods require:
- Purchasing and managing servers
- Operating system maintenance and security updates
- Higher cost even for simple frontend websites

This approach is inefficient for static applications.

## Solution
Azure Blob Storage provides a Static Website feature that allows direct hosting of static files. This eliminates the need for server management while ensuring high availability and scalability.

## Tools and Technologies Used

### Frontend
- HTML – Structure of the website
- CSS – Styling and layout

### Cloud Platform
- Microsoft Azure
- Azure Portal
- Azure Resource Group
- Azure Storage Account
- Azure Blob Storage
- Static Website feature

### Version Control
- Git
- GitHub

## Architecture Flow
User Browser  
↓  
Azure Static Website Endpoint  
↓  
Azure Blob Storage ($web container)  
↓  
HTML / CSS / JavaScript files  

## Deployment Process (High-Level)
1. Frontend files are created locally
2. Source code is pushed to GitHub
3. Azure Storage Account is created
4. Static Website option is enabled in Blob Storage
5. Files are uploaded to the `$web` container
6. Azure provides a public endpoint URL
7. Users access the website through the URL

## Key Learnings
- Basics of cloud computing
- Serverless hosting concepts
- Azure storage services
- Cost-effective cloud architecture
- Understanding when not to use virtual machines

## Future Enhancements
- Enable Azure CDN for faster global access
- Add custom domain support
- Automate deployment using GitHub Actions
