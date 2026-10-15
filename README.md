ACC User Guide (acc-guide)

Markdown version of the ASUS Control Center (ACC) user manual, parsed from the manual PDFs and published through GitBook.

Scope
Item	Description
Version	ACC v4.0 and earlier
Source	Manual PDFs (E26192_ASUS_Control_Center_V4.0_EM_WEB, 11 files)
Publishing	GitBook, synced from this repo
v4.1 and later	See acc-tech, parsed from the acc-code/src (trunk) source code
Structure
text
acc-guide/
├─ README.md          # This file
├─ SUMMARY.md         # GitBook navigation
├─ MAPPING.md         # PDF-to-GitBook mapping
├─ STYLE.md           # Writing style
├─ PDF/               # Manual PDFs
├─ IMG/               # All images (flat, with red boxes and number callouts)
├─ Begin/             # ch1
├─ Monitor/           # ch2
├─ Deployment/        # ch3
├─ Centralized/       # ch4
├─ Report/            # ch5
├─ Notification/      # ch6
├─ Account/           # ch7
├─ Options/           # ch8
├─ License/           # ch9
└─ ...                # ch0 (README + INDEX), ch10 (Appendix)
Naming Rules
UPPERCASE folders (PDF/, IMG/): resources.
PascalCase folders and files (Monitor/Inventory/Inventory.md): content, following the ACC left-side menu. Path format is Category/Module/File.md; Begin/ uses Category/File.md.
README.md and SUMMARY.md must stay in the repo root (GitBook requirement). Pages not listed in SUMMARY.md are hidden from navigation.
Keep letter case consistent everywhere; GitHub and GitBook are case-sensitive.
Images: IMG/<Category>-<Page>-<Seq>.png (two-digit Seq, in manual order), for example Monitor-Inventory-01.png.
Images
Images keep the manual's annotations. The text refers to them (for example, "see ① in the figure"), so do not replace them with clean screenshots.
ch2 (Monitor) uses full-color screenshots only.
Clean screenshots are in acc-img (asusserverssd/accimg) and used by acc-tech.
Related Projects
Project	Source	Version	Images
acc-guide (this repo)	Manual PDFs	v4.0 and earlier	IMG/ (annotated)
acc-tech	acc-code/src (trunk)	v4.1 and later	acc-img (clean)

The two projects are maintained independently.

Maintenance
When adding, moving, or renaming a page, update SUMMARY.md and MAPPING.md, and check image links against IMG/.
To hide a page, remove it from SUMMARY.md; deleting the file deletes its content.
Content is final for v4.0. Fix text and links only; do not re-parse the PDFs.
To restore the original parsed state, check out tag guide-parsed-raw.
Copyright

Confirm copyright and public-release terms before publishing this repo.

Owner: (to be filled)
License: (to be filled)
