![](https://github.com/Microsoft/MCW-Template-Cloud-Workshop/raw/master/Media/ms-cloud-workshop.png "Microsoft Cloud Workshops")


<div class="MCWHeader1">
SQL Server hybrid cloud
</div>

<div class="MCWHeader2">
 Whiteboard design session trainer guide
</div>

<div class="MCWHeader3">
June 2018
</div>



Information in this document, including URL and other Internet Web site references, is subject to change without notice. Unless otherwise noted, the example companies, organizations, products, domain names, e-mail addresses, logos, people, places, and events depicted herein are fictitious, and no association with any real company, organization, product, domain name, e-mail address, logo, person, place or event is intended or should be inferred. Complying with all applicable copyright laws is the responsibility of the user. Without limiting the rights under copyright, no part of this document may be reproduced, stored in or introduced into a retrieval system, or transmitted in any form or by any means (electronic, mechanical, photocopying, recording, or otherwise), or for any purpose, without the express written permission of Microsoft Corporation.

Microsoft may have patents, patent applications, trademarks, copyrights, or other intellectual property rights covering subject matter in this document. Except as expressly provided in any written license agreement from Microsoft, the furnishing of this document does not give you any license to these patents, trademarks, copyrights, or other intellectual property.

The names of manufacturers, products, or URLs are provided for informational purposes only and Microsoft makes no representations and warranties, either expressed, implied, or statutory, regarding these manufacturers or the use of the products with any Microsoft technologies. The inclusion of a manufacturer or product does not imply endorsement of Microsoft of the manufacturer or product. Links may be provided to third party sites. Such sites are not under the control of Microsoft and Microsoft is not responsible for the contents of any linked site or any link contained in a linked site, or any changes or updates to such sites. Microsoft is not responsible for webcasting or any other form of transmission received from any linked site. Microsoft is providing these links to you only as a convenience, and the inclusion of any link does not imply endorsement of Microsoft of the site or the products contained therein.

© 2018 Microsoft Corporation. All rights reserved.

Microsoft and the trademarks listed at <https://www.microsoft.com/en-us/legal/intellectualproperty/Trademarks/Usage/General.aspx> are trademarks of the Microsoft group of companies. All other trademarks are property of their respective owners.

**Contents**
<!-- TOC -->

- [Trainer information](#trainer-information)
    - [Role of the trainer](#role-of-the-trainer)
    - [Whiteboard design session flow](#whiteboard-design-session-flow)
    - [Before the whiteboard design session: How to prepare](#before-the-whiteboard-design-session-how-to-prepare)
    - [During the whiteboard design session: Tips for an effective whiteboard design session](#during-the-whiteboard-design-session-tips-for-an-effective-whiteboard-design-session)
- [SQL Server hybrid cloud whiteboard design session student guide](#sql-server-hybrid-cloud-whiteboard-design-session-student-guide)
    - [Abstract and learning objectives](#abstract-and-learning-objectives)
    - [Step 1: Review the customer case study](#step-1-review-the-customer-case-study)
        - [Customer situation](#customer-situation)
        - [Customer needs](#customer-needs)
        - [Customer objections](#customer-objections)
        - [Infographic for common scenarios](#infographic-for-common-scenarios)
        - [Azure Site Recovery](#azure-site-recovery)
        - [Azure Traffic Manager](#azure-traffic-manager)
        - [SQL Server Always Encrypted](#sql-server-always-encrypted)
        - [SQL Server Stretch Database](#sql-server-stretch-database)
    - [Step 2: Design a proof of concept solution](#step-2-design-a-proof-of-concept-solution)
    - [Step 3: Present the solution](#step-3-present-the-solution)
    - [Wrap-up](#wrap-up)
    - [Additional references](#additional-references)
- [SQL Server hybrid cloud whiteboard design session trainer guide](#sql-server-hybrid-cloud-whiteboard-design-session-trainer-guide)
    - [Step 1: Review the customer case study](#step-1-review-the-customer-case-study-1)
    - [Step 2: Design a proof of concept solution](#step-2-design-a-proof-of-concept-solution-1)
    - [Step 3: Present the solution](#step-3-present-the-solution-1)
    - [Wrap-up](#wrap-up-1)
    - [Preferred target audience](#preferred-target-audience)
    - [Preferred solution](#preferred-solution)
    - [Checklist of preferred objection handling](#checklist-of-preferred-objection-handling)
    - [Customer quote (to be read back to the attendees at the end)](#customer-quote-to-be-read-back-to-the-attendees-at-the-end)

<!-- /TOC -->

# Trainer information

Thank you for taking time to support the whiteboard design sessions as a trainer!

## Role of the trainer

An amazing trainer:

-   Creates a safe environment in which learning can take place

-   Stimulates the participant's thinking

-   Involves the participant in the learning process

-   Manages the learning process (on time, on topic, and adjusting to benefit participants)

-   Ensures individual participant accountability

-   Ties it all together for the participant

-   Provides insight and experience to the learning process

-   Effectively leads the whiteboard design session discussion

-   Monitors quality and appropriateness of participant deliverables

-   Effectively leads the feedback process

## Whiteboard design session flow 

Each whiteboard design session uses the following flow:

**Step 1: Review the customer case study (15 minutes)**

Outcome: Analyze your customer's needs

-   Customer's background, situation, needs and technical requirements

-   Current customer infrastructure and architecture

-   Potential issues, objectives and blockers

**Step 2: Design a proof of concept solution (60 minutes)**

Outcome: Design a solution and prepare to present the solution to the target customer audience in a 15-minute chalk-talk format 

-   Determine your target customer audience

-   Determine customer's business needs to address your solution

-   Design and diagram your solution

-   Prepare to present your solution

**Step 3: Present the solution (30 minutes)**

Outcome: Present solution to your customer

-   Present solution

-   Respond to customer objections

-   Receive feedback

**Wrap-up (15 minutes)**

-   Review preferred solution

## Before the whiteboard design session: How to prepare

Before conducting your first whiteboard design session:

-   Read the Student guide (including the case study) and Trainer guide

-   Become familiar with all key points and activities

-   Plan the point you want to stress, which questions you want to drive, transitions, and be ready to answer questions

-   Prior to the whiteboard design session, discuss the case study to pick up more ideas

-   Make notes for later

## During the whiteboard design session: Tips for an effective whiteboard design session

**Refer to the Trainer guide** to stay on track and observe the timings.

**Do not expect to memorize every detail** of the whiteboard design session.

When participants are doing activities, you can **look ahead to refresh your memory**.

-   **Adjust activity and whiteboard design session pace** as needed to allow time for presenting, feedback, and sharing

-   **Add examples, points, and stories** from your own experience. Think about stories you can share that help you make your points clearly and effectively.

-   **Consider creating a "parking lot"** to record issues or questions raised that are outside the scope of the whiteboard design session or can be answered later. Decide how you will address these issues, so you can acknowledge them without being derailed by them.

***Have fun**! Encourage participants to have fun and share!*

**Involve your participants.** Talk and share your knowledge but always involve your participants, even while you are the one speaking.

**Ask questions** and get them to share to fully involve your group in the learning process.

**Ask first**, whenever possible. Before launching into a topic, learn your audience's opinions about it and experiences with it. Asking first enables you to assess their level of knowledge and experience, and leaves them more open to what you are presenting.

**Wait for responses**. If you ask a question such as, "What is your experience with (fill in the blank)?" then wait. Do not be afraid of a little silence. If you leap into the silence, your participants will feel you are not serious about involving them and will become passive. Give participants a chance to think, and if no one answers, patiently ask again. You will usually get a response.

#  SQL Server hybrid cloud whiteboard design session student guide

## Abstract and learning objectives 

In this workshop, attendees will work with a media publishing company to design a hybrid cloud disaster recovery solution. Attendees will design the solution to handle large spikes in load and harden the security to include encryption of PCI data. Additionally, attendees will implement an archival strategy to keep databases sizes in check.

Attendees will be better able to design a hybrid disaster recovery solution between an on-premises VMWare environment and Azure. In addition,

-   Design a SQL Server scale-out solution

-   Protect database backups from local failures

-   Archive cold data from an on-premises SQL Server

-   Perform end-to-end encryption on sensitive application data

## Step 1: Review the customer case study 

**Outcome** 

Analyze your customer’s needs.

Timeframe: 15 minutes 

Directions: With all participants in the session, the facilitator/SME presents an overview of the customer case study along with technical tips. 

1.  Meet your table participants and trainer 
2.  Read all of the directions for steps 1–3 in the student guide 
3.  As a table team, review the following customer case study


### Customer situation

Fabrikam Publishing is a media and publishing company in Seattle, Washington with approximately 5000 employees. They have a successful direct-to-consumer e-commerce site built with .NET, and they use SQL Server to store customer profile and order information.

Fabrikam has a single data center for both internal and customer-facing applications. Most servers are virtualized on VMware. Application servers primarily run Microsoft server software, including Active Directory (AD) Domain Services and a number of AD-integrated services including Exchange 2013 as well as multi-tier, internal, and AD-integrated Microsoft Internet Information Services (IIS)--based web applications with SQL Server 2016 as the database platform.

Recently, the site experienced a multi-day outage due to a lightning strike that disabled both the primary and secondary cooling systems at the data center. In order to avoid such long outages in the future, Fabrikam is investing in a secondary site for disaster recovery. "A disaster recovery site has been on our project proposals for the last four years, but it has always been shelved due to budget constraints," says Michelle Jenkins, Chief Information Officer (CIO). "The recent outage combined with the new capabilities in the cloud have finally encouraged the board to approve the additional budget necessary to build out our disaster recover (DR) capabilities." To keep capital expenditures in check, Fabrikam would like to use the public cloud to host its DR site.

James Sherburn, Director of Information Technology Operations, describes Fabrikam's current disaster recovery strategy as a classic backup/restore strategy with no offsite warm standby machines. Backups are dumped on a network share, and these backups are then archived once per day to an offsite location. According to Sherburn, this strategy requires an "all hands-on deck" approach to recovering the site---which is resource-intensive and slow. It also requires significant expense to bring temporary hardware online at a remote, vendor-provided data center. Because of the cost and complexity, this disaster recovery plan has never been tested, and Information Technology (IT) is not confident that it could bring up the secondary site in a reasonable amount of time. This lack of confidence in the current DR strategy prevented IT management from implementing a failover during the last disaster, resulting in significant losses for the company.

The application team is concerned that the database DR solution will have a negative impact on the overall database performance. The website currently experiences periodic database latency issues during peak load. They would like to have a solution that improves performance of the predominantly read workloads generated by the website to improve the overall responsiveness and the user experience. The Database Architect, Brandon Burns, saw a presentation at a conference last year on leveraging SQL Server Availability Groups with readable secondaries to offload read workloads. Brandon said, "Our ideal solution would be a scale out solution for the data platform, however, we are concerned about potentially making a lot of application code changes." We need a solution that minimizes the amount of changes in the application, and we would like to investigate SQL Server Availability Groups and readable secondaries.

The database administration team is worried about future Payment Card Industry (PCI) compliance issues related to data that is currently stored in varchar fields in the database. In the current system, the database is inaccessible from outside the application except through a dedicated administrative jump-box. Implementing a DR site means that we will be transferring data, and they want to make sure that PCI data being transferred is encrypted. They are concerned about cloud security and the implications it may have to their annual PCI audits. To mitigate any perceived risk and shortcut any issues that may be raised in the PCI audit, they would like to encrypt ALL of the PCI data at both the application and database level.

Future application plans call for new applications that will need to access the encrypted PCI/PII data stored in the database. Key management should be handled by the Fabrikam Security Administration team. They will be responsible for protecting and managing the keys. They need a solution that enables them to accomplish this goal across the multiple applications that will potentially leverage the encrypted database without revealing unencrypted production keys to DBAs or developers.

An additional concern is that the database maintenance jobs are exceeding the current maintenance window. Robert Moore, Manager of Database Administration, believes this is due to the lack of an archive strategy on the current order related tables. Backup times have gradually increased over time to the point where they exceed the maintenance window. Moore's other concern is the sheer size of these databases could make initial synchronization or resynchronization of the DR site a long process that could result in the site running in an exposed state for extended periods. Currently, the database holds approximately 10 years worth of data. "Data older than one year is rarely accessed," says Moore. The business has resisted any data archiving because of several reports that periodically need access to the historical data.

Finally, Fabrikam has a requirement to store the database backups offsite in an encrypted format within two hours of backup completion. The current backup strategy consists of SQL Server backups to an on-premises file server; the backups are then copied to tape and shipped offsite. This process can take up to 24 hours to secure the tapes offsite. In addition to being slow, the tape backups are notoriously unreliable and are generally not available for ad hoc access in the case that a restore becomes necessary. Fabrikam would like to have these backups secured offsite within two hours of the backup completing.

![Fabrikam\'s datacenter is represented as icons that are labeled Web Farm, Application Servers, VMWare, and vCenter. Below that is another icon that is labeled SQL Server 2016, which is Fabrikam\'s database platform.](images/Whiteboarddesignsessiontrainerguide-SQLServerhybridcloudimages/media/image2.png "Fabrikam Publishing data center illustration")

### Customer needs 

1.  Full multi-site disaster recovery solution with minimal complexity, orchestrated failover, and near-zero data loss

2.  Highly available, fault-tolerant SQL Server service with cross-site disaster recovery and minimal impact on database performance

3.  Scale-out the data platform utilizing SQL Server Availability Groups with readable secondaries to offload the heavy read workloads from the primary replica with minimal changes to the application

4.  The ability to seamlessly scale DR site infrastructure as the environment grows

5.  Data encryption solution that encrypts only PCI data at the application and database level

6.  Key management solution that does not expose the unencrypted keys to unauthorized personnel (including DBAs and Developers) and allows for key management by the security administration team

7.  Data archiving to keep database sizes more manageable and reduce the amount of time needed for database maintenance

8.  Secure offsite backups in less than two hours after backup completion

### Customer objections 

1.  Solution must support orchestrated failover so that failover does not require an all hands-on deck

2.  Solution must support the existing VMware infrastructure

3.  Solution must not have a significant impact on database performance

4.  DR infrastructure must be easily scalable to support changes in the workload

5.  The disaster recovery sites must be highly available after a failover

6.  Archive solution must not impact the current applications that periodically pull historical data from the production system

7.  Backups need to be secured offsite in less than two hours.


### Infographic for common scenarios

### Azure Site Recovery

![This is a screenshot of a slide. Common scenarios for Azure Site Recovery include the following bulleted list items: ??? Support for on-premises to on-premises, and on-premises to Azure failover ??? Automated protection and replication of on-premises, Hyper-V, and VMware machines ??? Orchestrated failover ??? Customizable recovery plans ??? Recovery plan testing To the right of the list is a diagram of the multiple deployment architectures of Azure Site Recover: on-premises datacenter to Azure, and on-premises datacenter to on-premises datacenter. At this time, we are unable to capture all of the information in the diagram. Future versions of this course should address this.](images/Whiteboarddesignsessiontrainerguide-SQLServerhybridcloudimages/media/image3.png "Common Azure Site Recovery scenarios")

### Azure Traffic Manager

![This diagram is an example of the Failover traffic routing method for a set of endpoints. In step 1, Traffic Manager first receives an incoming request from a client through DNS and locates the profiles, which is represented as an arrow pointing from a user's laptop to an octagon with arrows inside of it. The octagon has an exploded table with the following columns: Endpoints and Status. The first row has an endpoint of CS-A and a status of Offline (highlighted in red). The second row has an endpoint of CS-B and a status of Online. The third row has an endpoint of CS-C and a status of Online. The fourth row has an endpoint of CS-D and a status of Online. Step 2 is a check of the ordered endpoints. The profile contains an ordered list of endpoints. Traffic Manager check which endpoint is first in the list. If the endpoint is online (based on the ongoing endpoint monitoring), it will specify that endpoint's DNS name in the DNS response to the client. If the endpoint is offline, Traffic Manager determines the next online endpoint in the list. In this example CS-A is offline (unavailable), but CS-B is online (available). In step 3, Traffic Manager returns CS-B's domain name to the client's DNS server, which resolves the domain name to an IP address and sends it to the client. This is represented by an arrow that points from the octagon through DNS to the laptop and user from step one. In step 4, the client initiates traffic to CS-B, which is represented as an arrow that points from the client to an icon of CS-B (Standby 1) at the bottom. To the left of this icon is an icon representing CS-A (Primary), which is in an Offline state. To the right of CS-B are icons representing CS-C (Standby 2) and CS-D (Standby 3).](images/Whiteboarddesignsessiontrainerguide-SQLServerhybridcloudimages/media/image4.png "Diagram of the Failover traffic routing method for a set of endpoints")

### SQL Server Always Encrypted

![On the Trusted side (left), an Apps icon has bidirectional arrows pointing to and from an Enhanced ADO.NET Library icon. At the bottom-left corner is a Column Master Key icon. On the SQL Server side (right), the bidirectional arrows continue and point to and from a database icon. Below this icon is a table with the following columns: Name (dbo.Patients), SSN (ciphertext), and Country. The values in the first row are as follows: Jane Doe, 1x7fg65se2e, and USA. The values in the second row are as follows: Jim Gray, 0x7ff65ae6d, and USA. The values in the third row are as follows: John Smith, 0y8fj75ea2c, and USA. At the bottom-right corner is a Column Encryption Key icon.](images/Whiteboarddesignsessiontrainerguide-SQLServerhybridcloudimages/media/image5.jpeg "SQL Server Always Encrypted diagram")

### SQL Server Stretch Database

![Stretch Database is a feature of SQL Server 2016. On the bottom-left side (on premises) are icons for a Local database (numbered 1) and a User Application (numbered 3 and represented as a monitor). In the Local database icon are tables representing Eligible Data (green) and Local Data (orange). On the top-right side (Azure) is an icon of an Azure SQL database (numbered 2 and labeled Remote Endpoint), and inside this icon is a table representing Remote Data. Two bidirectional arrows (the green one labeled Eligible Data and the orange one labeled T-SQL Queries) point across both sides to and from the local database icon and the Azure SQL database icon. One orange bidirectional arrow labeled T-SQL Queries point to and from the Local database icon and the User Application icon. Below the diagram is the following numbered list: 1. Local database: on-premises instance 2. Remote endpoint: Azure SQL Database holding remote copy 3. Application accessing data](images/Whiteboarddesignsessiontrainerguide-SQLServerhybridcloudimages/media/image6.png "SQL Server Stretch Database diagram")

## Step 2: Design a proof of concept solution

**Outcome**

Design a solution and prepare to present a solution to the target customer audience in a 15-minute chalk-talk format.

Timeframe: 60 minutes

**Business needs**

Directions: With all participants at your table, answer the following questions and list the answers on a flip chart.

1.  Who should you present this solution to? Who is your target customer audience? Who are the decision makers?

2.  What customer business needs do you need to address with your solution?

**Design**

Directions: With all participants at your table, respond to the following questions on a flip chart.

***Plan for high availability and disaster recovery***

1. **Orchestrated failover**: Fabrikam needs to automate and simplify the failover process for the web site. Design a solution that supports orchestrated failover of the entire site.

2. **Additional infrastructure:** Address what additional infrastructure Fabrikam needs to enable the stated solution

3. **SQL Server:** The DR solution for SQL Server should include near-zero data loss. Design the DR solution to provide near-zero data loss, but minimal overhead on normal transactions. The solution should not require the application to be recoded.

4. **Availability:** The site should be highly available at the primary site. Explain which services would be used, and how your design meets these goals after failover.

5. **Diagram the solution**

***Scale out data platform***

1. **Database scale out:** The solution should include the ability to scale out the data platform for heavy read workloads without major code changes to the existing application

2. **User experience**: Address the user experience issues of the data tier. How will this solution address this?

3. **Application impact**: What impact will your design have on the existing application?

4. **Diagram the solution**

***Protect data***

1. **Encrypt PCI data:** Choose an appropriate encryption technology to protect credit card related data

2. **Key management**: How are the encryption keys to be managed in your design?

3. **Application impact**: What impact will your design have on the existing application?

4. **Encryption type**: Create a table that shows each type of PCI data and the appropriate type of encryption for each

***Data archiving***

1. **Plan**: What questions would you pose to the customer in designing a data archive strategy?

2. **Identify archive data**: Describe how you would identify the appropriate tables for archiving

3. **Determine impact**: What impact will your design have on the existing reporting system? How will this solution effect the current maintenance issues?

4. **Diagram the solution**

***Offsite backup***

1. **Describe database backups:** What backup technologies would you consider? How does the solution meet the offsite requirements?
How does this design meet the stated security goals?

2. **Provide the following configuration details:** What will be needed in the event that a database needs to be restored? How does this solution impact the time to restore? What considerations need to be made with regard to Azure Storage Account scale targets?

3. **Diagram the solution Prepare**


**Prepare**

Directions: With all participants at your table: 

1.  Identify any customer needs that are not addressed with the proposed solution
2.  Identify the benefits of your solution
3.  Determine how you will respond to the customer’s objections

Prepare a 15-minute chalk-talk style presentation to the customer.

## Step 3: Present the solution

**Outcome**
 
Present a solution to the target customer audience in a 15-minute chalk-talk format.

Timeframe: 30 minutes

**Presentation** 

Directions:
1.  Pair with another table
2.  One table is the Microsoft team and the other table is the customer
3.  The Microsoft team presents their proposed solution to the customer
4.  The customer makes one of the objections from the list of objections
5.  The Microsoft team responds to the objection
6.  The customer team gives feedback to the Microsoft team.
7.  Tables switch roles and repeat Steps 2–6


## Wrap-up 

Timeframe: 15 minutes

Directions: Tables reconvene with the larger group to hear the facilitator/SME share the preferred solution for the case study. 

##  Additional references

|         |            |
| ------------- |:-------------:|
| **Description** | **Links** |
| Azure Site Recovery    | <https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-overview>  |
| Replicate VMware virtual machines and physical servers to Azure with Azure Site Recovery    | <https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-vmware-to-azure>  |
| Protect SQL Server with SQL Server disaster recovery and Azure Site Recovery         | <<https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-sql> |
| High availability and disaster recovery for SQL Server in Azure Virtual Machines |  <<https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sql/virtual-machines-windows-sql-high-availability-dr>   |  |
| Configure an ILB listener for AlwaysOn Availability Groups in Azure   | <https://docs.microsoft.com/en-us/azure/virtual-machines/windows/sqlclassic/virtual-machines-windows-classic-ps-sql-int-listener> |
| PCI DSS Quick Reference Guide   | <https://www.pcisecuritystandards.org/documents/PCIDSS_QRGv3_2.pdf>   |
| Always Encrypted  | <https://docs.microsoft.com/en-us/sql/relational-databases/security/encryption/always-encrypted-database-engine>  |
| Azure Key Vault | <https://docs.microsoft.com/en-us/azure/key-vault>  |
| SQL Server Stretch Database  | <https://docs.microsoft.com/en-us/sql/sql-server/stretch-database/stretch-database>  |
| SQL Server Backup to URL   | <https://docs.microsoft.com/en-us/sql/relational-databases/backup-restore/sql-server-backup-to-url>   |
| Azure Traffic Manager  | <https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview>   |
| Reduce RTO with Traffic Manager and Azure Site Recovery  | <https://docs.microsoft.com/en-us/azure/traffic-manager/traffic-manager-overview>  |
| Azure Storage Scalability and Performance Targets  | <https://docs.microsoft.com/en-us/azure/storage/storage-scalability-targets>  |

# SQL Server hybrid cloud whiteboard design session trainer guide

## Step 1: Review the customer case study

-   Check in with your table participants to introduce yourself as the trainer

-   Ask, "What questions do you have about the customer case study?"

-   Briefly review the steps and time frames of the whiteboard design session

-   Ready, set, go! Let the table participants begin

## Step 2: Design a proof of concept solution

-   Check in with your tables to ensure that they are transitioning from step to step on time

-   Provide some feedback on their responses to the business needs and design

    -   Try asking questions first that will lead the participants to discover the answers on their own

-   Provide feedback for their responses to the customer's objections

    -   Try asking questions first that will lead the participants to discover the answers on their own

## Step 3: Present the solution

-   Determine which table will be paired with your table before Step 3 begins

-   For the first round, assign one table as the Microsoft team and the other table as the customer

-   Have the Microsoft team present their solution to the customer team

    -   Have the customer team provide one objection for the Microsoft team to respond to

    -   The presentation and objections should be no longer than 10 minutes

-   Have participants on the customer team give feedback to the Microsoft team

    -   The feedback should be no longer than 5 minutes

    -   If needed, the trainer may also provide feedback

## Wrap-up

-   Have the table participants reconvene with the larger session group to hear the faciliator/SME share the following preferred solution

##  Preferred target audience

-   Michelle Jenkins, Chief Information Officer

-   James Sherburn, Director, IT Operations

-   Robert Moore, Manager, Database Administration

-   Brandon Burns, Database Architect, Enterprise Architecture

## Preferred solution

The solution for Fabrikam's scenario involved several technologies.

-   Implementing Azure Site Recovery to replicate VMware virtual machines to Azure and orchestrate failover in the event of a disaster

-   Using SQL Server AlwaysOn Availability Groups to provide synchronous high availability on-premises

-   Using SQL Server AlwaysOn Availability Groups to provide asynchronous disaster recovery in Azure

-   Take advantage of SQL Server AlwaysOn Availability Groups with readable secondaries and read-intent routing to offload the heavy read workloads.

-   Using SQL Server Always Encrypted to encrypt and decrypt PCI data at the application to protect data in-flight or at rest with keys stored in Azure Key Vault

-   Using SQL Server Stretch Database to archive historical data to Azure SQL Database

-   Implementing SQL Server Backup to URL to send backups to Azure Storage

-   Using Azure Traffic Manager with Azure Site Recovery for availability of customer-facing sites

***Plan for high availability and disaster recovery***

1. **Orchestrated failover**: Fabrikam needs to automate and simplify the failover process for the web site. Design a solution that supports orchestrated failover of the entire site. 

   Azure Site Recovery will be used to protect the web farm and orchestrate failover in the event of a disaster.

2. **Additional infrastructure:** Address what additional infrastructure Fabrikam would need to enable the stated solution.

   An on-premises process server that acts as a replication gateway. It receives data from protected source machines, optimizes it with caching, compression, and encryption, and it sends replication data to Azure storage. It also handles push installation of Mobility service to protected machines and performs automatic discovery of VMware VMs. The disaster recovery virtual machines in Azure will remain offline until failover. Replicated data will be sent directly to the VHD files sitting in Azure Storage.

   To enable Azure Site Recovery, the following is required:

   The Mobility service is deployed on each machine (VMware VM or physical server) that you want to replicate to Azure. It captures data writes on the machine and forwards them to the process server. See <https://docs.microsoft.com/en-us/azure/site-recovery/vmware-azure-tutorial-prepare-on-premises>.

   You will also need Active Directory on the secondary recovery site for SQL Server to run properly. A couple of options are available:

-  Small enterprise---if you have a small number of applications and a single domain controller for the on-premises site, and you want to fail over the entire site, we recommend you use Site Recovery replication to replicate the domain controller to the secondary datacenter or to Azure.

-   Medium to large enterprise---if you have a large number of applications, are running an Active Directory forest, and want to fail over by application or workload, we recommend you set up an additional domain controller in the secondary datacenter or in Azure. Note that if you are using AlwaysOn availability groups to recover to a remote site, we recommend you set up another additional domain controller on the secondary site or Azure to use for the recovered SQL Server instance.

3. **SQL Server:** The DR solution for SQL Server should include near-zero data loss. Design the DR solution to provide near-zero data loss along with minimal overhead on normal transactions.

    The SQL Server databases will be protected by SQL Server AlwaysOn Availability Groups. For on-premises high availability, we will use Synchronous Availability Groups with automatic failover. This allows for zero data loss, high availability in the event of a single node failure or during maintenance. The automatic failover will require the use of an additional file share witness on site.

    The disaster recovery SQL Server virtual machine in Azure will be an asynchronous replica of the availability group. Failover to an asynchronous replica is always forced, as there is a potential for data loss. In the event of a failover, Azure Site Recovery will orchestrate the failover through the use of a Recovery Plan, which will run the necessary scripts to failover the SQL Server. See the "Integrate with SQL Server Always On for replication to Azure" section of this article <https://docs.microsoft.com/en-us/azure/site-recovery/site-recovery-sql>.

4. **Availability:** The site should be highly available, even after failover to the disaster site. Explain how your design meets these goals after failover.

    For connectivity to the public-facing sites, Azure Traffic Manager will be configured in failover mode.

    Traffic Manager will be configured on two external endpoints (the existing on-premises site and a site that you will pre-configure in DNS for when ASR fails over). When Traffic Manager detects an outage on the primary on-premises site, it will failover DNS resolution to the pre-configured site in Azure.

 > *Note: as long as the attendees understand this far, they are doing great. Implementation notes are here for the full details: <https://azure.microsoft.com/en-us/blog/reduce-rto-by-using-azure-traffic-manager-with-azure-site-recovery/>.*  For SQL Server connectivity from the application servers, SQL Server Availability Groups uses a Listener for client connectivity.

***Scale out data platform***

1. **Scale out**: The solution should provide a scale out data platform to offload the heavy read workload to secondary servers.

   The SQL Server AlwaysOn Availability Group will be extended to include additional async readable secondaries. The application will leverage read-intent routing to take advantage of the readable secondaries.

2. **User experience**: Address the user experience issues of the data tier. How will this solution address this?

   The application sees performance issues under heavy read workloads. Leveraging multiple readable secondaries and read-intent routing allows us to spread the heavy read workloads out across all of the replicas minimizing the impact on any one server.

3. **Application impact**: What impact will your design have on the existing application?

   Application code does not have to be rewritten, so no changes will need to be made to application code, only to the connection strings. The application should see improved performance due to the offloading of the heavy read workload to the AlwaysOn Availability Group secondaries.

4. **Diagram the data tier solution**

    ![The diagram comprises two main boxes: On-premises (primary) on the left, and Azure (secondary) on the right. An octagon labeled Traffic Manager Configured in Failover/Priority Mode is above these boxes, and arrows lead from the octagon to the On-premises (primary) box and the Azure (secondary) box. Below the Traffic Manager octagon is an icon labeled ASR. At the top of the On-premises (primary) box, the Traffic Manager line points to nine icons labeled Web Farm/Application Servers VMWare/vCenter, and an angle bracket points from them to an icon labeled Process Server Compression & Encryption. At the bottom of the On-premises (primary) box is an icon labeled Fire Share Witness, which points to a cluster of icons (the Primary icon points to Async Secondaries icons and points to the Sync Secondary icon with the word "Sync"). At the top of the Azure (secondary) box, nine VM icons point to an Azure Storage icon. At the bottom of the box, an icon labeled ILB with listener is above a set of four icons labeled Async Secondaries. A dotted box labeled Availability Group surrounds the On-premises (primary) box's icon cluster and the Azure (secondary) box's four Async Secondaries icons, and an arrow labeled Asynchronous points from the icon cluster to the Async Secondaries icons. At the top of the boxes, an arrow labeled Azure Site Recovery Replication points from the Process Server Compression & Encryption icon in the On-premises (primary) box to the Azure storage icon in the Azure (secondary) box.](images/Whiteboarddesignsessiontrainerguide-SQLServerhybridcloudimages/media/image7.png "Data tier solution diagram")

***Protect data***

1. **Encrypt PCI data:** Choose an appropriate encryption technology to protect credit card related data.

   Since we need to protect data in-flight, we will use SQL Server Always Encrypted. Always Encrypted allows clients to encrypt sensitive data inside client applications. An Always Encrypted-enabled driver installed on the client computer achieves this by automatically encrypting and decrypting sensitive data in the client application. The driver encrypts the data in sensitive columns before passing the data to the Database Engine, and the driver automatically rewrites queries, so the semantics to the application are preserved. Similarly, the driver transparently decrypts data stored in encrypted database columns and contained in query results.

2. **Key management**: How are the encryption keys managed in your design?

   Always Encrypted uses two types of keys: Column master keys and column encryption keys. A column master key (CMK) is a key encrypting key (i.e. a key used to encrypt other keys) that is always in the client's control and is stored in an external key store. A column encryption key (CEK), is a content encryption key (i.e. a key used to protect data) protected by a CMK. Both encryption keys should be generated on a separate computer either dedicated for key management or is a machine hosting application that will need access to the keys anyway.

   It is common for keys to be rotated to comply with organizational policies or in case an encryption key is compromised. There are two high-level key rotation work-flows; rotating column master keys, and rotating column encryption keys.

   Column master key rotation involves decrypting column encryption keys that are protected with the current column master key, re-encrypting them using the new column master key, and updating the metadata for both types of keys. Column master key rotation can be completed with or without role separation (role separation is where a security or system admin has access to the keys but not the data and a database administrator has access to the data but not the keys). In Fabrikam's case they specifically asked for role separation to prevent exposure of unencrypted keys to DBAs and developers.

   Column encryption key rotation involves decrypting data that is encrypted with the current key, and re-encrypting the data using the new column encryption key. Because rotating a column encryption key requires access to both the keys and the database, column encryption key rotation can only be performed without role separation. Note that, rotating a column encryption key can take a long time if the tables containing columns are encrypted with the key, being rotated, are large. While the data is being re-encrypted, your applications cannot write to the impacted tables. Therefore, your organization needs to carefully plan a column encryption key rotation.

   Facilitating additional applications to access the encrypted data in the database can be accomplished by storing the keys in Azure Key Vault. Applications can be registered in Azure AD and given access to Azure Key Vault. The application can then be modified to pull the encryption keys from Azure Key Vault as opposed to storing the keys locally.

3. **Application impact**: What impact will your design have on the existing application?

   Application code will need to be updated to support pulling the key from Azure Key Vault. The application servers' client drivers will need to be updated to a compatible driver.

4. **Encryption type**: Create a table that shows each type of PCI data and the appropriate type of encryption for each.

   There are two types of encryption with Always Encrypted; deterministic and random. Deterministic encryption always generates the same encrypted value for any given plain text value. Using deterministic encryption allows point lookups, equality joins, grouping and indexing on encrypted columns. However, it may also allow unauthorized users to guess information about encrypted values by examining patterns in the encrypted column. Randomized encryption uses a method that encrypts data in a less predictable manner. Randomized encryption is more secure, but prevents searching, grouping, indexing, and joining on encrypted columns.

   Credit card processing has numerous data elements. You want searchable data elements to be deterministic to support point lookups, equality joins, grouping and indexing. Any other data can be random. Below is an example of some of the critical data elements as defined by PCI and how you might map them to different encryption types.

+------------------------------+---------------------+
| **Data Element**             | **Encryption Type** |
+==============================+=====================+
| Primary Account Number (PAN) | Deterministic       |
|                              |                     |
| (full credit card number)    |                     |
+------------------------------+---------------------+
| Cardholder Name              | Deterministic       |
+------------------------------+---------------------+
| Service Code                 | Random              |
+------------------------------+---------------------+
| Expiration Date              | Deterministic       |
+------------------------------+---------------------+

***Data archiving: Keeping cold/historical data online***

1. **Planning**: What questions would you pose to the customer in designing a data archive strategy? What is the retention period of the data? How many large tables are there in the database? How many large tables are there in the database?

   Customer data should be kept for 7 years. When customers come to the site, their order history for the last 7 years is available to them from the site.

   The tables to be archived are insert-only order tables. If an order is modified after the data is inserted into the table, it is represented as a new version of the order making the data in the table immutable.

   In this case, there are several large tables, but only the order-related tables are suitable for our archive strategy: the *orders* table and the *order\_detail* table.

2. **Identify archive data**: Describe how you would identify the appropriate tables for archiving.

   Generally, you only want to archive data that is not queried frequently and that will not be modified. The SQL Server Upgrade Advisor includes the Stretch Database Advisor utility to help identify databases and tables for Stretch Database. The utility allows you to modify the minimum size and row count parameters to expand or shrink the list of recommended tables. It also lists any blocking issues found for each table.

3. **Impact**: What impact will your design have on the existing reporting system? How will this solution effect the current maintenance issues?

   The existing reporting system will not need any modifications after implementing Stretch Database. Queries that include Stretch-enabled tables are expected to perform more slowly than they did before the tables were enabled for Stretch.

   By migrating a large portion of the data into Azure SQL Database, the regular maintenance should improve dramatically. Backups will only back up and index maintenance will have a significantly smaller data set to work with.

4. **Diagram the solution**

    ![On the left, three server icons are connected by a green, bidirectional arrow labeled Queries to an icon labeled On-premises SQL Server, within which are three orange icons labeled Eligible Data and six green icons labeled Local Data. An orange arrow labeled Eligible Data points from the On-premises SQL Server icon to an icon labeled Azure SQL Database, within which are nine icons that the same shape and color as the Eligible Data icons. A green, bidirectional arrow labeled Queries points between the On-premises SQL Server icon and the Azure SQL Database icon.](images/Whiteboarddesignsessiontrainerguide-SQLServerhybridcloudimages/media/image8.png "Diagram of the solution")

***Offsite backup***

1. **Database backups**: What backup technology would you recommend? How does the solution meet the offsite requirements? How does this design meet the stated security goals?

   SQL Server Backup to URL provides the most straightforward replacement of the existing backup solution. Managed backups are an option as well, but you do lose some control over the backup schedule. To use SQL Server Backup to URL, you will need to create an Azure Storage Account within your Azure subscription. SQL Server can either use the Azure storage account name and its access key value to authenticate and write and read blobs to the Microsoft Azure Blob storage service or use a Shared Access Signature token generated on specific containers granting it read and write rights. A SQL Server Credential stores this authentication information and is used during the backup and restore operations.

   In addition to backing up directly to Azure storage, which is by nature offsite, Azure Storage Accounts would be created with geo-redundancy to protect backup files by asynchronously copying backups to a second Azure region for additional protection.

   The Azure storage is protected by an access key, which will be stored in a SQL Server Credential. In addition to Azure storage access control, the SQL Backups should be created WITH ENCRYPTION to protect the contents of the backup file.

2. **Provide the following configuration details:** What will be needed in the event a database needs to be restored to a different server? How does this solution impact the time to restore? What considerations need to be made with regard to Azure Storage Account scale targets?

   If a backup needs to be restored to a different server, you will need the URL of the storage account and you will need to create a credential on the SQL Server with the name and access key of the storage account.

   Restore times will generally be slower than restoring from a local disk, but faster than restoring from a remote tape archive. To optimize restore times, it is recommended that you adhere to the following best practices:

- Add **perform volume maintenance tasks** user right to the SQL Server account to allow instant file initialization for the database during a restore

- Use compressed backups to minimize network transfer and disk read from Azure

- For backups in excess of 25 GB, copy the backup file locally with a utility, such as AzCopy, and perform the restore from the local copy

- If the log is very large in size (multiple gigabytes), it would be expected that restore would be slow. During restore, the log file must be zeroed, which takes a significant amount of time.

   Storage accounts have scale targets that determine the maximum file size, maximum capacity of the storage account, and the maximum throughput (among other things). All of these scale targets must be considered when sending backups to an Azure Storage Account.

## Checklist of preferred objection handling

1.  Solution must support orchestrated failover so that failover does not require all hands-on deck

    **Potential answer**

    Azure Site Recovery orchestrates replication of your on-premises and virtual machines to a secondary on-premises data center or to Azure. Site recovery handles the VM replication and integrates with SQL Server Availability Groups. Failover can be kicked off with a simple click.

2.  Solution must support the existing VMware infrastructure

    **Potential answer**

    Azure Site Recovery supports the replication of on-premises servers, Azure virtual machines, Hyper-V virtual machines, and VMware virtual machines.

3.  Solution must not have a significant impact on database performance

    **Potential answer**

    The use of asynchronous replicas to the disaster recovery site will keep the overhead of Availability Group replication to near zero, while providing the application the ability to offload the heavier read workloads to the secondary replicas.

4.  Disaster recovery infrastructure must be easily scalable to support changes in the workload

    **Potential answer**

    As workloads change, Azure virtual machines can be scaled up or down as necessary to provide the appropriate amount of resources.       This can be done by modifying the virtual machine size.

5.  The disaster recovery sites must be highly available after a failover

    **Potential answer**

    By placing Azure virtual machines into an Availability Set, you can keep your virtual machines available during downtime such as during maintenance or unplanned outages. It is best practice to use availability sets and load-balancing endpoints to help ensure that your application is always available and running efficiently.

    SQL Server virtual machines will rely on a combination of Availability Sets and SQL Server Availability Groups to maintain uptime and synchronization. The SQL Servers will belong to a separate Availability Set from the web servers and will also use an internal load balancer.

6.  Archive solution must not impact the current applications, which periodically pull historical data from the production system

    **Potential answer**

    SQL Server Stretch Database does not require any changes to existing queries or applications; the location of the data is completely transparent to the application. The entire table is always online and can be queried. You will set the policy that determines where the data is stored, either on the local server or in Azure.

7.  Backups need to be secured offsite in less than two hours after completion.

    **Potential answer**

    SQL Server Backup to URL backs up databases directly to Azure Storage. As soon as the backup is complete, it is offsite and protected. Furthermore, if using geo-redundant storage, your database backups will be asynchronously replicated to a secondary region hundreds of miles away.

## Customer quote (to be read back to the attendees at the end)

"*By using Azure, we have the confidence that we can keep our business running in the event of a disaster, with minimal overhead and near-zero data loss.*"

---Michelle Jenkins, Chief Information Officer, Fabrikam Publishing

