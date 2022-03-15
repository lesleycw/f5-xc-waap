
Requesting Access to a Distributed Cloud Sales tenant
=====================================================
Access to the sales Volterra tenants is based upon AD group membership.  To gain access to a tenant please 
open a ServiceNow Access to a cloud account ticket requesting access to the corresponding Tenant name:

ServiceNow link: https://f5.service-now.com.mcas.ms/sp?id=sc_cat_item&sys_id=aa2d8279dbbd6300b2c774dfaa96198e

.. list-table:: Distributed Cloud Sales Tenants
   :widths: 45 45
   :header-rows: 1

   * - Description
     - Tenant Name
   * - America Enterprise
     - f5-amer-ent
   * - America Service Provider
     - f5-amer-sp
   * - EMEA Enterprise
     - f5-emea-ent
   * - EMEA Service Provider
     - f5-emea-sp
   * - APAC Enterprise
     - f5-apac-ent
   * - APAC Service Provider
     - f5-apac-sp
   * - Solution Architect
     - f5-sa

Other tenants exist with Product Teams and Channel Teams.  Please coordinate with your respective business unit for access.

Logging into VoltConsole
========================

You should have received an email with an invitation to access VoltConsole.

The name of the tenant that will be used is dependent on your theatre and business unit tenant.

Your directa access link will be formatted as https://<tenant name>.console.ves.volterra.io

Exercise #1: Login to VoltConsole
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You will need to create a password that will be associated with your email address.

If you have NOT received an email from our system you may need to provide an alternate
email address that we can use for the purposes of this lab.

The following is a video that covers the steps involved.

.. raw:: html
  
  <iframe width="560" height="315" src="https://www.youtube.com/embed/AGV6z1-7NdU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**VoltConsole**

VoltConsole is a SaaS control-plane for Volterra services that provides a UI and API for managing network, security, and compute services.

VoltConsole can manage "sites" in existing on-prem data centers and sites in AWS, Azure, and GCP cloud environments.

Using VoltConsole, an end-user can centrally manage a distributed application environment.

Terminology
~~~~~~~~~~~~~

Namespace
    Namespace is a term that is commonly used in Kubernetes.  It can be thought of as a grouping of resources.

Exercise 2: Select your Persona
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Please log into your assigned Volterra tenant. https://f5-sales-public.console.ves.volterra.io/

    .. note:: The VoltConsole GUI has a relatively short timeout. This is not configurable. We have an enhancement request to allow this to be configured.

#. When you first login you will need to select your "persona"

   Enter your persona as "SecOps" and level as "Intermediate".  You can change these settings after logging in as well.

   Your persona will highlight workflows within Volterra.  You will be able to access all services, but making use of
   personas can focus your view on particular tasks that are relevant to your role.

#. Several tooltips will appear.  You can close these out.

Exercise 3: Identity your Namespace
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

#. Click on "Account Settings" by expanding the "Account" icon in the top right of the screen and 
   clicking on "Account Settings"

   .. image:: ../_static/screenshot-account-settings.png
#. Next click on "My Namespaces" and take note of the `studentxxx` namespace that you have been assigned.  Each student will have a unique number.

   .. image:: ../_static/screenshot-mynamespaces.png 