# Pro Meetings — public site

Privacy policy and support pages for the Pro Meetings iOS app, hosted on GitHub Pages.

These URLs are referenced from two places and must stay reachable:

- `Pro Meetings/Services/AppConfig.swift` — `privacyPolicyURL`, `supportURL`
- App Store Connect — the privacy policy and support URL fields

## Editing

Plain HTML, no build step. Edit and push; GitHub Pages redeploys within a minute.

To change the contact address, replace `CONTACT_EMAIL` everywhere:

```bash
grep -rl CONTACT_EMAIL . --include=*.html | xargs sed -i '' 's/CONTACT_EMAIL/you@example.com/g'
```
