# Hireboard demo

Interactive demo of a hiring tracker built on Microsoft 365. All people and data are fictional.

Open `index.html` in a browser.
Excel and PDF features load two small libraries from cdnjs, so they need an internet connection.

## Try this
1. Dashboard: click a number or a department card to jump to the matching candidates.
2. Candidates > Import from Excel: download the sample file, then upload it. Three people are added; two are already in the list and stay unchanged.
3. Check inbox for CVs: same duplicate check for applications that arrive by email.
4. Open a candidate: rate them with stars, change the status, send an email.
5. Culture fit > Log results: paste a sample email, click Parse automatically, then save.
6. Starred: your top-rated candidates across all roles.
7. Reports: pick a period (YTD, QTD, last 90 or 30 days, or custom) and download it as PDF or Excel.
8. Switch "Signed in as" to change who writes notes and who signs emails.

Data resets on reload. Names and contact details are set in `CONFIG` at the top of the script.
