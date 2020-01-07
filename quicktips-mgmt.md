---
title: Fastlane Management Quick Tips
layout: default-mgmt
permalink: /quicktipsmgmt
---
<div style="margin-left:-15px; margin-bottom: -15px;"  class="wow zoomIn"><a name="applicant"></a>
  <img src="https://storage.googleapis.com/fastlane-public-files/Images/HelpImages/water-01.png" class="img-responsive"/>
</div>

# Management Tips

------

## Confidential Projects

If a Project is considered "confidential" the Project must be marked "confidential" 24-hours prior to Advance submission. If the Project is marked "confidential" after Advance submission, it is possible that the Project information may be released to the public.

------

<br>

## System Emails

Any questions regarding system emails and recipients/CCs can be answered in the <a href="systememails.html">System Emails</a> section of this System Guide. 

------

<br>

## Applicant System Guide

The Applicant System Guide (and Help Center) can be viewed here: <a href="./#help" target="_blank">Applicant System Guide.</a>

------

<br>

## Other User System Guides

The guides for other system users can be found below:

- Assessor System Guide
- External Reviewer System Guide
- Auditor (CPA) System Guide



------

<br>

## Signature Processing<a name="signprocessingmgmt"></a>

<br>

### Adobe Sign

Adobe Sign, an Adobe Document Cloud solution is a cloud-based, enterprise-class e-signature service that lets you replace paper and ink signature processes with fully automated electronic signature workflows. With it, you can easily send, sign, track, and manage signature processes using a browser or mobile device.
Fastlane uses this third-party API to process all documents that require execution. 

#### Business Incentive Signature Workflows

Business Incentive documents are triggered through the “Send Forms for Signature” page.

**Contracts**

1. Manager Signature
2. Contract Signatory Signature
3. Undersecretary Signature
4. Governor Signature

**Renewal Contracts**

1. Manager Signature
2. Contract Signatory Signature
3. Undersecretary Signature
4. Governor Signature

**Project Complete Reports (PCR)**

1. Undersecretary Signature

**Contract Amendments**

1. Undersecretary Signature
2. Contract Signatory Signature

#### Entertainment Incentive Signature Workflows

Entertainment documents are triggered through the Initial Cert and Audit screens.

**Initial Certifications**

1. Manager Review
2. Legal Review
3. Undersecretary Signature
4. Manager Signature
5. Business Signatory Signature

 **Note:** LDR users are hardcoded CCs into the workflow to receive executed cert 



**Final Certification Attestations**

1. Manager Review
2. Authorized Representative Signature

**Note:** LDR users are hardcoded CCs into the workflow to receive the DM executed attestation



Final Certifications**

1. Manager Review
2. Legal Review
3. Undersecretary Signature
4. Manager Signature

Note: LDR users are hardcoded CCs into the workflow to receive executed cert

#### How to Use Adobe Sign

<img src="https://storage.cloud.google.com/fastlane-public-files/Images/Help/AdobeSignHowTo.gif" width="800" class="ml-4 boxshadow">



------

<br>

## Processing Executed Documents Outside of FastLane

If a document cannot be fully processed using the eSignature tool, the following steps should be taken. 

1. Upload the physically signed document into the project attachments. (Project Summary > Hamburger Menu > Manage Project Attachments.) Correctly label the uploaded document. 

2. Add a project comment explaining why the document wasn’t executed using eSign. (Project Summary > Hamburger Menu > Project Comments.)

3. If the executed document would have changed the overall project status, then the manager should change it accordingly. (Project Summary > Hamburger Menu > Update Project Status.)

4. If the executed document would have triggered critical date population, then the manager should add these dates accordingly. (Project Summary > Hamburger Menu > Manage Critical Dates.)

5. The eSign status for this document will remain as is (if there is one.) This is because the digital version of this document is stuck in that current status because the process was interrupted. 