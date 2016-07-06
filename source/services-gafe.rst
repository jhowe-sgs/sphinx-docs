Services:: GAFE
===============

Google Apps for Education ( GAFE ) has been used by SGS for several years now.

Originally initiated by Bert Hopkins for 8th grade usage, we had a few initial painful years as the service didn't scale well on site. Issues included:

- Students unable to log in
- Poor performance
- Only a limited number of students could log in at a time.

As we increased the campuses Internet bandwidth and wireless infrastructure, performance issues were alleviated.

We did a phased deployment of GAFE with the following:

- All 8th Grade students on GAFE
- All students on GAFE
- All users on GAFE

Fast forward to today, and all user accounts are hosted on GAFE services. Locally, accounts are provisioned via OU membership in the AD and synced back to GAFE.

Single Sign On services is provide by simpleSAML on the DMZ gateway. A future migration could replace this SSO solution by switching to Azure AD mirroring.