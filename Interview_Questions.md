How do you implement Azure RBAC to enforce least privilege? 
What's the difference between Azure Load Balancer and Application Gateway? 
How do you use Terraform to deploy an AKS cluster with network policies enabled? - By using Network Profile Block in Terraform Configuration
What is Azure Bicep, and how is it different from ARM templates?
How would you troubleshoot pod network latency in AKS? 
What is the purpose of Fluent Bit or Fluentd in a logging pipeline? 
How do you visualize Azure Monitor metrics for custom applications? 
How can you monitor long-running jobs in Kubernetes? 
Write a Bash script to delete all pods in a namespace older than 24 hours. 
Using Python, how do you list all Azure Resource Groups and their location? 
How do you use a Makefile in automating repetitive DevOps tasks?
How do you troubleshoot DNS issues inside a Kubernetes cluster?
how to config a new set-cluster for your kubectl client 
how to static pods manage to come up even if kubectl shows as node not-ready 
what is a feature flag, how and when is it used 
how do you register your cdr

Virtual Networks (VNets)

How would you design a VNet topology for a multi-region Azure deployment?

What is the difference between a VNet peering and a VNet-to-VNet VPN? When would you choose one over the other?

How do you configure DNS resolution between VNets in different regions?

What are the best practices for subnetting in Azure Virtual Networks?

How do you manage IP address ranges within a VNet to avoid IP conflicts?

What is Azure ExpressRoute, and how does it differ from a Site-to-Site VPN?

How would you implement Private Link in Azure to secure access to PaaS services?

Network Security

How do you configure Network Security Groups (NSGs) to restrict traffic between subnets in Azure?

Explain how Application Security Groups (ASGs) are different from NSGs in Azure. When would you use ASGs?

How do you use Azure Firewall to filter inbound and outbound traffic in a VNet?

What is Azure DDoS Protection, and how does it work in protecting Azure resources?

How can you secure DNS queries in Azure and protect against DNS-based attacks?

Load Balancing and Traffic Management

How do you configure an Azure Load Balancer for a highly available application in multiple regions?

Explain the difference between Azure Application Gateway and Azure Load Balancer. When would you use one over the other?

How would you implement Azure Traffic Manager for geo-distribution of traffic to your web applications across regions?

What is Azure Front Door, and how does it improve the performance of global applications?

Hybrid Networking

How do you implement VPN Gateway in Azure for secure communication between on-premises and Azure environments?

What are the benefits and limitations of Azure Virtual WAN? How does it simplify network management?

How would you configure Azure Bastion for secure remote access to VMs in a private subnet?

Explain how to set up a hybrid DNS resolution between on-premises DNS and Azure DNS.

Describe how to implement ExpressRoute Direct for high-throughput connections between on-premises infrastructure and Azure.

Azure Security
Identity and Access Management

What is the difference between Azure Active Directory (Azure AD) and Azure AD B2C?

How would you implement Conditional Access policies in Azure AD to enforce MFA for users accessing specific applications?

Explain how Role-Based Access Control (RBAC) works in Azure. How do you assign and manage roles for users?

How do you enable Azure AD Identity Protection to protect against risky sign-ins and compromised accounts?

Describe the process of Azure AD Join and Hybrid Azure AD Join. What are the differences and use cases?

Data Security

How do you use Azure Key Vault to securely store and manage secrets, certificates, and keys?

What is the role of Azure Storage Service Encryption (SSE) in securing data at rest in Azure Storage?

How do you implement Azure Disk Encryption for VMs to ensure that disks are encrypted both in transit and at rest?

What is Azure Information Protection, and how does it help secure data at rest in Office 365 or Azure?

How do you enforce encryption for data in transit across Azure resources?

Network Security

How would you secure a public-facing Azure web application using Azure Application Gateway WAF?

Explain how to configure Azure Firewall Policies to restrict outbound traffic from a VNet.

How would you use Azure Network Watcher to monitor and troubleshoot network issues in Azure?

