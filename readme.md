# Logic App New-PagerDutyIncident

author: Sebastien Molendijk

This playbook allows you to create PagerDuty incidents, based on Azure Sentinel incidents properties.
The playbook performs the following actions:

* Gather the details about the Sentinel incident
* Call the PagerDuty API using an <a href="https://support.pagerduty.com/docs/generating-api-keys" target="_blank">API token</a> to create the incident
* Add a comment in Azure Sentinel with th ePagerDuty incident link

## Deployment

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FSebmolendijk%2FPagerDuty%2Fmaster%2FNew-PagerDutyIncident.json" target="_blank">
    <img src="https://aka.ms/deploytoazurebutton"/>
</a>
