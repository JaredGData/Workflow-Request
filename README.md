Warehouse Ticket Insights — Real Job Analysis (Fully Anonymised)

A Power BI dashboard that breaks down ticket activity across warehouses — showing who’s requesting the most work, when tickets peak, and how performance shifts by warehouse, week, and time of day.  This report helps give a quick, visual overview of operational workload and lets you slice the data by month, warehouse, and more.

This dashboard reflects the type of analysis I do in my job, but the dataset here is fully anonymised for privacy.

Key Insights

1. Monthly Volume Trends
- Monthly completed tickets remain relatively stable, with the highest month reaching 154 and the lowest around 106.
- This suggests consistent demand rather than seasonal spikes.
- The total requests analysed = 800.

Operational implication:
Staffing levels can remain stable, with slight increases during peak days or months.

2. Day-of-Week Performance
- Early-week days (Monday–Thursday) show the highest number of completed tickets.
- Friday has a noticeable drop in volume.

Operational implication:
Workload is front-loaded, so scheduling more staff early in the week may improve response times.
Fridays may require attention to ensure queues don’t roll over into the next week.

3. Owner Performance (Task Handlers)
(Names replaced for privacy)
- Top Performer 1 handles the highest volume (134 tickets), significantly above the team average.
- Top Performers 2–5 also show strong throughput (≈50–100 tickets).
- Several owners complete fewer than 5 tasks, indicating either limited shifts or low engagement.
- Average time to accept/complete varies greatly:
- Some owners accept tasks immediately but take longer to complete.
- Others accept slowly but complete efficiently.

Operational implication:
- Identify top performers to model best practices.
- Investigate owners with long accept times—may indicate system notifications, prioritisation issues, or staffing gaps.
- Consider rebalancing workload distribution.

4. Requester Activity (Who is submitting tickets)
(Names removed)
- Requesters vary widely—from high-frequency submitters (70–80 tickets) down to occasional users (1–5 tickets).
- A small group of requesters drive the majority of incoming volume.

Operational implication:
Provide targeted training to high-volume requesters to reduce incorrect submissions.
Identify workflows frequently coming from “super-users” and explore automation.

5. Warehouse Distribution
- Warehouse SYD1 has the highest ticket output (~379).
- ADL1 closely follows (~329).
- HZ-L1 has significantly fewer (~92).

Operational implication:
- Larger or busier sites may need more workflow support or improved automation.
- Lower-volume warehouses may need process standardisation or training.

6. AM/PM Patterns
- AM requests dominate (~63%).
- PM requests account for ~37%.

Operational implication:
- The busiest period is the first half of the day.
- Allocate more staff or monitoring resources during morning hours.

7. Week-of-Month Insights
- Weeks 2–4 are the busiest (each ~180–190 tickets).
- Week 1 is significantly lighter (~74 tickets).
- Week 5 shows minimal activity (depending on calendar month).

Operational implication:
- Mid-month is the operational peak; plan staffing and SLA targets accordingly.

🛠 Technical Features of the Report
- Dynamic slicers (warehouse, month, day)
- Custom sorting (DayName sorted by weekday number)
- Matrix tables for granular breakdown
- Bar charts for volume and performance
- Line charts for trend behaviour
- Donut visual for AM/PM segmentation
- Anonymised dataset for safe sharing



