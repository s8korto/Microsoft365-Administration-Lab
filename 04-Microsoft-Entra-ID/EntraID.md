# Microsoft Entra ID

## Objective 

This lab demonstrates how to use Microsoft Entra ID to manage identities, security groups, administrator roles, authentication methods, and sign-in activity within a Microsoft 365 tenant.

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




