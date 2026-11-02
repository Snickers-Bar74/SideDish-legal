# SideDish legal launch checklist

Prepared 28 October 2026. Existing public policy, terms and deletion wording was
preserved. Source/deployment behavior and operating promises need release review.
See [the shared checklist](../LAUNCH-CHECKLIST.md).

## Prepared

- Repository moved intact to `D:\Prosjekter\Legal\SideDish-legal`.
- Existing privacy, terms, deletion pages, fonts and GitHub Actions deployment retained.
- Deployment now stages only public pages/assets, keeping maintainer checklists out of the published website.
- Repository name and published URL casing retained as `SideDish-legal`.

## Policy inventory to verify against the release

The existing privacy policy describes accounts/guest sessions and Google sign-in;
profiles/photos; live tables and game content; feedback/screenshots and safety
reports; RevenueCat subscriptions and Apple/Google payments; AdMob rewarded ads;
Sentry diagnostics; opt-in first-party analytics and PostHog EU counts; and a
Discord relay for non-safety feedback. These are policy claims, not a new audit
or live-service verification by this task.

## Resolve before launch

- [ ] Confirm the operator name, postal address and mailbox already in the policies.
- [ ] Add purpose-specific lawful bases and confirm provider contracts, processing locations and international-transfer safeguards.
- [ ] Verify the opt-in/consent behavior for both analytics destinations, ads and iOS tracking against the signed release and store disclosures.
- [ ] Verify policy promises in actual scheduled jobs/settings: feedback 14 days, safety reports 30 days, closed tables normally 30 days or up to two years with active Pro, analytics 90 days. Define diagnostics, logs, backups and support/provider records too.
- [ ] Test deletion for email and guest accounts, uploads, hosted tables, player history, analytics, reports, Discord-forwarded feedback and provider records. Record any legal retention exceptions precisely.
- [ ] Test subscription cancellation, restore, renewal/refunds and deletion with an active subscription. The deletion page correctly says deletion does not cancel billing.
- [ ] Check the 16+ self-attestation, store ratings and distribution countries. A stored confirmation is not independent age verification.
- [ ] Verify report/block/moderation flows, contact availability and handling of game-generated content.
- [ ] Complete applicable privacy rights and restrictions/portability/consent-withdrawal information; review the existing terms and retention exceptions.
- [ ] Verify production service configuration, privacy manifests/SDK declarations and store forms. Do not rely on an old STATUS snapshot as release evidence.
- [ ] Review the GitHub Actions diff, publish when approved, then check live HTTPS links on mobile/desktop without signing in.

## Release record

Not yet reviewed for launch by this task. Record app version, legal commit, URLs, date and reviewer here.
