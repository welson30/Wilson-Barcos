# Sailor Wil – site

Static site (index.html + images/). No build step.

## Before publishing
Open index.html and edit near the bottom:
- PHONE is set to (850) 775-0136 (texts only).
- EMAIL = "hello@example.com"
Confirm the prices in the "Pricing" section (search for "TODO").

## Deploy on Vercel
Option A: vercel.com > Add New > Project > drag this folder (or push to GitHub and import).
  Framework preset: "Other". No build command. Output directory: root.
Option B: npm i -g vercel && vercel --prod  (inside this folder)

## Adding photos
Put a .jpg in images/ (ideally ~1800px wide, under 400 KB) and copy one <button class="g-e"> block in the Recent work section.
