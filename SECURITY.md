# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| V13 (current) | ✅ Active |
| V12 | ✅ Security patches only |
| V11 and below | ❌ No longer supported |

## Reporting a Vulnerability

If you discover a security vulnerability in this project, **please do not open a public GitHub issue**.

Instead, email the maintainer directly:

📧 **moekyawaung@engineer.com**

Please include:
- A description of the vulnerability
- Steps to reproduce
- Potential impact assessment
- Any suggested fix (optional)

You can expect an acknowledgement within **48 hours** and a full response within **7 days**.

## Security Considerations

This is a static HTML portfolio. Key points:
- **No backend** — no server-side code, no database
- **No user data stored** — contact form is client-side only (no data persisted)
- **External resources** — Google Fonts, Cloudinary images, Google Maps embed
- **No cookies** — no tracking, no analytics, no session management

## Disclosure Policy

We follow responsible disclosure. Once a fix is available, we will:
1. Release a patched version
2. Credit the reporter in CHANGELOG.md (with permission)
3. Publish a brief advisory if the issue is significant
