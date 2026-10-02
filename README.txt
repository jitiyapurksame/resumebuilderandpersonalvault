PROFILEVAULT - TEST VERSION 0.8.1 (resume builder + certificates on record forms)
=============================================================

WHAT IS IN THIS ZIP
  index.html   The whole app (one file, no build needed)
  README.txt   These instructions

WHAT WORKS IN THIS VERSION
  People and profiles (English + Thai), photos, contacts, records
  (education, experience, training, awards, skills, projects),
  document vault with previews and linking,
  backup and restore (Settings page),
  AND NEW: Resume builder (Resume tab) with live A4 preview and PDF.

NOT BUILT YET
  Excel export (step 9), search / timeline (step 10).


STEP 1 - UPDATE GITHUB
  If you already deployed before: open your repository on GitHub,
  click "Add file" > "Upload files", drop the NEW index.html
  (same name, it replaces the old one) and click "Commit changes".
  Vercel updates in about a minute. Your saved data stays.

  First time? Create a repository, upload index.html, then on vercel.com
  choose "Add New" > "Project", pick the repository and click "Deploy".

STEP 2 - OPEN ON EACH DEVICE
  Open your Vercel link in Safari (iPhone / iPad) or any browser (computer).
  On iPhone / iPad: Share > "Add to Home Screen", then open from the icon.


HOW BACKUP WORKS (Settings page)
  CREATE A BACKUP
    1. Choose "Everyone" (or pick people), keep "Include files" ticked.
    2. Optional: set a passphrase. If you forget it, the backup cannot be
       opened. Recommended when you store ID numbers.
    3. Tap "Create backup", wait for "Backup ready", then tap
       "Save / share backup".
       iPhone / iPad: choose "Save to Files" (iCloud Drive is a good place).
       Computer: the file downloads.
    The file ends in .profilevault. Keep copies in two places.

  RESTORE / MOVE DATA TO ANOTHER DEVICE
    1. On the other device, Settings > Restore > "Choose backup file".
    2. Enter the passphrase if asked, check the preview, then pick:
         Merge (recommended)  adds what is missing and keeps the newer
                              version of anything that exists on both sides
         Replace everything   erases this device first. You must type REPLACE.
                              A safety snapshot is kept so you can undo it
                              (Settings > Safety snapshot > Restore from it)
         Import as new people adds copies, touches nothing that exists
    3. Tap Restore. A report shows what was added, updated and skipped.

  The Home screen shows a reminder when you have data but no recent backup
  (never, 14+ days, or 25+ changes). Only a full backup (everyone, with
  files) resets the reminder.


CERTIFICATES ON RECORD FORMS (new in 0.8.1)
  When you add or edit an education, experience, training, award, skill
  or project record there is a box "Supporting documents (optional)".
  1. Tap "Add files" (on iPhone/iPad you can take a photo or choose a file).
  2. Rename each file in the list if you want (the extension is kept).
  3. Tap Save. The files are stored in Documents, filed under a matching
     category, tagged like the record, and linked to the record.
  4. Later, on the record's edit page, use "Rename" under a document,
     or open it in Documents to edit its name, category, dates and notes.

HOW THE RESUME BUILDER WORKS (Resume tab)
  1. Pick a document type: Full CV, Short resume or Student profile.
     Each starts with sensible sections and limits that you can change.
  2. Choose the language of the document (English or Thai).
  3. Turn sections on/off, move them up/down, rename them, and set
     "Show at most" (for example the 3 newest awards).
  4. Open "Items" inside a section to untick single entries.
  5. Filters: only items with chosen tags, only items from a year on,
     and leave out anything marked Private (on by default).
  6. Choose which contact details and personal details appear.
     Private details only appear if you tick them.
  7. Watch the A4 preview. The pill above it says "Fits on 1 page"
     or "About N pages".
  8. "Save preset" stores your choices (for example "1-page Engineering").
  9. "Save as PDF / Print" opens the print screen and keeps a frozen copy
     under "Saved documents".
     Computer: choose "Save as PDF" as the printer.
     iPhone / iPad: in the print screen pinch OUT on the preview with two
     fingers to get a PDF, then tap Share > Save to Files.

TEST CHECKLIST (please try on iPhone, iPad and computer)
  1. Settings > "Run database self-test": all lines show a tick.
  2. Add a person with a photo, a record, and a document linked to the record.
  3. Settings > Create backup (no passphrase) > Save to Files.
     Does the file appear in the Files app? Note its size.
  4. Create a second backup WITH a passphrase.
  5. On another device (or another browser): Restore the first file.
     Do the person, photo, record and document preview all appear?
  6. Change something on one device, back up, and Merge into the other.
  7. Try "Replace everything" on a test device, then undo it using
     the safety snapshot.
  8. Try restoring with a wrong passphrase: you should get a clear message.
  9. Add an education record and attach a certificate while adding it.
     Check it appears in Documents with the name you gave.
 10. Resume tab: build a Full CV, then a Short resume. Turn things on/off
     and check the preview follows. Try the Thai language option.
 11. Save as PDF. Open the PDF and check: Thai vowels and tone marks sit
     correctly, nothing is cut off, the photo shows, the layout is A4.
 12. Save a preset, change something, reload the preset.
 13. Note anything cut off, hard to tap, slow, or confusing.

IMPORTANT
  Each device still keeps its own separate data. Backup/restore is how you
  move data between iPad, iPhone and computer until cloud sync is built.
  Please keep using test data until you have confirmed a full
  backup-and-restore round trip on your own devices.
