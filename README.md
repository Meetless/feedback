# Meetless Feedback

Public feedback tracker for [Meetless](https://meetless.com) — the change control plane for product delivery.

## How to submit feedback

Click **[New Issue](../../issues/new/choose)** and pick a template:

- **Bug Report** — something is broken or not working as expected
- **Feature Idea** — suggest an improvement or new feature
- **Complaint** — something is frustrating, slow, or feels wrong

Or just open a blank issue if none of these fit.

## How we triage

Every issue goes through this lifecycle:

| Label | Meaning |
|-------|---------|
| `bug` / `idea` / `complaint` | **Type** — set automatically from the template |
| `accepted` | Confirmed and prioritized for work |
| `in-progress` | Actively being worked on |
| `done` | Shipped |
| `wont-fix` | Reviewed and decided not to address |
| `duplicate` | Already tracked in another issue |

Severity labels (`severity:critical` through `severity:low`) are added during triage.

## What happens next

Once an issue is marked `accepted`, our team picks it up, creates a fix or feature in our private repo, and links the PR back here. When the PR merges, the issue gets closed with a comment explaining what shipped.

You'll get GitHub notifications at every status change if you're subscribed to the issue.

## License

This repository is for feedback and discussion only. No source code is distributed here.
