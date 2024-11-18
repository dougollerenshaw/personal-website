# Personal Website

This repository contains the source code for my personal website at doug.ollerenshaw.us.

## Site Architecture

- **Hosting**: Netlify (free tier)
- **DNS Management**: Cloudflare (free tier)
- **Domain**: Managed through Squarespace Domains
- **Source Control**: GitHub (this repository)

## Local Development

To work on this site locally:

```bash
git clone https://github.com/dougollerenshaw/personal-website.git
cd personal-website
```

The site is currently a simple static HTML page. To make changes:
1. Edit `index.html`
2. Commit and push to GitHub
3. Netlify automatically deploys changes

## Image Management

Photos are stored in `assets/images/`

## Service Configuration Notes

### Netlify
- Auto-deploys from GitHub main branch
- No build configuration needed (static site)

### Cloudflare
- Manages DNS for doug.ollerenshaw.us
- Provides SSL/HTTPS
- Proxies traffic for security and performance

## Future Additions
- Blog functionality can be added using a static site generator
- Images can be moved to dedicated hosting if needed

## Maintenance

To update the site:
1. Make changes locally
2. Test by opening index.html in a browser
3. Commit and push to GitHub
4. Netlify automatically deploys changes

Remember: DNS changes can take 24-48 hours to fully propagate.