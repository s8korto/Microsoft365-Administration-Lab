# License Management

## Objective

This lab demonstrates how to manage Microsoft 365 licenses by viewing available subscriptions, assigning and removing licenses, enabling or disabling individual services, and performing bulk license assignments.

---

## Lab 1 - View Available Licenses

### Steps

1. Sign in to the Microsoft 365 Admin Center.
2. Navigate to **Billing** → **Licenses**.
3. Review the available subscriptions.
4. Note the total, assigned, and available licenses.

### Verification

- Microsoft 365 Business Premium is listed.
- License counts are displayed correctly.


![View Licenses](screenshots/01-view-licenses.png)

---

## Lab 2 - Assign a License

### Steps

1. Navigate to **Users** → **Active users**.
2. Select a user.
3. Click **Licenses and apps**.
4. Enable **Microsoft 365 Business Premium**.
5. Click **Save changes**.

### Verification

- User status displays **Licensed**.
- Assigned license count increases.

![Assign Licenses](screenshots/02-assign-license.png)

---

## Lab 3 - View Included Apps

### Steps

1. Select the licensed user.
2. Open **Licenses and apps**.
3. Review the available Microsoft 365 services.

Example services include:

- Exchange Online
- Microsoft Teams
- OneDrive
- SharePoint
- Microsoft Defender
- Microsoft Intune

### Verification

- All licensed services are displayed.

![License Apps](screenshots/03-license-apps.png)

---

## Lab 4 - Disable a Service

### Steps

1. Open **Licenses and apps**.
2. Expand the Microsoft 365 Business Premium license.
3. Disable **Microsoft Teams**.
4. Click **Save changes**.

### Verification

- Teams is disabled.
- Other Microsoft 365 services remain enabled.

![Disable Teams](screenshots/04-disable-teams.png)

---

## Lab 5 - Remove a License

### Steps

1. Navigate to **Users** → **Active users**.
2. Select the licensed user.
3. Open **Licenses and apps**.
4. Remove the Microsoft 365 Business Premium license.
5. Save the changes.

### Verification

- User displays **Unlicensed**.
- Available license count increases.

![Remove License](screenshots/05-remove-license.png)

---

## Lab 6 - Bulk License Assignment

### Steps

1. Go to Billing → Licenses.
2. Select Microsoft 365 Business Standard.
3. Look for Assign licenses.
4. Select Microsoft 365 Business Premium.
5. Add users from there.

### Verification

- All selected users receive a license.

![Remove License](screenshots/05-remove-license.png)





