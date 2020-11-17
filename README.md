```
gcp associate engineer certification exam objectives
    - planing a cloud solution using one or more gcp services
    - creating cloud environemtns for an organization
    - deploying applications and infrastructure
    - using monitoring and logging to ensure availability of cloud solutions
    - setting up identity managament, access controls, and other security measures.

objective map:
    https://cloud.google.com/certication/guides/cloud-engineer/

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

1.3 installing and configuring the command-line interface (CLI), specifically Cloud SDK (setting up default project)

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
- deploying a cloud function thast receives Google Cloud events (cloud Pub/Sub events, cloud storage object change notification events)

3.4 deploying and implementing data solutions tasks include:

- initializing data systems with products (CloudSQL, cloud datastore, BigQuery, Cloud Spanner, Cloud Pub/Sub, Cloud BigTable, Cloud DataProc, Cloud Storage)
- loading data (command line upload, API transfer, import/export, load data from cloud storage, streaming data to cloud Pub/Sub)

3.5 
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