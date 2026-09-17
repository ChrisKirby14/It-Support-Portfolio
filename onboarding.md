# Exercise: Add a new user to the company

**Situation:** A new employee requires a managed identity in Microsoft Entra ID, including appropriate M365 licensing, group-based access, and enforced Multi-Factor Authentication (MFA) to meet corporate security baselines.

**Objective:** Provision a new user account from scratch, configure identity attributes, and simulate the end-user first-run experience to verify security policies are functioning correctly.

### 1. Initialise User Profile & Temporary Credentials
*Generated a new cloud-only identity and captured the temporary password to transmit securely to the user's manager.*

<img width="583" height="190" alt="01-Create-New-User" src="https://github.com/user-attachments/assets/85ece379-786d-4050-8c01-4b9331924332" />

<img width="687" height="549" alt="02-New-User" src="https://github.com/user-attachments/assets/29d9e7aa-dcf0-404f-a589-d4bb441103c8" />

### 2. Configure Identity Attributes & Licensing
*Populated standard directory attributes (Job Title, Department)*

<img width="927" height="626" alt="03-Account-Details" src="https://github.com/user-attachments/assets/7408b549-e459-4b0e-9893-4f55a4e7fdcd" />

### 3. Apply Group-Based Access Controls
*Assigned the user to relevant security and Microsoft 365 groups to ensure they inherit the correct SharePoint, Teams, and shared mailbox permissions upon login.*

<img width="723" height="288" alt="04-Assign-Group" src="https://github.com/user-attachments/assets/0989943e-9f26-4599-9e4f-035715b49f72" />

### 4. Final Review & Provisioning Execution
*Audited the configured details before committing the object creation to the Entra ID tenant.*

<img width="562" height="729" alt="05-Account-Completion" src="https://github.com/user-attachments/assets/04628661-bb96-460c-96ac-a4c2c686ab82" />

### 5. Verify First Sign-In & Forced Password Reset
*Simulated the end-user login in a private session to confirm that the "Require this user to change their password" security flag successfully triggered.*

<img width="493" height="530" alt="06-Account-Sign-in" src="https://github.com/user-attachments/assets/2dffe8c6-ee2f-4792-b39f-00eb87a06a5e" />

### 6. Enforce MFA Registration (End-User Experience)
*Verified that tenant-level Conditional Access / Security Defaults correctly intercepted the login to force Microsoft Authenticator app registration.*

<img width="523" height="508" alt="07-Authenticator-Prompt" src="https://github.com/user-attachments/assets/16c49e37-f22f-4c95-a86f-9ec05a85dcdf" />

<img width="552" height="587" alt="08-Authentication-QR" src="https://github.com/user-attachments/assets/304fd2b4-bd9f-4bf7-bce2-5dbe4aca3b8e" />

### 7. Validate Successful Authentication
*Confirmed the MFA challenge succeeded and the user was granted access to the Microsoft 365 portal.*

<img width="523" height="604" alt="09-Confirm-Auth" src="https://github.com/user-attachments/assets/28fe2e11-48e9-4b19-878d-98332d6cc1ca" />

<img width="442" height="568" alt="10-Auth-Approved" src="https://github.com/user-attachments/assets/159e1f68-b4c0-47a3-9844-b021f99e4efe" />
