# Security Policy

Security is core to Opus Growth. We manage advertising accounts on behalf of our
customers, so we hold ourselves to a high bar.

## How we protect your accounts

- **Official OAuth only.** We never see or store your platform password. Access is
  granted through Google / Meta / LinkedIn OAuth and can be revoked by you at any time.
- **Encrypted at rest.** Access & refresh tokens are stored encrypted.
- **Preview + confirm.** Every write action shows a dry-run preview and applies only
  after your explicit confirmation. The AI can never change an account on its own.
- **Budget guardrails.** Budget increases are capped per change.
- **Audit log.** Every change is recorded.
- **HTTPS everywhere**, strict security headers (HSTS, CSP, X-Frame-Options).

## Reporting a vulnerability

If you believe you've found a security issue, please email
**security@opus-growth.com** (or support@opus-growth.com). Include steps to reproduce
and any relevant details. Please do **not** open a public issue for security reports.

We aim to acknowledge reports within **48 hours** and to keep you updated through
resolution. Responsible disclosure is appreciated and credited (with your permission).
