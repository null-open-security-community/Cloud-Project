# Project Overview

Cloud technologies empower organisations to build and run scalable applications in modern, dynamic environments such as. Cloud Services, Containers, cloud functions (serverless), service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach. Cloud-Native Applications is a fundamentally new and exciting approach to designing and building software. However, it also raises an entirely new set of security challenges. For example, when you move to a microservice model, end-to-end visibility, monitoring, and detection become more complex and challenging to execute, and security operations and management becomes hectic.

This project aims to deliver an awareness and reference report to highlight the most common Cloud and Cloud-Native security issues along with the toolchain to test the infrastructure for those issues.

# Project Purpose

The primary purpose of this project is to provide assistance and education for organisations looking to adopt Cloud and Cloud-Native Technologies. 

The project will give the organisations guides and tools that will include information about what are the significant security risks for Cloud and Cloud-Native environments, how to find and mitigate them.

# Goals

The project's primary goal is to enable a conversation on cloud and cloud-native security helping people/organisations secure their products and services running in the cloud or using cloud-native infrastructure by providing a set of attacker and defender scenarios that pool together the expertise and experience of the communities.

The project will collect a dataset of identified vulnerabilities related to cloud and cloud-native technologies to enable analysis and further research. The data will be analysed to determine the most significant and common issues and develop tools to assist in auditing and fixing the vulnerabilities.


# Project Roadmap:

- ## Initial Project Draft (Done)

As the first step for this project, A detailed project document explaining a different aspect of the projects, including a project plan and goals will be documented.

- ## Contribution Process design (Done)

For the collection of the required dataset, an appropriate submission format will be designed, which can include all the aspects of the issue. The team will also finalise an approach and methodology for collection, storage and processing.

- ## Official Call for Contribution (On-Going)

The official public call for contribution via different channels and request community to contribute the most common vulnerabilities they see in the cloud and cloud-native environments will be sent, along with this the project team will also start collecting the data from the internet.

- ## Data Processing

The team will analyse collected dataset on the various available parameters associated with issues and create the relevant mapping. The team would also explore additional insights that could be extracted from the contributed datasets to see what else can be learned that could be of use to the community.

- ## Document Release &amp; Internal Review

The project team will create an internal draft analysis report and will submit that to the null team and active volunteers for review, suggestions and areas to focus.

- ## Public Release of Report

The team will publish a release candidate for the report once all the inputs provided by the internal team are incorporated and fixed. The release candidate will remain in public for 15 days open to suggestions for improvements, and the team release a final report post the final review and changes.

- ## Tool Kit Beta Release

A toolkit will be created to test the cloud and cloud-native infrastructures against the collected issues.

# **Project Assumptions**

- ## What is Cloud Computing

As per **NIST (National Institute of Standards and Technology)**, _&quot;Cloud computing is a model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction.&quot;_

For this project, the public cloud providers and services will be considered in the scope for the cloud-related security issues, and definition of the public cloud is as below.

&quot;_The public cloud is defined as computing services offered by third-party providers over the public Internet, making them available to anyone who wants to use or purchase them. They may be free or sold on-demand, allowing customers to pay only per usage for the CPU cycles, storage or bandwidth they consume. E.g. AWS, Azure, GCP, Oracle, Digital Ocean etc.&quot;_

- ## What is Cloud-native?

As per **CNCF (Cloud Native Computing Foundation)**, _&quot;Cloud native technologies empower organisations to build and run scalable applications in modern, dynamic environments such as public, private, and hybrid clouds. Containers, service meshes, microservices, immutable infrastructure, and declarative APIs exemplify this approach. These techniques enable loosely coupled systems that are resilient, manageable, and observable. Combined with robust automation, they allow engineers to make high-impact changes frequently and predictably with minimal toil.&quot;_

For this project, the standard cloud-native technologies of such as containers (Docker, ContainerD etc), container orchestrators (Kubernetes, SWARM, Apache Mesos etc), Serverless Computing (AWS Lambda, Azure Functions etc.) &amp; Services Mesh (Istio, Linkerd and Consul etc.) will be considered in the scope for the cloud-native security issues

# **Data** Collection Methodology:

Under the project, we would collect data for cloud and cloud-native issues separately to generate two different reports for cloud and cloud-native security issues. Each collected issue will have two types of stories.

- Attacker&#39;s Story: The attacker&#39;s story will focus on the root cause for the issue, how to test for the issue &amp; the possible exploitation scenarios.

- Defender&#39;s Story: The defender&#39;s story will focus on how to detect if a particular issue is being exploited, how to remediate the issue and possible workaround to limit the exposure in case of complete remediation is not possible.

The data collection will be done with the help of Google Form, the form will collect the following details for each contribution.

- **Contribution Type (Individual, Organization):** Every contributor will have a choice to make either an individual contribution or they can contribute to the project on behalf of the organisation they represent/work.
- **Issue Name:** A widely accepted name for the issue.
- **Issue Type:** Is it a cloud issue or cloud-native issue?
- **Affected Platform:** Which platforms are affected by the issue
- **Attacker&#39;s View:**
  - **The root cause for the issue:** What is the main cause of this issue to occur.
  - **Steps for testing and exploitation:** How to test and exploit the issue:
- **Defender&#39;s View:**
  - **Steps to detect if the issue is being exploited:** The ways to detect if the issues present in the infrastructure are being exploited.
  - **Steps to Remediate:** How to fix the issue
  - **The workaround in case of dependency:** In case of complete remediation is not possible, what are the must-do steps to ensure the exposure is minimal.
- **The criticality of the issues:** How would you rate the criticality of the issue, CVSS Vector string would be plus.
- **The uniqueness of the issue:** Provide a rating on the uniqueness of the issue between 1-10 which 1 is a common issue and 10 is a unique issue.
- **Total Number occurrence of the issue:** Please provide a count on how many times the issue has occurred in all the project you have worked on. If the issue has arisen or identified five times in a single project, please consider it single occurrence.