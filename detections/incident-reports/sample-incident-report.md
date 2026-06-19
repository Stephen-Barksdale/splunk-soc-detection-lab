# Sample Incident Report

## Incident Title

Repeated Failed Login Attempts

## Summary

A lab system generated repeated failed login events from a single source IP address. The activity may indicate password guessing or unauthorized access attempts.

## Evidence Reviewed

- Windows Event ID 4625
- Source IP address
- Target account
- Hostname
- Time range

## Initial Findings

Multiple failed authentication attempts were observed against the same account within a short time period.

## Recommended Actions

- Verify whether source IP is expected
- Confirm account owner
- Review successful logins after the failed attempts
- Check endpoint health
- Review firewall and VPN logs
- Reset password if suspicious
- Document findings in ticket/case system

## Status

Lab example only.
