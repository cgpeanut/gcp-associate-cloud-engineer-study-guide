```
gcp associate engineer certification exam objectives
    - planing a cloud solution using one or more gcp services
    - creating cloud environemtns for an organization
    - deploying applications and infrastructure
    - using monitoring and logging to ensure availability of cloud solutions
    - setting up identity managament, access controls, and other security measures.
objective map:

section 1: setting up a clopud solution environment 

1.1 setting up cloud projects and accounts
    - creating a project
    - assigning users to predefined IAM (identity access management) roles within a project
    - linking users to G suite identities
    - enabling APIs within projects
    - provisioning one or more stackdriver accounts

1.2 managing billing configuration.
    - creating one or more billing accounts
    - linking projects to billing accounts
    - establishing billing budgets and alerts
    - setting up billing expports to estimate daily/monthly charges

1.3 installing and configuring the command-line interface (CLI), specifically
    Cloud SDK (setting up default project)

section 2: Planing and configuring a cloud solution

2.1 planning and estimating GCP product use using price calculator

2.2 planning and configuring compute resources. considerations include:
    - selecting appropriate compute for a given workload (compute engine, kunernetes engine, app engine)
    - using preemptible VMs and custom machine type as appropriate.

2.3 planning and configuring data storage options. 
    - product choice (e.g: Cloud SQL, BigQuery, Cloud Spanner, Cloud Bigtable)
    - choosing storage options (regional, multiregional, nearline, coldline)

2.4 planning and configuring network resources. Tasks include:

- differentiating load balancing options
- identifying resource locations in a network for availability
- configuring cloud DNS

Section 3: Deploying and implementing a cloud solution 

3.1 deploying and implementing compute engine resources. Tasks include:

- launching a compute instance using cloud console and cloud SDK (gcloud) (assign disks, 
availability policy and SSH key)
- creating an autoscaled managed instance group using instance template.
- generating/uploading a custome SSH key for instance
- accessing compute quotas and requesting increases
- installing the stackdriver agent for monitoring and logging

3.2 deploying and implementing kubernetes engine resources. task include:

- deploying kubernetes engine cluster
- deploying a conatiner application to kubernetes engine using pods
- configuring kubernetes engine application monityoring and logging

3.3 deploying and implementing app engine and cloud functions resources tasks include:

- deploying an application to app engine (scaling configuration, versions and traffic splitting)
- deploying a cloud function thast receives Google Cloud events (cloud Pub/Sub events,
  cloud storage object change notification events)

3.4 deploying and implementing data solutions tasks include:

- initializing data systems with products (CloudSQL, cloud datastore, BigQuery, Cloud Spanner, Cloud Pub/Sub, Cloud BigTable, Cloud DataProc, Cloud Storage)
- loading data (command line upload, API transfer, import/export, load data from cloud storage, streaming data to cloud Pub/Sub)

3.5 deploying and implementing networking resources. tasks include

- creating VPC and subnets (e.g custom-mode VPC, shared VPC)
- launching a compute engine instance with custom network configuration (internal-only 
  IP address, google private access, static external and private IP address, network tags)
- creating ingress abd egress firewall rules for a VPC (IP subnets, tags, service accounts)
- creating a VPN between a Google VPC and an externsal network using Cloud VPN
- creating a load balancer to distribute application network traffic to an application (global HTTP(s) load balancer, global SSL proxy load balancer, global TCP proxy load balancer, regional network load balancer, regional internal load balancer)

3.6 deploying a solution using cloud launcher Tasks include: 
- browsing the cloud launcher catalog and viewing solutions details
- deploying a cloud launcher marketplace solution

3.7 deploying an application using deployment manager tasks include
- developing deployment manager templates to automate deployment of an application
- launching a deployment manager template to provision GCP resources and configure an
  application automatically. 

section 4: ensuring successful operation of a cloud solution

4.1 managing compute engine resources task include
- managin a single VM instance (start, stop, edit configurations, or delete an instance)
- SSH/RDP to an instance
- attaching a GPU to a new instance and installing CUDA libraries
- viewing current running VM inventory (instance IDs, details)
- working with snapshots (create a snapshot from a VM, view snapshot, delete snapshot)
- working with images (create an image from a VM or a snapshot, view images, delete
  an image)
- working with instance groups (set autoscaling parametersm assign an instance template,
  create an instance template, remove an instance group)
- working with management interfaces (cloud console, clous shell, cloud SDK)

4.2 managing kubernetes engine resources tasks include
- viewing current runing cluster inventory (nodes, pods, services)
- browsing the container image repository and viewing container image details
- working with nodes (add, edit, or remove a node)
- working with pods (add, edit, or remove a pods)
- working with services ( add, edit, or remove a service) 
- working with management insterfaces ( cloud console, cloud shell, cloud SDK)



chapter1: Overview of GCP Platform
chapter 2: GCP Computing Services
chapter 3: projects, services, accounts and billi g
chapter 4: introduction to computing in google cloud
chapter 5: computing with compute engine virtual machines
chapter 6: managing virtual machines
chapter 7: computing with kubernetes
chapter 8: managing kubernetes clusters
chapter 9: computing with app engine
chapter 10: computing with cloud functions
chapter 11: planning storage in the cloud
chapter 12: deploying storage in google cloud platform
chapter 13: loading data into storage
chapter 14: networking in the cloud: virtual private cloud and virtual private networks
chapter 15: networking in the cloud: DNS, load balancing, and IP addressing
chapter 16: deploying applications with cloud launcher and deployment manager
chapter 17: configuring access to security
chapter 18: manitoring, logging and cost estimating
```