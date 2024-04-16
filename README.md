![](img/image0.png)

## TLDR PowerBI Dashboard [link]([https://app.powerbi.com/groups/me/reports/ac167198-815a-4753-ae73-669a4913ed77/ReportSectionfc58e66b54837de74490?experience=power-bi](https://app.powerbi.com/view?r=eyJrIjoiZGIwMzg3MjgtZjg1Yy00OWUwLWE3Y2YtNzc0NjUzNWQyZDJjIiwidCI6ImUzYjYyMmQ1LWNhOTQtNDVmYy05OGM4LTcyNGI4MTczOTMxMCJ9&pageName=ReportSectionfc58e66b54837de74490))

**MISSION:** Use the data contained within the sent Excel file to create
a Power BI data model using industry best practices to solve our
simulated consulting project business challenge and to create a demo
report.

-   Recreate the legacy report from the Excel file screenshot.

-   We will evaluate your understanding of the DAX language and modeling
    in creating these metrics.

-   Consider that the client will add additional data and therefore
    needs time-intelligence calculations.

-   Design an additional 1--2-page report demo highlighting both data
    analysis and report design.

1.  **LEGACY REPORT**

![](img/image1.png)

2.  **EXPLORATORY DATA ANALYSIS**

We found several issues in the report upon exploring the data:

-   First, the primary metric (Percent Customers Returned within 90 Days
    of **FIRST** Purchase) did not actually have any positive hits for
    the first two years. For 2001 and 2002, none of the customers
    purchased again the same year, let alone the same quarter.

    -   ![](img/image2.png)

    -   ![](img/image3.png)

> **Corrective Action:** After sharing and discussing this finding with
> the client, it was decided to update the metrics to a more generic
> calculation of monthly customers and the count and percentage who
> returned within 90 days (inclusive) and within 3 months (exclusive) of
> any given monthly purchase. So instead of counting repeat customers
> from their **First month**, we count repeat customers for **Each
> month.**
>
> **Because of this, the updated report shows no repeat customers in
> 2001 and 2002:**

![](img/image4.png)

-   Secondly, the updated calculations for 90D and 3M repeat customers
    show that quarterly repeat customers did not occur until April 2003:

![](img/image5.png)

-   Finally, to make a comparison with the quarterly metrics, we added a
    Lifetime (LT) Repeat Customer metric to see if a customer in any
    given month or year purchased again (without and upper time limit):

![](img/image6.png)

3.  **SALES PERFORMANCE**

![](img/image7.png)

-   Total vs Last Year Sales with %-Change KPI card.

-   Total vs Last Year Profits with %-Change KPI card.

-   Sales and Profit line/bar chart with time-intelligent drill-down.

-   Sales by Region to inform marketing efforts appropriate to each
    region.

-   Top 10 Products to identify high revenue items for inventory
    balancing.

-   Top 10 Customers to identify high-value outreach targets.

-   Year and Region slicers to investigate historical and categorical
    data.


**P3 Adaptive Consulting Team**

**Name**: Ahmed Rashed **Title**: Principal BI Consultant **Date**:
April 15, 2024
