# Module 5: Collecting Data

Azure Monitor can collects any kind of data and from any data source, for example, Azure Monitor can collect events from the Windows event logs that are specified in the settings. 

Azure Monitor is based on a common monitoring data platform that includes Logs and Metrics. 

Collecting data into this platform allows data from multiple resources to be analyzed together using a common set of tools in Azure Monitor. 

Monitoring data may also be sent to other locations to support certain scenarios, and some resources may write to other locations before they can be collected into Logs or Metrics.

In addition, You can use the HTTP Data Collector API to send log data to a Log Analytics workspace in Azure Monitor from any client that can call a REST API. 

This might be a runbook in Azure Automation that collects management data from Azure or another cloud, or it might be an alternate management system that uses Azure Monitor to consolidate and analyze log data.

All data in the Log Analytics workspace is stored as a record with a particular record type. You format your data to send to the HTTP Data Collector API as multiple records in JSON. When you submit the data, an individual record is created in the repository for each record in the request payload.


### Azure Monitor Webinars and DOCS

Azure Monitor Webinar [Hybrid identity and access management best practices](https://youtu.be/MP5IaCTwkQg) (Insight from mintue 31)

Azure Monitor Webinar [Understand Azure Monitor data types and collection](https://www.youtube.com/watch?v=GuaQvSPqlTA)

From GitHub [Send log data to Azure Monitor with the HTTP Data Collector API](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/azure-monitor/platform/data-collector-api.md)

From Microsoft DOCS [Sources of monitoring data for Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-sources)

From Microsoft DOCS [Windows event log data sources in Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/platform/data-sources-windows-events#:~:text=Configure%20Windows%20Event%20logs%20from,the%20selected%20severities%20are%20collected.)

Tool [Collect-ManagementGroupActivityLogs](https://github.com/MicrosoftDocs/azure-docs/blob/master/articles/azure-monitor/platform/data-collector-api.md)
