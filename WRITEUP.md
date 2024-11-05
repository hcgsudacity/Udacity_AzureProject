# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

After assessment, an App service was chosen, due to the current use case, when there's primarily no need for high performance compute service, and a simple app is being created, allowing developer to focus on the application, and worrying less about the OS level.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

Decision would probably change, when there would be a higher usage demand of the application, which would require changes on the compute or memory of the underlying infrastructure.
