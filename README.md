VitRx

A medication, vitamin, and supplement scheduler that checks for interactions.

Add what you take, and VitRx cross-checks every item against a database of known interactions. It then builds a daily schedule around your routine. For example, it spaces Adderall away from protein powder, keeps levothyroxine four hours from calcium and iron, and moves stimulants away from bedtime.

🔗 Live app: https://YOUR-SITE.netlify.app

⚠️ Not medical advice. VitRx is an educational tool. Its database is a draft that hasn't been reviewed by a pharmacist yet. Always check changes to your medications or supplements with your doctor or pharmacist.

Features
Interaction checker: flags combinations to avoid, to space apart, or to take with caution, with the reason and a cited source for each.
Personalized schedule: set your wake time, meals, workouts, and bedtime, and VitRx places each item at the best time.
Multiple day types: separate schedules for work days and days off.
Split doses: set different amounts and times for each dose (e.g. Adderall XR in the morning and IR in the afternoon).
Pill times: group everything into morning, afternoon, and bedtime.
Health conditions: optional cautions for conditions like pregnancy, diabetes, kidney disease, and more.
Search and compare: search by brand, generic, or alternate names, and compare items or forms side by side (e.g. folic acid vs. methylfolate).
"Used for": what each item is used for, with an evidence grade.
My stack: a cart-style panel with quick add and remove.
Watchlist: keep a list of supplements to try or to ask your doctor about.
Reminders: browser notifications, plus a calendar file (.ics) you can export.
Saved schedules: save snapshots, print them, and export or import backups.
Privacy

Everything you enter stays in your own browser (localStorage). There are no accounts and no server, and nothing is sent anywhere. Use Export backup to move your data to another device.

How it's built

VitRx is one self-contained index.html file: plain HTML, CSS, and JavaScript, with no frameworks, build tools, or external dependencies. The interaction database is built into the file.

Part	What it holds
ITEMS	Medications, vitamins, and supplements, with aliases, best times, and food rules
RULES	Pairwise interactions, with severity, spacing, evidence level, and source
CONDITIONS	Health-condition cautions
FORMS	Comparisons of different forms of the same nutrient
USES	What each item is used for, with an evidence grade
SOURCES	Citations for everything above

To run it locally, open index.html in any browser.

Sources

Notes are compiled from:

FDA drug labels (DailyMed)
NIH Office of Dietary Supplements fact sheets
NCCIH
MedlinePlus
CDC
Peer-reviewed studies and reviews

Every rule links to its source in the app. Notes still marked "general guidance" are waiting for a specific citation. In the app, go to Library → Sources & review status to see these, or to download all notes as a CSV for pharmacist review.

Roadmap
Pharmacist review of all interaction notes
More items and citations
Installable phone app (PWA) with offline support

Built by Angelina Sorensen.
