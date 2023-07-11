# Jason W. Plummer
* 3454 Howard Road, Murfreesboro, TN 37127 + home: 832.543.3281 + vhsjwp01@gmail.com
  * The latest version of this document can be found here: http://
---
# Experience:
* Infrastructure Architecture and Design: since 1991
* Compute Architecture and Design: since 1995
* Workflow Optimization: since 1999
* Product Development: since 2000
* Program Management Knowledge Base:
  * Stake holder identification and expectation management
  * Requirements elicitation, refinement and dissemination
  * Resource planning, effort estimation and risk mitigation
  * Communication, communication, communication
* Software Development Knowledge Base:
  * Continuous integration and deployment (Jenkins/Hudson, Cruise Control, Bamboo)
  * Source code repository management (gitolite/ssh, subversion/apache, ClearCase, Bitbucket)
  * Containerization (Docker, Virtual Machines, LXE)
* OS Knowledge Base:
  * Unix / Linux - since 1996
  * Mac OS X - since 2006
---
# Employment:
## 2014 - 2017: Ingram Content Group, LaVergne, TN
### Title: Senior Systems Engineer
* IT Research and Development
  * Charged with maintaining awareness and performing assessment of emerging techonologies that can enhance the corporate portfolio with respect to efficiency and revenue stream.
  * Created shell based middleware to aid in converting from MainFrame COBOL to COBOL-IT on Linux.
  * Created continuous integration middleware to enable the development and deployment of docker containers to runtime hosts using Atlassian Stash and Bamboo.
  * Developed Puppet modules to aid in customizable deployment of dockerized services.
  * Assisted in the design and deployment of a 67 node Elasticsearch-Logstash-Kibana based OS and application log aggregation cluster.
* IT Architecture and Engineering
  * Champion for the integration of continuous integration and continuous delivery with software development efforts.  Business owner of Atlassian Stash and Bamboo.
  * Champion for the integration of docker for both infrastructure tooling and business application development.
* Software Development Best Practices
  * Evangelical proponent of unit testing, life cycle management, continuous feature deployment, and continous improvement.
  * Work with software development teams to improve their diagnostic capabilities in an effort to make them more self reliant.
  * Work across software development teams and IT support teams in an effort to give software developers a more self service approach to application deployment without sacrificing security or provisioning standardization constraints.
* Mentoring and Leadership
  * Provide eduction on source code management best practices, containerization using docker, and continous integration services to new hires and new software development teams.
  * Provide technical writing education to junior engineers.
  * Provide IT architectural guidance to IT support and software development teams.

## 2011 - 2014: METECS, Houston, TX (via Johnson Space Center, NASA)
### Title: Software Simulation Engineer
_as Corporate IT solutions architect:_
* Network Architecture and Design
  * Charged with establishing a corporate style infrastructure for the company from scratch.
  * Deployed a scalable virtualized infrastructure environment leveraging VMware ESXi and high speed NAS.
  * Deployed the following network services: DNS, DHCP, LDAP, NTP, HTTP/HTTPS, VPN, NFS, CIFS, PXE, Kickstart.
  * Implemented automated vulnerability scanning using OpenVAS virtual appliances.
* Workflow Optimization
  * Implemented a cryptographically secure storage system for the Windows platform using SAMBA and an open source project called BoxCryptor.
  * Implemented a PBX intercom system using FreeSWITCH and off the shelf SIP phones.
  * Worked closely in a team effort to implement an open source project management tool called Trac. Created a PERL CGI script enabling authenticated employees to create their own Trac project, along with any LDAP groups and mailman distribution lists via an internal web resource.
  * Created a web based self service tool for company employees to create and manage their own VPN access SSL certificates.
  * Wrote a script to generate RSS and ATOM feed links from the company's internal mailman based email list server.
* Product Development
  * Fabricated hardware and developed software for a construction vehicle simulation rig. Became familiar with cutting, mounting, and assembling 8020 bar stock and its associated fittings.
  * Became familiar with the Unity3D game development software package. Wrote a client side program in C++ that read in JSON formatted telemetry from a network based Logitech joystick via TCP/IP. This C++ code was compiled as a Windows DLL using Visual Studio Express, which was then integrated as a plugin into Unity3D. Wrote a Unity C# script to call functions in the DLL to harvest data from the remote joystick.

