Write-up
App Deployment using Microsoft Azure

Virtual Machine
Azure IaaS provides full access to the OS of a compute resource, available as Windows or Linux machines, offering great availability, scalability, and redundancy. They require more maintenance by cloud developers.

App Service
Azure PaaS allows developers to focus on their apps while Azure manages the infrastructure. It's an HTTP-based service for hosting web applications, REST APIs, and mobile backends, supporting multiple languages and continuous deployment.

Choosing the Right Resource for the CMS App
Appropriate Solution
App Service is the suitable choice for deploying this web application.

Why App Service
Comprehensive tools for websites, mobile backends, and web APIs.

Built-in infrastructure maintenance, security patching, and scaling.

Supports multiple languages (e.g., Python, .NET, Java).

Quick build, deploy, and scale capabilities.

Why Not Virtual Machines
No need to control the OS or install software on the server.

Rapid deployment without creating a programming environment.

Full responsibility for maintenance and security with VMs.

Justification Based on Cost, Scalability, Availability, and Workflow
Cost: App Service is less expensive with plans like Free and Shared. Built-in load balancers save infrastructure costs.

Scalability: Easily scale apps horizontally or vertically with Auto Scaling.

Availability: Host apps globally with high availability.

Workflow: Automated deployments from GitHub, Azure DevOps, or any Git repository. GitHub Actions streamline workflows for build, test, package, release, and deploy.

Potential App Changes Affecting Decision
App Service limitations in hardware and future expansion; VMs preferred for larger scale and advanced features.

Advanced scaling and traffic management easier with Azure Virtual Machine Scale Sets.

Different programming languages not supported by App Service might necessitate VMs.


