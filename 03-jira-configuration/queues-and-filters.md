# Queues and Filters

## What are queues?
Queues in Jira Service Management help service teams organise and monitor work items that need attention. A queue may show tickets based on criteria such as status, priority, assignee, request type, or team.

## Example queue views
- All open incidents.
- Unassigned incidents.
- High-priority incidents.
- Tickets assigned to me.
- Pending customer response.
- Recently resolved tickets.

These are suggested queue ideas, not a claim that these queues have been configured.

## Filters
Filters save searches so users can return to a defined set of work items. A filter may use fields such as project, issue type, status, priority, or assignee.

## Example JQL
```jql
project = IT AND issuetype = Incident ORDER BY created DESC
```

```jql
project = IT AND assignee = currentUser() AND statusCategory != Done
```

JQL field names and issue type values should be checked against the actual Jira instance.

## Validation
- Confirm the user has permission to view the relevant tickets.
- Run the search and verify the results.
- Save a filter only if the feature is available and appropriate.
- Capture a screenshot if a queue or filter is actually created.
