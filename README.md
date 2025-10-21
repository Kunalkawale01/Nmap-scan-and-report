## Author
**Kunal Kawale**  
Cybersecurity Intern  
Task 1 — Scan Your Local Network for Open Ports 

# Nmap-scan-and-report
perform an authorized scan of your local network to identify hosts and open TCP/UDP ports, note running services and versions when possible, and produce a concise report listing findings and recommended mitigations.

1. Copy the repository into Termux home (or download the ZIP and unzip).
2. Make the main script executable: 
    chmod +x run_scan_and_generate_report.sh

3. Run the script: 
    ./run_scan_and_generate_report.sh

Follow prompts. The script attempts to auto-detect your network (via termux-wifi-connectioninfo or getprop) and will ask for a CIDR if detection fails (e.g., 192.168.1.0/24).
