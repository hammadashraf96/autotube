# Security policy

AutoTube is a private tool its operator uses to make videos for their own YouTube channels. This repository holds only
its public landing page (privacy policy, terms, channel stats). No credentials, user data or pipeline code live here.

## Reporting a vulnerability

Please report security problems **privately**:

1. Go to the **Security** tab of this repository and choose **Report a vulnerability**
   (GitHub private vulnerability reporting). Only the operator can see the report.
2. If that is not possible, open an issue that says only "security contact requested", without any details,
   and the operator will reach out.

Please do not post exploit details, tokens or personal data in public issues.

What to expect: an acknowledgement within 7 days, and a fix or explanation as soon as the problem is understood.
If credentials could be affected, they are revoked and reissued first.

## Scope

- This landing page (`hammadashraf96.github.io/autotube`): content, links, the published stats files.
- How AutoTube handles its Google sign-ins and uploads, as described on the page's Security tab.

Out of scope: YouTube and Google services themselves (report those to Google), and social-engineering attempts.

## How AutoTube is kept safe

Summarised on the landing page's [Security tab](https://hammadashraf96.github.io/autotube/#security):
least-privilege YouTube permissions per channel, credentials kept only on the operator's machine with owner-only file
permissions, secret scanning on every commit and site publish, private-by-default uploads with an audit log,
digest-pinned container images, a disk failsafe, and encrypted off-machine backups.
