# Security Policy

We take the security of the LokaLaku Trip project seriously. We appreciate the help of the community and security researchers in responsibly reporting vulnerabilities. All reports will be reviewed and addressed as soon as possible.

## Supported Versions

As this is a continuously updated static website, we only provide security support for the latest version available on the `main` branch.

| Version | Supported          |
| ------- | ------------------ |
| `main`  | :white_check_mark: |

## 🛡️ Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub Issues.**

If you discover a security issue, please report it privately via email to:

**`lokalakutrip@gmail.com`**

Please include as much information as possible in your report to help us reproduce and validate the issue.

### Information to Include

* A detailed description of the vulnerability found.
* Clear steps to reproduce the vulnerability.
* The potential impact of the vulnerability.
* Suggested fixes or mitigations (if you have them).

## Our Commitment

After receiving a vulnerability report, we will strive to:

1.  Acknowledge receipt of your report as soon as possible (usually within 48 hours).
2.  Confirm the existence of the vulnerability and provide an estimated timeline for a fix.
3.  Notify you when the fix has been released.
4.  Provide credit or thanks to the reporter in the release notes (with your consent).

## Scope

This policy applies to the code within this repository.

### In Scope:

* Cross-Site Scripting (XSS) vulnerabilities.
* Use of third-party libraries (e.g., jQuery, Bootstrap) with known vulnerabilities.
* "Mixed Content" issues (loading HTTP assets on an HTTPS page).

### Out of Scope:

* Vulnerabilities in third-party services we use (e.g., Formspree, Vercel, Google Fonts). These issues should be reported directly to the service provider.
* Spam or Phishing reports not directly related to the code in this repository.
* Best practice suggestions (e.g., HTTP header configurations) that do not indicate an active vulnerability.

Thank you for helping keep LokaLaku Trip secure.