What is Azure Sentinel, and how does it help in identifying, responding to, and preventing security threats in your network?

How do you configure Just-In-Time (JIT) VM access to minimize the attack surface for your virtual machines?

Compliance and Governance

How do you use Azure Policy to ensure compliance with industry standards and regulatory requirements across your Azure resources?

Explain how Azure Blueprints can help ensure that deployed resources comply with organizational security policies.

What is the role of Azure Security Center in identifying and mitigating potential security risks in an Azure environment?

How would you configure Security Center standard tier to improve threat detection for workloads in Azure?

What is the difference between Azure AD Privileged Identity Management (PIM) and Azure AD Access Reviews?

Monitoring and Incident Response

How would you use Azure Monitor and Azure Log Analytics to set up alerts for suspicious activities across your Azure resources?

How do you configure Azure Sentinel to detect and respond to security incidents?

How do you manage security alerts in Azure Security Center to handle potential vulnerabilities in your infrastructure?

What is the process to set up Azure Security Center’s Threat Protection to detect threats in your workload?

How would you implement audit logging and security logging in an Azure environment to ensure that critical security events are recorded?


What is a Virtual Network (VNet) in Azure, and how does it work?

What are the different types of VPN connections supported in Azure?

Can you explain the concept of VNet Peering? When would you use it?

What is Azure Load Balancer, and how does it work with application-level traffic?

Explain the difference between a Standard and Basic SKU for Azure Load Balancer.

What is Azure ExpressRoute, and how does it differ from using a traditional VPN?

What is Azure Application Gateway, and how does it differ from Azure Load Balancer?

How do you secure communication between Azure VMs in different VNets?

What is a Network Security Group (NSG), and how would you use it in Azure?

What is Azure Firewall, and how does it enhance the security of your Azure environment?

How can you monitor and troubleshoot network traffic in Azure?

What are some strategies for optimizing network performance in Azure?

Explain the concept of Azure Private Link and its use cases.

What are the use cases for Azure Traffic Manager, and how does it help with traffic distribution?

What are the differences between Azure DNS and on-premises DNS? How would you configure DNS in an Azure environment?

what are the considerations for taking cost considerations in vnet peering in azure

Azure firewall how it differs from other network components

📍Basic Level:

What is Linux?
Briefly explain the Linux operating system and its main components.
What is the difference between Linux and UNIX?
Discuss the differences between these two operating systems, including their origins, structure, and usage.
What is the kernel in Linux?
Explain the role of the Linux kernel and its responsibilities in the system.
What are the different types of file permissions in Linux?

📍Intermediate Level:

What are runlevels in Linux?
Explain the different runlevels (e.g., 0 to 6) and their functions in system startup and shutdown.
How do you search for a string in a file?
Discuss commands like grep to search for text within files.
What is the difference between hard links and symbolic links?
Define and contrast hard links and soft (symbolic) links in Linux.
Explain the concept of pipes and redirection in Linux.
Discuss how pipes (|) and redirection (>, >>, <) work in Linux to manage input and output.
What are cron jobs? How do you schedule a job in Linux?
Explain the cron daemon and how to schedule tasks using the crontab command.
How would you check system resource usage in Linux?
Discuss tools like top, htop, vmstat, free, and iostat for monitoring system resources.
Explain the difference between fork() and exec() system calls.
Provide an explanation of these two fundamental system calls in process creation and execution.
What is SELinux and how does it work?
Discuss Security-Enhanced Linux (SELinux), its purpose, and how it enforces security policies.

📍Advanced Level:

