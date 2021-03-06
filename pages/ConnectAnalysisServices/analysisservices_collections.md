---
title: Analysis Services collections
last_updated: July 29, 2016
tags: [collections]
summary: "The following collections are used for displays (home page components and drilldowns)."
sidebar: c_analysisservices_sidebar
permalink: analysisservices_collections.html
folder: ConnectAnalysisServices
---


## Alarms

Alarm | Collection Name
------|-----------------
Command - Long Running Command Alarm | SSAS - Command List
Cubes - Days Since Last Processed Alarm | SSAS - Cube List
Cubes - Unprocessed Alarm | SSAS - Cube List

## Spotlight Overview page

### Connections Panel

Component | Collection Name
----------|----------------
Connections | SSAS - Connection  
User Sessions | SSAS - Connection  
Avg Time Per Query | SSAS - Storage Engine Query
Data Flow: Queries Answered/s | SSAS - Storage Engine Query
Data Flow: Queries Requested/s | SSAS - Connection
Data Flow: Queries From Cache Direct | SSAS - Storage Engine Query
Data Flow: Queries from Cache Filtered | SSAS - Storage Engine Query
Data Flow: Queries From File | SSAS - Storage Engine Query

### Memory Panel

Component | Collection Name
----------|----------------
Memory Limit Low | SSAS - Memory
Memory Limit High | SSAS - Memory
Memory Usage | SSAS - Memory
Current Latch Waits | SSAS - Locks
Current Lock Waits | SSAS - Locks
Query Pool Job Queue Length | SSAS - Threads
Data Flow: Temp File Rows Written | SSAS - Proc Aggregations
Data Flow: Rows Read | SSAS - Processing
Data Flow: Rows Written | SSAS - Processing

### Storage Panel

Component | Collection Name
----------|----------------
 | SSAS - Database Summary


## SQL Activity drilldown

Page | Collection Name
----------|----------------
Connections page | SSAS - Connection List
Sessions page | SSAS - Session List
Commands page | SSAS - Command List


## Memory  drilldown

Page | Collection Name
----------|----------------
Cache chart | SSAS - Cache
Proactive Caching chart | SSAS - Proactive Caching
Memory chart | SSAS - Memory
Threads chart | SSAS - Threads


## Storage drilldown

Page | Collection Name
----------|----------------
Databases page | SSAS - Database List
Cubes page | SSAS - Cube List


## Configuration drilldown

Page | Collection Name
----------|----------------
 | SSAS - Server Properties



{% include links.html %}
