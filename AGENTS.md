# AGENTS.md – Stipendiene (scholarship hunting for Germany)

Rules for any agent (chat session or daily scheduled run) working in this repo.

## Goal
Find **every realistic way to finance study and living in Germany** for the owner:
scholarships, exchange funding, summer/winter course grants, tuition waivers, foundation
funding, student jobs (Werkstudent) and anything else that reduces costs.
Track them in `scholarships.md`, keep `transfer.md` as the handoff for the next session.

## Owner profile (no personal IDs here)
- Vietnamese, lives in Vietnam (Hanoi area), studies **Mechatronics (Bachelor)** at the
  **Vietnamese-German University (VGU)**. Partner universities in Germany are relevant
  (e.g. Frankfurt UAS runs the VGU exchange; confirm which partner covers Mechatronics).
- German level: **around B1, not yet certified**. Plans to take **ÖSD B1** later
  (ÖSD centre in Hanoi: IVES, Cau Giay – offers ZB1).
- Unknown yet (ask once, then record here): year of study, GPA, Master plans, target cities.

## Language rule (important)
- Talk to the owner in **simple German at B1 level**: short sentences, Präsens/Perfekt,
  common words. Put hard or technical words in English in brackets once,
  e.g. *Frist (deadline)*, *Bewerbung (application)*.
- If the owner writes in English or Vietnamese, still answer mainly in B1 German,
  with a short English line only where a mistake would cost money or a deadline.
- `AGENTS.md` and `transfer.md` stay in English (for agents). `scholarships.md` is in
  simple German with English glosses (the owner reads it).

## How to search
1. Official sources first: DAAD database (daad.de, www2.daad.de), DAAD Vietnam
   (daad-vietnam.org), VGU (vgu.edu.vn, tuyensinh.vgu.edu.vn), partner universities,
   foundations' own sites (boell.de, kas.de, fes.de, rosalux.de, freiheit.org, hss.de),
   deutschlandstipendium.de, university scholarship pages.
2. Aggregators (mystipendium.de, e-fellows.net, stipendienlotse.de, mygermanuniversity.com)
   only to discover leads – always confirm on the official page before listing.
3. Every entry needs: name, who pays, amount, who is eligible, German level needed,
   deadline (exact date if known), link, status, fit for owner (hoch / mittel / später).
4. Never invent amounts or deadlines. If a page doesn't say it, write "unklar – prüfen".
5. Mark deadlines that are **less than 60 days away** with ⚠️ at the top of the reply.
6. Prefer things the owner can use **now or soon** (as a VGU Bachelor student) over
   far-future Master/PhD items, but keep the Master/PhD items in the list.

## Files
- `scholarships.md` – the tracker. Add new finds under "Neu gefunden" with the date
  (YYYY-MM-DD). Don't delete expired items; move them to "Abgelaufen / nächste Runde".
- `transfer.md` – overwrite the "Current state" and "Next steps" sections each session;
  append to the "Log" at the bottom (one line per run).
- No personal data (full name, student ID, passport, email, phone) in any file.

## Daily scheduled run
A scheduled task runs once a day. It clones this repo, reads these three files,
searches for **new** opportunities and **changed deadlines**, updates the files,
commits ("Stipendien-Update YYYY-MM-DD") and pushes to `main`, then sends the owner
a short B1-German summary (max ~10 lines). If nothing new was found, say so in one line
and still append to the Log.
