# GitHub Pages Project Plan

## Core Sequence (Must Do In Order)
1. **Repository Decision**: Create public repo (free GitHub Pages requirement)
2. **Enable GitHub Pages**: Settings > Pages > Deploy from main branch  
3. **Test Default URL**: Verify site works at `username.github.io/repo-name`
4. **DNS Configuration Choice**: Replace Hostinger A record with GitHub's IPs OR create CNAME
5. **Custom Domain Setup**: Add `baines.org.uk` in GitHub Pages settings + create CNAME file
6. **HTTPS Activation**: Enable "Enforce HTTPS" after domain propagates

## Key Learning Concepts
7. **DNS Propagation**: Understand 15min-48hr delay for domain changes
8. **GitHub Pages Deployment**: Changes take 1-5 minutes to go live after push
9. **Repository Visibility**: Public repo required for free custom domains

## Optional Enhancements (Any Time After Step 6)
10. **Development Workflow**: Test local-to-live change process
11. **Basic Styling**: Add CSS when ready to improve appearance
12. **Additional Pages**: Expand beyond single index.html

## Critical Decisions You'll Make
- **A Record vs CNAME**: A records give more control (recommended)
- **Repository Name**: Affects initial URL structure  
- **HTTPS Timing**: Don't enable until domain fully propagates