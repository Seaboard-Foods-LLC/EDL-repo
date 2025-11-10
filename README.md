# 🛡️ SBD Threat Blocklists

## Files

- **`blocklist.txt`**  
  A plain-text list of IP addresses identified as malicious or suspicious. Intended for use in firewalls and security platforms that support IP-based blocking.

- **`domains.txt`**  
  A plain-text list of domains associated with threats such as malware, phishing, or command-and-control activity. Suitable for use in DNS filtering, anti-spyware profiles, or URL filtering systems.

## Usage

These lists can be integrated into security tools such as Palo Alto Networks firewalls via External Dynamic Lists (EDLs), or used in custom automation workflows for threat prevention.

> ⚠️ Ensure you validate and sanitize the lists before deployment to avoid false positives or unintended blocks.
