.. _gcp_projects:

============
GCP Projects
============

Each Rackspace account can house one or more GCP projects from the same
Google organization. We generally recommend provisioning a GCP project per
application deployment phase (e.g. development, staging, and production),
thereby allowing you to assign different users in your company access to
the appropriate GCP projects without complex IAM policies. In this
example, developers could be granted access to provision Compute Engine
instances, Cloud SQL databases, etc. in your development and staging
projects, but be restricted to read access of the resources in your
production project.

In addition to being a strong permission boundary, GCP projects also
provide a convenient construct for tracking expenses, since by default, both
GCP and Rackspace charges are grouped by GCP project. For example, if four
separate GCP projects are used called app1-dev, app1-prod, app2-dev,
app2-prod, it is very easy to see how much is being spent on each application
environment.

Lastly, using separate GCP projects per environment gives you the flexibility
to select different Rackspace service levels for each environment, since
Rackspace service levels are applied at the GCP project level. For example,
you may opt for the Runway service level on your development project
while using the Aviator service level for your production project.

.. toctree::
   :maxdepth: 2

   offboarding.rst
