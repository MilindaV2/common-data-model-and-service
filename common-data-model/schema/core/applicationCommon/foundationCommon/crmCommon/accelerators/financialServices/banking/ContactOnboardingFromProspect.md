---
title: ContactOnboardingFromProspect - Common Data Model | Microsoft Docs
description: Process entity for Contact Onboarding from Prospect.
author: nenad1002
ms.service: common-data-model
ms.reviewer: deonhe
ms.topic: article
ms.date: 8/28/2019
ms.author: nebanfic
---

# Contact Onboarding from Prospect

Process entity for Contact Onboarding from Prospect.  
  
 Latest version of the JSON entity definition is available on <a href="https://github.com/Microsoft/CDM/tree/master/schemaDocuments/core/applicationCommon/foundationCommon/crmCommon/accelerators/financialServices/banking/ContactOnboardingFromProspect.cdm.json" target="_blank">GitHub</a>.  

## Instances

Instances of this entity are listed below.  

- /foundationCommon/crmCommon/accelerators/financialServices/banking/ContactOnboardingFromProspect  

## Attributes

|Name|Description|First Included in Instance|
|---|---|---|
|[activeStageStartedOn](#activeStageStartedOn)|Date and time when current active stage is started|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[contactId](#contactId)||<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[bpfDuration](#bpfDuration)|Duration of Business Process Flow|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[leadId](#leadId)||<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[msfsiKycId](#msfsiKycId)||<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[name](#name)|Description|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[businessProcessFlowInstanceId](#businessProcessFlowInstanceId)|Unique identifier for entity instances|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[completedOn](#completedOn)|Date and time when Business Process Flow instance is completed.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[createdBy](#createdBy)|Unique identifier of the user who created the record.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[createdOn](#createdOn)|Date and time when the record was created.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[createdOnBehalfBy](#createdOnBehalfBy)|Unique identifier of the delegate user who created the record.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[importSequenceNumber](#importSequenceNumber)|Sequence number of the import that created this record.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[modifiedBy](#modifiedBy)|Unique identifier of the user who modified the record.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[modifiedOn](#modifiedOn)|Date and time when the record was modified.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[modifiedOnBehalfBy](#modifiedOnBehalfBy)|Unique identifier of the delegate user who modified the record.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[organizationId](#organizationId)|Unique identifier for the organization|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[overriddenCreatedOn](#overriddenCreatedOn)|Date and time that the record was migrated.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[stateCode](#stateCode)|Status of the Contact Onboarding from Prospect|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[stateCode_display](#stateCode_display)||<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[statusCode](#statusCode)|Reason for the status of the Contact Onboarding from Prospect|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[statusCode_display](#statusCode_display)||<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[timeZoneRuleVersionNumber](#timeZoneRuleVersionNumber)|For internal use only.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[traversedPath](#traversedPath)|Comma delimited string of process stage ids that represent visited stages of the Business Process Flow instance.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|
|[UTCConversionTimeZoneCode](#UTCConversionTimeZoneCode)|Time zone code that was in use when the record was created.|<a href="ContactOnboardingFromProspect.md" target="_blank">banking/ContactOnboardingFromProspect</a>|

### <a href=#activeStageStartedOn name="activeStageStartedOn">activeStageStartedOn</a>

Date and time when current active stage is started  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Active Stage Started On</td></tr><tr><td>description</td><td>Date and time when current active stage is started</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>activestagestartedon</td></tr></table>

### <a href=#contactId name="contactId">contactId</a>

First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bpf_contactid</td></tr></table>

### <a href=#bpfDuration name="bpfDuration">bpfDuration</a>

Duration of Business Process Flow  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Duration</td></tr><tr><td>description</td><td>Duration of Business Process Flow</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>0</td></tr><tr><td>sourceName</td><td>bpf_duration</td></tr></table>

### <a href=#leadId name="leadId">leadId</a>

First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Lead</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bpf_leadid</td></tr></table>

### <a href=#msfsiKycId name="msfsiKycId">msfsiKycId</a>

First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Msfsi_Kyc</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>bpf_msfsi_kycid</td></tr></table>

### <a href=#name name="name">name</a>

Description  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Name</td></tr><tr><td>description</td><td>Description</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>100</td></tr><tr><td>sourceName</td><td>bpf_name</td></tr></table>

### <a href=#businessProcessFlowInstanceId name="businessProcessFlowInstanceId">businessProcessFlowInstanceId</a>

Unique identifier for entity instances  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Contact Onboarding from Prospect</td></tr><tr><td>description</td><td>Unique identifier for entity instances</td></tr><tr><td>isPrimaryKey</td><td>true</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>businessprocessflowinstanceid</td></tr></table>

### <a href=#completedOn name="completedOn">completedOn</a>

Date and time when Business Process Flow instance is completed.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Completed On</td></tr><tr><td>description</td><td>Date and time when Business Process Flow instance is completed.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>completedon</td></tr></table>

### <a href=#createdBy name="createdBy">createdBy</a>

Unique identifier of the user who created the record.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By</td></tr><tr><td>description</td><td>Unique identifier of the user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>createdby</td></tr></table>

### <a href=#createdOn name="createdOn">createdOn</a>

Date and time when the record was created.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created On</td></tr><tr><td>description</td><td>Date and time when the record was created.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>createdon</td></tr></table>

### <a href=#createdOnBehalfBy name="createdOnBehalfBy">createdOnBehalfBy</a>

Unique identifier of the delegate user who created the record.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Created By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who created the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>createdonbehalfby</td></tr></table>

### <a href=#importSequenceNumber name="importSequenceNumber">importSequenceNumber</a>

Sequence number of the import that created this record.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Import Sequence Number</td></tr><tr><td>description</td><td>Sequence number of the import that created this record.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-2147483648</td></tr><tr><td>sourceName</td><td>importsequencenumber</td></tr></table>

### <a href=#modifiedBy name="modifiedBy">modifiedBy</a>

Unique identifier of the user who modified the record.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By</td></tr><tr><td>description</td><td>Unique identifier of the user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>modifiedby</td></tr></table>

### <a href=#modifiedOn name="modifiedOn">modifiedOn</a>

Date and time when the record was modified.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified On</td></tr><tr><td>description</td><td>Date and time when the record was modified.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>modifiedon</td></tr></table>

### <a href=#modifiedOnBehalfBy name="modifiedOnBehalfBy">modifiedOnBehalfBy</a>

Unique identifier of the delegate user who modified the record.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Modified By (Delegate)</td></tr><tr><td>description</td><td>Unique identifier of the delegate user who modified the record.</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>modifiedonbehalfby</td></tr></table>

### <a href=#organizationId name="organizationId">organizationId</a>

Unique identifier for the organization  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Organization Id</td></tr><tr><td>description</td><td>Unique identifier for the organization</td></tr><tr><td>dataFormat</td><td>Guid</td></tr><tr><td>sourceName</td><td>organizationid</td></tr></table>

### <a href=#overriddenCreatedOn name="overriddenCreatedOn">overriddenCreatedOn</a>

Date and time that the record was migrated.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Record Created On</td></tr><tr><td>description</td><td>Date and time that the record was migrated.</td></tr><tr><td>dataFormat</td><td>DateTimeOffset</td></tr><tr><td>sourceName</td><td>overriddencreatedon</td></tr></table>

### <a href=#stateCode name="stateCode">stateCode</a>

Status of the Contact Onboarding from Prospect  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status</td></tr><tr><td>description</td><td>Status of the Contact Onboarding from Prospect</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statecode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th></tr><tr><td>en</td><td>Active</td><td>0</td></tr><tr><td>en</td><td>Inactive</td><td>1</td></tr></table></td></tr></table>

### <a href=#stateCode_display name="stateCode_display">stateCode_display</a>

First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#statusCode name="statusCode">statusCode</a>

Reason for the status of the Contact Onboarding from Prospect  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Status Reason</td></tr><tr><td>description</td><td>Reason for the status of the Contact Onboarding from Prospect</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>sourceName</td><td>statuscode</td></tr><tr><td>valueConstrainedToList</td><td>true</td></tr><tr><td>defaultValue</td><td><table><tr><th>languageTag</th><th>displayText</th><th>attributeValue</th><th>correlatedValue</th></tr><tr><td>en</td><td>Active</td><td>1</td><td>0</td></tr><tr><td>en</td><td>Finished</td><td>2</td><td>1</td></tr><tr><td>en</td><td>Aborted</td><td>3</td><td>1</td></tr></table></td></tr></table>

### <a href=#statusCode_display name="statusCode_display">statusCode_display</a>

First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>isReadOnly</td><td>true</td></tr></table>

### <a href=#timeZoneRuleVersionNumber name="timeZoneRuleVersionNumber">timeZoneRuleVersionNumber</a>

For internal use only.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Time Zone Rule Version Number</td></tr><tr><td>description</td><td>For internal use only.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>sourceName</td><td>timezoneruleversionnumber</td></tr></table>

### <a href=#traversedPath name="traversedPath">traversedPath</a>

Comma delimited string of process stage ids that represent visited stages of the Business Process Flow instance.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>Traversed Path</td></tr><tr><td>description</td><td>Comma delimited string of process stage ids that represent visited stages of the Business Process Flow instance.</td></tr><tr><td>dataFormat</td><td>String</td></tr><tr><td>maximumLength</td><td>1250</td></tr><tr><td>sourceName</td><td>traversedpath</td></tr></table>

### <a href=#UTCConversionTimeZoneCode name="UTCConversionTimeZoneCode">UTCConversionTimeZoneCode</a>

Time zone code that was in use when the record was created.  
First included in: banking/ContactOnboardingFromProspect (this entity)  

#### Properties

<table><tr><th>Name</th><th>Value</th></tr><tr><td>displayName</td><td>UTC Conversion Time Zone Code</td></tr><tr><td>description</td><td>Time zone code that was in use when the record was created.</td></tr><tr><td>dataFormat</td><td>Int32</td></tr><tr><td>maximumValue</td><td>2147483647</td></tr><tr><td>minimumValue</td><td>-1</td></tr><tr><td>sourceName</td><td>utcconversiontimezonecode</td></tr></table>