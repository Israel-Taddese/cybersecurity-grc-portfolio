# Sanitization Checklist

Before publishing anything publicly, remove or replace:

- Passwords, API keys, tokens, secrets, and environment variables.
- Real account numbers, broker data, balances, order IDs, and financial screenshots.
- Personal emails, phone numbers, addresses, school login details, and student IDs.
- Employer/client names, private work documents, internal trackers, and private screenshots.
- TryHackMe or Hack The Box flags, credentials, challenge answers, and prohibited walkthrough details.
- Real IP addresses, hostnames, cookies, session tokens, and browsing data from packet captures.
- Professor names, grading screenshots, answer keys, internal rubrics, and private course materials.
- Raw logs that expose local usernames, machine names, file paths, or internal configuration.
- Any code or wording that supports unauthorized access, ad injection, click fraud, credential misuse, or platform abuse.

## Project-Specific Notes

### OpenClaw / Docker
Remove `.env` files, tokens, local paths, machine identifiers, debug logs, account names, and proxy details.

### GRC / Vendor Risk
Use fictional vendors, fictional requestors, fictional tools, and recreated assessment templates.

### Cybersecurity Labs
Use only authorized lab environments. Redact target IPs when needed and avoid publishing flags or exploit chains.

### Trading System
Present as risk architecture only. Do not publish live performance claims or sensitive account information.

### Browser Extension
Publish only the ethical educational version. Do not include unauthorized ad replacement or monetization logic.
