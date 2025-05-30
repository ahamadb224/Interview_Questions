your client is migrating a monolithic application to a cloud native microservices architecture. How would you design the solution to ensure scalability, reliability and cost effectiveness? 

a client wants to automate infrastructure provisioning across multiple cloud providers, how would you approach this. 

your organization is adopting a multi cloud strategies. What key challenges did you do you foresee, and how would you overcome them? I that. 

What is open policy agent?

struggling with long deployment times? wants to optimize the ci/cd pipeline to reduce the time? how to do?

developer put a fault code to prod, how do you design a rollback strategy?

flakey testing in automated test?

Git-secrets, GitGuardian, TruffleHog, Gitleaks to scan the code for any secrets in git files?

What do you do for avoid leaking of secrets in github actions?
how do you configure to detect secrets?

GitOps ensures all infrastructure changes go through version-controlled repositories before applying them.

Define a GitOps Workflow
Developers must commit changes to a Git repository.
Use pull requests (PRs) for code reviews and approvals.
Terraform runs in CI/CD pipelines (e.g., GitHub Actions, GitLab CI/CD).

what is the bootup process of linux? how its going to bootup?
systemd - is the first process and then it will start all other process

how are you going to handle incident management in SRE?

using monitoring and alerting tools?

What is chaos engineering?

a process is causing a high memory usgae? how do you kill it or isolate it?

users home directory is missing? how you are going to resolve it?

ntp server? time adjustement

ntp sync
cloning, snapshot of db, backup
restore and recover -db

how do you troubleshoot nfs is unable to mount it on the VM?
1. if nfs serice or app is not installed
2. when nable to ping nfs, they also u can't 
3. if any firewall configured, then also you can't mount

adding 100 gb to VM? Volume mounting -- need to review

boot diagnose & serial console logs -- full access to VM

/etc/fstab has info about all the mount points.

I have a database (azure sql database), SSMS using that I am connecting to db, 

nslookup db url, I see a public IP, 

How I can make db connection to VM internally?

by using private end points?

separately create a private subnet, we create private end point and we can connect to db using private endpoint

It will create another network interface where it connects internally

what is the load average value in the top command means?

what are best practices for on-call rotation?

when the app is running and you need to reduce the fie size to zero to make the app able to write log files?

there is a corrupted file system. how are you going to resolve it?

fsek command - file system check command

occurence changing- sed without opening

with opening - trying to replace the occurence of some word - 

pod is freezed but status is showing as running.

what is your experience with tenants? do you know about cross tenants syncronization in devops?

have you ever assigned rbac roles to management level?

what is delegated identity?

microsoft graph API?

What kind of activities we do in PIM?

what security compliance frameworks are followed in your project?

what is the difference between private end point and service end point?

how to access services within the cluster?

how do you convert monolithic app to microservice app? what are the tools you use?

what is CNI? where do we use it?

have you come across any migration strategy? what were your steps in migration?

how do you make sure of security and compliance post migration?

diff b/w firewall and nsg?

diff b/w azure sql and cosmos DB?

when prod server is slow, how do you handle that situation

what are Key componenets of Azure Monitoring?

How do you configure azure monitor alerts?

How does promatheus collects data?

How are we going to setup alerts in promatheus?

How are we going to create Grafana alerts?

How do you monitor AKS cluster using promatheus and Grafana?

How are we going to monitor logs from AKS cluster in Azure monitor?

Can we integrate Azure monitor with third party monitoring tools?

If you are using Azure monitor for log retention? what is going to happen?

How we can monitor background jobs in application insights?

How promathus is going to handle large scale metrics data?

How do you monitor kubernetes cluster control plane using promatheus?

can we setup grafana dashboard dynamically using terraform?

how do you configure grafana alerting with azure monitoring?

how do you Setup end to end monitoring or log capturing for microservice application in AKS? how to do that?

what different types of data collected by Azure monitoring?

how are we going to monitor AKS using azure monitor?

how do you analyze data in azure monitor using KQL?

can you ensure high availability for promatheus in prod environment?

common data sources that can be connected to azure log analytics? NSG flow logs

diff between azure monitor and log analytics?

default log retention period for log analytics?

how log analytics helps in troubleshooting issues in AKS?

diff b/w diagnostic logs and log analytics logs?

can log analytics works with hybrid cloud environment?

how can we secure azure log analytics?

how to differentiate between structured logs, semi structred and unstructured logs

what are different log categories in azure? 6 logs

If I want to block internet access to azure VM? using azure firewall

how do you differentiate b/w threshhold base alert and rate based alert?

what is the difference between virtualization and containeraization?

high priority issue arises in prod. Critical resources down in kubernetes cluster? how do you resolve it?

alerts are not on time? how do you resolve the monitor?

developer wants to setup docker with specific version? how do you do it?

how do you integrate monitoring tools promatheus and grafana in kubernetes?

how do you configure promatheus scarping?

what is the extra feature we get in promatheus when compared with Azure Monitor?

how do you diagnose the performance issue/degradation in containerization environment in public cloud evironment

what kind of security principles can be created with microsoft Azure AD?

rotation of service principles and secrets. how often do we need to do?

how often secret peas or portion?

if we create azure sql server, how do you add access for logical functions?

through terraform how do you check different subscriptions in azure?
How can you minimize cost in AKS cluster?

How can Azure load balancer contribute to scalability?

where do we configure the SSL/TLS certificates?

how can we prevent resource over provisioning in Azure? -- using Azure Advisor

What is auto healing in Azure App service?

How does Azure blob storage scale automatically?

What are the performance tiers in Azure storage?

how can you scale Azure SQL database?

