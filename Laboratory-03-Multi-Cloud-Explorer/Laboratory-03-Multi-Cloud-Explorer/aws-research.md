# AWS Research

## Brief Overview

Amazon Web Services (AWS) is a cloud computing platform provided by Amazon. It offers many cloud-based services that allow individuals, businesses, schools, and organizations to use computing resources over the internet without having to purchase and maintain their own physical servers.

AWS provides services for computing, storage, databases, networking, security, analytics, artificial intelligence, Internet of Things (IoT), and application development. AWS services can be provisioned on demand and generally follow a pay-as-you-go pricing model, allowing organizations to use resources according to their needs. AWS currently provides more than 200 cloud services.

In simple terms, AWS allows users to **rent computing resources through the internet** instead of buying expensive physical hardware. For example, a company can use Amazon EC2 to run a website, Amazon S3 to store files, and Amazon RDS to manage a database.

---

## Global Infrastructure

AWS has a global infrastructure designed to provide reliable, scalable, and secure cloud services around the world. Its infrastructure is organized into **Regions, Availability Zones, Local Zones, and Wavelength Zones**.

### 1. AWS Regions

An AWS Region is a separate geographic area where AWS operates its cloud infrastructure. Examples include:

* Asia Pacific (Singapore)
* Asia Pacific (Tokyo)
* Asia Pacific (Sydney)
* Asia Pacific (Mumbai)
* US East (N. Virginia)
* Europe (Ireland)

AWS currently lists **39 launched Regions**, with multiple Availability Zones within each Region.

Choosing a Region is important because organizations can select a location that is closer to their users, which can help reduce network latency. It can also help organizations satisfy legal, regulatory, and data-residency requirements.

### 2. Availability Zones

Availability Zones (AZs) are isolated locations within an AWS Region. They consist of one or more separate data centers with redundant power, networking, and connectivity.

Each AWS Region has multiple Availability Zones, and AWS states that each Region has at least three Availability Zones.

Using multiple Availability Zones helps protect applications from failures affecting a single location. For example, if a company places its application servers in two different Availability Zones and one zone experiences a problem, the other zone can continue serving users.

### 3. Local Zones

AWS Local Zones allow computing and storage resources to be placed closer to end users in specific metropolitan areas. This is useful for applications that require very low latency, such as real-time applications and media processing.

### 4. Wavelength Zones

AWS Wavelength Zones are designed for applications that require extremely low latency for 5G devices. AWS places computing and storage services closer to users by deploying them within telecommunications providers' 5G networks.

### Importance of Global Infrastructure

AWS Global Infrastructure helps organizations:

* Deploy applications closer to their users.
* Improve application availability.
* Reduce network latency.
* Recover from failures more effectively.
* Meet certain geographic and regulatory requirements.
* Serve customers in different countries and regions.

---

## Cloud Management Console

The **AWS Management Console** is a web-based interface that allows users to access and manage AWS services through a graphical user interface.

Instead of using command-line commands, users can log in to the AWS Management Console using a web browser and select the AWS service they want to use.

Through the console, users can perform tasks such as:

* Creating virtual servers.
* Creating and managing storage.
* Creating databases.
* Configuring networks.
* Monitoring cloud resources.
* Managing security settings.
* Viewing billing and costs.
* Managing users and permissions.

For example, a student can open the AWS Management Console, select **Amazon EC2**, and create a virtual server. Another user can select **Amazon S3** to create a storage bucket for files.

The AWS Management Console makes cloud computing easier to manage because users can configure resources without having to type every command manually.

---

## Four Core Services

### 1. Amazon EC2 – Elastic Compute Cloud

Amazon EC2 provides virtual servers called **instances** that users can use to run applications and websites.

Instead of purchasing a physical server, an organization can create an EC2 instance and use it as a virtual computer in the AWS Cloud.

**Example use:**

A company can use an EC2 instance to host its company website or web application.

**Main purpose:**

* Running applications
* Hosting websites
* Running backend systems
* Performing computing tasks

---

### 2. Amazon S3 – Simple Storage Service

Amazon S3 is a cloud object storage service used to store and retrieve data.

Users can store different types of files, including:

* Images
* Videos
* Documents
* Backups
* Application files
* Data archives

S3 organizes stored objects inside containers called **buckets**.

**Example use:**

A school can use Amazon S3 to store student documents, project files, and backups.

**Main purpose:**

* File storage
* Data backup
* Website assets
* Application storage

