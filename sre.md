# Diego Alejandro Puertas
[diego@puertas.name](mailto:diego@puertas.name) |
[LinkedIn](https://www.linkedin.com/in/diegopuertas/) |
+41 76 495 61 16

Online version: [https://bit.ly/3yUSJZm](https://bit.ly/3yUSJZm)

## Work Experience

### Site Reliability Engineer | Google

01.2022 - 05.2023

Responsible for the reliable operation of the Access Managemnt part of [Google 
Cloud IAM](https://cloud.google.com/iam) service, a prerequisite to the utilisation
of any other Google Cloud resource. This involved the application of the [Site
Reliability Engineering](https://sre.google) principles, which puts in balance 
both the needs of systems reliability and innovation velocity.

#### Responsibilities
- OnCall rotation, incident handling.
- Postmortem analysis of incidents.
- Postmortem Action Items resolution.
- Monitoring requirements analysis and implementation.
- Service sizing and resource allocation.
- Quota requests analysis and granting.
- Resource access permission analysis and granting.
- Code reviews.

#### Projects
- Design document for the migration of the Access Management service monitoring
  configuration.
- Design document for the migration of the Globalisation Service probers.


### Technical Solutions Engineer | Google

05.2019 - 01.2022

3rd level Support for the Google Cloud customers on the infrastructure shard.
Helping customers on architecture design, providing expertise on resource features
and utilization, and issues troubleshooting.
- Products supported:
  [Google Kubernetes Engine](https://cloud.google.com/kubernetes-engine),
  [Container Registry](https://cloud.google.com/container-registry),
  [Compute Engine](https://cloud.google.com/products/compute),
  [Cloud Storage](https://cloud.google.com/storage),
  [Identity and Access Management](https://cloud.google.com/iam),
  [Stackdriver](https://cloud.google.com/products/operations).
- [Deployment Manager](https://cloud.google.com/deployment-manager) Product
  Engagement Lead.
- [Lowes](https://www.lowes.com) Customer Engagement Lead (CEL).
- Mentoring (3 mentees), tutoring, and interviewing.

#### Accomplishments

- Took ownership of the Customer Engagement Lead (CEL) for Lowes, one of the
  biggest Google Cloud customers, with only four weeks to go before [Black Friday](https://www.investopedia.com/terms/b/blackfriday.asp)-[Cyber Monday](https://www.investopedia.com/terms/c/cybermonday.asp)
  (BFCM) 2019. In this time I ramped up as Customer Engagement Lead (CEL),
  familiarized myself with Lowes architecture, projects, and the Professional 
  Service Office (PSO) team. I produced the necessary documentation for Support
  and coordinated the efforts of PSO, Customer Engineering, and Support for the 
  stress testing of their infra. Lowes was a key account in their recent adoption 
  of GCP. Given their size and experiences in the previous two BFCM with another 
  cloud provider, it was critical both for Lowes and Google that 2019 was a 
  success. Thanks to an amazing team effort, Lowes named Google Cloud as "Top 
  Partner of the Year", and [increased their investment](https://corporate.lowes.com/newsroom/press-releases/google-cloud-helps-lowes-build-true-channel-less-customer-experience-01-13-20)
  on the platform.

- Solid case work. Second largest number of cases closed in the Infra shard,
  3rd place overall on the East Coast in 2020, while maintaining high case quality
  CES score of 4.42/5.

#### Awards & Recognition

Received 7 spot bonuses and 2 peer bonuses. Among the spot bonuses I've got a
2021 Q1 Team Titans Award for my case work closing P1 cases and a C19 Hard Work
spot bonus for my contribution on supporting the critical rollout of COVID-19 governmnet web sites.

#### Mission Control Rotation with the IAM SRE team (06.2021 - 08.2021)

Worked as prime responsible of the migration of the IAM Globalization Server
Probers from a legacy to a new server development/administration platform.

The project required the calculation and allocation of resources, redefinition
of users and permissions, health validation, traffic migration without service
interruption, and old binaries deprecation.


### Sr Cloud Software Engineer (DevOps) | [TD Canada Trust](https://www.td.com)

11.2018 - 05.2019

Responsible for the quality of the [SaltStack](https://saltproject.io), [Cloudify](https://cloudify.co), and [Jenkins](https://www.jenkins.io) code used to
deploy infrastructure (Linux, Windows), and platforms (Jboss, Oracle, Websphere,
etc), on the bank’s private/public cloud (OpenStack, VMWare, Azure). Vetting the
merging of said code to production branch. Software life cycle and release 
management. Pipeline design and maintenance. Helping Subject Matter Experts
coding their SaltStack [states](https://docs.saltproject.io/en/latest/topics/states/).

#### Projects and Accomplishments

- Setting up a [GNS3](https://www.gns3.com) lab to test network configuration
  automation.
- Produced sample configurations to showcase in the GNS3 lab the binding of
  service VMs configuration to their [network configuration](https://docs.saltproject.io/en/latest/topics/network_automation) (Cisco, Junos,
  f5 Big-IP). Up to that point every update of a service in the bank required a 
  toil-heavy process of coordination between the application team and the network 
  team.
- SaltStack version upgrade to 2018.3.x. Codebase review and testing to certify
  compatibility with the new version.


### Sr Information Systems Analyst | [Blackberry](https://blackberry.com)

03.2017 - 11.2018

Introducing DevOps workflow on the recently acquired team, [Good Technology](https://www.blackberry.com/us/en/company/newsroom/press-releases/2015/blackberry-completes-good-technology-acquisition).

#### Projects and accomplishments
- Helping migrate their platform from [CFEngine](https://cfengine.com) to a modern
  Configuration Management system (CMS), and to streamline a 6 step process (DNS,
  kickstart, cfengine, release, monitoring, load balancer) into a single action.
  Presented [Ansible](http://ansible.com) and [Chef](https://chef.io) solutions.\
  The product had to run on VMware, so we couldn’t use the standard BlackBerry
  private cloud, OpenNebula, and all the resource management infrastructure
  already developed. We didn't have vCloud or vRealize as part of our contract
  with VMware, so the whole resource provisioning and management had to be coded
  into the CMS. Left a working proof of concept done in Ansible, providing a
  one-step procedure that ralked to vCenter for VM provisioning, replaces CFEngine
  for system configuration, adds the host to Nagios, and handles the F5's DNS and
  load balancer configuration.

- Identified an issue that caused 10% of downtime over a week, along with very 
  heavy oncall toil. The OracleDB processes, once assigned to a given core,
  wouldn’t write to non-local NUMA memory, instead they were swapping heavily to 
  disk. The solution was to disable NUMA on the servers, so Oracle could write to
  any place of the RAM.


### Sr Infrastructure Specialist | [Blackberry](https://blackberry.com)

07.2015 – 02.2017

Handling the DevOps software flow from development to production in their private
cloud ([Open Nebula](https://opennebula.io)) for corporate sites.
The CMS of choice was [Chef](https://www.chef.io). Worked with Devand QA teams to 
ensure their code went through a proper dev-to-production lifecycle, collecting 
information for continuous improvement, and architecting the platform to meet the 
needs of the software.

Acting as a liaison between development and different teams providing the
infrastructure.

#### Projects

- High-utilization API site, providing access to resources as Hadoop, Oracle, 
  MySQL, MS-SQL relational databases, and other BlackBerry internal services.
- Learning management tool with connection to both internal and external
  course providers (Jboss).
- Apache Camel pool of hosts, providing SOAP message routing for different
  applications.
- Internal corporate news board PHP site.


### Unix Administrator | [Descartes Systems Group](https://descartes.com)

05.2014 – 07.2015

UNIX systems analysis, re-architecture, and administration. Descartes grew
mainly by acquisition, resulting on a very diverse inflow of platforms and
design philosophies. The UNIX team was responsible for taking these diverse
systems and shaping them into a part of a coherent and sustainable ecosystem:
Virtualisation of physical machines on VMWare. Disk space management using LVM.
Monitoring (Zabbix). Configuration management (Puppet).

#### Projects
- Priority reports of product deficiencies for the development team.
- Design of an “Incident Management Framework”, using an incident database to
  classify them and provide solution procedures for 1st, 2nd, and 3rd line
  support.
- Part of the knowledge transference and integration team for newly acquired
  products.
- Produced product operation documentation, as well as the virtualisation and
  migration plan to the Descartes’ datacenter.
- Design of a network backup solution based on Bacula.

#### Outstanding accomplishment
A physical container scheduling service went down, and the cause was narrowed
to a smoking server on a remote colocation space. The server was undocumented
And the only thing we knew is that it was labeled *MX2* on the rack. Rebuilt the
server out of the missing product functionality in less than 6 hours, putting an 
end to a very costly downtime, both in revenue and reputation.


### Deployment Specialist | [Intelerad Medical Systems](https://intelerad.com)

09.2008 – 06.2013

Remote installation and configuration of the company’s Picture Archiving and
Communication Systems (PACS) on clinics and hospitals in North America and
overseas. Deployment projects included large systems of 100+ RedHat Linux
servers.

#### Tasks
- Project management
- Analysis of the client’s system architecture,
- SAN and DAS storage administration (HP and Dell)
- System programming (python, bash)
- Database administration (Sybille and Postgres)
- RedHat’s Yum repositories creation/administration
- 3rd level support on Linux OS related issues

#### Projects
- Produced two standard procedures: server evergreening and renaming (DICOM).
  Well defined and auditable processes are crucial both to standardise and 
  facilitate deployment work and maintain the very strict medical industry
  conformance certifications the company requires to operate.
- Development of tools to automatise the PACS deployment process (sanity check,
  package installation, hosts file generation, parallelised services restarts).
- Refined the categorisation of the different kinds of deployments and created
  the Deployment Information Requirements Forms, providing Account Managers with
  a simple tool to gather all the necessary data to initiate a deployment. This
  reduced the amount time of initial back and forth communications, saving from
  one to two days of communication time with our Australian customers.


### Applications Administrator | [Interdigital](https://interdigital.com)

02.2007 – 09.2008

Provided the engineers and programmers of this wireless technologies
R&D powerhouse with the necessary tools to do their job. Worked alongside
Them to assess their needs and plan the implementation and operation of
such tools.

#### Responsibilities
- Sun Grid® Engine cluster administration (RedHat and Solaris servers) for high
  performance distributed computing, managing the distribution of resources for
  simulation and compilation jobs.
- Administration of the Software Configuration Management [ClearCase](https://www.ibm.com/products/rational-clearcase)
  servers, a pair of fault tolerant Solaris servers sharing a SAN array.
- Implementation and maintenance of Active Directory GPOs to install and update
  Windows workstations.
- Racking and replacement of servers, network devices. Datacenter cabling.

#### Projects
- Implementation of a kickstart server to deploy RedHat grid servers and 
  workstations.
- Implementation of Nagios for services and environmental (temperature, humidity) 
  monitoring.
- Developed [expect](https://linux.die.net/man/1/expect) [scripts](https://www.oreilly.com/library/view/exploring-expect/9781565920903/ch01.html)
  to perform daily backups of the Cisco network devices configuration on ClearCase.
  This avoided the purchase of the Cisco provided software of automated backups.
- Developed a script to monitor the applications installed on windows workstations, 
  using python and the SysInternals suite, replacing the functionality of an
  expensive commercial application.


### Systems/Network Administrator | Carabobo University

02.2002 – 09.2006

Part of a team that designed, built, and administered the network services of
the Carabobo University, a 37,000+ student’s institution, with a large campus
and several sites all over the city. On a very tight budget we got the user base
from 2 to 50 thousand in 4 years. Built all services from scratch: DNS, SMTP,
HTTP, FTP, NFS, Terminal Server, change management scheme, disaster recovery
plan, and backup system.

Design and administration of the LDAP central authentication, server
configuration, and resources directory server. Migration of the data from legacy
sources, which required the coordination of multiple parties working on the
project. The LDAP database eventually became widely used throughout the
university not only for authentication, but also as a systems configuration
repository.

Design and administration of a 2-layers, fault-tolerant email system based in
Postfix. Wrote mailbox maintenance scripts for MDA provided soft quotas
(maildrop).

Coded a Linux server configuration script, so non savvy administrators could
install 2nd layer mail servers with minimum support, configuration was picked up
from the LDAP server.

Designed the network (layers 1 and 2) of the Faculty of Medicine, a 2 square Km
area, with 11 buildings and 4 thousand users.


### Lecturer Professor | Carabobo University

2003 – 2006

Electrical Engineering School, Telecommunications Department. \
Taught the courses:

- Electrical Measurements II
- Microwaves.

Elaboration of a laboratory practices manual.

## Education

- Electrical Engineering bachelor - 2000 \
  Universidad de Carabobo, Venezuela \
  Telecommunications minor

- Computer Science Diploma - 2009 \
  Concordia University, Montreal

- Master of Engineering - 2015 \
  Waterloo University, Waterloo
