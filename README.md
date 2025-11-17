# Network-Discovery
quick script to automate detection of devices on your local network, works cross-platform

# Network Device Discovery

Scans local network for devices, grabs hostnames, MAC addresses, and open ports. Works on Windows and Linux.

## Usage

```bash
python network_discovery.py
```

Prompts for network range (default /24) and custom ports. Leave blank to use defaults.

## Output

Shows IP, hostname, MAC, and open ports. Saves timestamped report to `network_scan_YYYYMMDD_HHMMSS.txt`.

No dependencies needed - uses standard Python libraries.