---

### 3. Amazon RDS – Relational Database Service

Amazon RDS is a managed relational database service. It makes it easier for organizations to create, operate, and maintain relational databases in the AWS Cloud.

Instead of manually setting up database servers, organizations can use RDS to simplify database deployment and management.

**Example use:**

An online shopping system can use Amazon RDS to store information about customers, products, orders, and payments.

**Main purpose:**

* Storing structured data
* Managing application databases
* Supporting websites and business applications
* Simplifying database administration

---

### 4. Amazon VPC – Virtual Private Cloud

Amazon VPC allows users to create a logically isolated virtual network within AWS.

Users can configure network components such as:

* IP address ranges
* Subnets
* Route tables
* Internet gateways
* Security controls

For example, an organization can create a VPC containing its EC2 servers and database resources while controlling how those resources communicate with the internet and with each other.

**Main purpose:**

* Creating private cloud networks
* Controlling network traffic
* Connecting cloud resources
* Improving network security

---

## Three Advantages

### 1. Scalability

AWS allows organizations to increase or decrease their cloud resources according to demand.

For example, an online store may need more computing resources during a large sale. AWS can provide additional resources when demand increases and allow the organization to reduce resources when demand decreases.

This means businesses do not always need to purchase additional physical servers to handle temporary increases in users.

### 2. Cost Efficiency

AWS uses a cloud-based pricing model where organizations can pay for the resources they use instead of making a large upfront investment in physical servers and data centers.

This can reduce hardware, maintenance, and infrastructure costs, especially for organizations that do not want to build their own data centers.

AWS also allows organizations to start with a small amount of resources and increase their usage as their applications grow.

### 3. Global Availability and Reliability

AWS has infrastructure distributed across many geographic locations. Regions contain multiple Availability Zones, which helps organizations design applications that can continue operating even when an individual location experiences a failure.

This is especially useful for businesses that need their websites and applications to remain available to customers.

---

## Typical Enterprise Use Cases

AWS is widely used by enterprises for different types of business and technology requirements.

### 1. Website and Application Hosting

Companies can use Amazon EC2, Amazon S3, and other AWS services to host websites and web applications.

For example, an online business can host its website on AWS and allow customers to access it from different countries.

### 2. Data Storage and Backup

Organizations can use Amazon S3 to store important files, backups, documents, images, and other types of data.

Cloud storage can also help organizations create backup strategies and protect important information.

### 3. Database Management

Companies can use Amazon RDS to manage databases used by applications.

For example, a banking application, school management system, or e-commerce website can use a cloud database to store and retrieve information.

### 4. Business Data Analytics

Enterprises can use AWS services to collect, process, and analyze large amounts of business data.

Organizations can use the results to understand customer behavior, identify trends, and support better business decisions.

### 5. Disaster Recovery

AWS can be used to create backup and disaster recovery solutions. Organizations can replicate important resources and data so they can recover their systems after hardware failures, software problems, or other disruptions.

### 6. Software Development and Testing

Developers can use AWS to create development and testing environments without purchasing physical servers.

For example, a software development team can create temporary cloud servers for testing an application and remove them when testing is finished.

### 7. Artificial Intelligence and Machine Learning

Enterprises can use AWS services to develop and deploy artificial intelligence and machine learning applications.

These technologies can be used for tasks such as customer support, data analysis, recommendation systems, and automated business processes.

AWS provides enterprise-focused cloud capabilities and services for organizations across different industries.

---


### What the Screenshot Should Show

Your screenshot should clearly show the AWS website homepage, preferably including:

* AWS logo
* AWS homepage navigation
* Main AWS page content
* Browser window or webpage interface

Make sure the screenshot is readable and that the AWS homepage is clearly identifiable.

---

## Conclusion

Amazon Web Services is a major cloud computing platform that provides organizations with computing, storage, database, networking, security, and other cloud services. Its global infrastructure is organized into Regions and Availability Zones, allowing applications to be deployed closer to users and designed for high availability.

The AWS Management Console makes it easier to manage cloud resources through a graphical interface. Services such as Amazon EC2, Amazon S3, Amazon RDS, and Amazon VPC provide the basic building blocks needed to develop and operate many types of applications.

AWS is useful for enterprises because it provides scalability, cost efficiency, global infrastructure, and a wide range of cloud services. It can be used for website hosting, data storage, database management, analytics, disaster recovery, software development, and many other business applications.

