PROFILEVAULT - TEST VERSION 0.6 (step 6: documents)
====================================================

WHAT IS IN THIS ZIP
  index.html   The whole app (one file, no build needed)
  README.txt   These instructions

WHAT WORKS IN THIS VERSION
  People and profiles (English + Thai), photos, contacts,
  records (education, experience, training, awards, skills,
  projects), document vault with previews and linking.

NOT BUILT YET
  Backup and restore (step 7), resume/PDF/Excel export (steps 8-9).
  Data is stored only inside the browser on each device.
  Until backup exists, please use TEST data only.
  Do not rely on this version to keep real certificates or ID numbers.


STEP 1 - PUT IT ON GITHUB (in the browser)
  1. Open github.com and sign in.
  2. Create a new repository (for example "profilevault"). Keep it Private if you like.
  3. Click "Add file" > "Upload files".
  4. Unzip this file on your computer and drag ONLY index.html into GitHub.
     (Keep the name exactly: index.html)
  5. Click "Commit changes".

STEP 2 - PUBLISH WITH VERCEL
  1. Open vercel.com and sign in with GitHub.
  2. Click "Add New" > "Project" and choose your profilevault repository.
  3. Leave every setting as it is and click "Deploy".
  4. When it finishes, Vercel shows a link like https://profilevault-xxxx.vercel.app
     Open that link.

STEP 3 - INSTALL ON iPHONE / iPAD
  1. Open the Vercel link in Safari.
  2. Tap the Share button, then "Add to Home Screen".
  3. Open the app from the new icon.
     (This helps Safari keep your data. In Settings inside the app, it
      should say "Running as an installed app".)

STEP 4 - UPDATING LATER
  On GitHub, open index.html, click the pencil icon (Edit), or upload a new
  index.html with the same name. Vercel updates automatically in about a minute.
  Your saved data stays, because the address does not change.


TEST CHECKLIST (please try on iPhone, iPad and computer)
  1. Settings > "Run database self-test": all lines should show a tick.
  2. Add a person with English and Thai names. Switch language to Thai.
  3. Add a photo (camera or library) and a contact (try a Thai address).
  4. Add an education record and an award record. Try a tag.
  5. Documents > upload a PDF and a photo. Open it, check the preview,
     link it to the award, tap Download.
  6. Delete something, then restore it in Settings > Recently deleted.
  7. Note anything that looks cut off, is hard to tap, or does not work.

IMPORTANT: each device keeps its own separate data for now.
What you add on the iPad will not appear on the iPhone until the
backup/restore step is built.
