# Google Sheets Setup Guide

1. Create a Google Sheets workbook named `IT_Service_Desk_Management`.
2. Import `ticket-management/sample-tickets.csv` into a tab named `Tickets`.
3. Import `asset-management/asset-register.csv` into a tab named `Asset Register`.
4. Create tabs named `Dashboard`, `SLA Tracker`, and `Knowledge Base`.
5. Use filters on the Tickets tab and freeze the header row.
6. Use pivot tables or `COUNTIF` / `COUNTIFS` formulas to summarize ticket status, priority, and category.

## Example formulas

Assuming the Tickets sheet has:
- Priority in column J
- Status in column L
- Category in column G

Open ticket count (exclude resolved and closed):
```excel
=COUNTIFS(Tickets!L:L,"<>Resolved",Tickets!L:L,"<>Closed",Tickets!A:A,"<>")
```

Count P1 tickets:
```excel
=COUNTIF(Tickets!J:J,"P1")
```

Count tickets by status (replace `A2` with a status label):
```excel
=COUNTIF(Tickets!L:L,A2)
```

Count tickets by category (replace `A2` with a category label):
```excel
=COUNTIF(Tickets!G:G,A2)
```

## SLA tracker note

The sample CSV contains a mixture of resolved and unresolved tickets. Add formulas only after choosing whether your exercise measures elapsed clock time or business hours. The included training policy describes both the targets and the limitations.
