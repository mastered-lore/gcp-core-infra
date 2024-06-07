# Cloud Foundation Toolkit vs. Cloud Fabric FAST

Both Cloud Foundation Toolkit (CFT) and Cloud Fabric FAST are open-source frameworks provided by Google Cloud for setting up and managing Google Cloud Platform (GCP) environments. However, they have distinct approaches and goals.

## Cloud Foundation Toolkit (CFT)

Cloud Foundation Toolkit is a comprehensive framework that provides a opinionated set of best practices and automated tools for deploying and managing GCP environments. It aims to help organizations establish a secure, consistent, and scalable cloud infrastructure.

Key features of CFT:

1. **Modular Design**: CFT is organized into modules that represent different components of a GCP environment, such as networking, identity and access management (IAM), and project factories.

2. **Opinionated Approach**: CFT follows a specific set of best practices and conventions for configuring GCP resources, making it prescriptive in nature.

3. **Terraform-based**: CFT uses Terraform as its primary Infrastructure as Code (IaC) tool, providing a declarative way to define and manage GCP resources.

4. **Enterprise Focus**: CFT is designed with enterprise-level requirements in mind, prioritizing security, compliance, and scalability.

5. **Continuous Integration and Deployment (CI/CD)**: CFT includes support for CI/CD pipelines, enabling automated deployment and management of GCP environments.

## Cloud Fabric FAST

Cloud Fabric FAST (FAST) is a framework that provides a design and reference implementation for setting up a production-ready GCP organization. It takes a more flexible and modular approach compared to CFT.

Key features of FAST:

1. **Staged Approach**: FAST is organized into stages, each responsible for a specific task or set of resources. These stages are designed to align with typical security boundaries found in organizations.

2. **Customizable Design**: FAST presents a flexible design that can be customized and extended to meet specific organizational needs.

3. **Modular Implementation**: FAST encourages the use of "pluggable modules" or reference architectures, allowing users to adopt or modify components as needed.

4. **Security-First Mindset**: Security is a core principle in FAST's design, with a strong emphasis on minimizing permissions and implementing guardrails.

5. **Multitenant Support**: FAST includes built-in support for multitenant organizations, enabling tenants to independently manage their own environments.

6. **Infrastructure as Code**: While FAST provides a reference implementation using Terraform, it is designed to be agnostic to the specific IaC tool used.

While both frameworks share the goal of facilitating the deployment and management of GCP environments, they differ in their approaches and target audiences.

**CFT** provides a more opinionated and prescriptive set of best practices, making it well-suited for organizations that prefer a standardized and consistent approach to cloud infrastructure management. It is particularly valuable for enterprises with strict security and compliance requirements.

**FAST**, on the other hand, offers a more flexible and modular design, allowing for greater customization and adaptation to specific organizational needs. It may be preferred by organizations that require a tailored approach or have unique requirements that cannot be easily accommodated by a prescriptive framework like CFT.

Ultimately, the choice between CFT and FAST will depend on the organization's specific requirements, priorities, and desired level of flexibility in managing their GCP environments.
