# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a static website for Cybersol, a Solana validator service. The site is hosted on GitHub Pages at cybersol.xyz.

## Project Structure

- `index.html` - Main landing page
- `brij.html` - Additional page
- `coming.html` - Coming soon page
- `CNAME` - GitHub Pages custom domain configuration
- Image assets: `logo.png`, `CyberSol.png`, `Frame1.png`

## Development Commands

This is a simple static HTML website with no build process, package manager, or dependencies.

### Local Development
To view the site locally, open any HTML file directly in a web browser or use a simple HTTP server:
```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (if available)
npx http-server
```

### Deployment
The site is automatically deployed via GitHub Pages when changes are pushed to the main branch.

## Architecture

This is a minimal static website:
- Plain HTML/CSS without frameworks
- No JavaScript functionality
- Inline CSS styling
- Direct image references
- External links to Twitter and Stakewiz

## Key Information

- Domain: cybersol.xyz (configured via CNAME)
- Primary purpose: Landing page for Cybersol Solana validator
- Validator address: 8N4nic4yCUbHf82FCJfM51XjRDhhFA6C2ghiPfZLjAkL