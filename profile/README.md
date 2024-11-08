# [**Turing DevSecOps Technology**](https://turingtec.framer.website/)

![image](https://github.com/user-attachments/assets/d1cb298a-6489-4594-a8c3-c131bc275637)


Turing is a suite of innovative services that collects and distributes end-to-end vulnerability analysis and cybersecurity risk information. The project offers advanced functionality, robust security, and is easy to use, facilitating end-to-end vulnerability management, from collection to patch tracking.

Turing helps organizations streamline processes, improve team collaboration, and achieve greater operational efficiency. By replacing CSV exports and automating the secure development cycle, Turing becomes an essential component in strengthening information security.

## **Market Opportunity**

With experience in the DevOps and information security market, the need to integrate tools and processes with the secure development cycle is evident. Vulnerabilities often suffer from a gap between discovery and remediation, and this is exactly the problem that Turing solves.

Originally developed as independent APIs, the project has evolved into a unified product that captures vulnerabilities, standardizes, stores and distributes information for management in different systems, such as Jira or BI Dashboards. Turing connects each point of the secure development cycle in an efficient and centralized way.

## **Value Proposition**

Turing offers the following benefits to its customers:

- **Simplified Integration**: Ease of configuring and managing services between internal and external systems.
- **Efficient Information Distribution**: Ability to distribute information quickly and accurately to stakeholders, continuing development flows.
- **Advanced Security**: Implementation of robust security measures to protect data and ensure compliance with regulations.
- **Improved Collaboration**: Facilitation of collaboration between teams and departments, promoting efficiency and innovation.

### **Collection and distribution settings**

Users can configure distributions between different vulnerability management systems and discovery tools by specifying connection parameters, data synchronization rules, and where they want the collected data to be made available. 

- Cloud Security
    - CSPM
        - Palo Alto Prisma
        - Azure Defender for Cloud
    - TPRM
        - Zanshin
        - Security Score Card
- Development
    - SAST
        - SonarQube
        - Semgrep
    - DAST
        - Nessus
    - SCA
        - Dependaboot
        - Snyk
- Patch Management
    - Vicarius
- Management
    - Jira
    - Microsoft Teams
    - Webhooks
    - PowerBI
    - DefectDojo
    - Native Dashboa

Next:
- Slack
- ServiceNow
- Zendesk
- Datadog
- Grafana
- Vicarius
- Fortify
- Dependaboot
- Snyk
- Dependency Check
- Checkov
- Terrascan
- Veracode
- Owasp Zap

![image](https://github.com/user-attachments/assets/c8c0d218-e06a-40dc-ae85-f6784e87b435)

### **Monitoring and Management**

With Turing, you can integrate monitoring dashboards like PowerBI, Grafana, or Datadog to view detailed information about vulnerabilities found and the progress of their remediation. These insights help your business make quick and effective security decisions.

Focused on real security risks, the services send notifications in Teams and Slack, open tickets in Zendesk, and request changes in Service Now.

## Service Implementation

### Development and Staging

To ensure compatibility and ease of deployment, the services were containerized using Docker and Kubernetes, making them easy to install and manage across different cloud environments. Automation scripts were developed for installation and upgrades, using Infrastructure as Code (IaC) tools such as Terraform and AWS CloudFormation.

### Planning and Kickoff

We work closely with each customer to plan the implementation and establish clear expectations. The goal is to ensure that the transition to the services is smooth and seamless.

### Product Roadmap

The product roadmap is shared with customers and their feedback is incorporated into future updates and features. This ensures that development is always aligned with customer needs and constantly innovating.
