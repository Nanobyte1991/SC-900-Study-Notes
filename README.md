# SC-900 Study Notes

## Additional Learning Resources

- **Microsoft Learn:**
  - [SC-900 Microsoft Security, Compliance, and Identity Fundamentals](https://learn.microsoft.com/en-us/credentials/certifications/security-compliance-and-identity-fundamentals/?practice-assessment-type=certification) - Time to Complete: 6 hours
- **Udemy:**
  - [SC-900 Exam Prep](https://www.udemy.com/course/sc900-azure/?couponCode=ST10MT8624) - Time to Complete: 5 hours
- **Pluralsight:**
  - [Microsoft SC-900: Security, Compliance, and Identity Fundamentals](https://app.pluralsight.com/paths/certificate/microsoft-security-compliance-and-identity-fundamentals-sc-900) - Time to Complete: 4 hours
- **YouTube:**
  - [SC-900 Exam Preparation](https://www.youtube.com/watch?v=Bz-8jM3jg-8) - Time to Complete: 6 hours

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

### Shared Responsibility Model
- **Customer Responsibilities:** Data, endpoints, account management.
- **Cloud Provider Responsibilities:** Physical infrastructure, network, host environment.
- **Example:** Azure Shared Responsibility Model

## Privacy Principles

### Data Minimization
- **Description:** Only collecting data that is necessary for a specific purpose.
- **Example:** Only asking for an email address when signing up for a newsletter.

### Data Sovereignty
- **Description:** Data is subject to the laws and regulations of the country where it is collected.
- **Example:** GDPR compliance in the EU.

### Data Subject Rights
- **Description:** Rights of individuals to access and control their personal data.
- **Example:** Right to be forgotten under GDPR.

## Key Areas

### Identity and Access Management (IAM)
- **Description:** Framework for managing digital identities and controlling access to resources.
- **Example:** Azure Active Directory

### Information Protection
- **Description:** Protecting sensitive information from unauthorized access and disclosure.
- **Example:** Azure Information Protection

### Threat Protection
- **Description:** Detecting and responding to threats to maintain security.
- **Example:** Microsoft Defender for Cloud

## Cloud Deployments

### Public Cloud
- **Description:** All resources are hosted in the cloud provider’s infrastructure.
- **Example:** Azure

### Private Cloud
- **Description:** All resources are hosted within an organization's own data center.
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
- **Description:** Geographic locations where Azure resources are hosted.
- **Example:** East US, West Europe

### Availability Zones
- **Description:** Physically separate locations within an Azure region.
- **Example:** Zone-redundant services to protect from datacenter failures.

### Resource Groups
- **Description:** Logical containers for Azure resources.
- **Example:** Grouping related resources for management and billing purposes.

