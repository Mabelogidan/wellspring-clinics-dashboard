# Wellspring Clinics Performance Dashboard

- **Type:** Personal training project — Power BI
- **Program:** TechCrush Data Analytics Program
- **Tools:** Power BI (Power Query, DAX, interactive visuals)

## Overview

As part of my transition into data analytics, I built an interactive Power BI dashboard analyzing patient visit data across Wellspring Clinics' network. The goal was to take a raw dataset through the full analytics workflow — cleaning, modeling, visualizing, and interpreting — to answer a real operational question: **how is the clinic network performing across locations and departments, and where are the opportunities to improve?**

## Process

1. **Data cleaning** — Imported the raw visits dataset into Power Query, handled data types (dates, durations, currency), and removed inconsistencies before loading into the model.
2. **Measures** — Built core DAX measures for Total Visits, Total Revenue, Distinct Patients, and Average Wait Time (converted from raw duration into minutes for readability).
3. **Visualization** — Designed a single-page dashboard with a KPI summary row, six supporting charts, and slicers (Clinic, Department, Year) for interactive filtering.
4. **Iteration** — Refined chart types based on data shape (e.g., bar charts for multi-category comparisons, donut chart for a binary follow-up rate), fixed formatting issues (currency symbol rendering, font consistency), and cleaned up the file structure before finalizing.

## Key Insights

- **Visit volume varies by ~20% across clinics** — Wuse leads with 78 visits, while Lugbe trails at 65, suggesting differences in demand, staffing, or accessibility worth investigating further.
- **Revenue isn't evenly distributed across departments** — Pediatrics and Immunization generate the highest revenue (₦0.5M each), while Antenatal trails at ₦0.38M despite likely requiring more resource-intensive visits — a possible signal for a pricing or capacity review.
- **Follow-up rate sits at 54.74%** — nearly half of patients don't return for a follow-up visit, representing a meaningful gap in continuity of care.
- **Transaction volume dipped sharply between June and September** (from 59 down to 9) before recovering in October — this pattern warrants further investigation into whether it reflects seasonality, staffing gaps, or a data collection issue.

## What I'd Explore Next

- Cross-reference the June–September dip with staffing records or external events to identify a root cause
- Segment follow-up rate by department to see if certain services have stronger patient retention than others
- Build a cohort view tracking whether first-time patients convert to repeat visits over time

## Skills Demonstrated

Data cleaning 
· DAX measure creation 
· KPI design 
· Chart selection & data storytelling 
· Dashboard layout & interactivity 
· Business interpretation of data
