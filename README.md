# VULNERABILITY SCANNER
by: Sr-Mxr

Description
The Vulnerability Scanner is a bash script designed to provide various security assessment functionalities, including port scanning, web vulnerability scanning, network device discovery, network traffic monitoring, activity logging, and report generation.

## Features
Port Scanning with Nmap: Scan ports on a target host using Nmap to identify open ports.
Web Vulnerability Scanning with Nikto: Perform web vulnerability scanning on a target host using Nikto.
Network Device Discovery: Display all users and devices connected to the network using arp-scan.
Network Traffic Monitoring: Monitor network traffic using tcpdump.
Activity Logging: Log activity to a file with timestamps.
Report Generation: Generate reports summarizing the scan results and activities performed.

## Usage
Clone this repository to your local machine.
Open a terminal and navigate to the repository directory.
Run the vulnerability_scanner.sh script with the following command:
bash
## Copy code

```bash
./vulnerability_scanner.sh
```

Choose an option from the menu by entering the corresponding number and pressing Enter.
Follow the prompts to provide necessary inputs for scanning or monitoring.
Review the results displayed or generated by the tool.

## Requirements
Linux operating system.
Nmap and Nikto installed for port scanning and web vulnerability scanning, respectively.
Superuser privileges for some functionalities like arp-scan and tcpdump.

## Contribution
Contributions are welcome. If you wish to enhance the script or report any issues, feel free to open an issue or submit a pull request on this repository.

## Author
Developed by Sr-Mxr.

## License
This project is licensed under the MIT License. See the LICENSE file for more information.
