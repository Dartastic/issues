# Security policy

## Reporting a vulnerability

**Do not file a public issue for security-sensitive reports.**

Email [security@dartastic.io](mailto:security@dartastic.io) with:

- A description of the vulnerability
- Steps to reproduce (or a proof of concept)
- The Dartastic component(s) affected
- Your contact info so we can follow up

We'll acknowledge within 1 business day and aim for a fix or
mitigation timeline within 3 business days for high-severity
issues.

## What's in scope

- Any Dartastic-shipped package on `pub.dartastic.io`
- The engine binary (`libdartastic_engine.*`)
- `symbolizer.dartastic.io` and `pub.dartastic.io` services
- `dartastic.io` website and dashboard
- Hosted observability customer boxes

## What's not in scope (please don't report these)

- Findings on third-party services we depend on — report those
  upstream (Grafana, GitHub, Cloudflare, etc.)
- Reports on infrastructure we don't operate (your own apps using
  our packages — those are yours to secure)
- Social-engineering attacks on Dartastic employees

## Recognition

We're happy to credit security researchers in our release notes
when a fix ships, if you'd like the attribution. Let us know in
your initial report.
