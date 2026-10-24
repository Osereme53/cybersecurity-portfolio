Assignment 4: Security Log Analysis and Risk Assessment

Overview

This project involved exploring security log data, creating a dashboard visualization, and documenting observations and potential security risks.

Objectives

* Examine security-related log records.
* Create a visualization to summarize log data.
* Present the results in a dashboard.
* Document observations and assess potential risks.

Tools Used

* Elasticsearch
* Kibana
* Security log data
* Dashboard visualizations

Methodology

1. Accessed the log analysis environment.
2. Explored available log fields and selected a message keyword field for visualization.
3. Configured a vertical bar chart to display the count of log records.
4. Added the visualization to a dashboard.
5. Captured a screenshot of the dashboard for evidence.
6. Prepared a written explanation and risk assessment based on the available information.

Results

A dashboard visualization was created to display the distribution of log records by message keyword. A screenshot was captured as evidence of the completed visualization.

The security significance of individual events should be assessed using the actual log contents, timestamps, source information, and event context. A chart alone does not confirm that an attack occurred.

Risk Assessment

Potential risks in a log monitoring environment include:

* Suspicious activity going undetected because of inadequate monitoring.
* Important events being overlooked due to incomplete or noisy logs.
* Delayed incident response when alerts are not reviewed promptly.
* Insufficient visibility when logs lack useful contextual information.

These are general risks to investigate, not confirmed incidents from this exercise.

Recommendations

* Monitor security logs regularly.
* Investigate unusual patterns using the underlying event records.
* Configure useful alerts for relevant suspicious activity.
* Ensure timestamps and important event fields are available.
* Review dashboard visualizations periodically.

Lessons Learned

This exercise provided practical experience with log visualization, dashboard configuration, security reporting, and the importance of investigating event context before drawing conclusions.

Scope

The analysis was limited to the available lab data and the visualization created during the exercise.