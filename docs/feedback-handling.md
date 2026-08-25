# How feedback is handled

## Who reads it

Reports are read by **Shopping Companion**, the maintainer of this beta. There is
no support team and no ticketing system behind this repository; a report goes
directly to the person who can change the code.

The repository is monitored through GitHub notifications. Issue forms place new
reports in the triage inbox; a reopened report is returned there during review.
The maintainer aims to triage security, privacy, installation, and page-breaking
reports first, and other reports within five working days. The first human reply
is the acknowledgement. These are response targets for the beta, not a
guaranteed service level.

## Where reports live

| Channel | Visibility |
| --- | --- |
| Issues in this repository | Public and searchable, permanently, including after they are closed |
| [Private vulnerability reporting](../../security/advisories/new) | Visible only to you and the maintainer until resolved |

There is no email address for this beta. That is deliberate: publishing must not
depend on running a mail service. If one is added later it will be stated here
and on the website's privacy page.

Administrative inquiries that can be public use the administrative issue form.
There is not yet a private channel for other administrative inquiries, so do
not submit one that requires confidential details. Security, privacy, and
personal-data problems must use private vulnerability reporting.

## What we ask you not to send

Amazon account details, order numbers, delivery addresses, payment information,
or an uncropped screenshot showing any of them. None of it helps reproduce a
problem, and issues here are public.

## Priority

1. **Security or privacy** — handled first, ahead of any other work, and stated
   in the release notes for the version that fixes it.
2. **Cannot install, or the extension breaks the page** — handled next, because
   it blocks use entirely.
3. **Wrong comparison or wrong annotation** — treated as a correctness problem.
   Please include the search you used, since results differ by query.
4. **Accessibility** — treated as a correctness problem, not a preference.
5. **Everything else** — scope questions, suggestions, and improvements.

The reporter's choice describes impact; it does not set priority. The maintainer
confirms priority during triage so that a public form cannot create its own
escalation.

## Status and the feedback loop

Every open report has one public status label:

1. `status: needs triage` — received, but not yet assessed;
2. `status: waiting for reporter` — a specific answer or reproduction detail is needed;
3. `status: planned` — accepted and linked to the private engineering backlog;
4. `status: in progress` — work has started;
5. `status: resolved` — shipped, answered, or otherwise concluded.

Triage records the type, confirmed priority, and disposition. Accepted product
work is tracked in the private engineering repository without copying personal
information. The public issue remains the user's source of truth. When work is
complete, the maintainer posts the release version or explains the outcome,
invites the reporter to verify where practical, applies `status: resolved`, and
closes the issue. Duplicate reports remain linked to the canonical issue so the
original signal is not lost.

## Retention

Public issues are kept as long as this repository exists, as the record of what
was reported and what changed. Private reports are kept while the issue is being
handled and afterwards as a private record of the fix.

## Removing something you sent

Ask in the report itself, or open a new issue saying what to remove. A public
issue you filed can be edited or deleted. Content already quoted in a fix or a
release note may be summarised instead of removed outright, and you will be told
which applies to your request.

## What this repository is not

It holds no source code, no website, no downloads, and no release packages. It
carries feedback, and the information needed to send it.
