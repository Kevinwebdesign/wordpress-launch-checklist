# WordPress Launch Checklist

Used by **Kevin Web Design Hong Kong** ([@kevinwebdesignhongkong](https://github.com/kevinwebdesignhongkong)).

---

## 1. Domain and DNS

- [ ] Domain is not expired
- [ ] DNS A record points to correct server
- [ ] CNAME for `www` is correct
- [ ] `www` and non-`www` redirect to one canonical version
- [ ] TTL is reasonable
- [ ] MX records are correct
- [ ] SPF record is set
- [ ] DKIM is set
- [ ] DMARC is set
- [ ] DNS propagation checked

## 2. SSL and HTTPS

- [ ] SSL certificate is valid
- [ ] Certificate covers `www` and non-`www`
- [ ] Auto-renewal is enabled
- [ ] HTTPS is forced
- [ ] No mixed content
- [ ] HSTS considered
- [ ] SSL expiry reminder is set

## 3. WordPress Core Settings

- [ ] Site URL is correct
- [ ] Home URL is correct
- [ ] Permalinks are set
- [ ] Timezone is correct
- [ ] Language is correct
- [ ] Date and time format are correct
- [ ] Admin email is correct
- [ ] Default content removed
- [ ] Search engine visibility is enabled after launch
- [ ] Reading settings are correct

## 4. Users and Permissions

- [ ] No default `admin` username
- [ ] Strong passwords enforced
- [ ] Two-factor authentication enabled
- [ ] Least privilege applied
- [ ] Subscriber / Editor / Author roles checked
- [ ] Inactive users removed
- [ ] Login attempt limit enabled
- [ ] Audit log enabled

## 5. Plugins and Themes

- [ ] All plugins updated
- [ ] Unused plugins deleted
- [ ] Theme is updated
- [ ] Child theme used if needed
- [ ] Plugin conflicts checked
- [ ] License keys activated
- [ ] No abandoned plugins
- [ ] Backup plugin configured

## 6. Performance and Caching

- [ ] Page caching enabled
- [ ] Browser caching enabled
- [ ] Object caching considered
- [ ] CDN configured
- [ ] Images compressed
- [ ] WebP / AVIF used
- [ ] Lazy loading enabled
- [ ] Fonts optimized
- [ ] CSS / JS minified
- [ ] Database cleaned
- [ ] LCP under 2.5s
- [ ] INP under 200ms
- [ ] CLS under 0.1

## 7. SEO

- [ ] SEO plugin configured
- [ ] Titles and meta descriptions set
- [ ] XML sitemap generated
- [ ] `robots.txt` correct
- [ ] Canonical URLs correct
- [ ] Open Graph tags set
- [ ] Schema markup added
- [ ] 301 redirects for old URLs
- [ ] 404 page checked
- [ ] Google Search Console connected
- [ ] Bing Webmaster Tools connected
- [ ] GA4 installed
- [ ] Google Business Profile linked if needed

## 8. Forms and Notifications

- [ ] Contact form works
- [ ] Email notifications received
- [ ] WhatsApp button works
- [ ] Thank-you page works
- [ ] Spam protection enabled
- [ ] Privacy policy linked
- [ ] GDPR / PDPO considerations checked
- [ ] File upload limits checked if needed

## 9. Security

- [ ] Security headers set
- [ ] File permissions correct
- [ ] Database prefix changed from `wp_`
- [ ] File editing disabled in dashboard
- [ ] XML-RPC limited or disabled
- [ ] WAF enabled
- [ ] Malware scan completed
- [ ] Login URL protected if needed
- [ ] Security plugin configured
- [ ] PHP version supported

## 10. Backup and Restore

- [ ] Automatic backups enabled
- [ ] Database backups enabled
- [ ] File backups enabled
- [ ] Offsite backup configured
- [ ] Backup encryption enabled
- [ ] Restore tested
- [ ] Backup retention policy set

## 11. Post-Launch Monitoring

- [ ] Uptime monitoring enabled
- [ ] SSL expiry monitoring enabled
- [ ] Performance report scheduled
- [ ] Error logs checked
- [ ] Update notifications enabled
- [ ] Monthly health report enabled
- [ ] Emergency contact defined

---

Maintained by **Kevin Web Design Hongkong**.
