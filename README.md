# Port Operations Analytics Dashboard

**Power BI · Data Analytics · Business Intelligence**

An interactive Power BI dashboard developed during my internship at **Marsa Maroc – Port of Nador** (15 June to 15 July, 2025) to analyze vessel stays, port calls, berth occupancy, and port activity.

## Architecture

The project follows a data analysis workflow, from raw Excel files to an interactive dashboard.

```mermaid
flowchart TD
    A["Excel Data Sources<br/>Escales · MouvementsNavires · TypesNavires"]
    B["Data Preparation<br/>Power Query"]
    C["Data Modeling<br/>Tables & Relationships"]
    D["Analytics<br/>DAX Measures & KPIs"]
    E["Interactive Dashboard<br/>Power BI"]

    A --> B --> C --> D --> E

    style A fill:#EAF2FF,stroke:#4776B9,color:#183153
    style B fill:#E9F7F0,stroke:#39966A,color:#174D36
    style C fill:#F1ECFF,stroke:#8060C5,color:#38245F
    style D fill:#FFF4E5,stroke:#D99A35,color:#704710
    style E fill:#FCEEF1,stroke:#C76C83,color:#642D3B
```

## Dashboard Preview

![Dashboard Preview](screenshots/dashboard.png)

**Key insights and features:**
- Vessel stays and port calls.
- Average stay duration and berth occupancy.
- Activity analysis by month and year.
- Vessel distribution by type and designation.
- Interactive filters for dynamic exploration.

## Data Model

![Data Model](screenshots/data-model.png)

## Tools & Technologies

`Power BI` · `Power Query` · `DAX` · `Microsoft Excel`

