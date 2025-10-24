---
layout: docwithnav-trendz
title: Use New Metrics in ThingsBoard 
description: Step-by-step guide to use new Metrics in ThingsBoard
---

* TOC
{:toc}

Trendz allows you to use generated metrics across Trendz and ThingsBoard like regular telemetries.

## Save New Metric to ThingsBoard

To use a metric across Trendz and ThingsBoard, you first need to save it as telemetry in ThingsBoard. Trendz enables
you to convert a metric into a **Native Calculation Field**, and then use that calculation to save the metric as telemetry.

### Create Calculation Field from the Metric

You can create a calculation field from a metric by clicking **Save Calculation**.

Specify the following parameters:

1. **Calculation Name** – the name displayed in Trendz.
2. **Calculation Key** – the telemetry key used in ThingsBoard (prefixed with `_ECD_`).

Example:
If you save a calculation named **Energy Consumption Rate** with key **energy_consumption_rate**, Trendz will show a new
field called *Energy Consumption Rate*, and ThingsBoard will display telemetry with the key `_ECD_energy_consumption_rate` 
(once the refresh and reprocess jobs are configured).

Once created, the calculation field appears in the **Calculation** folder.

Before saving telemetry to ThingsBoard, verify the following parameters:

1. **Grouping Interval** – defines how data is aggregated (e.g., *HOUR* means one point per hour in ThingsBoard).
2. **Aggregation** – specifies how multiple values in the same interval are combined (e.g., *SUM* aggregates values within the same hour).
3. **Time** – defines the time range used by refresh jobs (e.g., *Last 7 Days* for daily updates).

**Recommended time settings:**

* **Today** – for minute or hourly jobs
* **Last 7 days** – for daily jobs
* **Last 14 days** – for weekly jobs
* **Last 3 months** – for monthly jobs

You can also adjust additional parameters as needed.

### Save Historical Data to ThingsBoard (Reprocess Job)

Once the calculation field is created, you can run a **Reprocess Job** to save historical data to ThingsBoard.

Steps:

1. Open the **Tasks** tab.
2. Select a time range for reprocessing.
3. Choose items to run the job on (you can apply the same calculation to all entities of the same profile).

After completion, the telemetry will appear in ThingsBoard.

### Set Up Automatic Telemetry Generation (Refresh Job)

You can automate telemetry updates using a **Refresh Job**.

Steps:

1. Click the **Jobs** button.
2. Enable *calculation result saving*.
3. Set the **start date**.
4. Define the **frequency** (how often the job runs).
5. Choose the target items (entities with the same profile).

## Use the Metric in Trendz

Once the calculation field, refresh job, and reprocess job are configured, the generated telemetry remains continuously 
updated in ThingsBoard.

You can now use the metric across both platforms.

### Use the Metric in Trendz Views

Visualize the generated metric using any Trendz widget, such as a line chart. You can also share the view with ThingsBoard.

### Predict the Metric

You can use Trendz **Prediction Models** to forecast future values of the generated metric. Learn more about prediction 
models in Trendz documentation.

### Find Anomalies in the Metric

You can detect anomalies or outages in the generated metric using **Trendz Anomaly Models**. 
Learn more about anomaly detection [here].

## Create Alerts in ThingsBoard for the Metric

Since the telemetry exists in ThingsBoard, you can create alarms based on it:

1. Open the entity profile where the calculation is created.
2. Navigate to **Alarm Rules**.
3. Select the alarm type.
4. Configure **create** and **clear** conditions.
5. Save the rule.

Whenever the calculation refresh produces values that meet the alarm conditions, an alert will be triggered.

**Example:** You can create a metric that calculates deviations from the average temperature for sensors in a building. 
If the deviation exceeds a threshold, an alarm will be triggered.

This can detect device overheating or even prevent a building fire at its origin.

## Next Steps

{% assign currentGuide = "MetricExplorer" %}{% include templates/trndz-guides-banner.md %}
