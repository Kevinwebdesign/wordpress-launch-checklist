# wordpress-launch-checklist
# WordPress Launch Checklist

A practical WordPress launch checklist and GitHub Actions workflow for DNS, SSL, SEO, performance, security, forms and backups.

Maintained by **Kevin Web Design Hong Kong** ([@kevinwebdesignhongkong](https://github.com/kevinwebdesignhongkong)).

---

## Why this repo?

Launching a WordPress site is not just about clicking "Publish".

Before go-live, you need to check:

- DNS and domain settings
- SSL / HTTPS
- WordPress core settings
- Permalinks
- User roles and permissions
- Plugins and themes
- Caching and performance
- SEO basics
- Forms and email notifications
- Security hardening
- Backup and restore
- Post-launch monitoring

This repo gives you a reusable checklist and automation examples used by **kevinwebdesignhongkong** in real WordPress projects.

---

## What's inside

- [`checklist.md`](./checklist.md) — full WordPress launch checklist
- [`lighthouse-budget.json`](./lighthouse-budget.json) — performance budget example
- [`.github/workflows/launch-checks.yml`](./.github/workflows/launch-checks.yml) — GitHub Actions workflow
- [`scripts/ssl-expiry.sh`](./scripts/ssl-expiry.sh) — SSL expiry check script
- [`docs/brand-notes.md`](./docs/brand-notes.md) — how kevinwebdesignhongkong uses this checklist

---

## Quick start

1. Fork this repo.
2. Edit `checklist.md` for your project.
3. Set your site URL in GitHub Actions secrets:
   - `SITE_URL`
   - `SSH_HOST`
   - `SSH_USER`
   - `SSH_KEY`
4. Run the workflow manually or on schedule.
5. Fix issues before launch.

---

## Checklist categories

- Domain and DNS
- SSL and HTTPS
- WordPress core settings
- Users and permissions
- Plugins and themes
- Performance and caching
- SEO
- Forms and notifications
- Security
- Backup and restore
- Post-launch monitoring

See [`checklist.md`](./checklist.md) for the full list.

---

## Automation

This repo includes GitHub Actions examples for:

- Lighthouse CI performance checks
- Broken link checking
- SSL expiry checking
- Optional WP-CLI checks via SSH

Used by **Kevin Web Design Hong Kong** for WordPress launch reviews.

---

## Contributing

Pull requests are welcome. Please keep items practical and WordPress-specific.

---

## License

Code: GPLv2+  
Documentation: CC BY 4.0

---

## Need help?

Need a WordPress website launch review or maintenance plan?

Contact **kevinwebdesignhongkong**.
