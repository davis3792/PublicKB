{{{
  "title": "Getting Started with X2Engine Sales CRM - Blueprint",
  "date": "05-14-2015",
  "author": "<a href='https://twitter.com/KeithResar'>@KeithResar</a>",
  "attachments": [],
  "contentIsHTML": false
}}}



### Description

<img alt="X2Engine Sales CRM Logo" src="../images/bitnami_logos/x2engine-stack-110x117-f2439ac26534398a07f9a32bcecd8cd8.png" style="border:0;float:right;max-width:250px">
   
After reading this article, the reader should feel comfortable deploying the X2Engine Sales CRM stack (version 5.0.6-0) by Bitnami.

<a href="https://bitnami.com/" rel="no-follow">Bitnami</a> has integrated their <a href="https://bitnami.com/stack/x2engine" rel="no-follow">X2Engine Sales CRM stack</a> with the CenturyLink Cloud platform with a single-click deploy solution.  The purpose of this KB article is to help the reader take advantage of this integration to achieve rapid time-to-value for this X2Engine Sales CRM solution.

X2Engine Sales CRM is an intuitive solution for managing your contacts, accounts, sales opportunities, marketing projects, calendar and more. Your administrator will have a great set of tools to define user roles and permissions, set up workflow, and automate important tasks. Users will appreciate the drag & drop interface for moving around fields and columns, an activity feed that keeps them up-to-date with peers, and the ability to generate meaningful reports.


### Audience

CenturyLink Cloud Users


### Deploying X2Engine Sales CRM on a New Server

X2Engine Sales CRM is available as a Blueprint for deployment on a **new server**.

#### Steps


1. **Locate the Blueprint in the Blueprint Library**

  Starting from the CenturyLink Control Panel, navigate to the Blueprints Library. Search for **X2Engine Sales CRM on Linux** in the keyword search on the right side of the page.

2. **Click the Deploy Blueprint button.**

3. **Set Required parameters.**

  Set the following parameters in addition to those associated with your server itself (password, network, group, etc.):

  * **Apache server SSL port** - default 443
  * **Apache server port** - default 80
  * **Service Password** -  Provide service password 6 chars or more 
  * **User's name** -  Users Name 

5. **Review and Confirm the Blueprint**

6. **Deploy the Blueprint**

  Once verified, click on the `deploy blueprint` button. You will see the deployment details stating the Blueprint is queued for execution.

  This will kick off the Blueprint deploy process and load a page where you can track the deployment progress. Deployment will typically complete within five minutes.

7. **Deployment Complete**

  Once the Blueprint has finished executing on your server you may access X2Engine Sales CRM by navigating to your server via http.

8. **Enable public access** (optional)

  Servers are built using private IPs only with access with client or IPSEC VPN.  For inbound access from the Internet add a public IP to your master server.

  <a href="../../network/how-to-add-public-ip-to-virtual-machine/">
    <img style="border:0;width:50px;vertical-align:middle;" src="../images/shared_assets/fw_icon.png">
    Adding a public IP to your virtual machine
  </a>



### Deploying X2Engine Sales CRM on an existing server (alternate option)

X2Engine Sales CRM is available as a Blueprint Package for deployment on an existing server based on your own sizing requirements or to support more advanced configurations such as customized Blueprint Workflows to repeatably deploy multiple stacks on the same machines

#### Steps


1. **Deploy or Identify an Existing Server**

  Identify the server targeted for X2Engine Sales CRM installation.  Operating sustem must be linux.

  See the [Creating a new enterprise cloud server](../Servers/creating-a-new-enterprise-cloud-server.md) KB for more information on completing this step.

2. **Select to Execute the Package on a Server Group**

  Packages can be executed on one more more servers in a group.  Search for the public script package named **Install X2Engine Sales CRM on Linux**.

  See the [using group tasks to install scripts on groups](../Servers/using-group-tasks-to-install-software-and-run-scripts-on-groups.md) KB for more information on how to complete the next few steps.

3. **Set Parameters**

  Set the following parameters:

  * **Apache server SSL port** - default 443
  * **Apache server port** - default 80
  * **Service Password** -  Provide service password 6 chars or more 
  * **User's name** -  Users Name 

4. **Deploy the Blueprint**

  Once verified, click on the `execute package` button. You will see the deployment details stating the Blueprint is queued for execution.

  This will kick off the Blueprint deploy process and load a page where you can track the deployment progress. Deployment will typically complete within five minutes.

5. **Deployment Complete**

  Once the Blueprint has finished executing on your server you may access X2Engine Sales CRM by navigating to your server via http.

6. **Enable public access** (optional)

  Servers are built using private IPs only with access with client or IPSEC VPN.  For inbound access from the Internet add a public IP to your master server.

  <a href="../../network/how-to-add-public-ip-to-virtual-machine/">
    <img style="border:0;width:50px;vertical-align:middle;" src="../images/shared_assets/fw_icon.png">
    Adding a public IP to your virtual machine
  </a>


### Pricing

The costs listed above in the above steps are for the infrastructure only.


### About Bitnami

CenturyLink Cloud works with [Bitnami](http://www.bitnami.com) to provide open source software integrations to its customers.  Bitnami is a library of popular server applications and development environments that can be installed with one click, either in your laptop, in a virtual machine or hosted in the cloud. Bitnami takes care of compiling and configuring the applications and all of their dependencies (third-party libraries, language runtimes, databases) so they work out-of-the-box. The resulting packaged software (a 'stack') is then made available as native installers, virtual machines and cloud images. These Bitnami application packages provide a consistent, secure and optimized end-user experience when deploying any app, on any platform.


### Frequently Asked Questions

**Who should I contact for support?**

* For issues related to cloud infrastructure, please open a ticket using the [CenturyLink Cloud Support Process](../Support/how-do-i-report-a-support-issue.md).
* For issues related to deploying the Bitnami Blueprint on CenturyLink Cloud, Licensing or Accessing the deployed software, please visit the [Bitnami Support website](http://www.bitnami.com/support)

**How do I access X2Engine Sales CRM for the first time?**

Nearly all Bitnami stacks can be accessed and configured by navigating to your server with a web browser.


