---
title: SQL Agent - Status Alarm
last_updated: July 29, 2016
summary: "This alarm becomes active when this SQL Server supporting service is installed but not active."
sidebar: c_sqlserver_sidebar
id: Home.btnServices.SQLServerServiceStatus.Alarm
permalink: sqlserver_alarm_sqlagent_status.html
folder: ConnectSQLServer
---


Services currently monitored are:

* SQL Server Agent (SQLServerAgent) service.
* Distributed Transaction Coordinator (MSDTC) service.
* Microsoft OLAP/Analysis (MSSQLServerOLAPService) service.
* Full-Text Search (Microsoft Search) service.
* The SQL Server Integration service.
* The SQL Server Reporting service.


When this alarm is current, you should:

* Check the **Service Status** page on the **Support Services** drilldown to see the status of all known SQL Server support services.
* Review messages in the **SQL Error Log** drilldown to determine the reason the service is not running.
* Restart the affected service if necessary. This can be done from the **Service Status** page by right-clicking the service in the Services Status grid.


{% include links.html %}
