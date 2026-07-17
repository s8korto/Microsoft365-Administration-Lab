# Microsoft 365 Tenant Setup

## Objective

This lab demonstrates the initial configuration of a Microsoft 365 tenant used throughout the project.

This tenant serves as the foundation for managing users, licenses, security policies, Exchange Online, Teams, SharePoint, and other Microsoft 365 services.

---

## Prerequisites

- Microsoft 365 Developer Tenant or Trial Tenant
- Internet connection
- Administrator account
- Web browser

---

## Steps

### 1. Configure a Microsoft 365 Business Tenant

1. Signed up for Microsoft 365 Business.
2. Entered the organisation name.
3. Selected the tenant name.
4. Completed identity verification.
5. Signed in as the Global Administrator.

![Tenant Dashboard](screenshots/01-tenant-dashboard.png)

---

### 2. Verify Organization Information

After completing the Microsoft 365 Business setup, I verified the tenant configuration in the Microsoft 365 Admin Center.

Navigation:

Settings
→ Org settings
→ Organization profile
→ Organization information

Verified:

- Organization information is accessible.
- Default tenant domain is configured.
- Tenant ID is assigned.
- Technical contact email is configured.
- Preferred language is configured.

![Organisation Information](screenshots/02-organisation-information.png)

---

### 3. Verify Default Domain

Navigation:

Settings
→ Domains

Verify:

- Default domain exists.
- Domain status is Healthy.
- Domain type is Microsoft-managed.

The default onmicrosoft.com domain is automatically assigned during tenant provisioning and is required for user accounts and Microsoft 365 services.

![Domain](screenshots/03-domain.png)

---

### 4. Review Licences

Navigate to:

Billing
→ Licenses

Verify:

- Available licenses
- Assigned licenses
- License type

Reviewing available licenses confirms which Microsoft 365 services can be assigned to users.

![Licence](screenshots/04-licence.png)

---

### 5. Explore the Microsoft 365 Admin Center

After provisioning the tenant, I explored the Microsoft 365 Admin Center to become familiar with the administrative interface and available management areas.

The following sections were reviewed:

- Home
- Users
- Teams & Groups
- Billing
- Reports
- Health
- Settings
- Admin Centers

---

## Verification

Successfully confirmed:

- Tenant created
- Global Administrator account available
- Admin Center accessible
- Default domain verified
- Licenses available

---

## Key Takeaways

- Created a Microsoft 365 tenant.
- Verified the default domain.
- Explored the Microsoft 365 Admin Center.
- Reviewed available licenses.
- Confirmed administrative access.

---

## Next Steps

The tenant has now been configured and verified.

The next stage of the lab focuses on:

- Creating users
- Managing passwords
- Assigning licenses
- Creating security groups





