# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
-  my choice is to go with app service since its have some free options and cheaper than VM , In app service AZURE takes care of application deployment and management, while the developer only needs to concentrate on app development. App service make me focus in devolping the application when AZURE takes care of the infrastructure, and support continuous deployment With GitHub Actions for Azure web app, developer can create workflows in github repository to build, test, package, release and deploy to Azure. 
-  In app service you have the option of horizintal or vertical scailing in vertical scaling, vertical scaling automatically increases or decreases resources allocated to our App Service, when horizintal scaling provide more VMs for your application 

- Azure provides global scale with high availability, with its datacenters around the globe. 
-   When VM the devoloper have full control of application managment and deployment. Virtual machines behaves like a full, separate computer that I am responsible for everything: maitenance, security, update etc.



### Assess app changes that would change your decision.

app service have some limitations such as: the maximum of RAM memory is 14GB if i need a larger memory i would use VM, limited set of programming languages if i am using a fluter for my applicion i can't use app service. 
