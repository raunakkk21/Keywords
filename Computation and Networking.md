#  COMPUTATION 💻  
   
### Processor Architectures
1.**CISC**(Closed source)-CISC stands for Complex Instruction Set Computer. It comprises a complex instruction set. It incorporates a variable-length instruction format. Instructions that require register operands can take only two bytes.

2.**RISC**(Closed source)-A Reduced Instruction Set Computer is a type of microprocessor architecture that utilizes a small, highly-optimized set of instructions rather than the highly-specialized set of instructions typically found in other architectures.

3.**RISC-V**(Open source)-RISC-V is an open-source instruction set architecture used to develop custom processors for a variety of applications, from embedded designs to supercomputers.

4.**ARM**-ARM stands for Advanced RISC Machine. It's a processor architecture based on a 32-bit reduced instruction set (RISC) computer. ARM is one of the most licensed and extensive processor cores in the world.


### Types of processing units
1.**CPU**- A CPU (Central Processing Unit) is the most important component of a computer.It performs all types of data processing operations, including:  
 <img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/21ceda3d-76b9-44b1-92d6-3fcbc1bae8cd" height="300" width="500" align="right">
  - Arithmetic
  - Logic
  - Controlling
  - Input/output (I/O) operations
     
2.**GPU**-A Graphics Processing Unit (GPU) is a chip that renders graphics for display on an electronic device.GPUs are designed to accelerate computer graphics and image processing.They can perform mathematical calculations at high speed. Computing tasks like: 
- Graphics rendering
- Machine learning (ML) 
- Video editing
  
3.**DPU**- A data processing unit (DPU) is a programmable computer processor that integrates a CPU with network interface hardware. DPUs are also known as "IPUs" (infrastructure processing units) or "SmartNICs".DPUs are used in data centers to:
- Move data around
- Handle networking functions
- Relieve the CPU from data processing jobs

### Operating Systems
- An operating system is a set of programs that enables a user to operate and interact with a computer.
#### Types of OS
- Batch OS(Payroll System, Bank Statements )
- Time-sharing or multitasking OS(UNIX,Linux,Windows)
- Distributed OS(Cloud Computing)
- NetworkOS(NOS)-It is software that connects multiple devices and computers on the network and allows them to share resources on the network.
- Real-time OS(Airline reservation systems, Heart pacemakers,anything that needs immediate reponse)
- Mobile OS(Android,GrapheneOS,Window phone,etc)
##### Dual boot
Dual booting is a way to install and run two or more different operating systems (OS) on a single computer.

### Host
Bare metal- Server with no OS

### Virtual Machine(VM)
- A VM is a virtualized instance of a computer that can perform almost all of the same functions as a computer, including running applications and operating systems.
- Types of VM's
  - process VM's
  - system VM's
- *eBPF*-Extended Berkeley Packet Filter. It is a lightweight virtual machine that runs sandboxed programs in a Linux kernel. eBPF is a Linux kernel technology that allows engineers to build programs that run securely in kernel space.

- **Hypervisors**-A hypervisor is a type of computer software, firmware, or hardware that creates and runs virtual machines. Hypervisors are also known as virtual machine monitors (VMMs) or virtualizers.
- *Type of Hypervisors*  

<img width="747" alt="Screenshot 2023-11-03 172732" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/6f33a7ed-e4d0-4462-b63c-4a07de3af000">  

- *SR-IOV*-Single Root I/O Virtualization  is a hardware standard that allows a PCI Express (PCIe) device to present itself as multiple virtual devices to a hypervisor. The physical device is called a Physical Function (PF) and the virtual devices are called Virtual Functions (VF)

### Containers
- A container is a software package that contains all the elements needed to run an application. 

- *Types of containers*

1.*Docker*-Docker is one of the most popular and widely used container platforms. It enables the creation and use of Linux containers.

2.*LXC*- LXC is an open-source project of LinuxContainers.org. The aim of LXC is to provide isolated application environments that closely resemble virtual machines (VMs) but without the overhead of running their own kernel.

3.*CRI-O*- It is an open-source tool which is an implementation of the Kubernetes CRI (Container Runtime Interface) to enable using OCI (Open Container Initiative) compatible runtimes. Its goal is to replace Docker as the Container engine for Kubernetes. 

