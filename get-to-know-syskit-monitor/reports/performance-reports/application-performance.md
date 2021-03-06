---
title: Application Performance
description: >-
  These reports help you easily track the performance values of the processes
  running on all the servers in your environment, such as CPU, Memory, IO Reads,
  IO Writes, and IO Operations.
author: Andrea Budisa
date: 25/5/2017
---

# application-performance

The **Application Performance** reports are available in both Real-Time and History form. The Real-Time and History reports have a grid-based layout, while the History report has a **preview chart** in addition to the grid-based layout, that provides a visual representation of computer performance.

## Real-Time

The **Real-Time** report displays the performance values of the processes running on all the servers in your environment, such as CPU, Memory, IO Reads, IO Writes and IO Operations. The performance values for processes shown in the Real-Time report are updated **every 60 seconds** and are grouped by Computer. This report has two filters available in the right panel: Computers and Applications.  
**Performance counter columns** have a small pop-up window that concisely describes the performance counter being pointed to.

### Performance counter columns explanation

* CPU \(% Processor Time\) – counter indicates the processor activity.
* Memory \(Available Mbytes\) – counter indicates the amount of physical memory currently used by running processes.
* IO Reads \(IO Read KB/sec\) – counter indicates the number of bytes read in input/output operations generated by a process, including file, network, and device I/Os per second.
* IO Writes \(IO Write KB/sec\) – counter indicates the number of bytes written in input/output operations generated by a process, including file, network, and device I/Os per second.
* IO Operations \(IO Data Operations/sec\) – counter indicates the rate at which the process is issuing read and write I/O operations. It counts all I/O activity generated by the process including file, network, and device I/Os.

Performance counter values in the Real-Time report are shown in various **shades of yellow**, with darker colors representing heavier use. These thresholds cannot be modified.

The Real-Time report has an option for the current running processes – it provides the ability to **end multiple processes at once**.

## History

The **History** report displays detailed performance statistics for the processes running on all the computers in your environment, such as CPU, Memory, IO Reads, IO Writes and IO Operations, for the selected Date Range, Computer\(s\), and Application\(s\). The performance values for processes shown in the History report display an **average** and are grouped by Computer.  
This report has two filters available in the right panel: Computers and Applications. **This report includes some useful tricks:**

* You can **quickly zoom in and out** of a chart’s diagram using the mouse wheel.
* When you click on a grouped header, the chart will be hidden and a grid-based layout will be displayed.

**Performance counter columns** have a small pop-up window that concisely describes the performance counter being pointed to.

### Performance counter columns explanation

The performance counter columns display the average CPU, Memory, IO Reads, IO Writes,and IO Operations within the selected Date Range.  
The **charts** display a performance overview for the selected process within the selected Date Range, while the grid values represent an average of all collected values based on the same Date Range.  
A small but very important item to note here is the **chart tooltip**. The tooltip displays details about the data point the mouse is currently hovering over, such as the date and time values, and value of the data point.  
Use the **Date Range filter** to set date boundaries on your performance data. You can select any day, week, or month or a custom date range.

> **Please note!** You will not be able see any performance data outside 30 days unless you change the Performance Counters [Data Retention](application-performance.md#internal/get-to-know-syskit-monitor/backstage-screen/configuration/options/#data-retention) settings. The default is set to delete performance counters data older than 30 days.

### Reports Ribbon

Depending on whether the report type is real-time or history, you will have a different set of options and filters available. Use the reports ribbon to change the current layout or take the following actions:

* **Export** – Save the current report to PDF, Excel, HTML, or CSV files.
* **Subscription Manager** – Create, edit, and send subscriptions that contain reports and views. Subscriptions can be delivered to email, SharePoint, and FileShare.
* **Schedule This Report** – Schedule the current report or view to email, SharePoint, or FileShare.
* **Save As View** – Each report can have two different filters applied: Computers and Applications. To create a View, click on the Save As View button on the ribbon, enter the view name, choose the view type and visibility, and click on Save. Afterwards, you can **adjust the filters** on the newly created view, and save the changes by clicking the **Save View Changes** button on the ribbon. When you find an arrangement that you like, you can further customize it with other options, such as sorting, grouping, and changing your view.
* **Refresh** – Refresh items in the left navigation panel, filters, and the main view.
* **Default Layout** – Reset the current layout of the main view to default.
* **Expand** – Expand collapsed groups in the current report or view.
* **Collapse** – Collapse expanded groups in the current report or view.
* **Options** – Allows configuration of options for Report and Dashboard data, Alerts, Export and System Jobs.

