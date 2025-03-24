### <ins> Day-1 | Basics of Cloud Computing | Fundamentals of Azure </ins>

* Data Center -->  It is the collection of servers
* Server --> It is a computer system which has CPU and RAM required to run the applications and processes.
* Replica --> is nothing but a copy
* Few of the companies are still in private cloud because they still use legacy systems (means old or outdated computer system, software, or technology)
* multi cloud - mix of services from AWS, azure or from GCP, it is different from hybrid.
-------------------------------------------------------------------------------------------------
* Virtualization, Virtual Machine --> in olden days the full server will be allocating to a person, which is not beneficial to the company hence virtualization concept came into existence. system admin will install the hypervisor software in the server. It implements the concepts of virtualization, it breaks the server logically not physically. the breaks down servers (the logically separated servers) are called as virtual machines. 
* API --> let say Jenkins can be accessed through API and CLI. 
	API means Application Interface which will expose the application using the API, application developers (who ever can be)     allow to access the Jenkins application programmatically because to test the application or to perform some scripting. 
* Regions --> refer to geographic locations where cloud providers have data centers. Each region contains multiple data centers
* Availability Zones --> they are data centers
* Scalability -->  infrastructure scalable
* Elasticity --> Automatic scaling the infrastructure
*  Agility
* High Availability --> making available of the application most of the time (e.g. Instagram, Facebook)
* Fault Tolerance
* Disaster Recovery -->  it is technic or mechanism where you need to have plan or action if something goes wrong, it is 
  having a backup
* Load Balancing --> is to split the load between data centers

### <ins> Day-2 | Getting Started With Azure </ins>
* IAAS - Infrastructure as Service eg - VM, storage, networking, Load balancer - you will take the complete infrastructure and install the required components/software in it. Eg --> companies will take VM, Storage, Networking on top of it you will install SQL database and configure it by your own. So you are only picking up only VM, Storage, Networking.
* PAAS - Platform as service eg - companies will pick up the complete platform like database, SQL, app service - you will configure it and use it
	 Eg --> Directly using SQL service not to procure VM, Storage, Networking
* SAAS - Software as Service 
         Eg --> you will directly get the infrastructure, platform and also get the service, not to configure anything. Best example is - outlook you will 
                pay the subscription and start using. 
* why datacenters are located in different regions because is to avoid latency and downtime. Each data center is availability zone. 

### <ins> Day-3 | Resource, Resource Groups and Azure Resource Manager | Demo and Use cases </ins>
![image](https://github.com/user-attachments/assets/b63afed7-cc62-4441-ab7c-aec09c1494b3)
* Service --> what we have in azure is called services and what we create using this services is called as resources.
* To Create Virtual Machine, we fill all the properties and click on create button, after that request goes to Azure resource manager and it will 
  receive the request and create the Virtual Machine resource. Resource is the outcome of the service.
* In any of these way UI, CLI, API the request goes to azure resource manager only. 
* Resource Group --> it is mandatory, without this we cannot create the resources. It means grouping of resources. It is combination of the 
  resources like VM+DB+App resources. Why should combine --> if we group resources, we can easily to track. E.g.. if we have multiple projects, it 
  will be easily track the project and its resources, that will also allow you to manager the Access, permission, security, auditing, cost 
  monitoring etc.
* when the virtual machine is created --> parallelly it will create public Ip address, network security group, virtual network, SSH Key, Virtual 
  network, Network Interface, Disk.
* The resource and the resource group is always one to one map.




