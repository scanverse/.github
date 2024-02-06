# Scanverse

Welcome to Scanverse - Your automated solution for comprehensive security scanning!

It is often a daunting task for pentesters to conduct exhaustive security scanning, especially without automation. The process of running multiple security scanning tools one after another, commonly known as binge-tool-scanning, can be time-consuming and laborious. Unless one is proficient at automating tasks, this endeavor can be quite challenging for each engagement. Enter Scanverse, a powerful automation tool designed to streamline the security scanning process, saving valuable time and effort while ensuring thorough vulnerability assessment.

## Features

- **One-Step Installation**: Easy setup process to get started quickly.
- **Multitude of Security Scanning Tools**: Executes various security scanning tools, including but not limited to nmap, dnsrecon, wafw00f, uniscan, sslyze, fierce, lbd, theharvester, amass, nikto, all under one entity.
- **Time-Saving**: Significantly reduces the time required for security scanning.
- **False-Positive Detection**: Checks for the same vulnerabilities with multiple tools to effectively identify false positives.
- **Lightweight and Efficient**: Not resource-intensive, ensuring smooth operation.
- **User-Friendly Interface**: Provides legends to indicate tests that may take longer, allowing users to skip if necessary.
- **Integration with OWASP Top 10 & CWE 25**: Identifies vulnerabilities associated with these industry standards (under development).
- **Vulnerability Classification**: Classifies vulnerabilities into critical, high, medium, low, and informational categories.
- **Comprehensive Reporting**: Generates detailed reports in a portable document format (*.pdf) with complete scan details (under development).
- **Automated Tool Deployment**: Utilizes artificial intelligence to deploy tools automatically based on identified issues (under development).
- **Metasploit Integration**: Provides on-the-run Metasploit auxiliary modules for discovering additional vulnerabilities (under development).

## Vulnerability Checks

Scanverse performs a wide range of vulnerability checks, including but not limited to:

- DNS/HTTP Load Balancers & Web Application Firewalls.
- Checks for Joomla, WordPress, and Drupal vulnerabilities.
- SSL related Vulnerabilities (HEARTBLEED, FREAK, POODLE, CCS Injection, LOGJAM, OCSP Stapling).
- Commonly Opened Ports.
- DNS Zone Transfers using multiple tools (Fierce, DNSWalk, DNSRecon, DNSEnum).
- Sub-Domain Brute Forcing (DNSMap, amass, nikto).
- Open Directory/File Brute Forcing.
- Shallow XSS, SQLi, and BSQLi Banners.
- Slow-Loris DoS Attack, LFI (Local File Inclusion), RFI (Remote File Inclusion), & RCE (Remote Code Execution).

## Architecture 
- ![](./scanversearchitecture.svg)



## Get Started

To begin using Scanverse, simply follow the installation instructions and start automating your security scanning process today.

## License

Scanverse is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! Feel free to open issues or pull requests to enhance the functionality of Scanverse.

## Contact

  For any inquiries or support, please contact [support@scanverse.com](mailto:iamanubhavgain@gmail.com).

---

Scanverse - Automating Security Scanning for Enhanced Vulnerability Detection.
