
## Findings (short)
- Local VM IP 10.0.2.15 is up. Scans show [replace with your actual finding — e.g., filtered ports or open ports].
- Evidence is saved in the `nmap/`, `wireshark/` and `screenshots/` folders.

## Evidence files
- `nmap/nmap_filtered_reason.txt`
- `nmap/nmap_filtered_common_ports.txt`
- `wireshark/capture_local.pcap`
- `screenshots/nmap_terminal.png`
- `screenshots/wireshark_icmp.png`

## Short remediation suggestions
1. If hosts are intentionally filtered, document policy and mark hosts exported as “filtered”.
2. If services should be reachable, allow scanner IP or open specific ports and restrict by source IP.
3. Check host-based firewall and router ACLs.

## Author
- Name: Balamurugan
- Date: $(20+10)
