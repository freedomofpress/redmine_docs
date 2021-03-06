Using Redmine
=============

.. _Logging In:

Logging In
----------

Once your account has been activated, go to the `Support Page`_ and log
in with your new account.

.. _Support Page: https://support.freedom.press

|Login|

After logging in, you will be be taken to the Home page. In the top
menu bar, you will see helpful links to a variety of resources. The most
important links are:

* **Projects**: The list of projects you have access to.
* **My Page**: An overview of the open issues that were either created
  by you or are assigned to you.

|Home|

Click on **Projects** in the top menu bar. You'll see a project for your
SecureDrop instance listed underneath the parent SecureDrop project.
Only Freedom of the Press Foundation staff and people within your
organization have access to your instance's project.

|Projects|

Click on the project link. You'll be shown an **Overview** of the project and
all of its issues.

|Overview|

To view the list of open issues, click the **Issues** button to open the issues
pane.

|Issues|

.. |Login| image:: images/login.png
.. |Home| image:: images/home.png
.. |Projects| image:: images/projects.png
.. |Overview| image:: images/overview.png
.. |Issues| image:: images/issues.png


Onboarding Issue
----------------

By the time you log in, we'll have created an initial issue for
onboarding, called "Onboarding Verification". Please write a reply on
this issue, which will let us know that you succeeded in logging in and
finding your project page.

|OnboardingIssue|

To write a reply, click **Edit** button at the top of the issue.
Write your reply in the Notes text box, then click **Submit**.

|EditIssue1|

We'll reply to the issue and start a little exchange to explain some
features of the platform and answer any questions you might have. The
goal here is to make sure you're comfortable and confident using the new
Support site.

|EditIssue2|

Once we're satisfied you're ready to use the new site, we'll close the
issue.

Once we're finished with the onboarding issue, you're ready to use the Support
site. If you want to additionally set up encrypted email notifications, head
over to the :doc:`Encrypted Email Overview <encrypted_email_overview>`.

The rest of this documentation is for your reference.

.. |OnboardingIssue| image:: images/onboarding_issue.png
.. |EditIssue1| image:: images/edit_issue_1.png
.. |EditIssue2| image:: images/edit_issue_2.png

Key Features
------------

Creating a new issue
^^^^^^^^^^^^^^^^^^^^

To create a new issue, click **New issue** and fill out the Subject and
Description fields. All other fields can be left blank, although you can
assign a priority if you want. When we see the issue, we will respond
and assign it to the appropriate person. If we're waiting for a reply
from someone in your organization, we may assign it back to you.

|NewIssue|

.. |NewIssue| image:: images/new_issue.png

Creating a new issue via email
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Sending an email to support@freedom.press will automatically create a
new issue in your project, using the subject line of the email for the
Subject and the body of the email for the Description.

Enabling two-factor authentication
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Two-factor authentication (2FA) protects your account in the event that your
passphrase is compromised. Once enabled, you will be prompted to provide a
one-time six digit code every time you log into the support portal, in addition
to your passphrase.

To enable 2FA:

1. Choose an application to generate two-factor codes. We recommend the
   `FreeOTP app <https://freeotp.github.io/>`__ for Android or iOS, but any
   app that implements the Time-based One Time Password (TOTP) algorithm
   should work.
2. If you are not already logged in, log into the support portal.
3. Click **My account** in the top right corner to navigate to your
   account settings. On the settings page, click **Enable authenticator app**.

   |2FA setting|

4. You will see a page that shows a QR code, similar to the one below.
   Use your 2FA app's QR code scanning function to scan the code on the page,
   or manually enter the 2FA secret (called a "plain text key" here) in the app.

   |2FA example|

5. Select the account you have just added to your 2FA app, and generate a new
   one-time token using the app. Enter it on the webpage and click **Activate**.
6. You should see a success message like the one below. Follow the recommendation
   and click **generate backup codes**.

   |2FA success|

7. You will see a list of codes like the one below. Each code (e.g., ``ec96 a5d7 c678``)
   can be used once *instead of* a 2FA code during the login sequence. Store
   these codes securely and separately from your passphrase. The recommended
   method is to keep a printout of the recovery codes in a secure location.

   |2FA backup codes|

8. Log out of your account and attempt to log in again. After entering your
   passphrase, you will additionally be prompted for a two-factor code, which
   you can generate using your 2FA app.

If you have to reset your 2FA settings at any time, you can use a recovery code.
Once you are logged in, disable and then re-enable 2FA from your account settings.

Please do not hesitate to open a ticket or email us at
securedrop@freedom.press (`GPG-encrypted <https://securedrop.org/sites/default/files/fpf-email.asc>`__)
if you encounter difficulties using 2FA on the support portal.

.. |2FA setting| image:: images/account_settings_with_2fa_highlighted.png
.. |2FA example| image:: images/qr_code_example.png
.. |2FA success| image:: images/2fa_success.png
.. |2FA backup codes| image:: images/2fa_backup_codes.png

Other account settings
^^^^^^^^^^^^^^^^^^^^^^
In addition to two-factor authentication, you can also configure your local
time zone in the account settings.

We encourage you to leave the notification setting as the default:
"For any event on all my projects".

|Account settings|

.. |Account settings| image:: images/account_settings.png

Additional Documentation
^^^^^^^^^^^^^^^^^^^^^^^^

For more information on using Redmine, consult their `User Guide
<https://www.redmine.org/projects/redmine/wiki/User_Guide>`_.
