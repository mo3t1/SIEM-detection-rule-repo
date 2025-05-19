SIEM Detection Rules Repository

Welcome to the SIEM Detection Rules repository — a collection of vendor-agnostic detection rules, written primarily in Sigma format, to help defenders detect suspicious and malicious activity across different environments.



📂 rules/

Detection rules organized by platform (Windows, Linux, Cloud, etc.). Each platform may have subcategories.

📂 parsers/

Contains parsing configs for log normalization tools (e.g., sysmon, auditd).

📂 tests/

Test cases (e.g. logs, payloads) to validate rules against detection engines.

📂 tools/

Helper scripts, rule formatters, or Sigma-to-SIEM converters.

🧪 Example Use Cases

Detect suspicious PowerShell usage

Alert on brute-force login attempts

Flag risky AWS IAM changes

🧰 Tooling Support

These rules are designed to work with:

Sigma CLI

Elastic Stack (via Sigma + Logstash)

Splunk (via Sigma + sigmac)

Microsoft Sentinel (via conversion)

Wazuh, Graylog, QRadar, and others

👥 Contributing

We welcome PRs! Please read CONTRIBUTING.md for guidelines.

📜 License

MIT License — use freely with attribution.

💬 Questions or Ideas?

Feel free to open an issue or contact us!