4.*rkt*-The rkt has a set of supported tools and community to rival Docker. rkt containers also known as Rocket, turn up from CoreOS to address security vulnerabilities in early versions of Docker.Like LXC, rkt doesn’t use a central daemon and thereby provides more fine-grained control over your containers

5.*Podman*-Podman is an open-source container engine, which performs much of the same role as the Docker engine. But the difference between them is the way in which they work. Like rkt and LXC, Podman also does not have a central daemon but Docker follows the client/server model which is, using a daemon to manage all containers.

6.*runC*-runC is a lightweight universal OS container runtime. It was originally a low-level Docker component, which worked under the hood embedded within the platform architecture.

7.*containerd*-containerd is basically a daemon, supported by both Linux and Windows, that acts as an interface between your container engine and container runtimes.

#### Orchestration containers
- Container orchestration is a process that automates the management of containerized workloads and services.
- Examples:
   - *Kubernetes*-Kubernetes orchestration is an open-source container orchestration system that automates the deployment, management, and scaling of applications. It can be used with or without Docker.
       - *Rancher*-Rancher is a Kubernetes management tool that can be used to deploy and run clusters anywhere and on any provider.
       - *Amazon EKS*-Amazon Elastic Kubernetes Service (Amazon EKS) is a managed Kubernetes service that makes it easy for you to run Kubernetes on AWS and on-premises.
   - *Dockerswarm*- Docker Swarm is a container orchestration tool that allows you to manage a cluster of Docker hosts or run docker applications. It is a lightweight and easy-to-use tool that is well-suited for small and medium-sized deployments.
   - *Apache Mesos*- Mesos brings together the existing resources of the machines/nodes in a cluster into a single pool from which a variety of workloads may utillize. Also known as node abstraction, this removes the need to allocate specific machines for different workloads.
   - *Amazon ECS*-Amazon Elastic Container Service (Amazon ECS) is a fully managed container orchestration service that helps you easily deploy, manage, and scale containerized applications.
     

## User space and Kernal space
<img width="700" alt="Screenshot 2023-11-10 145334" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/7ae4aa3c-fa23-4f47-8b8b-fc525ec9975d">

### IAAS, PAAS,SAAS

<img width="700" alt="Screenshot 2023-11-10 150501" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/d1d8c33e-bc93-4b93-9a82-27f8bda1a574">

- *KaaS*-Kubernetes as a Service (KaaS) makes it possible to operate Kubernetes, the world's most popular container orchestrator, as a managed service. KaaS services are commonly provided in the public cloud, but some KaaS platforms can also be deployed on-premises.


### Types of Integrated circuits
  
1.**SOC**- A system on chip (SoC) is an integrated circuit (IC) that combines many or all of the high-level function elements of an electronic device onto a single chip. SoCs are much smaller than multi-chip designs found in PCs or notebooks and consume less power, but are typically much slower.  
SoCs usually contain:
- CPU,GPU
- USB controller
- Power management circuits

2.**ASICS**
-  ASIC stands for Application-Specific Integrated Circuit. ASICs are computer chips that combine several different circuits on one chip. They are custom-built for a specific purpose, such as running in a digital voice recorder or a high-efficiency video codec.
-  ASICs are the opposite of CPUs and GPUs, which perform general operations. ASICs are more power efficient and have better performance than general purpose integrated circuits. ASICs are used in more specific applications, such as: Cryptocurrency mining, Network processing, Digital cameras.

3.**FGPA**- FGPA stands for field-programmable gate array. It's a type of integrated circuit that can be programmed or reprogrammed after manufacturing.FPGAs are versatile and can be configured to perform a wide range of digital logic functions.
  



  ------------------------------------------------------------------------------------------------------------

# STORAGE
1.**RAID**- RAID stands for "Redundant Array of Inexpensive Disks" or "Redundant Array of Independent Disks". It's a data storage virtualization technology that combines multiple physical disk drive components into one or more logical units.  
RAID is used for:    
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/41a1ccf5-2e22-4c8a-99d2-33aadefc7d92" height="250" width="450" align="right">
- Data redundancy
- Performance improvement
- Storing the same idea in different places
- Applications that require high data read/write transfer rates for large sequential files
- Enabling the array to function, even if one drive were to fail

