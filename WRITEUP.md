# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*
- *A VM is the more expensive option, and can be grouped to provide high availbility through failover mechanisms and redundancy, and scalability. They also allow for full control over the operating system and the ability to install custom software. However, they can be more time-consuming for developers to manage. App Service allows you to set the amount of hardware allocated to host your application, and the cost varies based on the plan you choose. App Service supports both vertical and horizontal scaling as well as high availibility. App Service supports a continuous deployment model using GitHub, Azure DevOps, or any Git repo. It simplifies the deployment process and allows developers to focus on the application rather than the underlying infrastructure. For this app, I believe App Service is the way to go.*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
* For a more complex app where I needed more control and customizations, I would select the VM option.*