_as NASA systems integrater:_
* Network Architecture and Design
  * Constructed a Space Network Traffic emulator using Linux and its rules for specialized IP traffic queue disciplines to mimic time delays, packet loss, and packet corruption. Developed a web based remote control system for ground operators to monitor training sessions from orbit on the International Space Station. The web interface allowed remote manipulation of simulated station cameras, as well as real time streaming video of a laptop X display to any IP addressable device, and real time strip charting of hand controller telemetry using websockets.
  * Led the effort to develop a data streaming solution suitable for use in deep space networks, where latency and re-transmit times on the order of several weeks make traditional IPv4 methodologies unusable. Operated as a project manager leading a team of three developers to synthesize an open architecture solution using Packet Forward Error Correction (PFEC). Tested the soluton over a VPN mesh (OpenVPN) connecting various computers at disparate locations, and then varied the latency and throughput of the network using a WAN emulator (WANem).  The PFEC software was written for both Linux and Windows. On the windows side a DLL was produced, targeted for use in LabView applications, but generally usable in any windows based coding effort.
  * Developed a standardized, data driven, automated method to deploy 802.11ad compliant mesh networks using OpenWRT and Raspberry Pi. Method includes the ability to provision access points, and DHCP services.
* Workflow Optimization
  * Implemented revision control for NIS, DHCP, and DNS source files using git and gitolite, eliminating the need for root access to perform these operations. Created an rsync based token framework for service synchronization with gitolite.
  * Converted disparate provisioning mechanisms of a simulation framework for certain functions of the International Space Station's on board computer system from legacy disk images and tarballs to a Linux kickstart deployable process. Created a custom RPM package whose purpose was to define all the dependent packages needed for the simulation environment, allowing for the deployment of the necessary software via a single command. This effort involved mentoring other developers in the art of RPM package construction and testing.

## 2008 - 2011: LZ Technology, Houston, TX (via Johnson Space Center, NASA)
### Title: Principal Software Engineer
* Network / Compute Architecture and Design
  * Charged with system administration duties over 6 different software development laboratories across the Guidance and Robotics Engineering divisions of NASA, Johnson Space Center.
  * Implemented a continuous integration framework for software developers using Apache, CruiseControl, ImageMagick, PERL, PHP, and git.
  * Provided IT architectural guidance for ClearCase environment layout. Used VMWare ESXi and DELL iSCSI storage chassis to virtualize all infrastructure services, including VOB and View storage. Later created scripts to enable migration from ClearCase to SubVersion for same.
* Workflow Optimization
  * Implemented revision control for DHCP, DNS, RPM sources, and RPM spec files using SubVersion, Apache, and LDAP, eliminating the need for root access to perform these operations.
  * Developed a bridging script to automate the construction / destruction of tap based OpenVPN meshes used to securely integrate remotely federated vehicle simulation sessions across NASA centers.
  * Provided software provisioning mentoring to software engineers.
  * Implemented automated work flow for Unix account creation across all supported lab networks.
  * Developed a customizable, scalable, and portable virtualized Windows7 framework using QEMU.
  * Created a init style scripting framework to automate VirtualBox headless operation.

## 2007 - 2008: L3 Communications, Houston, TX (via Johnson Space Center, NASA)
### Title: Principal Software Engineer
* Network / Compute Architecture and Design
  * Responsible for the synthesis, procurement, deployment, and management of several different software development environments whose primary function was the development of vehicle training simulations.
  * Established a series of high speed localized networks, each capable of supporting 100+ users, and making heavy use of LDAP for authentication and authorization, with NFS and SMB for network accessible shared storage.
  * Using standard tools provided by modern Linux distributions, created a kickstart / Apache / TFTP / PXE based automated provisioning system for rapid desktop deployment.
  * Became familiar with RPM construction for the purpose of deploying inventory trackable system customizations.
  * Became familiar with CFEngine, a clientserver based configuration management framework. Created RPMs of CFEngine and implemented it as part of kickstart to handle post installation configuration.
  * Created an OpenVPN network to unify management of all supported labs via CFEngine.
  * Deployed VMWare ESX with HA and VMotion capability on a cluster of nodes using shared Adaptec SNAP NAS.
