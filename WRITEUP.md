## Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### My Choice for deploying Application
The service I choose for deploying this web application is App Service.

### Why App service for my App?
- Azure App Service handles everything and all I have to do is build and setup my application and rest will be taken care.b
- Azure App service has a built-in infrastructure maintenance, security patching, and scaling.
- Azure App service Support multiple languages, such as .NET, Java, Ruby, Node.js, PHP, or Python.
- Azure App service allows me to Quickly build and deploy my web application to Azure cloud.
- Azure App service is less expensive than Virtual Machines. It provide different plans options such as Free and Shared (preview) plans to test or deploy an app. App Services also has built-in load balancers that help save infrastructure costs.
- Azure App service can be hosted anywhere in the world & is highly available.
- Azure App service support automated deployments from GitHub, Azure DevOps, or any Git repository. With GitHub Actions for Azure web app, developer can create workflows in github repository to build, test, package, release and deploy to Azure. 

### Why not Virtual Machines?
- I have to control the underlying Operating System or install a software on the server which is much complex & time consuming to get started with my production ready application.
- Virtual machines is like computer or laptop where I have to install everything required to get started

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

- Azure app service has a hardware limitations. Also is not an appropriate solution for apps which have scope to expand for future. Instead, VMs are preferred. If this app grows to a larger scale, when we have vast increase in the number of users or when more features are added to the app, I would choose a Virtual Machine.
- For advanced scaling (auto) and traffic management features, I would go for VM. this can be done easier with Azure Virtual Machine Scale Sets.
- Using App service, I have limited access to the host server, if I want to control the underlying OS or install a software on the server, I have to choose Virtual Machine.
- If this application is later implemented using another programming language that is not supported by Azure app service. here, I will choose VM and create the environment for that programming language.