---
title: Service Level Agreement
slug: sla
layout: legal
description: >
  This Service Level Agreement (“SLA”) is included in all Enterprise, Premium and legacy Business plans.
---

**Tailscale Service Level Agreement**

Effective date: 2024-02-19

This Service Level Agreement (“**SLA**”) is included for all customers that purchase a Silver or Gold support package pursuant to an Order Form with Tailscale. For purposes of this SLA, the “**Agreement**” refers to either the Terms of Service or the Main Service Agreement between you and Tailscale (as applicable to you). This SLA is incorporated by reference into the Agreement. Any capitalized terms that are not defined in this SLA have the meanings assigned to such terms in the Agreement.

1.  **Service Obligations**. Tailscale will use commercially reasonable efforts to make the Tailscale Solution available in accordance with the standards set forth below in Section 2 (Service Availability), Section 3 (Support Standards) and Section 5 (Exclusions). If we fall short of the standards described in this SLA and your use of the Tailscale Solution is impacted, we will provide Service Credits as set forth below in Section 4 (Service Credits). This Service Credit will be Customer’s sole and exclusive remedy for any failure to meet the targets set forth in this SLA.
   
2.  **Service Availability**.

    2.1  **Uptime**. For purposes of this SLA, “**Uptime**” is the percentage of total possible minutes that core systems of the Tailscale Solution – namely, the <tailscale.com> website and Documentation, admin console, API, coordination server, DERP relay servers, and package server– are operational and available each calendar month. Tailscale will make commercially reasonable efforts to maintain at least 99.00% Uptime.
   
         (Total minutes in a month - Downtime minutes) / total minutes in a month > 99.00%
   
    2.2  **Downtime**. For purposes of this SLA and our Uptime commitment, “**Downtime**” is the number of minutes the Tailscale Solution is not operational or available. Downtime may encompass periods of time when the entire Tailscale Solution is not operational or completely unavailable (a “**Full Outage**”) and periods of time when only certain systems, features or functionality are not operational or unavailable (a “**Partial Outage**”). Downtime excludes routine maintenance (see 2.2.1) and emergency maintenance (see 2.2.2).

      2.2.1  **Routine Maintenance**. Sometimes we need to perform routine maintenance to keep the Tailscale Solution working smoothly. For any maintenance that might cause a material disruption to a customer’s network, we will strive to provide notice at least forty-eight (48) hours in advance. Whenever possible, routine maintenance will take place so as to minimize potential business disruption. Please note, however, that, due to our global customer base, we cannot guarantee that routine maintenance will always take place during a particular window of time or that there will be no disruption in service.

      2.2.2  **Emergency Maintenance**. Sometimes we need to do emergency maintenance on the Tailscale Solution, such as for example a security patch or high priority fixes identified as a result of an outage. We will strive to provide notice of emergency maintenance at least twenty-four (24) hours in advance, but reserve the right to perform emergency maintenance with no notice, as determined by us in our sole discretion.
   
    ‍2.3  **Status Updates**. Reports on service availability may be accessed 24x7x365 on https://status.tailscale.com (the “**Status Page**”). Tailscale will provide the notices described in this SLA and other details regarding status of the Tailscale Solution solely via the Status Page. 