* Workflow Optimization
  * Provisioned a battery of virtual Windows XP workstations for remote access by lab users.
  * Implemented a MailMan based mail list server to track and archive system logs, backup logs, and CFEngine operations.
  * Charged with the design and provisioning of a software integration and test network whose primary task was to demo simulation software deliverables.
  * Provided mentoring to entry level system administrators.

## 2005 - 2007: Motorola, Schaumburg, IL
### Title: Senior Staff System Design Engineer
* Product Development
  * System Design focus on unified crossplatform networkbased provisioning for both deployment and disaster recovery planning in the 2way radio public safety market products.
  * Disaster Recovery and Business Continuance champion in the ASTRO Systems Network Security / Information Assurance team. Served as primary architect for backup and disaster recovery features in the ASTRO product line.  Responsible for the introduction of NAS, IPSAN, and virtualization technology as part of the feature. Development of project management, feature maturity road map, and deployment strategy plans. Matrix style coordination of development efforts across 20+ box teams spanning North America and Europe. Creation of technical requirements at the system and box level. Created training material and conducted training for field support personnel with respect to OS / application provisioning and data archival features in the product line. Worked closely with business planners to create disaster recovery and business continuance purchasing options for customers.
* Workflow Optimization
  * Responsible for the generation of internal standards to improve development efficiency and consistency between box teams.
  * Trained in Agile, CMMI, Six Sigma, and Digital SixSigma. Became a proponent and disciple of continuous improvement quality initiatives.

## 2000 - 2005: Motorola, Schaumburg, IL
### Title: IT Systems Engineer IV
* Compute Architecture and Design
  * Installation and configuration of all UNIX servers (HPUX, Linux, Solaris) deployed in the Worldwide Solutions Data Division (WSDD), Commercial Government Industrial Solutions Sector (CGISS) IL02 Motorola environment.
  * Development and maintenance of customer driven compute architectures and environments. Handled all aspects of the compute environment including system specifications, new hardware evaluation, system patching, data mirroring, disaster recovery, performance tuning, diagnostics, monitoring, file system layout, security updates, system hardening, system enhancements, account creation, and NIS/LDAP data store architecture and management.
  * Extensive training in Rational ClearCase architecture.
* Workflow Optimization
  * Managed the Schaumburg Engineering Computing UNIX Team (5 direct reports).
  * Trained in ITIL and Five Nines.

## 1996 - 2000: The University of Alabama at Birmingham, Biomedical Engineering Department
### Title: Information Systems Specialist / Research Scientist
* Compute Architecture and Design
  * Managed a computation lab consisting of several Linux, Solaris, and SGI workstations.
  * Performed finite element biomechanics research.
  * Taught introductory UNIX to incoming graduate students.
* Workflow Optimization
  * Implemented the first web based recruitment site for the Department of Biomedical Engineering.
---
# Education:
## 1993 - 1996: The University of Alabama at Birmingham
* __Degree:__ Master of Science in Biomedical Engineering, May 1996
* __Area of Research:__ Finite Element Biomechanics
  * __Thesis Title:__ "Parametric Finite Element Studies of the Human Pelvis: The Influence of Load Magnitude and Duration on Pelvic Tolerance During Side Impact"
    * Constructed a clear acrylic phantom with tubes for Xray contrast agents. Used the phantom to scan a cadaveric hemipelvis specimen. Created software to generate 3D geometry from CT image source files.
    * Built a 3D mesh of a hemipelvis and modeled side impact crash impulse scenarios to determine the onset and type of fracture. This information was used to identify mitigating boundary conditions for the purpose of improving the crash survivability of all cars manufactured today.

## 1987 - 1992: Louisiana Tech University
* __Degree:__ Bachelor of Science in Biomedical Engineering, May 1992
  * __Degree Specialty:__ Mechanical Engineering
  * __Senior Design Project:__ A surgical stainless steel Kirschner wire driver
    * Designed and constructed a prototype Kirschner wire driver. Based on the concepts of a mechanical pencil, the device was capable of advancing a single Kwire about 35 mm per trigger pull. Device was constructed entirely of stainless steel, suitable for autoclaving.
---
# Publications and references available upon request

