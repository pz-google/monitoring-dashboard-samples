### Dashboards for Windows

Note: [Blue Medora Bindplane](https://cloud.google.com/stackdriver/blue-medora) needs to be configured for some dashboards. For detailed instructions, please review the setup doc from Blue Medora.

|Windows Active Directory Monitoring|
|:---------------------|
|Filename: [active-directory-monitoring.json](active-directory-monitoring.json)|
|This dashboard has 8 charts to display the metrics for the `Active directory servers`. Blue Medora needs to be [configured](https://bluemedora.com/monitoring-microsoft-active-directory-with-stackdriver-logging/). The metrics include resource utilization and service status.|

&nbsp;

|Windows Server Monitoring|
|:----------------------|
|Filename: [windows-server-monitoring.json](windows-server-monitoring.json)|
|This dashboard has 11 charts to display the Cloud Monitoring metrics for Windows servers. Please make sure the [Cloud Monitoring Windows agent](https://cloud.google.com/monitoring/agent/install-agent#agent-install-windows) is installed and configured. The metrics include VM resource usage, IIS, and SQL server status.|

&nbsp;

|IIS Overview|
|:----------------------|
|Filename: [iis-overview.json](iis-overview.json)|
|The dashboard displays the overview of metrics collected by the Ops Agent for IIS. This includes charts for `IIS connections`, `IIS open connections`, `IIS requests`, `IIS transferred bytes` and a couple charts for related VM Instances.|

&nbsp;

|MS SQL Server Overview|
|:----------------------|
|Filename: [mssql-overview.json](mssql-overview.json)|
|The dashboard displays the overview of metrics collected by the Ops Agent for MS SQL Server. This includes charts for `SQL Server open connections`, `SQL Server transaction rate`, `SQL Server write transaction rate` and a couple charts for related VM Instances.|