2.**Object, file and block storage**    
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/935f9697-575e-4662-a855-76f82fa70197" width="750"  height="450">

3.**Sharding**-Database sharding is the process of breaking up large database tables into smaller chunks called shards. A shard is a horizontal data partition that contains a subset of the total data set.     
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/9ae45b73-327b-4566-89fd-4716037fbb2c" width="600" height="300">  
*Types of sharding*  
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/9a7bfe17-2caa-42c3-ac51-add91f83a8f3" width="600" height="400">  

  
4.**DATA CENTERS**- A data center is a physical facility that stores a company's critical applications and data. It contains computing and networking equipment that is used to: 
- Collect, process, and store data
- Distribute and enable access to resources
  
5.**HCL**-HCL stands for Hindustan Computers Limited. HCL is an Indian multinational IT services and consulting company.HCL offers data center solutions, including: Modernization, Platform tech refresh, Datacenter consolidation, Datacenter migration, Hybrid cloud.  

6.**Hyperscale Data Center**-A hyperscale data center is a large facility that houses critical compute and network infrastructure. These facilities are designed to support robust and scalable workloads.They are often associated with large companies that require vast data processing and storage requirements, such as: Google, Amazon, Microsoft, Facebook, Apple.Hyperscale data centers typically house 5,000 or more servers.  

7.**Public Data centers**-A public data center is a facility that provides shared access to applications and data using a complex network, compute, and storage infrastructure.Some of the most reliable colocation data center companies are:   

- QTS Realty Trust Inc (NYSE: QTS)
- Digital Realty (NYSE: DLR)
- Equinix (NASDAQ)

8.**NFS**-NFS stands for Network File System. It is a file system mechanism that allows users to store and retrieve data from multiple disks and directories across a shared network. NFS is a distributed file system protocol that allows users to access files and directories located on remote computers and treat those files and directories as if they were local. 


# NETWORK
# CDN  
- Content delivery networks (CDNs) work by establishing a point of presence (POP) or a group of CDN edge servers at multiple geographical locations. This geographically distributed network works on the principles of caching, dynamic acceleration, and edge logic computations.
1.**SR-IOV**- Single Root I/O Virtualization (SR-IOV) is a technology that allows a physical PCIe device to present itself multiple times through the PCIe bus. SR-IOV is an extension to the PCI Express (PCIe) specification. It allows a device, such as a network adapter, to separate access to its resources among various PCIe hardware functions.   

2.**NTP**- Network Time Protocol (NTP) is an internet protocol that synchronizes computer clock time sources in a network. NTP is one of the oldest parts of the TCP/IP suite. It runs on User Datagram Protocol (UDP), which in turn runs on IP.  

3.**PTP**- Precision Time Protocol (PTP) is a protocol that synchronizes clocks in a computer network. It's similar to Network Time Protocol (NTP), but PTP is more accurate, measuring in nanoseconds. PTP is used to synchronize clocks in systems that require precise time synchronization, such as:  
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/38808ddb-e3ac-445b-b5eb-58cec8004bf7" height="400" width="350" align="right"> 
- Mobile networks
- Measurement and control systems
- The metaverse
  
4.**CISCO**- Cisco is a US technology company that develops, manufactures, and sells networking hardware, telecoms equipment, and other IT services and products.Cisco offers courses and certifications in: 
- Installing, monitoring, and troubleshooting network infrastructure products, Programming
- Computer Hardware Basics
  
5.**Mysterium Network**- Mysterium Network is a free, open-source network that provides anonymous access to the internet.Users and clients can pay to connect to these nodes, which provide: 
- A VPN or proxy service
- Access to the open internet
- A secure line of communication

6.**Kubernetes vs Mesos vs Dockerswarm**    
- Container orhestration tools
<img width="600" height="400" alt="Screenshot 2023-11-03 124703" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/10f11bc8-5b75-445b-807b-3b977f141c2c">

