
=====================
Getting Started
=====================

If you need assistance with this process, please contact your support team.

.. create_your_rackspace_account:

Create your Rackspace account
-----------------------------

The first step is to create your Rackspace account. Visit https://www.rackspace.com/contact reach out to sales person who can guide you through the process. 

.. login_with_google:

Log in with Google
------------------

 * After you have created your Rackspace account and the account checks have been completed , navigate to  `Google Cloud Platform Control Panel <https://manage.rackspace.com/gcp/welcome>`_.

 * Select Login with Google to open the Google Sign in prompt. Google allows multiple active login browser sessions. Choose the correct account, or login to a new one if not already authenticated. TIP: If you run into trouble with Google login, it is always recommended to try this in fresh browser session with no prior logins (Incognito in Chrome, Private browsing in Firefox, Browse InPrivate on MS Edge)

    * WARNING: The Google Login prompt is a popup - An error may appear if the user closes the popup before making a selection or if a popup blocker is enabled.

 * After authenticating with Google, you should receive an access request stating Managed Google Cloud Platform by Rackspace wants to access your Google Account to manage your data across Google Cloud Platform services. Please select ALLOW. You should return to the Rackspace Customer Portal.

.. link_a_google_org:

Link a Google Organization
---------------------------

 * You must have at least the Organization Viewer role on the Google Cloud Platform side for a successful link to Rackspace. Rackspace recommends that the Organization Administrator performs the initial onboarding of the organization. This will allow the customer to grant Rackspace access to the Organization during onboarding to create projects on-demand and view project details.

    * In the IAM section of the GCP console, the role required is ‘Resource Manager’ > ‘Organization Administrator’

 * Next, you'll be prompted to select the Google organization that you want Rackspace to manage. If you have not created an GCP organization, please visit `Creating and Managing Orgnization <https://cloud.google.com/resource-manager/docs/creating-managing-organization`

 * Depending on your setup, you may see a single Google Organization, or multiple. We currently only support linking to one Google organization. It is important that you choose the correct Google Organization before proceeding. This organization must have all GCP projects you wish for us to manage must belong to that organization. 

.. granting_rackspace_permissions:

Granting Rackspace Permissions
------------------------------

* This step requests permission to grant the Rackspace automation service account limited access to the Organization. Here's additional information on each permission. 

    * Organization Viewer: (Required) Allows Rackspace to view basic organization details like name, domain, and id. All customers must grant Rackspace this permission.

    * Project Browser: Allows Rackspace to browse project information in the organization. This role does not include permission to view resources or list the contents of storage buckets. It is primarily used to gather an inventory of available projects to present to the customer.  All customers must grant Rackspace this permission.

    * Project Creator: Allows Rackspace and the customer to create additional projects in the Google organization through Rackspace tooling. Customers who are consuming the following service levels must grant this role

        - Aviator

        - Manage and Operate

        - Architect and Deploy

        - Elastic Engineering

        - Optimizer 

        - Advanced monitoring and resolution
    
* If your account does not have sufficient permissions to grant Rackspace any of these roles, you may see a warning. This is not critical enough to stop the linking process, but will impact our ability to provide services on the account. At the time of the service onboarding, we will (re)request these permissions. Alternatively, you will need to work with their Organization Administrator to grant yourself the Organization IAM Admin role.

.. finish_setup:

Finish Setup
------------------

 * Make sure the folowing are correct

    * Desired Rackspace account

    * Desired Google organization

    * Granted the desired roles to Rackspace

 * Acknowledge the Global Service Agreement, Terms and Conditions and select FINISH.

 * This should complete the linking process of the customer's Google Cloud Platform account to Rackspace.