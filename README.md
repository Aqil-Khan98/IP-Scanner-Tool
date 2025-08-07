# IP Conflict Checker (PowerShell)

This is a simple PowerShell script designed to detect possible IP address conflicts on your local network using the ARP table.

### 📌 Features

- Scans your local ARP table using `arp -a`
- Extracts IP addresses from ARP entries
- Detects and highlights duplicate IPs (potential conflicts)
- Color-coded console output for better readability

### 🛠️ How It Works

The script:
1. Runs `arp -a` to retrieve current ARP table.
2. Parses the output and extracts all IP addresses.
3. Groups the IPs and identifies any duplicates.
4. Displays any potential IP conflicts found.

### ⚡ Usage

1. Open PowerShell as Administrator.
2. Run the script:

```powershell
.\IP-Conflict-Checker.ps1