7.**Control plane vs Data Plane**    
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/9fcc5798-9b18-4a6d-884c-3dc6f5a09dce" width="700" height="400" >  

8.**COTS**-Commercial-off-the-shelf: A product that is a standard, existing hardware product that is available from commercial sources.COTS products are designed to be easily installed and interoperate with existing system components.  

9.**CIDR Notations**-CIDR notation, or Classless Inter-Domain Routing notation, is a way to represent IP addresses in computer networks. CIDR notation uses a slash ('/') character to separate a prefix from a suffix. The prefix is the IP address, and the suffix is a decimal number that indicates how many bits are in the entire address.  

10.**Subnetting**-Subnetting is a method of dividing a single physical network into logical sub-networks, also known as subnets.  
*Benifits*:
- Reduce network traffic
- Conceal network complexity
- Increase routing efficiency
- Enhance the security of the network

11.**L4 and L7 load balancers**  
- L4 load balancers deliver traffic with limited network information using a load balancing algorithm. They calculate the best server based on fewest connections and fastest server response times.
- L7 load balancers disconnect network traffic and process the message inside. They make a decision based on the content of the message. Once decided, they establish a new TCP connection to the designated upstream server and send the request to the server.

12.**SSO**-Single sign-on (SSO) is a system that allows users to access multiple applications and services with just one set of login credentials. SSO works by authenticating a user's identity once and then granting access to all of the applications and services that the user is authorized to access.   

13.**Okta**-The Okta app integrations in your org use Single Sign-On (SSO) to provide a seamless authentication experience for end users. After end users sign in to Okta, they can launch any of their assigned app integrations to access external applications and services without reentering their credentials.  

14.**OIDC**-OpenID Connect (OIDC) is an open authentication protocol that works on top of the OAuth 2.0 framework. It allows individuals to use single sign-on (SSO) to access relying party sites using OpenID Providers (OPs), such as an email provider or social network, to authenticate their identities.  

15.**LDAP(Lightweight directory access protocol)**-LDAP authentication is the process of verifying a user's identity by checking their credentials against an LDAP directory server.  

   

17.**API Gateway**-An application programming interface (API) gateway is software that takes an application user's request, routes it to one or more backend services, gathers the appropriate data and delivers it to the user in a single, combined package.  

19.**Isolation**-An isolated local network consists of servers that are connected in an environment which has no connection to any other network. In this model, there is zero network connectivity to a larger internal network or the Internet.  

20.**Site to site VPN**-A site-to-site virtual private network (VPN) is a way to connect local area networks (LANs) in multiple locations across the public internet. It allows employees in different sites to securely share resources and information.   

21.**Client to site VPN**-A client-to-site VPN (Virtual Private Network) is a type of VPN that connects a single device, such as a laptop or smartphone, to a remote network, such as a corporate or cloud network.      
![1_2LhRE8Y2KD8hZhcz9BNYFA](https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/b44adbf9-79ee-42b7-9e4a-a042b5066b9a)






## KEYWORDS   
1.**VCS**-A version control system (VCS) is software that tracks changes to a file or set of files over time. VCSs are used in software development, where a team of people may concurrently make changes to the same files.  
VCSs help developers: 
- Efficiently communicate and manage changes to source code
- Maintain a record of every change, including authorship, timestamp, and other details
- Recall specific versions later

2.**Ciphering**-In cryptography, a cipher is an algorithm for performing encryption or decryption. A cipher is a method of hiding words or text with encryption by replacing original letters with other letters, numbers, and symbols through substitution or transposition.  

3.**DMV**-(Dynamic Management View) A SQL enhancement that provides management information about the SQL Server database.  

4.**Redis**-Redis is an in-memory data store that is widely used as a caching layer to speed up access to frequently accessed data. Redis caching leverages its in-memory storage capabilities, allowing applications to store and retrieve data with extremely low latency.    

<img width="600" alt="Screenshot 2023-11-03 130048" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/75beb12f-3816-48c4-9216-55118d312487">   

5.**TPM and HSM**-Trusted Platform Module (TPM) and Hardware Security Module (HSM) are both security components in cybersecurity. TPM focuses on securing the platform and ensuring system integrity, while HSM specializes in cryptographic key management and secure cryptographic operations.     
<img width="750" alt="Screenshot 2023-11-03 130303" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/54a051c3-3648-4e3c-8d61-b1d0bbb7cf07">   

