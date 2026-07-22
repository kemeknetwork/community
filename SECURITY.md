# Security Policy

## Reporting a vulnerability

**Do not open a public discussion for a security vulnerability.** A public
thread tells attackers before it tells us.

Email **[security@kemek.com](mailto:security@kemek.com)**.

Include what you have:

- The affected product, site, or endpoint (a URL is ideal).
- Steps to reproduce, or a proof of concept.
- What an attacker gains — data read, data written, access escalated.
- The version or date you tested, if you know it.
- A suggested fix, if you have one.

You do not need a polished report. A rough description of something that looks
wrong is worth sending.

## What to expect

- **Acknowledgement within 3 business days.** If you hear nothing after that,
  assume the mail went astray and send it again.
- An assessment and a remediation plan once we have reproduced the issue.
- Credit in the fix announcement if you want it, and none if you don't.

## Scope

This repository contains no product code, so reports here are about KeMeK
Network products and services generally. In scope:

- The KeMeK web properties: `kemek.com`, `kemek.net`, `kemek.org`, and their
  subdomains.
- Hosted products and tools served from those domains.
- Authentication, session handling, and access control on any of the above.
- Accidental exposure of secrets, credentials, or customer data.
- Injection, XSS, CSRF, SSRF, and path traversal in anything we serve.
- Supply-chain risk in dependencies we ship to users.

Out of scope:

- Third-party services we resell but do not operate. Report those to the
  vendor; tell us too, and we will chase it.
- Findings from automated scanners with no demonstrated impact.
- Social engineering, physical access, and denial of service by volume.

## Safe harbour

Test only against your own accounts and data. Do not access, modify, or retain
anyone else's information; do not degrade service for other users; stop as soon
as you have confirmed a vulnerability exists.

Research conducted in good faith within those limits is welcome, and we will
not pursue action over it. Tell us before you tell anyone else, and give us a
reasonable window to ship a fix.
