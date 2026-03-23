# AWS Cloud Practioner

## Module-00 : Course overview

## Module-01 : Introduction to Amazon Web Services

## Module-02 : Compute in the cloud

## Module-03 : Global infrastructure and reliability

## Module-04 : Networking

## Module-05 : Storage and databases

## Module-06 : Security

## Module-07: Monitoring and analytics

## Module-08: Pricing and support

## Module-09: Migration and innovation

## Module-10: AWS Certified Cloud Practitioner



### Basic client-server model

<img width="390" height="170" alt="image" src="https://github.com/user-attachments/assets/f9f3fd0f-ba49-4a49-ba89-67a1f7484fa2" />

# What is Cloud Computing:

-> Access services on demand
->Avoid upfront large investments
->Provision computing resources as needed.
->Pay only for what you use

->Client-server model enables Cloud Computing
->Cloud computing refers to the on-demand delivery of IT resources and applications through the internet.


->pay as you go pricing 



### What is the server composed of?
->CPU, RAM, Storage, Database & Network

cpu + ram acts as a brain which means cpu will perform computation tasks like calculations, where as RAM will retrieve the information fastely.
these two act a a brain.

Storage: Data(Binary)
Database: stores data in structured way
network: routers switches & DNS server


If i Elaborate more on Network:
->Network is some thing that has routers, switch & the DNS server connected with each other.

routers: This is a networking evice that forwards datapakets between computers.

switch: it takes the Data packet and sent it to correct server/client on your network.

<img width="763" height="252" alt="image" src="https://github.com/user-attachments/assets/59cd4ae9-1f4b-46f9-b957-7ca309110b95" />


### IAM Users & Groups

-> IAM is a global service(Identity and access Management)
-> Root account created by default. shouldn't be used or shared.
-> users are people with in your organisation, and can be grouped.

-> Groups only contain user not any other groups
->users can belong to no group or multiple groups.

<img width="845" height="197" alt="image" src="https://github.com/user-attachments/assets/45e190a6-bb16-4890-84b3-2d8fcde3917f" />

IAM permissions:
-> users and groups can be assigned  JSON document called policies
users can belongs to group, there can be an individual users may or may not belongs to the group.
Root account is creted by defult, should not be or shared
IAM stands for identity and access management, It is a global service.
users can be merged and form a group but groups may not have other groups. 

### What is AWS?

  AWS(Amazon Web Services) is a cloud provider.
  AWS can provide you with servers and services 

### IAM: Permissions

Here, users and groups were assigned a JSON document called policies

##### Sample example
<img width="460" height="415" alt="image" src="https://github.com/user-attachments/assets/4a209573-5b2d-4f2d-91ab-825c4cc415be" />

Here we can see, as per my undersanding we have two parts, one we can consider as the head and the other as the body
Head = version
Body = statement
Here, version means date we can say as per the image.
When we go to statment section, we  have other fields as well. Let's break down all the things one by one.

I can see there are three keywords in common. Effect, Action, Resources

Effect can be some thing like allowing or disabling the resoures to be used by the user or the group.

Action is is some thing we are trying to access a particular resource from AWS.
Resources are some thing those are other extensions of actions, as per my understanding.

In AWS we dont allow user to use all ths servces because of traffic. and also a new user can launch a service and it will costs you a lot of money.

In AWS, we apply the least privilege principle. We wont give more permission then the uesr need.









