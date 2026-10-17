# IPCO volleyball tournament

Persian, right-to-left company volleyball tournament page with the completed 15-team draw, team rosters, 29-match schedule, bracket, offline audio, and Excel export.

## Published site

https://barbodmazlaghani.github.io/ipco-volleyball/

## Portal image

`assets/ipco-volleyball-banner.png`

Use the published site URL as the destination when users click the image in the company portal.

## Updating the official page

1. Open the published page and use the administrator controls to enter results.
2. Select **دریافت HTML به‌روز**.
3. Replace `index.html` in this repository with the downloaded HTML and commit the change.
4. GitHub Pages republishes the site. Verify the public URL after deployment.

Browser-only edits affect that browser. The official shared site changes after committing the updated HTML.

## Network

Visitors need outbound HTTPS access to `barbodmazlaghani.github.io` on port 443. Access to `github.com` alone does not confirm access to this separate host. No inbound ports need to be opened on the company server for this GitHub-hosted site.
