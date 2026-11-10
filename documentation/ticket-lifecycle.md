# Ticket Lifecycle

## Standard workflow

1. **Create:** Receive a report through the service desk form, phone, email, or approved channel.
2. **Log:** Create a unique ticket ID and record the requester, contact method, device, symptoms, and time reported.
3. **Categorize:** Select the most appropriate service/category and issue type.
4. **Assess:** Determine impact and urgency, then assign a priority using the documented matrix.
5. **Assign:** Allocate the ticket to an available technician or support queue.
6. **Investigate:** Confirm the symptoms, gather relevant details, and perform authorized first-line checks.
7. **Resolve or escalate:** Apply a verified fix where possible. Escalate when access, expertise, permissions, or risk requires it.
8. **Validate:** Ask the requester to confirm service has been restored, where practical.
9. **Close:** Record the resolution, relevant timestamps, and closure reason.

## Status definitions

| Status | Meaning | Next action |
|---|---|---|
| Open | Ticket has been logged and is awaiting work | Triage and assign |
| In Progress | A technician is actively investigating | Record checks and updates |
| Pending | Work is waiting on the requester, vendor, or another dependency | Record what is awaited and follow-up date |
| Resolved | A solution or workaround has been applied | Validate and follow closure process |
| Closed | Work is complete and the record is finalized | Reopen only under the defined process |
| Escalated | Ticket has been transferred to a higher support tier or specialist | Provide a complete handover |

## Minimum documentation standard

Use clear, factual language. Record:

- What the user reported.
- The affected user, device, application, or service.
- Scope and business impact.
- Error messages and time observed.
- Checks performed and their results.
- Changes made, with authorization where required.
- Current status, owner, and next action.
- Resolution and user confirmation, if obtained.

Never record passwords, authentication codes, or unnecessary personal information.

## Example ticket note

**User report:** Employee cannot access the shared team folder.

**Checks:** Confirmed the user can access the network; checked whether the issue affects other users; verified the mapped path and captured the exact error.

**Outcome:** Access issue requires permissions review by the file-services team.

**Status:** Escalated.

**Next action:** File-services team to validate group membership and folder permissions.
