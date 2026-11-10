# Simulated SLA Policy

> **Training disclaimer:** This is an illustrative policy for a portfolio project only. These targets are fictional practice values. They are not industry standards, vendor commitments, or real company SLAs.

## 1. Purpose

Demonstrate how a service desk can record response and resolution targets and identify tickets that need attention.

## 2. Definitions

- **Response time:** Time from ticket creation to the first meaningful response from support.
- **Resolution time:** Time from ticket creation to a recorded resolution.
- **Business hours:** For this exercise, Monday to Friday, 9:00 AM–6:00 PM, excluding fictional organization holidays.
- **Elapsed time:** The actual time difference between two timestamps.
- **Breach:** A target is missed according to the policy and clock rules in use.

For a simple spreadsheet exercise, use elapsed clock time unless you explicitly build business-hours calculations. State which method your dashboard uses.

## 3. Training targets

| Priority | Example response target | Example resolution target |
|---|---:|---:|
| P1 – Critical | 15 minutes | 4 hours |
| P2 – High | 30 minutes | 8 business hours |
| P3 – Medium | 4 business hours | 3 business days |
| P4 – Low | 1 business day | 5 business days |

These values are deliberately simplified for practice. Real organizations define targets based on contracts, service hours, impact, urgency, and service-specific agreements.

## 4. Tracking fields

Recommended SLA Tracker columns:

- Ticket ID
- Priority
- Created At
- First Response At
- Resolved At
- Response Target
- Resolution Target
- Response Time
- Resolution Time
- Response Result
- Resolution Result
- Notes

## 5. Spreadsheet logic

If timestamps are stored as valid date/time values:

- Response elapsed hours: `(First Response At - Created At) * 24`
- Resolution elapsed hours: `(Resolved At - Created At) * 24`

Compare the calculated duration with the relevant target after converting both values to the same unit. These simple formulas calculate elapsed clock time, not business hours.

Suggested result labels: `Within Target`, `Target Missed`, `Pending`, `Not Applicable`.

Do not mark an unresolved ticket as a breach until the target and clock rules have been applied consistently.

## 6. Good practice

- Record timestamps consistently.
- Document pauses and dependencies according to the stated policy.
- Do not alter timestamps to make performance look better.
- Report missing data as `Not Recorded`, not as a successful result.
- Explain the calculation method in the dashboard.
