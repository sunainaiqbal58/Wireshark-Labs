# 🔒 HTTP & HTTPS Analysis

## Overview

HTTP and HTTPS are application-layer protocols used for web communication.

Wireshark can capture both protocols, allowing us to compare encrypted and unencrypted traffic.

---

## Display Filters

HTTP

```text
http
```

HTTPS

```text
tls
```

---

## Key Difference

| HTTP                  | HTTPS             |
|------                 |-------            |
| Data is not encrypted | Data is encrypted |
| Port 80               | Port 443          |

---

## Why It Matters

Understanding HTTP and HTTPS traffic helps explain how secure web communication works and why encryption is important.

---

## Summary

Comparing HTTP and HTTPS traffic is a practical way to understand secure communication on modern networks.
