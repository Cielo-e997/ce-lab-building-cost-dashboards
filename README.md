# Lab M7.09 - Building Cost Dashboards

## What I Did
- Built an Engineering Cost Dashboard with:
  - Monthly cost trend visualization
  - Per-service cost breakdown (EC2, S3, RDS)
  - Budget utilization tracking
  - Alarm status overview
- Built an Executive Summary Dashboard designed for leadership
- Created a weekly cost report template for ongoing reporting

## Dashboard Design

### Engineering Dashboard
Designed for engineers to monitor and troubleshoot cost drivers:
- Time series view of total cost trends
- Breakdown by key AWS services
- Budget tracking with thresholds (80% warning and max limit)
- Centralized alarm visibility

### Executive Dashboard
Simplified dashboard for non-technical stakeholders:
- Month-to-date total spend
- Top service cost visibility
- Budget utilization percentage
- 30-day cost trend
- Clean and minimal layout for quick insights

## Key Findings
- Billing metrics update approximately every 6 hours
- Cost visibility improves significantly with per-service breakdown
- Budget tracking with visual thresholds helps prevent overspending
- Executive dashboards must prioritize clarity over detail

## Screenshots
- `screenshots/engineering-dashboard.png`
- `screenshots/executive-dashboard.png`

## Notes
- Alarm widget uses a placeholder ARN for demonstration purposes
- Some widgets may show "No data available" if billing metrics are not yet populated