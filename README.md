# 🛡️ Threat Blocklists

## blocklist.txt

A plain‑text **IP Address External Dynamic List (EDL)** containing IPv4 and/or IPv6 addresses and CIDR ranges associated with malicious or untrusted activity.  
This file is intended for **IP‑based enforcement** in Palo Alto Networks firewalls and is commonly referenced in Security Policies to block or restrict traffic based on **source or destination IP address**, independent of application or encryption.

---

## domains.txt

A plain‑text **Domain External Dynamic List (EDL)** containing fully qualified domain names (FQDNs) associated with threats such as malware, phishing, or command‑and‑control infrastructure.  
This list enables **domain‑based enforcement** using DNS resolution, TLS SNI, or hostname inspection, and is well‑suited for blocking cloud‑hosted or frequently changing threat infrastructure where IP addresses are not stable.

---

## urlblocklist.txt

A plain‑text **URL External Dynamic List (EDL)** evaluated by the **URL Filtering engine** to block web destinations based on hostname and, optionally, URL path.  
Entries may be full URLs or bare FQDNs, allowing **application‑layer (Layer 7) enforcement** and enabling granular control of web traffic, including selective blocking of specific content hosted under a domain.
