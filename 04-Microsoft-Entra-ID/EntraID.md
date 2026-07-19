# Microsoft Entra ID Administration

## Objective 

This lab demonstrates how to use Microsoft Entra ID to manage identities, security groups, administrator roles, authentication methods, and sign-in activity within a Microsoft 365 tenant.

---

## Business Scenario

An company employs approximately 20 staff across multiple departments including:

- IT
- Human Resources
- Finance
- Sales
- Operations

Following several phishing attempts targeting employee accounts, management requested the IT department to strengthen identity security and improve access management across the Microsoft 365 environment.

As the Microsoft 365 Administrator, I was responsible for reviewing user identities, implementing security controls, monitoring authentication activity, and applying the principle of least privilege.

---

## Business Requirements

- Review user accounts and identity information
- Verify department security groups
- Enable Multi-Factor Authentication (MFA)
- Create a Conditional Access policy
- Reset compromised user passwords
- Review sign-in activity
- Assign administrator roles using the Principle of Least Privilege

---


## Prerequisites

- Microsoft 365 Business 
- Existing users created in previous labs

---


## Lab 1 - Access Microsoft Entra Admin Center

### Steps

1. Sign in to the Microsoft 365 Admin Center.
2. Select **Admin centersc**.
3. Click **Identity** to open Microsoft Entra Admin Center.

## Verification

Verify the Microsoft Entra dashboard is displayed.

![Entra Dashboard](screenshots/01-Entra-Dashboard.png)

---

## Lab 2 - View Users

### Steps

1. Navigate to **Identity** → **Users** → **All users**.
2. Review the existing users.
3. Select a user to view:
   - Profile
   - Assigned licenses
   - Assigned roles
   - Authentication methods

## Verification

Confirm the user information is displayed correctly.

![All Users](screenshots/02-AllUsers.png)

---

## Lab 3 - Create a Security Group

### Steps

1. Navigate to **Groups** → **All groups**.
2. Click **New group**.
3. Configure the following:

| Setting | Value |
|----------|-------|
| Group Type | Security |
| Group Name | IT Support |
| Membership Type | Assigned |

4. Click **Create**.
5. Add existing users as members.

## Verification

Confirm the group has been created and members have been added.

![Security Group](screenshots/03-SecurityGroup.png)

---

## Lab 4 - Explore Administrator Roles

### Steps

1. Navigate to **Roles & administrators**.
2. Open the following roles:
   - Global Administrator
   - User Administrator
   - Groups Administrator
   - Helpdesk Administrator
3. Review each role's permissions.

## Verification

Confirm the available administrator roles are displayed.

![Roles](screenshots/04-Roles.png)

---

## Lab 5 - View Authentication Methods

### Steps

1. Navigate to **Users**.
2. Select an existing user.
3. Open **Authentication methods**.
4. Review the available authentication options.

## Verification

Confirm the user's authentication methods are displayed.

![Authentication](screenshots/05-Authentication.png)

---

## Lab 6 - View Sign-in Logs

### Steps

1. Navigate to **Monitoring** → **Sign-in logs**.
2. Review recent sign-in activity.
3. Observe:
   - User
   - Status
   - Application
   - IP Address
   - Time

## Verification

Confirm sign-in logs are available.

![SignInLogs](screenshots/06-SignInLogs.png)

---

## Lab 7 - Explore Enterprise Applications

### Steps

1. Navigate to **Applications** → **Enterprise applications**.
2. Review the available applications.

## Verification

Confirm enterprise applications are displayed.

![Enterprise Application](screenshots/07-EnterpriseApplications.png)

---

# Key Takeaways

- Microsoft Entra ID is the identity and access management service for Microsoft 365.
- Users, groups, and administrator roles are centrally managed through Entra ID.
- Security groups simplify permission management.
- Authentication methods and sign-in logs help secure user accounts and troubleshoot access issues.
- Enterprise Applications provide centralised management of applications integrated with Microsoft Entra ID.





