# Power Automate - MIS & Operational Reporting Automation

## Overview

This project demonstrates the use of Microsoft Power Automate to automate recurring MIS, production, quality, and manpower reporting workflows.

The automation workflows are designed to process operational data, prepare management-ready reports, and distribute the required reports automatically through email.

The project demonstrates practical use of workflow automation to reduce repetitive manual reporting activities and improve the consistency and timely distribution of operational reports.

> **Note:** Screenshots and examples in this repository are sanitized for portfolio purposes and do not contain confidential company information.

---

## Automated Reports

The automation workflows cover the following reports:

1. Production Compliance Chart
2. AOQL & EGA Report
3. Production Priority Report
4. Manpower Summary Report
5. MIS Report
6. Daily Production Report

---

## Automation Workflow

The general automation process follows these stages:

```text
Scheduled Trigger
       ↓
Retrieve Source Data
       ↓
Process / Filter Data
       ↓
Prepare Report
       ↓
Generate Report Output
       ↓
Send Report through Email