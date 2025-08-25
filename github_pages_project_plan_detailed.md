# GitHub Pages Website Project Plan

## Project Goal
Get a basic website live at baines.org.uk using GitHub Pages, with the ability to modify and publish changes.

## Phase 1: Repository Setup & Basic Site
- [X] Create a new GitHub repository for your website
  - [x] Name it something like `baines-website` or `personal-site`
  - [x] Initialize with README
  - [X] Make it public (required for free GitHub Pages)
- [X] Clone repository to your local machine
- [ ] Create basic HTML structure
  - [ ] Create `index.html` with "Hello World, David Here." message
  - [ ] Add basic HTML structure (DOCTYPE, html, head, body tags)
  - [ ] Test locally by opening in browser
- [ ] Commit and push initial files to GitHub
- [ ] Verify files appear in GitHub web interface

## Phase 2: Enable GitHub Pages
- [ ] Access repository settings on GitHub.com
- [ ] Navigate to "Pages" section in settings
- [ ] Configure source (usually "Deploy from a branch" > "main")
- [ ] Wait for initial deployment (usually 2-10 minutes)
- [ ] Test site at the GitHub Pages URL (will be something like `username.github.io/repository-name`)
- [ ] Verify "Hello World, David Here." displays correctly

## Phase 3: Custom Domain Setup
- [ ] Add custom domain in GitHub Pages settings
  - [ ] Enter `baines.org.uk` in custom domain field
  - [ ] Wait for DNS check (may show warning initially)
- [ ] Create CNAME file in repository root
  - [ ] File should contain just: `baines.org.uk`
  - [ ] Commit and push this file
- [ ] Configure DNS at Hostinger
  - [ ] Replace current A record (`145.14.151.52`) with GitHub's IPs:
    - `185.199.108.153`
    - `185.199.109.153` 
    - `185.199.110.153`
    - `185.199.111.153`
  - [ ] Or create CNAME record pointing to `username.github.io`
- [ ] Wait for DNS propagation (15 minutes to 48 hours)
- [ ] Test `baines.org.uk` loads your site

## Phase 4: HTTPS Setup
- [ ] Enable "Enforce HTTPS" in GitHub Pages settings
- [ ] Wait for SSL certificate provisioning (can take up to 24 hours)
- [ ] Test `https://baines.org.uk` works
- [ ] Verify automatic redirect from HTTP to HTTPS

## Phase 5: Development Workflow
- [ ] Test the modify-and-publish process:
  - [ ] Make a small change to index.html locally
  - [ ] Commit the change
  - [ ] Push to GitHub
  - [ ] Wait for deployment (usually 1-5 minutes)
  - [ ] Verify change appears on live site
- [ ] Document your workflow for future reference

## Phase 6: Enhancements (Optional)
- [ ] Add basic CSS styling
- [ ] Add favicon.ico
- [ ] Create additional pages (about.html, contact.html)
- [ ] Add basic navigation
- [ ] Test mobile responsiveness

## Key Learning Checkpoints
- [ ] **DNS Understanding**: Can explain how A records work
- [ ] **Git Workflow**: Comfortable with local changes → commit → push → live site
- [ ] **GitHub Pages Mechanics**: Understand deployment triggers and timing
- [ ] **Domain Management**: Know where to make DNS changes for your domain

## Troubleshooting Checklist
- [ ] Know how to check DNS propagation (tools like whatsmydns.net)
- [ ] Understand GitHub Pages deployment status
- [ ] Know how to check browser cache issues
- [ ] Understand difference between repository visibility and Pages access

## Success Criteria
- ✅ Site visible at baines.org.uk
- ✅ Can make changes locally and see them live within 5 minutes
- ✅ HTTPS working properly
- ✅ Understand the complete workflow from code to live site

## Resources to Bookmark
- GitHub Pages Documentation
- DNS propagation checker tools
- Your Hostinger DNS management panel
- GitHub repository settings page