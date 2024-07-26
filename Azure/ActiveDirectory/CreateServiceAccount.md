# Service Account Creation
To create a service account in Azure Active Directory (Azure AD) with Multi-Factor Authentication (MFA) disabled, you'll need to create a regular user account and ensure that the account is excluded from any Conditional Access policies enforcing MFA. Here's a step-by-step guide to achieve this:

---
## Step 1: Create a New User Account

Navigate to Azure Portal &#8594; Open Azure Active Directory &#8594; In the left-hand navigation pane, select "Users" &#8594; Click "New user". &#8594; Choose "Create user" and fill in the required fields:

|Field|Description|
|-|-|
|User name|Ex:serviceaccount@yourdomain.onmicrosoft.com|
|Name| Give a descriptive name for the service account|
|Password| Set an initial password (you may want to choose "Let me create the password")|

Click "Create" to create the new user account.

## Step 2: Assign License