---
title: ﻿Monitored Server - Hyper-V Collection Execution Failure Alarm
last_updated: July 29, 2016
summary: "Raised when a (specified collection) failed to execute against the server."
sidebar: c_hyperv_sidebar
permalink: hyperv_alarm_monitoredserver_collectionexecutionfailure.html
id: procedureexecutionfailure.alarm
folder: ConnectHyperv
---



<h2>Collection Execution Failure</h2>
<p>The specified collection failed to execute against this server. </p>
<p>To disable this alarm, go to the Alarms dialog for this connection and add a disabled severity to the 'Monitored Server - Collection Execution Failure' alarm for this collection.</p>
<p>To do this:</p>
<ol>
    <li>Select <b>Configure | Alarms</b>.</li>
    <li>Select the connection where the collection failed.</li>
    <li>Select the alarm <strong>Monitored Server - Collection Execution Failure</strong> for the connection type.</li>
    <li>Select <strong>Override default setting for alarm 'Monitored Server - Collection Execution Failure'</strong>.</li>
    <li>Click <strong>Add</strong>.</li>
    <li>From the Key value list, select the collection that the alarm was raised for.</li>
    <li>With the key selected, click the Severity list and select <strong>Disabled</strong>.</li>
</ol>

{% include links.html %}
