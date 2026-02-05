# Nmap Scan Findings for demo.testfire.net

## Target Information
*   **Target:** `demo.testfire.net`
*   **Resolved IP Address:** `[65.63.137.117]`
*   **Date of Scan:** `[2023-10-27]`
*   **Time of Scan:** `[12:02 IST]`

## Scan 1: Basic SYN Scan with Service Version Detection
*   **Command Executed:** `sudo nmap -sS -sV demo.testfire.net`
*   **Output File:** `nmap_syn_service_scan_testfire.txt`

### Open Ports and Services (Example Output - actual results may vary):
| Port | State | Service | Version |
|------|-------|---------|---------|
| 80/tcp | open  | http      | Apache Tomcat/Coyote JSP           |
| 443/tcp| open  | ssl/https?|                                    |
|8080/tcp| open  | http      | Apache Tomcat/Coyote JSP engine 1.1|

## Scan 2: Operating System Detection
*   **Command Executed:** `sudo nmap -O demo.testfire.net`
*   **Output File:** `nmap_os_detection_testfire.txt`

### OS Details (Example Output - actual results may vary):
*   **OS Guess:** `[Oracle Virtualbox (98%), QEMU (94%)]`
*   **OS CPE:** `[cpe:/o:oracle:virtualbox cpe:/a:qemu:qemu]`


## Scan 3: Aggressive Scan
*   **Command Executed:** `sudo nmap -A demo.testfire.net`
*   **Output File:** `nmap_aggressive_scan_testfire.txt`

### Key Findings from Aggressive Scan (Example Output - actual results may vary):
*   `[ HTTP title: TestFire.net - Home]`
*   `[ Http-server-header: Apache-Coyote/1.1]`


## Raw Scan Outputs (for reference)
*   [Link to `nmap_syn_service_scan_testfire.txt`]
*   [Link to `nmap_os_detection_testfire.txt` ]
*   [Link to `nmap_aggressive_scan_testfire.txt` ]
