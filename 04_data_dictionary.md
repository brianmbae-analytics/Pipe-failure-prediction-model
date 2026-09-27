# Project 4 — Pipe Failure Prediction
Each row represents a pipe asset. The target is failure_within_90_days.
- pipe_id: unique asset ID
- diameter_mm: diameter
- material: pipe material
- installation_year: installation year
- age_years: age in 2026
- length_m: pipe length
- operating_pressure_m: operating pressure head
- soil_type: surrounding soil
- elevation_m: elevation
- previous_failures: historical failures
- leakage_incidents: historical leakage incidents
- annual_rainfall_mm: long-term annual rainfall
- recent_rainfall_mm: recent rainfall
- maintenance_count_24m: maintenance events in previous 24 months
- failure_within_90_days: target (0/1)
- failure_risk_score: synthetic underlying risk score
- risk_category: Low/Moderate/High/Very High
