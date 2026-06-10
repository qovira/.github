# Security Policy

Thanks for helping keep Qovira and its users safe. This policy is the org-wide default for every repository in the [`qovira`](https://github.com/qovira) organization — `@qovira/theme`, `@qovira/ui`, the website, and anything else that doesn't ship its own `SECURITY.md`.

## Reporting a vulnerability

**Please report security issues privately — do not open a public issue, discussion, or pull request for a suspected vulnerability.** Public reports expose users before a fix is available.

Use either channel:

- **Email** [security@omnilium.com](mailto:security@omnilium.com). This is the reliable channel and works for every repo.
- **GitHub private vulnerability reporting** — on a repo that has it enabled, open the **Security** tab and choose **Report a vulnerability**. This opens a private advisory only the maintainers can see.

If in doubt, email us — we'd much rather hear about something that turns out to be harmless than miss something that isn't.

A useful report usually includes:

- The repository or package affected, and the version or commit you tested against.
- A description of the issue and its impact — what an attacker could do.
- Steps to reproduce, ideally a minimal proof of concept.
- Any relevant environment details (browser, runtime, configuration).

You don't need all of this to reach out; send what you have and we'll follow up.

## Supported versions

Qovira is **pre-1.0**, and the API and surface are still moving. We support **only the most recently published release** of each package — please reproduce against the latest version before reporting. We don't back-port fixes to older `0.x` releases; the fix ships in the next release instead. (Once a package reaches 1.0 we'll publish a supported-versions table here.)

## What to expect

- **Acknowledgement** within **3 business days** of your report.
- An initial **assessment** — whether we can reproduce it and how we rate the severity — within **10 business days**.
- **Updates** as we work toward a fix, and credit for your report once a fix is released, unless you'd prefer to stay anonymous.

We practice **coordinated disclosure**: we'll work with you on a fix and a release, and we ask that you give us reasonable time to ship it before any public write-up. We'll always tell you when a fix is out.

## Safe harbor

We won't pursue or support legal action against anyone who reports a vulnerability in good faith — testing only against your own data and accounts, avoiding privacy violations and service disruption, and giving us a reasonable chance to respond before going public. If you're unsure whether something is in scope or in bounds, ask first at [security@omnilium.com](mailto:security@omnilium.com).
