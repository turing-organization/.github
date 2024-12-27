# [**Turing DevSecOps Technology**](https://turingtec.framer.website/)

![image](https://github.com/user-attachments/assets/177ee2c5-c298-430d-a6c3-e6113cc53df6)


Turing is a suite of innovative services that collects and distributes vulnerability and cyber risk analyses across the entire enterprise ecosystem.
The difference lies in the complete automation of the vulnerability management and compliance cycle, integrating multiple security platforms (such as Prisma, Sonar, Fortify, SecurityScoreCard), task management tools (such as Jira, Zendesk, ServiceNow) using AI to rank, predict potential attacks and offer automated solutions.

Our solution transforms security reports into automated actions, generating tickets, tasks and workflows, in addition to unifying and standardizing data to facilitate the creation of real-time dashboards. This allows companies to have a centralized and more agile view, significantly reducing response time and manual efforts of their security teams.

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

![image](https://github.com/user-attachments/assets/958300b6-3527-4802-8877-fa69f37352a9)

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
- Patch Management
    - Vicarius
- Management
    - Jira
    - Microsoft Teams
    - Webhooks
    - PowerBI
    - DefectDojo
    - Native Dashboard
    - Movidesk

Next:
- Slack
- ServiceNow
- Zendesk
- Datadog
- Grafana
- Fortify
- Dependaboot
- Snyk
- Dependency Check
- Checkov
- Terrascan
- Veracode
- Owasp Zap

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
