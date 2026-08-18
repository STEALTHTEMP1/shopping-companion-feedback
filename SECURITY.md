# Security and privacy reporting

## Report privately, not in a public issue

Use [GitHub's private vulnerability reporting](../../security/advisories/new) on
this repository. The report is visible only to you and the maintainer until it is
resolved, so nothing sensitive is exposed while a fix is prepared.

Please use it for anything that could put a tester at risk, including:

- the extension reading, storing, or transmitting something the privacy notice
  says it does not;
- any network request originating from the extension;
- code executed from a remote source;
- a published package whose checksum does not match the one on the download
  page, or a download served from somewhere other than the official site;
- a way to make the extension damage, hijack, or misrepresent the retailer page.

## What to include

The extension version and build identity from the popup, what you did, what
happened, and why you believe it is a security or privacy problem. A proof of
concept is welcome but never required.

## What happens next

Security and privacy reports are handled ahead of all other work. You will get an
acknowledgement, a decision on whether it is confirmed, and — if it is — a fix
and a note in the release notes for the version that carries it. If a published
package is affected it is withdrawn, and the withdrawal is stated publicly rather
than done silently.

## Scope

This is a beta extension with no backend, no accounts, and no telemetry. There is
no server-side attack surface to test, and this repository holds no product code.
Reports about GitHub itself, the hosting platform, or Amazon belong to those
parties rather than here.

## Please do not

Test against other people's accounts, attempt to disrupt the download site, or
publish a confirmed issue before a fix is available.
