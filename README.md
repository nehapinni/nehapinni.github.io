# Personal Website - Networks Project

## Website Access
**URL:** https://nehapinni.com

The website is also accessible at:
- https://www.nehapinni.com
- https://nehapinni.github.io

## Project Overview
This project involved creating a personal website using GitHub Pages with Jekyll, registering a custom domain, configuring DNS records, and implementing HTTPS encryption.

### Part 1: Website Creation
- Forked existing Jekyll repository: https://github.com/academicpages/academicpages.github.io
- Customized content and design for personal website
- Deployed using GitHub Pages

### Part 2: Custom Domain Configuration
- Registered custom domain: nehapinni.com
- Configured DNS records with A records pointing to GitHub Pages IP addresses:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153
- Set up CNAME record for www subdomain pointing to nehapinni.com
- Added CNAME file to repository root containing "nehapinni.com"

### Part 3: HTTPS Implementation
- Used Let's Encrypt through GitHub Pages automatic certificate provisioning
- Enabled "Enforce HTTPS" option in GitHub Pages settings
- Verified SSL certificate functionality and secure connection

## Technical Details
- **Hosting:** GitHub Pages
- **DNS Management:** Cloudflare (set to DNS-only mode)
- **SSL Certificate:** Let's Encrypt (via GitHub Pages)
- **Framework:** Jekyll

## Development Notes
- Used AI assistance (Claude) for troubleshooting DNS configuration and HTTPS setup issues, specifically due to initial problems with Cloudflare proxy settings that prevented SSL certificate generation - the proxy was intercepting requests and GitHub couldn't verify domain ownership


