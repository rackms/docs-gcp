.. _support:

Support
=======

There are multiple ways to receive Fanatical support for your GCP
projects. A helpful Racker is always just a phone call or ticket away. We
are available live 24x7x365.

Tickets
-------

The primary way you interact with a Racker is by creating a ticket in the
`Managed Services for Google Cloud Platform Control Panel <https://manage.rackspace.com/gcp>`_.
Once logged in, click the Support button in the black bar at the top of the
screen and follow the links to create a new ticket or view an existing ticket.

Our automated systems will also create tickets for events on your GCP
project(s) that require either your attention or the attention of a Racker.

Any time a ticket is updated, you will receive an email directing you back
to the Control Panel to view the latest comments.

Runway Service Level
--------------------

Runway projects offer 24x7x365 support.

Billing and account management issues are included in the Runway service
offering.  All other issues are treated as on-demand support and are charged
a fee per ticket to address.

If you need 24x7x365 support for the Google services running in your project
and have frequent support needs you should upgrade to the Aviator service
level. Contact your Technical Account Manager for additional details.


Phone
-----

Would you prefer to speak to a live Racker? Give our team a call at
800-961-4454 (US) or 0800-988-0300 (UK) and we'll be happy to assist
you. Additional international contact numbers are available on our
`Contact Us <https://www.rackspace.com/information/contactus>`_ page.

Monitoring
----------
Rackspace uses Stackdriver Metrics to capture performance metric data for
GCP infrastructure components. Stackdriver includes a large number of
standard metrics via the default agent, and can also  be used to monitor
third party applications and services via a variety of additional agents.

Stackdriver metrics for installed agents are always captured, and are
subject to retention periods based on the Stackdriver tier purchased by the
user (currently this is the same for all tiers). Customers who desire
longer metric retention can opt for data to be copied to an external
location, e.g. Google Cloud Storage or BigQuery. Dashboards can be generated
in the Stackdriver web interface to explore stored metric data, and Alert
and Notification Policies can be created to inform users via a variety of
means as to emergent conditions.

Rackspace deploys standard alerts for Aviator customers using common GCP
components like Compute Engine and Cloud SQL. These may be customized with
the cooperation of the MGCP operations team.

Rackspace configures a set of webhook notification targets in
Stackdriver, one for each Rackspace ticket severity level. When an alert is
posted to one of these webhooks, the data is received by a Rackspace system
called Watchman.  Watchman groups alerts into appropriate tickets according
to the infrastructure involved and the corresponding alert policies.
Rackspace operations personnel then respond to these alerts based on
customer runbooks.

Logging
-------
Stackdriver Logging can be used to capture system and application logs in
GCP. Log capture is not currently configured by default for Aviator
customers, but can be activated with the cooperation of the MGCP operations
team.

Logs are retained for 30 days by default, and may be archived to Google
Cloud Storage and/or analyzed with BigQuery. Log-based metrics can also be
used to trigger alerts via Stackdriver Monitoring.
