WHEELZA — WEBSITE FOLDER
========================

HOW TO USE
----------
1. Keep "index.html" and the "assets" folder together, in the same place.
2. Double-click index.html to open it in any browser.
   (Or upload the whole folder to any web host.)

That's it. The site works as-is.


THE FOLDER
----------
wheelza_site/
├── index.html          ← the website (clean, editable)
├── README.txt          ← this file
└── assets/
    ├── hero-lambo.jpg   ← hero background (also the video fallback)
    ├── hero-buggy.jpg   ← bottom "Start your collection" background
    ├── card-ferrari.jpg
    ├── card-lambo.jpg
    ├── card-mclaren.jpg
    └── card-bugatti.jpg


ADDING THE HERO VIDEO (optional, do later)
------------------------------------------
The hero is already wired for video. To switch it on:
  1. Put your video file in the assets folder, named exactly:  hero.mp4
  2. (Optional) Put a still frame in assets named:             hero-poster.jpg
No code changes needed. If hero.mp4 is missing, the hero simply
shows hero-lambo.jpg instead — nothing breaks.


THINGS TO UPDATE BEFORE GOING LIVE
----------------------------------
Open index.html in any text editor and replace:
  • WhatsApp number — search for:  910000000000
  • Prices         — search for:  ₹  (the card prices)
  • Email          — search for:  hello@wheelza.com
  • Social links   — search for:  href="#"  (Instagram / YouTube / Facebook)
