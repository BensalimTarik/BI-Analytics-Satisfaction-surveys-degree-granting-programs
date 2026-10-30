# BI Project – Student Satisfaction Analysis

🌐 Language: [Français](README.md) | English

## 1. Project Overview

This project aims to design and implement a solution for collecting, processing, and analyzing student satisfaction surveys within the **Compétences & Développement (C&D) Group**.

The solution provides insights into student satisfaction across several dimensions, including teaching quality, student support, information and guidance, logistical organization, and perceived value of training programs.

The main objective is to centralize data, automate processing workflows, and provide interactive Power BI dashboards to support academic managers and decision-makers.

## 2. Business Objectives

The project addresses six main objectives:

- **O1 – Questionnaire Design:** Create questionnaires covering predefined evaluation dimensions.
- **O2 – Automated Distribution:** Automate questionnaire distribution to eligible students.
- **O3 – Response Collection and Centralization:** Automate the collection and storage of survey responses.
- **O4 – Data Preparation:** Clean, transform, and structure data to ensure its usability.
- **O5 – Performance Monitoring:** Provide interactive dashboards displaying key performance indicators.
- **O6 – Decision Support:** Enable academic and business managers to identify trends, strengths, and areas for improvement.

## 3. Functional Scope and Business Processes

The solution is structured around four main stages.

### Stage 1 – Data Extraction and Preparation

- Extract data from the IGOR information system.
- Transfer and store data in a dedicated SQL Server database.
- Apply data quality checks and transformation rules.
- Reduce manual processing in Excel.
- Improve data standardization, reliability, and refresh traceability.

### Stage 2 – Questionnaire Design and Distribution

- Develop HTML questionnaires adapted to each school's visual identity.
- Assign a unique identifier to link each response to a specific survey and training period.
- Automate recipient selection and questionnaire distribution.
- Improve invitation tracking and reduce distribution errors.

### Stage 3 – Response Collection and Centralization

- Automate response processing using Azure Logic Apps.
- Store responses in a dedicated database.
- Validate submitted responses.
- Prevent duplicate records.
- Monitor processing errors.

### Stage 4 – Data Analysis and Reporting with Power BI

- Design interactive Power BI reports.
- Organize reports into several thematic pages.
- Implement a star-schema data model based on fact and dimension tables.
- Analyze satisfaction by school, training program, cohort, and evaluation dimension.
- Support dashboard refresh and maintenance.

## 4. Key Performance Indicators (KPIs)

The dashboards provide monitoring of the following indicators:

| KPI | Definition |
|---|---|
| Number of Responses | Number of valid responses after duplicate removal |
| Response Rate | Number of respondents / Number of invited students × 100 |
| Number of Notifications Sent | Number of invitations and reminders sent |
| Invitation Conversion Rate | Number of respondents / Number of invited students × 100 |
| CSAT | Percentage of ratings 4 and 5 on a 1-to-5 scale |
| Average Satisfaction Score | Average of valid satisfaction ratings |
| NPS | Percentage of promoters (9–10) minus percentage of detractors (0–6) |
| Satisfaction by Dimension | Percentage of satisfied responses for each evaluation dimension |
| Usable Comments Rate | Number of completed comments / Number of relevant respondents × 100 |

**Indicative targets specified in the project documentation:**
- Response rate: ≥ 70%.
- Planned notifications processed: 100%.
- Other targets are to be defined or confirmed based on the indicators and initial survey campaigns.

## 5. Data Architecture and Sources

### Data Sources

**Source 1 – IGOR / SQL Server**

Data includes:
- Student registration and student information.
- Training programs.
- Analytical dimensions.
- Current academic year.

Access to the source data is read-only, subject to the relevant authorizations.

**Source
