# 10. Frequently Asked Questions (FAQ)

## How do I set up my Multifactor Authentication
You should be prompted to set up multifactor authentication when you create your account, the options are SMS, voice call, email and the Okta verify application.

## Can I set up more than one form of Multifactor Authentication?
This is recommended. If you lose access to one form of MFA, you would still be able to gain access to your account using an alternative. To do so, please log on to https://adrf.okta.com and select your name on the top right and click settings. Here you can modify or set up your SMS, voice call, email or Okta multifactor authentication.

## How can I reset my Okta password?
You can use the “Need help signing in?” option on the sign on page (https://adrf.okta.com) which will send a link to your email to reset your password. You may have to verify your identify by answering security questions which you set up when creating your account.

## How can I reset my ADRF password?

You can reset your ADRF password (the one used for the project workspace) via the Workspace Password Reset tile located within the Coleridge PASS Portal.

### Purpose of the secondary password
As an added security measure, the ADRF uses a secondary password in addition to your primary login credentials. This password provides an extra layer of protection for sensitive data by ensuring that access to the secure research environment remains protected even if another account credential is compromised. It is managed separately from your Okta (primary) account and is required when accessing or reconnecting to your ADRF workspace and Redshift data.

### How to reset your secondary password:
1. Log into the ADRF by clicking on “ADRF Sign In” in the upper right hand corner of Colerdige’s website ([https://coleridge.us/](https://coleridge.us/)).
2. Click on your profile icon in the bottom left-hand corner and select “Profile.”
3. Click on the tile for the specific project workspace you would like to update.
4. Click on “Change Password” and follow the instructions to save your new password.

If you encounter issues or are locked out, please contact the support team via 'Support Tickets' in the PASS sidebar or email support@coleridge.us.


## What if I do not remember my security questions or if I get locked out?
You would have to reach out to support at support@coleridge.us to have your account unlocked and you would have to reset your security questions so that you can recover your account in the future.

## Why did my session close, and can I recover unsaved work?
The VDE automatically ends any session after eight hours of inactivity. Running programs will stop and unsaved data will be deleted, and it cannot be recovered. To preserve your work, always save your files to the P: or U: drives and select End Session from the top taskbar to formally log out.

## I can log into the ADRF but my desktop and DS application just show blank pages.
Please ensure the connection to ADRF is not being blocked by your organizations VPN and/or firewall (try using a device not connected to your organization’s network) and reach out to support@coleridge.us.

## I saved a file in the C: drive or in the Desktop. When I logged back in, the file is no longer there. Can you restore it?
The ADRF is a temporary workspace environment. Files left on the C: drive or Desktop will be removed when you log out of your session and cannot be restored. Best practice is to store all files in your user folder on the U: drive or the shared P: drive.

## How do I open an ipynb notebook?
On the desktop you should find an icon for JupyterLab, when you click that, a command prompt and a browser window are opened up, leave the command prompt running. You should be able to open the file by selecting File -> Open From Path and providing the path to the folder containing the ipynb notebook.

## How can I ingest publicly available data into the ADRF?
Please open a support request by sending an email to support@coleridge.us. Include the dataset you wish to have available inside the ADRF and documentation that confirms that the dataset is public.

## Where can I access publicly available data from within the ADRF?
Publicly available data is stored in the schema ds_public_1.

## Where is my project or training related data stored?
All project and training related databases are prefixed with ‘pr’ (for project) or ’tr’ (for training). You may use this space when creating intermediate datasets or as a “working space”. All project members have read and write access to this area (specific to your project).

## My data is not in a relational format. Where can I find these files?
Read-only non-relational data are stored in the G: drive on Windows Explorer. Project specific non-relational data and files are stored in project specific folders that are prefixed with ‘pr’ or ‘tr’. The location of these folders are in the P: drive on Windows Explorer.

## What is the difference between the P:, U: and G: drives?
Each drive location has a different purpose and access rule:
- **P drive**: Project specific files shared by ALL project members
- **U drive**: User personal space. Only the user has read/write access to this area.
- **G drive**: Non-relational datasets. Read-only access to authorized users only.

## I need to process a large amount of relational data. What is the destination location?
The best practice is to process the data where it is currently located. If the data is in a relational database, perform as much of your processing using Redshift to make the most efficient use of resources (i.e. filtering, sorting, etc).

## Why did I receive a SAML error when logging into Dbeaver?
There are several potential reasons this message may appear, and most of them have to do with credentials being entered incorrectly. Below are some scenarios when you may run into this error message.
- You forgot to enter “adrf\” at the beginning of your username.
- Your username was correct but your password was not.
- The username you entered is invalid.

**Solution:**
- Ensure both your username and password are entered correctly and that your username is preceded by “adrf\”.
- If the problem persists, try resetting your workspace password and making one more attempt to connect.
- If you are still running into problems, contact our support team at support@coleridge.us.

<br>

---
# Support

**Need help?**
- Email: support@coleridge.us
- Hours: Monday-Friday, 9 AM - 5 PM ET
