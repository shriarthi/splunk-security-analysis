# Splunk Security Log Analysis

## Objective
Analyze authentication logs using Splunk to detect suspicious login activity.

## Data Source
Simulated authentication logs ingested into Splunk as CSV data.

## Use Cases
- Failed login detection
- Brute force attack detection

## SPL Queries
See `searches/` directory for detection logic.

## Findings
- Multiple failed login attempts observed from same IPs
- Potential brute-force behavior identified

## Security Impact
Repeated failed logins indicate possible credential attacks.

## Conclusion
Monitoring authentication logs in Splunk helps detect early-stage attacks.
