# Microsoft SQL Server Reporting Services (SSRS) Add-On

## Description
This TA serves as a demonstration of ingesting SSRS-related data stored in `binary` log format into Splunk. 

The `props.conf` - particularly the field extractions may not work in your environment. This is due to the fact that you are able to customize the [SSRS log file fields](https://learn.microsoft.com/en-us/sql/reporting-services/report-server/report-server-http-log?view=sql-server-ver16).

A short *example* of this data is [contained in the root of the repository](Microsoft.ReportingServices.Portal.WebHost-example.log).

## Testing
This was tested using Splunk Enterprise 9.0.1 running in Docker in a single-instance deployment

## Support
Not Supported

## Questions and Comments
Add an Issue! Thanks!