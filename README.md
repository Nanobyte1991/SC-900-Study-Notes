# SC-900 Study Notes

## Table of Contents
1. [Encryption](#encryption)
2. [Responsibilities](#responsibilities)
3. [Privacy Principles](#privacy-principles)
4. [Key Areas](#key-areas)
5. [Cloud Deployments](#cloud-deployments)
6. [Total Cost of Ownership](#total-cost-of-ownership)
7. [Cloud Architecture Terms](#cloud-architecture-terms)
8. [Services and Regions](#services-and-regions)

## Encryption

### Symmetric Encryption
- **Description:** Uses the same key for encryption and decryption.
- **Example:** AES (Advanced Encryption Standard)

### Asymmetric Encryption
- **Description:** Uses a pair of keys – a public key for encryption and a private key for decryption.
- **Example:** RSA (Rivest-Shamir-Adleman)

### Hashing
- **Description:** Converts data into a fixed-size string of characters, which is typically a digest that is unique to each unique input.
- **Example:** SHA-256 (Secure Hash Algorithm 256-bit)

## Responsibilities

### Customer Responsibilities
- **Data Protection:** Ensure the data is secure both in transit and at rest.
- **Identity Management:** Manage user identities and access.
- **Compliance:** Ensure compliance with regulatory requirements.

### Cloud Provider Responsibilities
- **Infrastructure Security:** Secure the physical and virtual infrastructure.
- **Data Center Operations:** Manage data center operations, including disaster recovery.
- **Compliance:** Maintain compliance certifications for infrastructure.

## Privacy Principles

### Data Minimization
- **Description:** Collect only the data that is necessary for the intended purpose.
- **Practice:** Regularly review and delete unnecessary data.

### Purpose Limitation
- **Description:** Use data only for the purposes for which it was collected.
- **Practice:** Inform users about data usage policies.

### Data Accuracy
- **Description:** Ensure data is accurate and up-to-date.
- **Practice:** Regularly update and correct inaccurate data.

## Key Areas

### Identity and Access Management (IAM)
- **Description:** Processes and technologies for managing digital identities and controlling access to resources.
- **Example:** Azure Active Directory (Azure AD)

### Information Protection
- **Description:** Safeguard sensitive information from unauthorized access and disclosure.
- **Example:** Azure Information Protection

### Security Management
- **Description:** Tools and processes to manage security policies, monitor threats, and respond to security incidents.
- **Example:** Azure Security Center

## Cloud Deployments

### Public Cloud
- **Description:** All resources are hosted in the cloud provider’s infrastructure.
- **Example:** Microsoft Azure

### Private Cloud
- **Description:** All resources are hosted within an organization’s own data center.
- **Example:** On-premises data center

### Hybrid Cloud
- **Description:** Combines public and private clouds, allowing data and applications to be shared between them.
- **Example:** Azure Stack

## Total Cost of Ownership

### CapEx (Capital Expenditure)
- **Description:** Upfront costs associated with purchasing and owning hardware.
- **Pros:** Generally more cost-effective for licenses.
- **Cons:** Higher upfront costs, less flexibility.

### OpEx (Operational Expenditure)
- **Description:** Ongoing costs associated with cloud services.
- **Pros:** Lower initial costs, better scalability and flexibility.
- **Cons:** Higher ongoing costs for licenses.

## Cloud Architecture Terms

### Availability
- **Definition:** Ensuring services remain online and functional.
- **Example:** High Availability (HA) using multiple availability zones.

### Scalability
- **Definition:** Ability to increase or decrease resources based on demand.
- **Types:**
  - **Vertical Scaling:** Increasing the size of a single resource (e.g., larger VM).
  - **Horizontal Scaling:** Adding more resources (e.g., more VMs).

### Elasticity
- **Definition:** Automatically adjusting resources based on demand.
- **Example:** Azure Scale Sets

### Fault Tolerance
- **Definition:** Ability to continue operating in the event of a failure.
- **Example:** Using load balancers and multiple availability zones.

### Disaster Recovery (DR)
- **Definition:** Strategies to recover from unexpected failures.
- **Example:** Geo-redundant storage and backup solutions.

## Services and Regions

### Azure Regions
- **Description:** Geographic locations where Azure services are available.
- **Examples:** East US, West Europe, Southeast Asia

### Global Network
- **Description:** Microsoft’s private global network that connects its data centers.
- **Benefits:** Low latency, high availability, and robust security.

### Service Categories
- **Compute:** Virtual machines, containers, serverless computing.
- **Storage:** Object storage, file storage, databases.
- **Networking:** Virtual networks, load balancers, VPNs.
- **Security:** Identity management, encryption, threat protection.
- **Management Tools:** Monitoring, automation, governance tools.
