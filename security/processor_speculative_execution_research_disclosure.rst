.. _response_meltdown_spectre:

==========================================
Rackspace Response to Meltdown and Spectre
==========================================

On January 3, 2018, Rackspace was made aware of CPU architecture
vulnerabilities associated with Intel, AMD, ARM and other providers.
Information about this vulnerability has been provided by Google and is
available within the following Google posts:

* https://security.googleblog.com/2018/01/todays-cpu-vulnerability-what-you-need.html
* https://blog.google/topics/google-cloud/what-google-cloud-g-suite-and-chrome-customers-need-know-about-industry-wide-cpu-vulnerability/

These issues were originally uncovered by
`Google’s Project Zero <https://googleprojectzero.blogspot.com/2018/01/reading-privileged-memory-with-side.html>`_.
Their research findings show that an unauthorized party may read sensitive
information in the system’s memory such as passwords, encryption keys, or
sensitive information open in applications.

The remainder of this update is addressed to our Fanatical Support for GCP
customers specifically. For updates about our other Rackspace supported
hosting environments, please refer to the
`Rackspace blog <https://blog.rackspace.com/>`_.

Overview
--------

Details about the security vulnerabilities can be found in `CVE-2017-5753 <http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5753>`_, `CVE-2017-5715 <http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5715>`_, and `CVE-2017-5754 <http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-5754>`_. Google's security bulletin regarding these vulnerabilities can be found `here <https://security.googleblog.com/2018/01/todays-cpu-vulnerability-what-you-need.html>`_.

There is not a single fix
^^^^^^^^^^^^^^^^^^^^^^^^^

There is no single fix for all three security vulnerabilities. Many vendors
have patches available for one or more of these attacks.

Google Cloud Platform (GCP) Response
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Within Google Cloud Platform, the vulnerability affects two components: the
underlying GCP resources and the Google Cloud Services (GCE, GKE, Dataproc,
etc.) that run on those resources. Google has confirmed that they have
mitigated underlying GCP resources impacted by the vulnerability. For the
remaining Google Cloud Services impacted by this vulnerability, Google has
recommended that customers take further action.

Next Steps
^^^^^^^^^^

For Aviator supported projects, your Rackspace Cloud Engineering team will
coordinate with you to define the next steps needed to mitigate this
vulnerability. We are analyzing your current project(s) to understand the
scope of work required and will contact you within the next 24 hours.

For projects that are not supported by Rackspace Managed Services (i.e.,
Runway projects), we recommend that customers undertake mitigation steps per
the documentation provided by Google in the security links provided above. We
also recommend that you regularly review the
`Google Cloud security website <https://cloud.google.com/compute/docs/security-bulletins>`_.

For any further information, please contact your Rackspace team.


Change Log
----------

.. list-table::
   :widths: 10 30
   :header-rows: 1

   * - Date
     - Description
   * - 2018/01/05 14:03 CST
     - Initial revision of this security update
