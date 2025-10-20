# Basic firewall


This configuration is a basic example of a firewall on nftables with:
- `inet filter` table;
- `drop` policy for incoming traffic;
- named counters;
- HTTP/HTTPS/DNS permissions;
- SSH restriction by subnet with a limit;
- drop logging.
