NEWAGE PV — WEBSITE HOSTING PACKAGE
====================================

WHAT'S IN THIS FOLDER
  index.html      -> your complete website (everything is inside this one file)
  og-image.jpg    -> the preview picture shown when the link is shared on
                     WhatsApp / Facebook / LinkedIn / Google
  robots.txt      -> tells search engines they may index the site
  sitemap.xml     -> helps Google find your page
  README-hosting.txt -> this file

HOW TO PUT IT ONLINE (any host works — Hostinger, GoDaddy, Bluehost,
Netlify, cPanel, etc.)

  1. Log in to your web hosting account.
  2. Open the "File Manager" (or connect by FTP).
  3. Go to the website root folder — usually called:
        public_html   (cPanel / Hostinger / GoDaddy)
        www           (some hosts)
        htdocs         (others)
  4. Upload ALL FOUR files into that folder, side by side:
        index.html, og-image.jpg, robots.txt, sitemap.xml
     Do NOT put them in a sub-folder. They must sit directly in the root.
  5. Point your domain (newagepv.com) at this hosting if it isn't already.
  6. Open https://www.newagepv.com  — the site should appear.

FREE OPTION (no cPanel):
  - Go to netlify.com -> "Add new site" -> "Deploy manually"
  - Drag this whole folder onto the page. It goes live instantly on a free
    web address, and you can connect newagepv.com in Site settings > Domain.

AFTER IT'S LIVE
  - Test the WhatsApp button and the QR code from a phone.
  - Submit https://www.newagepv.com/sitemap.xml to Google Search Console
    (search.google.com/search-console) so Google indexes you faster.
  - To check the share preview: paste your link in a WhatsApp chat to
    yourself — the NewAge PV card should appear.

THINGS YOU MAY WANT TO UPDATE LATER (all inside index.html, editable in any
text editor — search for the text and change it):
  - WhatsApp number: search for 919426674925 (appears a few times)
  - Email:  info@newagepv.com
  - Address: Village Shapar, Taluka Kotda Sangani, Rajkot, Gujarat - 360024
  - Any specification values before going public.

The contact form opens WhatsApp with the visitor's details pre-filled — no
server or database is needed, so this works on the simplest/cheapest hosting.
