.. _security:

========
Security
========

Rackspace Shared Management Services
------------------------------------

Rackspace takes the security of our shared management services and the
`Managed Services for Google Cloud Platform Control Panel <https://manage.rackspace.com/gcp>`_
extremely seriously. All infrastructure is deployed leveraging the same set
of best practices that we apply to customer projects. The following sections
provide a sample of some of the key security focus areas.

Racker Authentication
^^^^^^^^^^^^^^^^^^^^^

All Rackspace employees must leverage two-factor authentication for all access
to customer account data and customer environments.

Racker Privileges
^^^^^^^^^^^^^^^^^

The level of privileges each Racker has to our Managed Services for Google
Cloud Platform management systems is tightly controlled based on job role
and is periodically reviewed to ensure that each Racker has the minimum
level of permissions required to adequately perform their job duties. All
privilege changes require management approval and are also logged for later
review.

Encryption at Rest
^^^^^^^^^^^^^^^^^^

All sensitive data is encrypted at rest.

Encryption in Transit
^^^^^^^^^^^^^^^^^^^^^

All communication between services that make up our shared management
system are encrypted during transit using SSL. Our customer and Racker
UIs and APIs are only accessible via HTTPS.

Activity Logging
^^^^^^^^^^^^^^^^

`Stackdriver Logging <https://cloud.google.com/logging/>`_ allows you to
view audit logs associated with admin and data access events on Google Cloud
Platform.

Permissions
-----------

We use a service account with the following permissions to deliver our
services to you:

* Organization: ``Project Creator``, which allows us to create additional
  projects in your Organization upon your request
* Runway Projects: ``browser``, ``billing.projectManager``,
  ``serviceusage.serviceUsageAdmin``, and ``servicemanagement.admin`` roles.
  (Note that this does not give us the ability to provision or deprovision
  resources on your projects)
* Aviator Projects: ``Owner`` permissions, which allow us to share full
  administrative control with you

GCP Security
------------

Review `Google Cloud Platform Security <https://cloud.google.com/security/>`_
for more information regarding Google's security practices.

If you have questions regarding any aspect of the security of your
environment, please :ref:`contact a member of your Support team <support>`.

Security Updates
^^^^^^^^^^^^^^^^

Google Cloud Platform
`Security Bulletins <https://cloud.google.com/compute/docs/security-bulletins>`_
are available from Google.

From time to time, Rackspace will provide additional detail or guidance to
our customers for specific security incidents.  We will publish such
value-add security updates below.

.. toctree::
   :maxdepth: 1

   processor_speculative_execution_research_disclosure.rst
