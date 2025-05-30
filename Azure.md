1) What Kind of Different security principles you can create using or in Microsoft Entra ID?

2) What is the difference between User assigned managed identity and system assigned managed identity?

3) Which one do you prefer or suggest system or user assigned according to situation?

4) What is the purpose of creating private end points and what are the benefits it will bring?

5) what challenges we would have when creating or using the private end points.

6) Name resolution process for private end points?

7) Azure SQL server created initiallly with public access,DNS lookup using FQDN, we will get public IP.
   If I create private end point, what would be DNS name resolution.

8) What is the relationship between Private end point and Private DNS zone?

9) Can we have multiple private DNS Zones? How private DNS Zones relates to different Azure Resources?

10) Can we have a single Azure private DNS Zone for all services? Do we need multiple for different services?
    When I create a private end point, which private DNS zone will be used?

11) What is the mechanism to create a record in private DNS zone?

12) When I am creating a private end point I will get records added to private DNS zone. But If I have multiple private DNS zones, which DNS zones will be used?

13) What is Azure Security policies? What is it used for?

14) At what level Azure security policies get applied?

15) We have two virtual networks in Azure. We need to establish connection between these two networks. What options do we have?
    When Connecting two Vnets, we got an error message saying that connection not allowed. What might be the reason?

	1. Can you explain the difference between Azure IaaS and PaaS with an example of where you’ve used both in    your projects?
	2. How would you configure a Virtual Network (VNET) to securely connect Azure resources?
	3. Explain how you’ve implemented VNET peering in one of your projects.
	4. How do you configure autoscaling for Azure App Services?
	5. Walk me through how you set up a CI/CD pipeline in Azure DevOps for a web application.
	6. Can you explain the role of Azure Automation Accounts in your project?
	7. How would you automate the start/stop of Azure VMs to save costs?
	8. What are the key differences between Managed Disks and Unmanaged Disks in Azure? When would you use one over the other?
	9. Explain the process of resizing an Azure Virtual Machine. How would you ensure minimal downtime?
	10. How do you configure Azure RBAC (Role-Based Access Control) to provide least-privilege access to manage VMs?
	11. How do you set up Just-In-Time VM Access in Azure Security Center?
	12. In your experience, what tools or strategies do you use to analyze the performance of an Azure VM?
	13. How do you configure Azure Cost Management to track expenses for Azure VMs?
	14. A VM has stopped responding, and you cannot RDP into it. How would you troubleshoot and resolve this issue?
	15. What are the steps to recover a corrupted OS disk for a VM in Azure?
	16. Can you highlight some challenges you faced in your most recent project and how you addressed them?
	17. How would you set up a secure Azure environment for hosting a web application?
	18. Explain the differences between Azure IaaS, PaaS, and SaaS. When would you use each?
	19. Can you explain the steps to create a CI/CD pipeline in Azure DevOps for deploying an Azure Web App?
	20. What are Azure Runbooks, and how have you used them in your projects?
	21. What are the differences between Terraform and Azure Bicep? Which one do you prefer and why?
	22. Can you explain a simple Terraform script to provision an Azure Storage Account?
	23. How to test the reliability and scalability of an Azure Function or Web App?
	24. Can you explain how you migrated a Microsoft SQL Server database to Azure SQL Database?
	25. What are VNETs and subnets in Azure? How do they help in securing resources?
	26. You need to schedule an automatic backup of all Azure SQL Databases nightly. How to achieve this?
	27. Can you tell me a scenario where you had to debug a CI/CD pipeline failure.
	28. Your application needs to access an Azure Key Vault. How to configure access for this scenario?
	29. Create a Terraform script to provision an Azure Resource Group, a Storage Account, and a Virtual Network. Include tags for resource management.
	30. Set up a CI/CD pipeline for a sample .NET application using Azure DevOps. Ensure the pipeline deploys the application to an Azure App Service and includes an automated rollback mechanism.
	31. Explain the process of integrating Application Insights with Azure services for monitoring in your recent projects.
	32. How did you automate the scheduling of start/stop operations for app services and environments using Azure Runbooks?
	33. What kind of automation have you implemented for scaling Azure App Services in your project?
	34. How do you handle rollback scenarios during a failed deployment? Can you share an example from your project?
	35. You’ve worked with Azure DevOps, can you explain the steps involved in setting up a build pipeline and a release pipeline?
	36. How to manage version control with GitHub or Azure Repos in a large-scale DevOps environment?
	37. What are some of the key features of Azure DevOps Boards? How do you use Boards for managing sprint backlogs, tasks, and releases?
	38. Can you write a simple script to automate the process of deploying a web application from GitHub to a Docker container on an Azure VM?
	39. In your role, how can you ensure automation for tasks like environment provisioning or configuration management? Could you describe a situation where you used scripting to resolve an issue?
	40. Explain how to implement a CI/CD pipeline using Github Actions for a typical web application.
	41. In a scenario where a release is delayed due to an issue with the build process, how to handle the situation?
	42. Could you explain how you manage release health metrics? What are the key performance indicators (KPIs) that you track in a DevOps pipeline?
	43. You have a project in GitHub, and the client wants you to automate the CI/CD pipeline using GitHub Actions. The workflow should:
		a. Trigger on every push to the main branch.
		b. Build the application using Maven/Gradle (or a build tool of your choice).
		c. Run unit tests.
		d. Deploy the app to Azure.
		e. Notify the team via Slack if the pipeline fails.
	
	44. Imagine you are tasked with deploying a multi-tier application (frontend, backend, and database) using Docker and Kubernetes.
		a. Write a Kubernetes deployment YAML for deploying the application and scaling it based on load.
		b. How to handle persistent storage in Kubernetes for a database container?
		c. Create a service to expose the backend to the frontend using Kubernetes Services.
	
	45. You are working with a cloud infrastructure running on Azure and Kubernetes. Write a script or configuration for setting up basic monitoring and alerting for:
		a. CPU and memory usage in Kubernetes pods.
		b. Application logs sent to Azure Monitor.
		c. Alerts when resource usage exceeds a certain threshold.
	46. In your current project, could you describe the overall architecture of your CI/CD pipeline that you have designed for cloud applications in Azure DevOps?
	
	47. Can you explain how you handled the integration of infrastructure-as-code (IaC) into your Azure DevOps pipeline? Did you use tools like Azure Resource Manager templates, Terraform, or others to manage resources, and how did it integrate with your CI/CD pipeline?
	
	48. How do you manage different deployment strategies like Blue-Green Deployment or Canary Releases using Azure DevOps and Azure Cloud?
	
	49. In your project, how do you handle the automation of your build pipelines using Azure DevOps?
	
	50. Can you provide examples of scripts or commands you’ve used in the release pipeline for deploying to multiple environments
	
	51. You mentioned using GitHub Actions for CI/CD automation. Can you provide a practical example of a custom script you created using GitHub Actions for automated testing or build tasks? 
	
	52. In Azure DevOps, you can use Azure CLI or PowerShell commands to automate tasks. Can you give an example of how you utilized these tools in your CI/CD pipeline to interact with Azure resources, such as creating or updating Azure VMs, storage accounts, or App Services?
	
	53. In the context of your deployment pipeline, can you explain how you wrote a script that triggers the deployment process after successful completion of build steps? How do you implement a rollback strategy if something goes wrong during deployment?
	
	54. Tell me the deployment process of a web application to Azure App Services using Azure DevOps pipelines. What steps and commands do you include in the pipeline, from building the artifact to testing and deploying to production?
	
	55. How did you implement continuous monitoring during the deployment process? Could you give an example of how you track deployments in real-time, and how do you handle failed deployments?
	
	56. In your current project, how did you handle the containerization of applications using Docker? Can you walk us through the process of creating a Dockerfile for a web application and how you integrated it into your Azure DevOps pipeline?
	
	57. Once you containerized an application, how did you manage the deployment to Azure Kubernetes Service (AKS)? What steps did you follow to push your Docker images to Azure Container Registry (ACR), and how did you create and deploy Kubernetes manifests (YAML)?
	
	58. Let’s say during a deployment, your build pipeline has passed successfully, but the deployment to a pre-prod environment fails. What steps would you take to debug the issue, and which logs or commands would you check first in Azure DevOps?
	
	59. In your CI/CD pipeline, how do you handle automated testing? Can you explain how you integrated unit tests, into your pipeline using Azure DevOps?
	60. How to create an Azure Virtual Machine using the Azure CLI or PowerShell?
	61. Can you explain how to create a Virtual Network (VNet) and configure subnets in Azure using Azure CLI?
	62. How to deploy a simple web application to Azure App Service using a CI/CD pipeline?
	63. What steps would you take to push a Docker image to Azure Container Registry (ACR) and deploy it to Azure Kubernetes Service (AKS)?
	64. How to configure Azure Monitor to track the performance of an Azure Web App?
	65. How to set up an Azure Function App and deploy it via Azure DevOps?
	66. Can you demonstrate how to configure an Azure Load Balancer to distribute traffic across multiple VMs?
	67. How to configure Azure Storage (Blob, Queue, File) using Azure CLI or PowerShell?
	68. Can you explain the steps to create an Application Gateway in Azure and associate it with a web app?
	69. Write a PowerShell script to create a new Azure Virtual Machine.
	70. Write a Bash script to build and push a Docker image to Azure Container Registry (ACR).
	71. Write an Azure CLI command to create an Azure Storage account and upload a file to Blob Storage.
	72. Write a script to automate the setup of a CI/CD pipeline using Azure DevOps to deploy an application to Azure App Service.
	73. How to use Azure CLI to deploy a containerized application to Azure Kubernetes Service (AKS)?
	74. Write a PowerShell script to create a new Azure Function App and deploy a simple function using Azure DevOps.
	75. How to write a script to monitor the health of an Azure VM using Azure Monitor and trigger an alert?
	76. Write a script to configure a Virtual Network and Subnet in Azure using Azure CLI.
	77. Create a script to automatically scale an Azure App Service based on CPU utilization.
	78. Can you provide a brief introduction about yourself and highlight key achievements in your DevOps career?
	79. What was the most challenging problem you faced in your role as a DevOps Engineer?
	80. Can you explain the difference between build and release pipelines in Azure DevOps?
	81. What are self-hosted agents, and when would you prefer them over Microsoft-hosted agents in Azure DevOps?
	82. Explain how to set up a CI/CD pipeline for a microservices-based application.
	83. What are some common issues you’ve encountered in CI/CD pipelines, and how did you address them?
	84. Explain the Git branching strategies you’ve implemented in your projects.
	85. If two developers accidentally overwrite each other’s changes during a merge in Git, how to resolve this issue?
	86. Can you explain the difference between Kubernetes deployments and stateful sets?
	87. Describe how to handle rolling updates and rollbacks in Kubernetes.
	88. How to handle log aggregation and analysis in a distributed environment?
	89. Suppose a production deployment fails, and the application is down. How can you troubleshoot and recover the environment?
	90. A developer reports that their changes are not getting reflected in the QA environment. What steps would you take to investigate and resolve the issue?
	91. Write a Dockerfile for a Python Flask application and provide the commands to:
		a. Build the image.
		b. Run a container from the image.
	92. Create a YAML pipeline in Azure DevOps to build and deploy a .NET application to an Azure App Service. Include the following:
		a. Steps to install dependencies.
		b. Building the application.
		c. Deploying it to the app service.
	93. A user reports that they are unable to log in despite entering the correct credentials and receiving the MFA code. How to troubleshoot this issue?
	94. How to assign application access to specific user groups in Azure AD?
	95. What are the differences between Azure AD Join and Azure AD Domain Services, and when would you use each?
	96. A policy you implemented is blocking legitimate users from accessing Azure resources. How to troubleshoot and resolve this?
	97. If a newly registered app in Azure AD isn’t able to authenticate users, what steps would you take to debug the issue?
	98. You need to resize the OS disk of a VM from 127 GB to 256 GB, but the option is grayed out. How would you resolve this?
	99. A web application hosted on a VM is experiencing latency issues. How would you troubleshoot the performance of the VM?
	100. What are the effects of redeploying a VM, and in what scenarios would you use this option?
	101. A VM fails to boot. How to use Boot Diagnostics to investigate and resolve the issue?
	102. What are the advantages and steps for creating and deploying a custom VM image in Azure?
	103. How to recover a deleted file from a VM using a disk snapshot?
	104. What are the differences between managed and unmanaged disks, and when should you use each?
	105. An application requires extremely low latency for its database workload. How to configure Azure Ultra Disks for this use case?
	106. How to encrypt an existing disk on a running VM in Azure?
	107. What is VNet peering, and how does it work? 
	108. VNet peering allows two Azure VNets to connect for private communication. % Traffic stays within Microsoft's global backbone, avoiding the public internet. 
	109. What role do route tables play in Azure VNet configuration? 
	110. Route tables determine how traffic is directed within the 
	111. VNet and beyond (e.g., to Azure Firewall or the © internet). 
	112. AA How does Azure NAT Gateway compare to public ip addresses? 
	113. Public IP: Provides direct public-facing access to Azure resources. 
	114. NAT Gateway: Secures outbound internet traffic for private subnet resources. 
	115. What are NSGs (Network Security Groups) and ASGs (Application Security Groups)? 
	NSG: Filters inbound/outbound traffic using rules at the NIC or subnet level. 
	ASG: Groups VMs logically to simplify security rule assignments. 
	116. How can traffic be restricted between subnets in Azure? 
	117. Use NSGs, custom route tables, or both to limit or block traffic between subnets based on IP ranges, ports, or protocols. 
	118. How can you build a robust multi-region VNet architecture? 
	119. Leverage Azure Virtual WAN or VNet peering to connect VNets across regions. Ensure redundancy and low-latency performance. 
	& What are the differences between Azure Virtual WAN and VNet Peering? 
	120. Virtual WAN: Hub-and-spoke architecture for managing connectivity across VNets, regions, and on-prem environments. 
	121. VNet Peering: Direct one-to-one connection between VNets. 
	122. SO How do Azure Load Balancers integrate with VNets? 
	123. Azure Load Balancers distribute incoming traffic across VMs in VNets, enabling high availability and fault tolerance. 
	124. How can high availability be achieved in a VNet design? 
	125. Deploy across Availability Zones or Regions. 
	126. Use redundant NAT Gateways, load balancers, and VPN/ 
	127. ExpressRoute connections. 
	128. I What are the default VNet limits in Azure? 
Default: 50 VNets per region and 100 subnets per Vnet

What is an imperative way of deploying a pod in kubernetes 
how to check pods whether they are running or not What is a pod? 
how to check the pod logs 
there are 5 pods, what will be the pod name - It will start with the name of the deployment, replicaset, hash value 
what are k8s objects? 
other than deployment where we will configure HPA -- Statful sets 
what is diff between vm and agent? 
in the vm it will fail in linux mostly due to wrong fstab entries
how can I configure SSL for Standard load balancer, Azure app gateway. 
In how many ways we can define variables azure devops

Diff b/w app registration & enterprise application?
