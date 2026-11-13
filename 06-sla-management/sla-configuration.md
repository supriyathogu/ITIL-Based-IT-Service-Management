# SLA Configuration and Management

## What is an SLA?
A Service Level Agreement (SLA) documents agreed service expectations between a service provider and a customer. In service desk tools, SLA goals may measure response and resolution times against defined conditions and working calendars.

## Common SLA measures
- **Time to first response:** Time until an appropriate first response is recorded.
- **Time to resolution:** Time until the incident or request reaches the defined resolution condition.
- **Working calendar:** Defines the days and hours counted by the SLA.
- **Pause conditions:** Conditions under which the SLA clock may stop, if the policy allows.
- **Breach:** When the agreed target is missed.

## Example learning targets
The values below are hypothetical examples for learning only. They are not configured Jira targets and are not real service commitments.

| Illustrative priority | First response target | Resolution target |
|---|---:|---:|
| Critical | 15 minutes | 4 hours |
| High | 30 minutes | 8 hours |
| Medium | 4 business hours | 2 business days |
| Low | 1 business day | 5 business days |

## Configuration planning checklist
- [ ] Identify the SLA metric (response or resolution).
- [ ] Define the start condition.
- [ ] Define the goal and applicable priorities/request types.
- [ ] Select the working calendar and time zone.
- [ ] Define pause and stop conditions.
- [ ] Test with sample tickets.
- [ ] Confirm how breached or at-risk SLAs are displayed.
- [ ] Capture screenshots of the actual configuration.

## Jira note
Available SLA configuration depends on Jira Service Management plan, permissions, and project settings. This document describes the intended configuration approach; it does not claim that the example targets are active in Jira.