3.  **Priority Support Standards**. We know how important it is to resolve issues quickly, and that’s why we make all reasonable efforts to meet or exceed the stated response times for issues within our scope of support. <ins>Table 1</ins> shows what is included in our Silver and Gold support packages. In addition, we offer reduced time to first response based on issue severity. Severity levels are detailed in <ins>Table 2</ins>. Tailscale will determine severity levels at its sole discretion. Table 2 also shows our initial response time (that is, when Tailscale will respond to any request for support), measured from when a ticket is submitted or the issue is otherwise formally reported to Tailscale through one of the approved support channels identified in Table 1. (For the avoidance of doubt, Slack is not an approved channel for formally reporting issues to Tailscale.) Tailscale will use commercially reasonable efforts to meet these response times.

    For purposes of this SLA, “**business hours**” are 9 AM ET – 6 PM ET, Monday through Friday.
   
    <ins>Table 1: Support Packages</ins>

    |                | Silver | Gold | 
    |----------------|------------|---------|
    | Eligible Plans |<ul><li>Enterprise</li><li>Premium</li><li>Legacy Business</li></ul>|<ul><li>Enterprise</li></ul>|
    | Channels       |<ul><li>Knowledge Base</li><li>Email</li><li>Contact Support form</li></ul>|<ul><li>Knowledge Base</li><li>Email</li><li>Contact Support form</li></ul>|
    | Support Hours  |<ul><li>Business hours</li></ul>|<ul><li>Business hours</li><li>Plus 24x7 support for Sev 1 and Sev 2 incidents*</li></ul>|
    | First Response SLA | See Table 2 | See Table 2 |
    | Other Perks    | <ul><li>Priority bug fixes</li></ul> | <ul><li>Priority bug fixes</li><li>Priority feature requests</li></ul>|
    
    To receive 24x7 support for Severity 1 incidents, you must first identify no more than three (3) authorized Customer contacts, and the request must come from one of those contacts. If you contact us from an account or email address that is not one of your authorized support contacts, we may not be able to verify and identify your associated account and will only be able to share generalized information. We also recommend that your contacts login to your account and use our [Contact Support form](https://tailscale.com/contact/support/) in order to be identified and routed correctly when submitting support tickets.
  
    <ins>Table 2: Severity Levels and First Response Times</ins>

    | Severity Level | Description | Silver First Response | Gold First Response |
    | ---- | ---- | ---- | ---- |
    | Sev 1<br><br>Critical | There is a Full Outage, a Personal Data Breach (defined in our DPA), or other major security breach.<br><br>Ex: Tailscale is not operational for your entire company.<br><br>Ex: A breach of our production database. | 4 business hours | 2 business hours|
    | Sev 2<br><br>High     | There is a Partial Outage of a core service, feature or functionality, or an attempted security breach.<br><br>Ex: SCIM is not operational. | 1 business day | 4 business hours |
    | Sev 3<br><br>Normal | There is a Partial Outage of a non-core or non-essential service, feature or functionality.<br><br>Ex: A user or subset of users are experiencing poor latency or disconnects when using Tailscale. | 2 business days | 1 business day |
    | Sev 4<br><br>Low | A non-material support item, and there is no Outage (Full or Partial).<br><br>Ex: configuration help requests; minor UX bugs. | 2 business days | 1 business day |


5.  **Service Credits**. If we fall short of our Uptime commitment (Section 2.1) during a particular calendar month you may be eligible for a “**Service Credit**” for that month.

    4.1  **Downtime Service Credits**. Downtime Service Credits are based on the relevant portion of the Fees in such month, calculated as follows:
  
    | Uptime (in a given month) | Service Credit (% of monthly fees) |
    | ---- | ---- |
    | 99.00% or greater | No Service Credit |
    | 90.00% - 98.99% | 5% |
    | Under 90.00% | 10% |

    Note that Downtime does not affect everyone at the same time or in the same way. For example, some customers may be eligible to receive Service Credits during an outage in their region, while other customers in other regions that have not been similarly affected will not.
  
    4.2  **Requesting Service Credits**. Customers must request Service Credits within thirty (30) days after the end of the impacted month by contacting Support. Tailscale will review all requests for Service Credits and, if Customer is eligible, will apply the Service Credits to Customer’s next invoice.
    
    4.3	 **Limitations**. For Service Credits to apply, all outstanding invoices must be fully paid up. Service Credits are not transferable or refundable, and have no currency or exchange value. Service Credits are capped at a maximum of the applicable monthly Fees. Upon expiration or termination of your Agreement, any unused Service Credits that have accrued to your account will expire.

6.  **Exclusions**. This SLA only applies to the current version of production instances of the Tailscale Solution. This SLA does not apply to any of the following:
    * Versions of the Tailscale Solution that have been retired as being “**end of maintenance**” (EOM) or “**end of life**” (EOL) as determined by Tailscale in our sole discretion (provided Tailscale has notified customers that such versions have been designated EOM or EOL);
    * Integrations or other Third Party Services;
    * Any pre-release, staging environment, sandbox environment, or Research experiences;
    * Unsupported ancillary applications or services;
    * Devices behind subnet routers; 
    * External network or equipment problems outside of our reasonable control, such as issues with bad routing tables between your Internet service provider (ISP) and our server, Internet service failures or delays, or the unavailability or modification by third parties of telecommunications or hosting infrastructure;
    * Any suspension of Permitted User accounts due to unauthorized access or use in violation of the Agreement;
    * Self-hosted coordination servers;
    * Self-compiled versions of our open source code;
    * Tailscale Client Software that is used on or in conjunction with hardware or software other than that specified in applicable Documentation;
    * Using the Tailscale Solution not in accordance with the Agreement or Documentation;
    * Alterations or modifications to the Tailscale Client Software;
    * Defects in the Tailscale Client Software due to device hardware malfunction, abuse or improper use; or
    * Any events beyond our reasonable control, including strikes or other labor problems, material shortages, epidemics, pandemics,  civil unrest, riots, insurrection, fires, flood, earthquakes, storms, explosions, cyber attacks, or acts of God, war, terror or government.

    Finally, our ability to perform under this SLA is contingent upon Customer’s reasonable cooperation. If Customer has not provided all necessary information to Tailscale to resolve a reported issue, or Tailscale is otherwise denied or delayed access or information by Customer, then Tailscale will be excused, without liability, from performing under this SLA with respect to that issue. In such a case, Customer will not be entitled to any Service Credits, and any such failure to perform resulting from Customer’s failures will not relieve Customer from its payment obligations to Tailscale.
