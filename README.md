#### What is AWS Cloud?
	- AWS (Amazone Web Service) is cloud platfrom.
	- The first product (S3) was released in 2006.

#### Why AWS?
	- Largest cloud provider
	- popular
	- big community


#### Different Cloud Services
	- On-premises (Traditional): We configure and manage the entire data center, such as the network cables, storage and servers. We that means the users are responsible for all parts of the application environment, support, and redundency. This approach provides maximum control, but with a lot of management overhead.
	- Infrastructure as a Service (IaaS): We purchase the base compute resources from a vendor that manages the core instructure. We create and Manage the VMs, data and applications. The cloud provider is responsible for the physical infrastructure, host management and resiliency. We may an infrastructure team to help support and deploy VMs, but the team is free form the time and cost of managing the physical equipment.
	- Platform as Service (PaaS): We purchase the underlying platform stack from a vendor that manages the OS and patches and bring your applications and data. User's don't have to worry about VMs or the virtal network and your operations team can focus more of their tie on application reliabilty and performance.
	- Software as a Service (SaaS): We just need access to software wth a vendor providing everything else. Developers can build against an existing platform to provide customizations or unique features without having to maintain a large code base.

#### Deployment model of cloud
	- Public Cloud
	- Private Cloud
	- Hybrid Cloud
	- Multi Cloud
	- Community Cloud
#### AWS Region
	- a region is a specific geographical area where AWS data centers cnters are located. Each region is separate and isolated geographical area with multiple data centers called Availability Zones (AZs). AWS operate in multiple regions.
	- An AWS region is like a specific area or location where AWS has its data centers. Each region is ike a separate zone that contains multiple data centers.
	- The purpose of having multiple regions is to make it easier for aws customers to use their services. By selecting the region colsest to their location, customers can ensure faster performance and lower latency. Regions also offer redundency and backup options , so if one region has an issue or outage, services and data can be quickly and seamlessly transferred to another region.
	- Advantage:
		- Data Residency and COmpliance
		- High Availability
		- Fault Tolerace and Disaster Recovery
		- Reduced Latency
		- Service Availability and Feature Parity
		- Cost Optimization
	- regions are independet of each other and resources created in one region are not automatically replicated to others.
	- Regions in AWS provide geograohical diversity, high availabity, fault tolerance, compliance adherence, reduced latency and flexibility in deploying applications and services to meet the need of global customers.

#### Availability Zone
	- An AWS availability zone (AZ) is an isolated location within an AWS region. Each availability zone's is essentially a separate data canter facility with its own power, cooling and networking infrastructure. These availibility zones are designed to be physically and logically separate from each other to ensure fault tolerace and high availabilty.
	- Adavanatge:
		- Redundancy
		- Fault Isolation
		- Low Latency
		- Scalability	
		- Disaster Recovery
		- High-Speed Networking
		- Independent power and cooling
		- Compliance and data Residency
		- Flexibility
		- Multi-AZ Deployments

#### Edge Locations
	- AWs Edge locations are an important part of the AWS global infrastructure that helps improve the performance and availability of websites and applications for users all around the world. 
	- Edge locations are separate from AWS regions and are designed to bring content and services closer to end users.
	- When we access a website or application hosted on AWS our requests are usually directed to the nearest AWS edge location for frequenly accessed content such as images videos and other static files. Tjis means that istrad of your requests traveling lomg distances to the main AWS servers in a region ther content can be delivered from the newarby Edge location reducing the time it takes for the content to reach us.
	- Advantage:
		- Improve Performance
		- Enhace Availability
		- Global content Delivery
	- AWS Edges locations are like mini data centers strategically places around the world to deliver content and services fasters to users. THey help improve performance increase availability and enable global content delivery for websites and application hosted on AWS.

#### Local Zone
	- A AWS Local zone is a smaller extension of an AWS region that is geographically closer to specific users or locations. It brings certain AWS services and resources closer to end users, providing lower latency and better performance for applications that require low latency access.

