# The Certinia API

**Source:** https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/GenericAPI.htm  
**Scraped:** 2025-08-01 11:22:36

---

[ ![](https://help.certinia.com/api/resources/images/Logo.png) ](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/Default.htm) Professional Services Automation Apex API Developer Reference |   
---|---  
    * [Home](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/Default.htm)
    * [Getting Started](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [Certinia API](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/GenericAPI.htm)
    * [Actuals](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [APIActualsService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/APIActualsService.htm)
    * [Billing](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [APIBillingService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/APIBillingService.htm)
      * [BillingDocumentService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/BillingDocumentService.htm)
      * [BillingEventsManager](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/BillingEventsManager.htm)
    * [Common](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [APICommonsService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/APICommonsService.htm)
      * [CalendarUtil](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/CalendarUtil.htm)
    * [Exceptions](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [APIException](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/APIException.htm)
    * [Milestones](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [MilestoneService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/MilestoneService.htm)
    * [Miscellaneous](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [MultiCurrencyService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/MultiCurrencyService.htm)
    * [Project Versioning and Baselines](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [VersionConfigService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/VersionConfigService.htm)
      * [VersionService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/VersionService.htm)
    * [Projects and Project Tasks](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [AddFromProjectTemplateService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/AddFromProjectTemplateService.htm)
      * [CreateProjectFromTemplateService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/CreateProjectFromTemplateService.htm)
      * [SObjectCloneMapper](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/SObjectCloneMapper.htm)
      * [TaskManagementService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/TaskManagementService.htm)
    * [Rate Cards](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [RateCardMatcherPlugin](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/RateCardMatcherPlugin.htm)
    * [Resource Management](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [ResourceAssignmentService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/ResourceAssignmentService.htm)
      * [ResourceSearchService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/ResourceSearchService.htm)
      * [ScheduleResourceService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/ScheduleResourceService.htm)
    * [Scheduling](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [AssignmentService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/AssignmentService.htm)
      * [HoursToDaysRuleService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/HoursToDaysRuleService.htm)
      * [ScheduleSaveDTO](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/ScheduleSaveDTO.htm)
      * [ScheduleService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/ScheduleService.htm)
      * [SchedulingStrategyService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/SchedulingStrategyService.htm)
    * [Services Forecasting](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [RevenueForecastScheduler](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/RevenueForecastScheduler.htm)
      * [RevenueForecastService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/RevenueForecastService.htm)
      * [RevenueForecastVersionScheduler](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/RevenueForecastVersionScheduler.htm)
      * [RevenueForecastVersionService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/RevenueForecastVersionService.htm)
    * [Shift Management](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [TeamScheduleService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/TeamScheduleService.htm)
      * [TeamScheduleTemplateService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/TeamScheduleTemplateService.htm)
    * [Skills](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [SkillsService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/SkillsService.htm)
    * [Time And Expense](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [PSATimecardService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/PSATimecardService.htm)
    * [Utilization Analytics](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/)
      * [UtilizationAnalyticsService](https://help.certinia.com/TechnicalReference/2025.1/ProfessionalServicesAutomation/Apex/UtilizationAnalyticsService.htm)

| 
# The Certinia API
Certinia provides programmatic access to your organization's information using a simple and secure application programming interface, the API. To use this document, you should be familiar with software development, Web services, and the Salesforce/Certinia user interface.  The API works with current SOAP development environments, including Visual Studio .NET, and Apache Axis. Refer to the Salesforce Apex Developer's Guide for information on data type mapping and system fields.
## Creating an API Class View
Always use the latest version of the API for each Apex class. It is useful to set up an API class view:
  1. Click **Setup | Develop | Apex Classes**.
  2. Click **Create New View**.
  3. Enter a view name of "Certinia API Classes".
  4. Specify the relevant filter criteria: e.g. for Accounting: 
     * Name | starts with | CODAAPI
     * Name | does not contain | Test
  5. Click **Add Filter Logic** to set filter logic, such as 1 AND 2.
  6. Select relevant fields to display, or accept the default.
  7. Restrict visibility to this view, as appropriate.
  8. Click **Save**.

This view will be available to you on all subsequent visits.
## Viewing a list of Certinia API Apex Classes
To view a list of all the relevant Apex classes:
  1. If necessary, create a new Apex class view called the "Certinia API Classes" as described in the related topic below.
  2. Click **Setup | Develop | Apex Classes**.
  3. From the View field, select the **"Certinia API Classes"** option.
  4. A list of all relevant Apex classes is displayed.
  5. Click the Apex class name to view its detail.


## Alternative views
If you are only interested in viewing services, you might want to add another filter condition: Name | does not contain | Types
## Grant Access to the API
Assign the necessary permission set or profile.
## Using the API within Apex
If you are developing Apex classes, triggers or Visualforce controllers, you may call the Certinia Apex classes directly to integrate with Certinia. You do not need to go via the Web Services interface. **Note** There is a Force.com platform restriction that means you can only use API calls in Visualforce controller constructors for reading data. See "Documentation Resources for Force.com Developers" in the Salesforce Help for more information. © Copyright 2009–2025 Certinia Inc. All rights reserved. Various trademarks held by their respective owners.   
---|---
