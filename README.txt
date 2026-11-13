OLIVE'S ENCHANTED LINK HUB
==========================

CONTENTS
- index.html: full mobile-friendly link hub page
- overlay.html: compact transparent overlay for streaming software
- assets/olive-logo.png: your supplied logo
- assets/olive-banner.jpg: your supplied banner

LINKS INCLUDED
- Twitch: https://www.twitch.tv/oliveoakwren
- TikTok: https://www.tiktok.com/@olive_oak_wren
- Discord: https://discord.gg/ghk3QMKpS
- TeePublic: https://www.teepublic.com/lic/3a-a_sdt3qQ

PREVIEW LOCALLY
1. Extract the ZIP.
2. Open index.html in a browser to preview the link hub.
3. Open overlay.html to preview the compact overlay.

IMPORTANT ABOUT STREAMING LINKS
The buttons in a browser overlay are clickable in the browser page, but viewers watching a livestream generally cannot click buttons embedded in the video itself. Use the hub URL in your profile/panels and add a QR code to the stream after the hub is published.

PUBLISH FOR FREE WITH GITHUB PAGES
1. Create/sign in to a GitHub account.
2. Create a new public repository, for example: olive-enchanted-links.
3. Upload index.html, overlay.html, and the entire assets folder (keep the folder structure).
4. In the repository, open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch; select main and /(root), then Save.
6. GitHub will provide a public site URL after publishing. Your hub will be at that URL and the overlay at URL/overlay.html.

ADD TO OBS
1. Add a Browser Source.
2. Enter the published overlay URL ending in /overlay.html.
3. Set width to 460 and height to 190 as a starting point.
4. Enable refresh browser when scene becomes active if desired.

ADD TO TIKTOK LIVE STUDIO
1. Add a Link source and paste the published overlay URL ending in /overlay.html.
2. Resize and position it. TikTok LIVE Studio's Link source behavior can vary by version; if it refuses the page or strips styling, use the hub URL in your profile and show a QR code/image overlay instead.

QR CODE
A QR code should point to the final published hub URL, not a temporary/local file path. Generate it once GitHub Pages gives you the final URL, then add the QR image as an OBS image source and a TikTok LIVE Studio image source.

EDITING LINKS
Open index.html and overlay.html in a text editor and replace the relevant href URL if any social link changes. Keep the asset folder alongside both HTML files.
