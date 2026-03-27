=====================================================
  JUAN MICHAEL PAAIS — PORTFOLIO SETUP GUIDE
=====================================================

FOLDER STRUCTURE (required):
-----------------------------
your-portfolio-folder/
├── assets/          ← FROM the Massively template download
│   ├── css/
│   └── js/
├── images/          ← PUT your project images here
│   ├── pic01.jpg    ← Main project image
│   ├── pic02.jpg    ← Project 2 image
│   └── pic03.jpg    ← Project 3 image
├── index.html       ← Home / Projects
├── education.html   ← Education page
├── experience.html  ← Working Experience
├── skills.html      ← Skills
└── certificate.html ← Certificate (images already embedded)

STEP 1 — GET THE MASSIVELY TEMPLATE ASSETS:
--------------------------------------------
1. Go to https://html5up.net/massively
2. Click Download
3. Unzip the file
4. Copy the "assets" folder into your portfolio folder

STEP 2 — ADD YOUR LOGO IMAGES:
--------------------------------
Open education.html in VS Code.
Find this comment:
    <!-- IMAGE SLOT 1 — RevoU Logo ... -->
    RevoU<br/>Logo<br/>Here

Delete "RevoU<br/>Logo<br/>Here" and replace with:
    <img src="images/revou-logo.png" alt="RevoU" />

Do the same for:
  - Universitas Pattimura → images/unpatti-logo.png
  - BMKG (in experience.html) → images/bmkg-logo.png

STEP 3 — TEST IN VS CODE:
---------------------------
1. Install "Live Server" extension in VS Code
2. Right-click index.html → "Open with Live Server"
3. It will open in browser with full dark styling ✅

STEP 4 — PUSH TO GITHUB:
--------------------------
git add .
git commit -m "Complete portfolio"
git push

Your site will be live at: https://yourusername.github.io
=====================================================
