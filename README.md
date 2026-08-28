# Archer — Cinematic Campaigns Landing Page

Git-backed, definitions-only landing-page content and media for Archer's public cinematic campaign experience.

The JSON is consumed by Gabriel Operator's registered `cinematic-campaigns` renderer. It contains bounded copy and asset references only; layout, CSS, security policy, anonymous preview limits, and workflow execution remain platform-owned.

```bash
node scripts/validate-landing-page.js assets/landing-page.json
```

When validating command compatibility from the persona workspace, pass the parent chat configuration as the second argument.

```bash
node scripts/validate-landing-page.js assets/landing-page.json ../../../assets/chat-config.json
```
