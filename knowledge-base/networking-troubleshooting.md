# Knowledge Base: Basic Network Troubleshooting

**Article ID:** KB-NET-001  
**Category:** Network  
**Audience:** L1 support practice

## Scenario: User cannot access the internet

### Initial questions

- Is one user affected or are multiple users affected?
- Is the device connected by Wi-Fi or Ethernet?
- Does the user have access to internal resources?
- When did the issue begin? Is an exact error displayed?

### Safe first-line checks

1. Check whether Wi-Fi is enabled or the Ethernet cable is securely connected.
2. Confirm the device is connected to the correct approved network.
3. Check whether other authorized devices are affected.
4. On Windows, run `ipconfig /all` to inspect the IP configuration.
5. Run `ping` against an approved known destination or gateway, if permitted.
6. Run `nslookup` for an approved domain to help identify DNS issues.
7. Record command output relevant to the issue, removing sensitive details before sharing.
8. Avoid changing IP, DNS, proxy, or router settings without authorization.

### Useful Windows commands

```powershell
ipconfig /all
ping 127.0.0.1
ping <default-gateway>
nslookup example.com
tracert example.com
```

Replace placeholders with approved test values. A failed ping alone does not prove that a host is down because some networks block ICMP.

### Escalate when

- Multiple users or a site are affected.
- The device cannot obtain a valid network configuration.
- Network equipment or access-point changes are needed.
- The issue appears to involve firewall, routing, or managed DNS configuration.
