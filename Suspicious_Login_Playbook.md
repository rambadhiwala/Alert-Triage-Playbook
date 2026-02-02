# Suspicious Login – Triage Playbook

## 1. Alert Overview
Triggered by anomalous login behavior (geo, device, time).

## 2. Triage Flow
1. Validate user identity
2. Review login source
3. Compare with historical behavior
4. Check MFA status

## 3. Evidence Checklist
- IP address & geo-location
- Device fingerprint
- MFA logs
- Failed login attempts

## 4. Escalation Criteria
- MFA bypass
- Impossible travel confirmed
- Repeated login failures

## 5. Containment Actions
- Force password reset
- Revoke active sessions
- Enforce MFA re-registration
- Block source IP

## 6. Notes
Common in credential stuffing and ATO cases.
