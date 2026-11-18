# Security Policy — SUNTEK Technology Co., Ltd.

## Reporting a Vulnerability

**Please DO NOT open a public GitHub issue for security vulnerabilities.**

If you discover a potential security issue in any SUNTEK SDK, system service, firmware
interface, or sample application (such as exposed credentials, privilege escalation, or
cryptographic flaws), please report it privately to:

- **Email**: [support@suntekai.com](mailto:support@suntekai.com)
- **Subject Format**: `[SECURITY] <Repository / Model> - <Brief Summary>`

We aim to acknowledge all security reports within **48 business hours** and coordinate
remediation before public disclosure.

## Supported Hardware & Software Security Practices

- Standard SDK calls bind to preinstalled vendor system services (`com.sdkapi.sdkapiservice`, etc.) using the customer's own commercial or Google Play application signature.
- When elevated `android.uid.system` privileges are required on unmodified factory firmware, SUNTEK provides either an installable vendor-signed `SuntekBridgeService.apk` or an internal unsigned-APK signing portal for authorized accounts.
- SUNTEK never distributes platform signing private keys (`.pk8`) in public repositories.

---

Copyright © 2026 SUNTEK Technology Co., Ltd.
