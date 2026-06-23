# 4. Working in the ADRF

This section provides an overview of how to work within the ADRF.

> 💡 You can find detailed information as well as video tutorials on how to work in the ADRF in the  **ADRF User Guide**, which is available to ADRF users in Secure PASS in their project workspaces.

## Project Workspace
A **project workspace** is a secure, isolated virtual environment in the ADRF within which an approved set of users can access a defined number of agency datasets. The project workspace is designed to allow approved researchers to access, analyze, and manipulate specific datasets relevant to their approved projects while maintaining strict data confidentiality and integrity.

Project workspaces in the ADRF are isolated from each other. Even if a person is granted access to two project workspaces, the user can not access or copy files from one into the other. This is important because the two project workspaces might have access to different datasets.

## Virtual Desktop
The **Virtual Desktop Environment** (VDE) is a secure, remote Windows system that allows you to work as if it were your own desktop. This environment is temporary: running programs will stop and unsaved data will be deleted after four hours of inactivity. Always save your files to the appropriate drives and log out by selecting End Session from the top taskbar to preserve your work. The interface is a familiar Windows desktop, with icons and a start menu for accessing programs and tools like PowerShell.

## Establishing a secondary password for your project workspace

As an added security measure, the ADRF uses a secondary password in addition to your primary login credentials. This password provides an extra layer of protection for sensitive data by ensuring that access to the secure research environment remains protected even if another account credential is compromised. The secondary password is managed separately from your primary account and may be required when accessing or reconnecting to the ADRF environment. The secondary password is also required for users accessing data stored in Redshift.

Example: If you see the following screen when logging into your ADRF workspace, it means you will need to enter your secondary password to enter the workspace. 
![Secondary Password Required](/images/secondary-password-required.png)

### How to set you secondary password

1. Log into the ADRF by clicking on “ADRF Sign In” in the upper right hand corner of Colerdige’s website ([https://coleridge.us/](https://coleridge.us/)).
2. Click on your profile icon in the bottom left-hand corner and select “Profile.”
3. Click on the tile for the specific project workspace you would like to update.
4. Click on “Change Password” and follow the instructions to save your new password.

If you encounter issues or are locked out, please contact the support team via 'Support Tickets' in the PASS sidebar or email support@coleridge.us.

## ADRF Session Security & Log Out Guidelines
To maintain compliance and protect research data, the ADRF enforces specific session inactivity and lock-out policies. Please be aware of the following requirements:
- **Session Lock (Auto-Lock)**: To protect your workstation, your session will automatically lock after 15 minutes of inactivity.
- **Session Termination**: Your active session will be terminated after 60 minutes of inactivity.
- **Account Deactivation**: Accounts are subject to deactivation after 90 days of inactivity.

### Account Reactivation
If you have a valid ADRF account; but the account has been deactivated due to inactivity, please reach out to support@coleridge.us to reactivate your account.

> **Post-Reactivation Requirement**: If your account is reactivated after a period of inactivity, you are required to log in within **1 hour** to complete the process and avoid triggering a secondary reactivation request.


**Best Practice**: Always manually lock your screen or log out of your session when stepping away from your workspace to ensure these automated controls do not interrupt your work unexpectedly.


## Modifying the Environment
### Establishing Personal Folders
Establishing your own personal folders is one of the simplest, yet most important, steps to take when setting up your environment. As we note in the section on Storing Analytic Results, the two possible places to store your analytic results or files are in either the U: drive or the P: drive.

You will find your personal folder in the U: drive. The folder name will include your Firstname and Lastname, and may additionally include your project workspace number. This is a personal workspace that only you can access in the ADRF.

### The U: Drive and the P: Drive
- The **U: drive** is your user drive; it’s where you will store any files you are working on. Only the user will have access to the U: drive. For example, if user A wants to share information with user B who is on the same project, user A will need to save files to a P: drive folder and not folders in their U: drive since user B will not be able to access user A’s U: drive.

- The **P: drive** is the project drive, which will be used to house project-specific folders. Thus, you and other collaborators on the same project will be able to save files to project drive folders.

### Other Modifications
The top taskbar contains shortcuts to the command prompt, multiple desktop windows, a temporary folder, settings, full-screen view, and toggling multiple monitors.

## Software in the ADRF

The ADRF project workspace provides a range of pre-installed, open-source, and commercial analytical software for data analysis. For detailed instructions on how to use each tool, refer to the full ADRF User Guide located in the secure data enclave.

Key analytical software includes:
- **JupyterLab**: An interactive environment for running Notebooks with R, Python, and Stata kernels, and the recommended way to conduct exploratory computing.
- **Statistical Software**: Dedicated environments are available for Python, R (via RStudio), and Stata.
- **DBeaver**: A universal database tool for querying and managing data stored in the Redshift database.

<br>

---
# Support

**Need help?**

- Email: support@coleridge.us

- Hours: Monday-Friday, 9 AM - 5 PM ET
