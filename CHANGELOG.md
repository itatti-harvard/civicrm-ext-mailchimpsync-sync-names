# Changelog

## 1.0.1 — 22 September 2026

Maintenance release. No functional changes to the extension.

- Release workflow: updated `actions/checkout` to v7 and replaced the third-party `softprops/action-gh-release` action with the built-in `gh release upload`, since the organisation's Actions policy only allows GitHub-owned actions.
- Dependabot: GitHub Actions updates are now grouped into a single PR per run.

## 1.0.0 — 02 February 2026

- Initial release. Populates Mailchimp `FNAME` and `LNAME` merge fields for subscribed members when the Mailchimpsync data sync runs with `with_data=1`.
