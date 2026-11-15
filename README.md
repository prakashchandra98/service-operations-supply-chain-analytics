# End-to-End Service Operations & Supply Chain Performance Analytics

## Project Overview

This portfolio project demonstrates how Excel and Power BI can be used
to analyse service operations and support operational decision-making.

The project uses a **fictional industrial services company** that
provides Parts Washer (PW) and Vacuum services across four branches. It
focuses on service-order completion, overdue work, on-time performance,
driver workload, service costs, customer ratings and monthly order
trends.

> **Data disclaimer:** All data is synthetic and created for portfolio
> demonstration. It does not contain confidential information or
> represent actual operations, customers, employees, vehicles or
> financial results from Amazon, Clean Harbors or any other employer.

## Business Questions

-   How many service orders were received, completed and left pending?
-   How many pending orders were overdue as of the reporting date?
-   What proportion of completed orders were completed on time?
-   How do order volumes and completion outcomes compare across
    branches?
-   How are completed orders distributed by service type?
-   What does the monthly order trend show?
-   How many pending orders are unassigned?
-   What are the total and average service costs?

## Dataset

The synthetic dataset contains:

  Data area          Records
  ---------------- ---------
  Service orders         400
  Customers              100
  Branches                 4
  Drivers                 12
  Vehicles                12

The reporting period is September--November 2026. **11 November 2026**
is used as the fixed reporting date for overdue calculations.

## Tools and Skills Demonstrated

### Microsoft Excel

-   Structured tables and calculated columns
-   Operational KPI calculations
-   PivotTables and PivotCharts
-   Interactive slicers
-   Dashboard design and reporting

### Microsoft Power BI

-   Data modelling with a service-orders fact table and supporting
    dimension tables
-   DAX measures for operational KPIs
-   KPI cards and interactive charts
-   Branch, Service Type and Status slicers

## Key Results

  KPI                                               Result
  ------------------------------------------ -------------
  Total service orders                                 400
  Completed service orders                             295
  Pending service orders                               105
  Completion rate                                   73.75%
  Overdue pending orders                               101
  On-time completed orders                             191
  Late completed orders                                104
  On-time completion rate                           64.75%
  Total service cost                           \$53,516.46
  Average service cost per completed order        \$181.41
  Average customer rating                             3.55
  Unassigned pending orders                             11

## Main Findings

1.  **Pending backlog:** 105 orders remained pending, including 101
    overdue orders as of the reporting date.
2.  **On-time performance:** 191 of 295 completed orders were on time,
    giving an on-time completion rate of 64.75%.
3.  **Unassigned work:** 11 pending orders had no driver assignment and
    should be reviewed during dispatch planning.
4.  **Branch comparison:** BR003 had the highest completed count (80)
    and lowest pending count (20). BR002 had the highest pending count
    (30).
5.  **Monthly demand:** October had the highest order volume, with 238
    orders, compared with 85 in September and 77 in November.

These results are descriptive findings from a synthetic dataset. They
identify areas for further investigation and do not establish the causes
of late service or demonstrate geographically optimised routes.

## Recommended Operational Actions

-   Review overdue pending orders regularly and prioritise by due date
    and customer commitment.
-   Resolve unassigned pending orders by checking driver, vehicle and
    capacity availability.
-   Investigate late completions by branch, service type and workload.
-   Compare branch workloads and capacity before reallocating work.
-   Use monthly demand trends to support resource planning.
-   Review low customer ratings alongside late completions and service
    exceptions.

## Repository Structure

``` text
Service_Operations_Supply_Chain_Project/
├── Data/
│   └── Synthetic_Service_Operations_Data.xlsx
├── Excel/
│   └── Service_Operations_Excel_Analysis.xlsx
├── PowerBI/
│   └── Service_Operations_Supply_Chain_Analysis.pbix
├── Documentation/
│   ├── Project_Summary.pdf
│   └── Business_Findings.pdf
└── README.md
```

The filenames above describe the intended contents. If your local files
have different names, keep your actual filenames when uploading.

## How to Explore the Project

1.  Read `Documentation/Project_Summary.pdf` for the project scope and
    methodology.
2.  Read `Documentation/Business_Findings.pdf` for the KPI results and
    recommendations.
3.  Open the Excel workbook to explore the PivotTables, KPI calculations
    and interactive dashboard.
4.  Open the Power BI `.pbix` file in Power BI Desktop to explore the
    data model, measures, visuals and slicers.
5.  Refer to the synthetic source dataset in the `Data` folder.

## Limitations

This is an independent learning and portfolio project built with
synthetic data. The analysis is intended to demonstrate data
preparation, reporting, dashboarding and operational KPI interpretation.
It is not a live dispatch system, a route optimisation model or evidence
of experience using a specific fleet-management platform.

------------------------------------------------------------------------

**Project type:** Independent portfolio project\
**Reporting period:** September--November 2026\
**Tools:** Microsoft Excel, Microsoft Power BI
