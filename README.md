📝 Exercise Steps

The full module is ~90 min. For a 60 min class, pick 3–4 tasks.

1. Warm-up (5 min)

Recap: basics of traffic flow theory and loop detectors.

Students open the notebook.

2. Data Exploration (10 min)

Inspect dataset structure (time span, variables, sensors, incidents).

Compute basic stats: mean speeds, flows, lane utilization.

3. Fundamental Diagram (15 min)

Use flow vs. density (or occupancy proxy = 1/speed).

Identify:

Free-flow branch (linear slope ≈ free-flow speed).

Capacity point (maximum flow).

Congested branch (negative slope ≈ backward wave speed).

Compare diagrams across days.

4. Travel Time Analysis (10 min)

Compute average travel time (Method 3 or reference).

Plot by time-of-day (06:00–21:00).

Compare peak vs off-peak and day-to-day variability.

5. Speed-Contour Plots (10 min)

Plot time × space matrix of speeds.

Identify congestion build-up and anomalies.

Compare days with vs. without incidents.

6. Shockwave Theory (10 min)

Use contour plots to estimate shockwave speed.

Select two times & locations where the congestion front moves.

Compute propagation speed and direction (upstream or downstream).

7. Sensor Correlation Analysis (10 min)

Compute correlations between consecutive sensors.

Explore lead/lag to see how congestion propagates.

Relate to the idea of information flow upstream.

8. Incident Integration (10 min)

Overlay incident data on contour plots.

Compare with congestion dynamics.

Discuss: can incidents be detected automatically from loop data?

9. Wrap-up (10 min)

Groups share one key insight.

Guided discussion:

How does the empirical FD compare with theory?

At what density/flow does breakdown occur?

How do incidents appear in contour plots vs. recurrent congestion?

What are shockwave speeds during breakdown/recovery?

How does sensor correlation explain congestion dynamics?

What data issues (NaNs, outages, scatter) affect interpretation?

What are implications for traffic management?