What is the difference between a process and a thread in Linux?
Describe the difference in terms of execution, memory sharing, and management.
What is the Linux boot process?
Explain the steps involved, including BIOS/UEFI, bootloader (GRUB), kernel loading, and init/systemd.
Discuss memory management concepts like virtual memory, swapping, memory paging, and allocation.
Explain the concept of Linux namespaces.
Discuss how namespaces are used to isolate resources in Linux, such as in containers (e.g., Docker).
How does the ls command work in Linux?
Explain how ls lists files and directories, including options for detailed listings (e.g., ls -l, ls -a).
What is the ldd command used for?
Explain how ldd is used to show shared library dependencies of a program.
What is a system call in Linux?
Define system calls and provide examples.
Discuss tools like top, ps, vmstat, htop, and strace for diagnosing performance issues.
Explain how Linux handles file systems.
Discuss file system types (ext4, xfs, etc.)
What is a kernel panic?
Describe what causes a kernel panic and how to diagnose and troubleshoot it.

How does IP networking is occur in k8s
What is ARP?
How http or https traffic sent? Let’s say I typed google.com, how the packets will travel 
How the IPs assignment happens to pods
How does containers interact with each other
For killing a process we use kill 9, are there any other numbers? What they used for?
Why do we create hard link?
What happens if k8s API server goes down?
How does the authentication happens with API server? 
With kubeconfig file Kubernetes will be authenticated right?
difference beween kubectl get, describe, explain
difference between linux and unix
what does etc/passwd file has
what is the swap file version of windows
how do we change hostname in linux
fstab in linux
what happens if a pod goes down, how the k8s will schedule a new pod etc
I heard there will be filter and scoring mechanism to schedule the pods on specific node, can u explain that
What is rate limiting and throttling in API Gateway?

What is an imperative way of depoying a pod in kubernetes

how to check pods whether they are running or not

What is a pod?

how to check the pod logs

there are 5 pods, what will be the pod name - It will start with the name of the deployment, replicaset, hash value

what are k8s objects?

other than deployment where we will configure HPA -- Statful sets

what is diff between vm and agent? in the vm

it will fail in linux mostly due to wrong fstab entries

how can I configure SSL for Standard load balancer, Azure app gateway.

In how many ways we can define variables azure devops

what is soft delete in azure 

What is difference between journal ctl logs and syslog 

Windows boot process

what is service connection in azure devops? what are the common service connection types?

how can you implement multi stage pipeline in azure devops?

pipeline shouldn't run when I directly commit to main branch, only it should run with PR onlt.

you have added in variable groups. how do you call those in azure devops pipeline?

how you are going to enforce quality gates in azure devops?

what are the security scanning tools that we can integrate with azure devops?

what are deployment groups in azure devops

how do you build or create multi repo pipelines in azure devops?

how are you going to handle approvals in azure devops?

what is dynamic pods

how are you going to integrate azure devops with github

diff between pipeline variables and Variable groups?

how can we run jobs parallely in azure devops

how to enable parallelism in azure devops?

what is the purpose of service hooks in azure devops

can we integrate azure monitor with azure devops, and as well JIRA with azure devops

Difference between service connection and service hook and service principle in azure. Just give definition for each

In Jenkins declarative pipeline which section is mandatory parameters, agent, env, tools

Purpose of poll scam trigger in jenkins

Main advantage of distributed Jenkins setup with agents

Purpose of retry failed build plugin in Jenkins

Primary benefit of using Jenkins multi branch pipeline

Kubectl  rollout restart deployment command

How does kubernetes store secrets by default

In k8s RabAC which role allows a user to create new pods

What happens when a persistent volume with a retain reclaim policy is deleted

Which ansible module is used to manage docker containers 

How does ansible use dynamic inventories 

When does ansible handler execute

Advantage of using loops in ansible

Primary benefit of using ansible roles

Where do u define vars in ansible playbook 

Purpose of ansible vault

Specific condition met task can be executed in ansible 

Purpose of tags in ansible 

Which module helps handle errors and continue execution 

With items loop in asible

What is ansible fact

purpose of VLAN

ping command protocol

dhcp primary function

which network topology isfault tolerant

purpose of default gateway

what is mac address

nohup command purpose

git stash pop command

git remote -v

git diff

git merge vs git rebase

purpose of git tag

git fetch & git revert commit hash
