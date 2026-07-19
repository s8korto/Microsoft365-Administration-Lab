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

# Task 1 - Review User Accounts

### Help Desk Ticket

**Ticket:** HD-4001

**Request**

HR recently onboarded several new employees and requested IT verify that all user accounts had been successfully created before Microsoft 365 services were assigned.

### Actions Performed

- Opened Microsoft Entra Admin Center
- Reviewed all users
- Verified account status
- Confirmed user information including department and job title
- Checked sign-in status

### Business Value

Reviewing user accounts ensures employee identities are accurate before access is granted to company resources, reducing administrative errors during onboarding.

### Verification

- All employee accounts successfully located
- User information matched HR records
- Account status 

![Review Users](screenshots/01-Review-Users.png)

---

# Task 2 - Review Security Groups

### Help Desk Ticket

**Ticket:** HD-4002

**Request**

The IT Manager requested verification that employees were assigned to the correct security groups to ensure department-based access to Microsoft 365 resources.

### Actions Performed

- Reviewed Security Groups
- Checked group membership
- Confirmed department assignments
- Verified group owners

### Business Value

Using security groups simplifies permission management and reduces the need to assign permissions individually.

### Verification

- Department groups displayed
- Users assigned to appropriate groups
- Group membership confirmed

![Security Groups](screenshots/02-Security-Groups.png)

---

# Task 3 - Enable Multi-Factor Authentication (MFA)

### Help Desk Ticket

**Ticket:** HD-4003

**Request**

Following multiple phishing attempts, management requested Multi-Factor Authentication be enabled for all office employees.

| Name | Department | Job Title |
|-------|------------|-----------|
| Ava Baker | Finance | Accounts Payable Officer |

### Actions Performed

- Selected target users
- Enabled Multi-Factor Authentication
- Verified MFA registration status

### Business Value

MFA significantly reduces the risk of compromised passwords being used to access company resources.

### Verification

- MFA enabled for selected users
- Authentication status displayed successfully

![Enable MFA](screenshots/03-Enable-MFA.png)

---

# Task 4 - Reset User Password

### Help Desk Ticket

**Ticket:** HD-4004

**Request**

A Sales employee contacted the IT Service Desk after forgetting their Microsoft 365 password and was unable to access Outlook and Teams.

| Name | Department | Job Title |
|-------|------------|-----------|
| Benjamin Scott | Sales | Sales Manager |

### Actions Performed

- Located the employee account
- Reset the password
- Required password change at next sign-in
- Provided temporary credentials

### Business Value

Password resets restore employee productivity while maintaining account security through mandatory password changes.

### Verification

- Password successfully reset
- User required to change password at next login

![Password Reset](screenshots/04-Password-Reset.png)

---

# Task 5 - Review Sign-in Logs

### Help Desk Ticket

**Ticket:** HD-4006

**Request**

The Security Team requested a review of recent sign-in activity after Microsoft reported unusual authentication attempts.

### Actions Performed

- Opened Sign-in Logs
- Reviewed successful sign-ins
- Reviewed failed sign-ins
- Examined login locations
- Checked authentication methods

### Business Value

Sign-in logs allow administrators to investigate suspicious login attempts and identify potential security incidents before they become serious threats.

### Verification

- Recent authentication activity displayed
- Successful and failed sign-ins reviewed
- Login locations verified

![Sign In logs](screenshots/05-Sign-In-Logs.png)


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





