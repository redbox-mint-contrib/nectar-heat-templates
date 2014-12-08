```
title: Deployment Guide
layout: page
tags: ['intro','page']
pageOrder: 2
```
You can now deploy ReDBox in the NecTAR cloud using the Nectar Heat functionality.

##Pre-requisites
* You must have access to NeCTAR
* You must have a tenancy with the appropriate allowances to launch the ReDBox configuration (details in template descriptions)


##Deployment Instructions
###Step 1. Decide which Heat template you would like to use.
We currently have 2 templates that deploy ReDBox using different server configurations. Information on each of them is available [here](/pages/heattemplates).

###Step 2. Load template in the NeCTAR dashboard
Instructions on how to do this is available on the [NeCTAR website](https://support.rc.nectar.org.au/docs/heat/dashboard).

**Note:** At the time of writing using a URL source for the Heat template was not functioning. If this is the case you may need to download the template and use the File source option

###Step 3. Configure your instance in the NeCTAR dashboard
Information on what the fields for your templates mean and how to configure your instance appropriately is available [here](/pages/heattemplates).

###Step 4. Launch the stack
Once NeCTAR reports that the stack is ready for use. You should have a running ReDBox instance! You can then grab the IP Address that has been assigned to the machine and visit http://<ip address>/redbox in your web browser. If everything was successful you will have will be greeted with the ReDBox dashboard
![](../../images/redboxscreenshot.png)

###Step 5. Configure your ReDBox Instance
Now that you have a running ReDBox instance it's time to configure it to your needs. The Heat templates deploy a supplementary ReDBox Administration interface to assist you with this task. Please visit the [ReDBox Administration Interface website](linkme) to learn more about it.
