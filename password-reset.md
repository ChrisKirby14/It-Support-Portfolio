# Exercise: User Account Lockout & Password Reset

**Situation:** User has entered the wrong password more than 3 times in a row, and the account is now locked out.
**Objective:** Securely reset a user's password in Microsoft Entra ID and assist with Multi-Factor Authentication (MFA) registration.

### 1. Locate the User Account
I located the user's account by navigating to **Entra ID > Users > All users**
<img width="2263" height="1040" alt="All-Users" src="https://github.com/user-attachments/assets/ec49d82a-d153-4f6c-9c5b-f16bdaaf955a" />

### 2. Initiate Password Reset
Opened the user's profile and selected **Reset Password**. Before proceeding, verified the user's identity.
<img width="310" height="224" alt="Reset-Password" src="https://github.com/user-attachments/assets/9662f0da-9c94-4e08-940f-1dcf4630d566" />

### 3. Generate Temporary Credential
Generated a temporary password to provide to the user securely.
<img width="313" height="344" alt="Temp-Password" src="https://github.com/user-attachments/assets/ea43875a-6778-4a49-96f5-c82aa13386ae" />

### 4. Verify Authentication Methods
Made sure the **Security defaults** are enabled and checked Temporary Access Pass and Microsoft Authenticator are enabled within the Authentication methods | Policies
<img width="1744" height="730" alt="Auth-Methods" src="https://github.com/user-attachments/assets/ae93dd08-7787-485d-8f0c-5520c6dcaaa6" />
<img width="418" height="345" alt="Security-defaults" src="https://github.com/user-attachments/assets/79ff7e9b-6b40-4b29-a697-e6773056b794" />

### 5. End-User First Sign-In
The user is prompted to change their temporary password on first login.
<img width="970" height="718" alt="New-Password" src="https://github.com/user-attachments/assets/959ce0c0-ff54-45ea-8990-d42b73139111" />

The user is then prompted to register for MFA via the Microsoft Authenticator app by scanning a QR code.
<img width="707" height="721" alt="QR-Auth" src="https://github.com/user-attachments/assets/a1b09005-eb42-4fd0-9fa7-b1bde647d791" />
<img width="579" height="601" alt="Auth-Added" src="https://github.com/user-attachments/assets/3fb38618-bc36-456d-a18d-fad49219fa55" />

**Result:** Issue resolved. User has successfully regained access.
