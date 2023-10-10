# Grafana Dashboards Repository

This repository contains custom Grafana dashboard configurations tailored for monitoring service levels and SRE (Site Reliability Engineering) metrics.

## Dashboards

1. **Service Levels Dashboard (`grafana-servicelevels-dashboard.json`)**:
    - This dashboard provides insights into the service levels of the application or system. It includes metrics like SLIs, SLOs, and error rates.

2. **SRE Dashboard (`grafana-sre-dashboard.json`)**:
    - Tailored for SRE teams, this dashboard provides an overview of the system's reliability, error rates, and other key SRE metrics.

## Importing Dashboards into Grafana

To import any of the above dashboards into your Grafana instance:

1. Download the desired `.json` file from this repository.
2. Open Grafana in your web browser.
3. Navigate to **Dashboards** > **Manage**.
4. Click on the **Import** button.
5. Use the **Upload .json File** option to select and upload the downloaded `.json` file.
6. Follow the on-screen prompts to complete the dashboard import.
