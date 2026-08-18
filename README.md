# Shopping Companion — beta feedback

This repository exists for one thing: collecting feedback on the **Shopping
Companion** Chrome beta, a local-first extension that compares the Amazon UK
search results already loaded in your page.

It holds no source code, no website, and no download packages. The extension
itself is distributed from the beta website.

## Report something

| What | Where |
| --- | --- |
| A bug, or something that looks wrong | [Open a bug report](../../issues/new?template=bug.yml) |
| Something unusable with a keyboard, screen reader, magnification, or contrast | [Open an accessibility report](../../issues/new?template=accessibility.yml) |
| A question about the beta, install, or scope | [Ask a question](../../issues/new?template=question.yml) |
| A security or privacy problem | [Report it privately](../../security/advisories/new) — please do not open a public issue |

Issues here are **public and permanent**. Do not paste your Amazon account
details, order numbers, delivery addresses, or payment information — none of it
is needed to reproduce a problem. If you attach a screenshot, crop or blur
anything personal first.

## What to include

The extension's popup shows a version and a build identity, for example
`v0.3.0 • a1b2c3d4e5f6`. Copy both into the form. They tell us exactly which
package you are running, which is usually the difference between a report we can
act on and one we cannot.

## How reports are handled

[`docs/feedback-handling.md`](docs/feedback-handling.md) states who reads
reports, how they are prioritised, how long they are kept, and how to have
something you sent removed.

## Scope

The beta works only on Amazon UK search-results pages at
`https://www.amazon.co.uk/s*`, and only on the results already loaded in the
page. It does not cover Amazon's full catalogue, other Amazon sites, other
retailers, or any other kind of page. Reports about anything outside that scope
will be closed as out of scope, with an explanation.
