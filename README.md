
# SeqLoom — NGS Sample Quality Monitoring

**Quality Today · Better Insights Tomorrow**

## Project Overview

SeqLoom is an NGS sample quality monitoring and assessment project
that brings together quality metrics from different stages of an
NGS workflow.

It uses SQL Server to store and combine quality metrics and Power BI
to present sample-level quality information through an interactive
dashboard.

## Project Objectives

- Organize NGS quality metrics in a structured database.
- Combine FastQC, trimming and alignment metrics.
- Assess samples using provisional quality assessment rules.
- Identify samples that may need further investigation.
- Present the results through an interactive Power BI dashboard.

## Tools and Technologies

- SQL Server
- T-SQL
- Power BI
- DAX
- FastQC
- NGS quality control concepts

## Workflow

1. Collect quality metrics from NGS samples.
2. Store the metrics in SQL Server tables.
3. Combine the metrics using SQL views.
4. Apply provisional QC assessment rules.
5. Summarize sample assessments.
6. Visualize the results in Power BI.

## Dashboard Features

- Total sample count
- Samples requiring review
- Average unique mapping percentage
- QC assessment category overview
- Unique read mapping by sample
- Sample-level QC details
- Sample ID filtering

## Important Note

The assessment categories use provisional project rules.
They are intended for quality monitoring and learning purposes,
not as validated clinical thresholds or diagnostic decisions.
A QC flag does not automatically mean that a sample is unusable.

## Project Author

Navya Thalathoti
