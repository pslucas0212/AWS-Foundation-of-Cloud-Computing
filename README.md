# AWS Foundation of Cloud Computing

[AWS Review Notes Table of Contents](https://github.com/pslucas0212/AWS-Review-Notes)

## Understanding Cloud Computing Resources
Cloud Computing delivers computing services over the Internet like:
- Compute
- Networking
- Storage
- Analytics
- Development
- Security
- Databases

Virtual Mahcines

Usage for services is on-demand with a pay-as-you-go model

Study for Exam
- Learn the categories.  Lambda and EC2 are compute services.
- Read the whitepaper.  Read the "Overview of Amazon Web Services" whitepaper, and review it again the day before your exam.

## Exploring the Advantages of Cloud Computing

Six Advantages to Cloud Computing
1. Go global in minutes
2. Stop spending money running and maintaining data centers
3. Benefit from massive economies of scale
4. Increase speed and agility
5. Stop guessing capacity
6. Trade capital expense for variable expense

CapEx vs OpEx

Study for Exam
- Understand the 6 advantages.  Explain the 6 advantages and understand how the cloud saves you money.
- Understand cloud terminology.  Explain high availability, elasticity, agility, and durability.

## Reviewing Cloud Computing and Deployment Models
Three Cloud Computing Models
1. On-premeise or Private Clouc
2. Public Cloud
3. Hybrid Cloud.  Link Private Cloud to AWS public cloud via AWS Direct Connect

Study for Exam
- Know the computing models. Explain the 3 common cloud computing models.
- Know the deployment models. Explain the differences and understand that hybrid deployments are supported by Direct Connect.

## Leveraging the AWS Global Infrastructure
Region is a physical location grouped into geographic locations.  Fully independant and isolated.  Resource and service specific.
Availability Zones (AZs) consist of one or more physically separated data centers,each with redundant power, networking, and connectivity, housed in separate facilities.
Edge locations cache content for fast delivery to your users.

Latency is the time that passes between a user request and the resulting response.

Study for Exam
- Multi-AZ deployments provide high availability. Systems that are highly available are dependable enough to operate continuously without failure.
- An AZ has multiple data centers. You can think of an AZ as a collection of data centers.
- A Region is global and has 2 or more AZs.  Regions are geographically isolated locations around the globe.
- Edge locations ensure low latency by placing content closer to users. There are more edge locations than Regions and AZs.

## Exploring Your AWS Account
- The AWS Management Console allows you to access your AWS account and manage applications running in your account from a web browser.
- Root User (and MFA)
- The AWS Command Line Interface (CLI) allows you to access your AWS account through a terminal or command window. 
- Programmatic access provides access to your AWS resources through an application or a tool like the CLI.
-- CLI
-- Application Code
-- SDK

Study for Exam
- Understand the root user. The root user should be protected with MFA. 
- The power of the root user. There are certain things that only the root user can do.
- The CLI.  Understand what's stored on your local machine to access AWS via the CLI.