What is DPUs?

what is automating tuning in azure database?

what is azure reserved instances. how can it reduce the cost?

how do you downsize the VM?

how do you prepare a AKS cluster for holiday season?

what is partition key in azure db?

what is the difference between reserved instances and on demand instances?

what is the typical use cases of spot VMs?

what is predective auto scaling?

how we can perform cost analysis?

what is a cost centre?

what is the criteria for eviction of azure spot VMs?

what is the notice time azure give us? -- 30 sec

on what basis azure spot Vms get charged? -- hourly

which is cost effective horizontal scaling or vertical? -- horizontal

how do you fetch a client secret you already provisioned in App registration?

command to fetch secret in powershell?

Want to setup a load balancer, what information you would ask me?

SCCM in Azure -- for patching

what level of patching you can do with SCCM?

How do you configure private end point for Azure storage account.

Difference between RBAC and ACL(Access Control lists)
In Azure, RBAC (Role-Based Access Control) provides broad, company-wide security control, while ACLs (Access Control Lists) offer fine-grained access control for specific resources like files and directories. RBAC uses role assignments to apply sets of permissions to users or groups,
whereas ACLs allow for more detailed permissions,
such as write access to a specific file or directory.

How do you configure Azure policy to restrict a VM SKU?

you want to track cost of work loads per team in a shared cluster? --namespaces, labels -- resource quotas

how can you simulate and test high availability for the node failures? -- by using cordon and drain

Difference between cordon and drain?

what is the impact of the master node on worker nodes in k8s?
- No new workloads schedules won't happen
- Nothing happens to existing work schedules
- if any pod goes down, it won't create the new pod

-- While upgrading k8s cluster, we got a failure due to network issue. Issue with vault configuration.
-- After fixing the valut configuration, we were good.

What was your involvement with conditional access?
Did you set policies, advise, or recommend? Please share your experience.

And for AD Connect, do you remember if you used pass-through authentication
or password hash syncing, or is that where ADFS may be used?

If you have on-prem servers where you want to run your pipeline from,
you can have a self-hosted agent that you install on them.
If you prefer doing it from the Azure side,
you can spin up an Azure VM that has a Microsoft-hosted agent.
What is your take on this, and which one would you choose for one over the other?

We have client application /desktop with many different technologies that are web based some are only desktop.
The lift/shift involves migrating the  on-premises server to the azure.
We have many different add on products and technology stacks like Angular node js.
Do you have any experience  with deploying any web applications, desk top applications?

how many parallel resources terraform can create? - 10, each run requires 512 MB minimum, so for 10 runs it need 5.2 GB of memory
we can increase these runs capacity_concurrency settings, but we need to make sure we allocate the memory accordingly. Its not recommended to go down below 512 MB

pipeline creation for creating service principles with a password

Network virual appliances

Azure firewall how it differs from other network components

Diff b/w app registration & enterprise application?

How can you give app API permissions in another tenant?

You logged into computer, and found that Azure AD sync not happened from past 8hours. what you do?

Azure virtual desktop has two types of users
1.User
2.Admin

application group -- various applications
remote group   -- remote desktop

First we need to create host pools
Manage--> Hostpools

for pool of virtual machines, this gonna act as a host

i want list of users and permissions in IAM, how do we get it?  -- Azure AD is the answer

walk me thorugh any security compliance you worked with?

can you walk me through ASR & DR ?

when you enable express route, how do you monitor that connectivity.

When you did the AKS deployment for a multi region application was the control plane in one region or in multiple region n how did you ensure HA?

what is service connection in azure devops? what are the common service connection types?

how can you implement multi stage pipeline in azure devops?

pipeline shouldn't run when I directly commit to main branch, only it should run with PR onlt.

how are you going to secrets in azure devops?

how do you implement Rollback in azure devops pipeline?

you have added in variable groups. how do you call those in azure devops pipeline?

what is the diff b/w self hosted and microsoft hosted agent?

how you are going to enforce quality gates in azure devops?

what are the security scanning tools that we can integrate with azure devops?

how do you build or create multi repo pipelines in azure devops?

what are deployment groups in azure devops?

how are you going to handle approvals in azure devops?

what is the difference between classic and YAML pipeline in azure devops?

how do you manage artifacts in azure devops pipeline?

what is dynamic pods?

diff between pipeline variables and Variable groups?

how can we run jobs parallely in azure devops? we need to enable parallelism?

how do you enable conditionalism in azure devops pipeline?

how to integrate azure key vault with azure devops?

difference between service principle and managed identity?

what is the purpose of service hooks in azure devops?

1. In a cluster with two nodes, one with pods and the other without, which node will a new pod be scheduled to?

2. If an application running in a container encounters an OOM (Out-of-Memory) error, will the container restart, or will the entire Pod be recreated?

3. Can application configurations such as environment variables or ConfigMap updates be applied dynamically without recreating the Pod?

4. Is a Pod stable once created, even if the user takes no further action?

5. Can a Service of type ClusterIP ensure load balancing for TCP traffic?

6. How should application logs be collected, and is there a risk of losing logs?

7. If an HTTP Server Pod’s livenessProbe is functioning correctly, does it mean the application is problem-free?

8. How can an application scale to handle traffic fluctuations?

9. When you execute kubectl exec -it <pod> -- bash, are you logging into the pod?

10. How would you troubleshoot if a container in a Pod repeatedly exits and restarts?

”Draw a map of authentication and Microsoft services in a hybrid environment, 
i.e. with an AD,   SharePoint, SQL Server ; Microsoft online services,
Azure and M365

Different types of backups? Full, Incremental, Differential