6.**TPM enabling**-A TPM (Trusted Platform Module) is a chip on your motherboard that can encrypt an entire laptop or desktop disk. It's used to improve the security of your PC.      

7.**PING**(Packet InterNet Groper)-Ping is a computer network administration software utility that tests the network connectivity between two systems. It is used to determine the communication latency, or the amount of time it takes for data to travel between two devices or across a network.    

8.**ELK Stack**-The ELK Stack is a collection of three open-source products: Elasticsearch, Logstash, and Kibana. It's a log management platform that provides centralized logging to identify problems with servers or applications. The ELK Stack allows users to search all the logs in a single place.   

9.**Prometheus and Grafana**-Prometheus and Grafana are two open-source tools used for application monitoring and analytics. Prometheus and Grafana are both built for time-series data. They are compatible with many, if not most, data source types. It is very common for DevOps teams to run Grafana on top of Prometheus.  

<img width="700" width="400"  alt="Screenshot 2023-11-03 131046" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/17ca3475-69fd-4d4b-a456-860ba419b074">    


10. **SCA(Side channel attack)**-A side-channel attack (SCA) is a security exploit that attempts to extract secrets from a chip or a system. SCAs are based on extra information that can be gathered because of the fundamental way a computer protocol or algorithm is implemented.
<img src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/21f0b9bf-86da-43fc-a09e-86e842b4feb1" width="600" height="400">

11.**Message que**-A message queue is a sequence of messages that are sent between applications. It's a form of asynchronous service-to-service communication that's used in serverless and microservices architectures.    

12.**IoT**-The Internet of Things (IoT) is a network of connected devices that exchange data with other IoT devices and the cloud. IoT devices are physical objects that are embedded with sensors, software, and other technologies.    

13.**SES**-Amazon Simple Email Service (SES) is a cloud-based email service provider that can integrate into any application for high volume email automation. You can use Amazon SES to send transactional emails, marketing emails, or newsletter emails.    

14.**Amazon MQ**-Amazon MQ is a managed message broker service for Apache ActiveMQ and RabbitMQ that streamlines setup, operation, and management of message brokers on AWS. With a few steps, Amazon MQ can provision your message broker with support for software version upgrades.

15.**SEP**-A standard-essential patent (SEP) is a patent that protects an invention that must be used to comply with a technical standard. 

16.**PRNG**-A pseudo-random number generator (PRNG) is an algorithm that uses mathematical formulas to produce sequences of numbers that approximate the properties of random numbers.The sequence generated by a PRNG is not truly random. However, an observer who does not know the value of the seed cannot distinguish the output from that of a (true) random bit generator.  


17.**QRNG**-QRNG stands for Quantum Random Number Generator. It's a device that generates random numbers using the principles of quantum physics. 
 QRNGs have many applications, including: Key generation, Cryptography, Banking, The automotive industry, Security.    
 


18.**Edge Traffic Management System**-Edge computing is a technology that can be used to manage traffic. It allows for the processing and analysis of data in real-time, locally. Edge computing can be used for:  
- Smart navigation of vehicles
- Traffic load balancing
 
19.**GrapheneOS**- GrapheneOS is a custom, open-source operating system (OS) that focuses on privacy and security. It's based on Android and is compatible with Android apps.GrapheneOS is compatible with selected Google Pixel smartphones, including:   
- Pixel 8 Pro,Pixel 8,Pixel Fold,etc

20.**BOSS**- Bharat Operating System Solutions (BOSS) is an open-source operating system (OS) developed by the Centre for Development of Advanced Computing (C-DAC) in India. BOSS is an Indian Linux distribution based on Debian.  
<img height="100" width="200" align="right" src="https://github.com/raunakkk21/Computing-and-Networking/assets/143111163/07aef32d-9e40-4bec-8f64-ff68ccad28bc">

21.**Host**-A network host is a computer or other device that is connected to a computer network. Hosts can include clients and servers that send or receive data, services, and applications.  









  





