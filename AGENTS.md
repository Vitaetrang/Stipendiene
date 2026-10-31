# AGENTS.md – Stipendiene (scholarship hunting for Germany)

Rules for any agent (chat session or daily scheduled run) working in this repo.

## Goal
Find **every realistic way to finance study and living in Germany** for the owner:
scholarships, exchange funding, summer/winter course grants, tuition waivers, foundation
funding, student jobs (Werkstudent) and anything else that reduces costs.
Track them in `scholarships.md`, keep `transfer.md` as the handoff for the next session.

## Owner profile (no personal IDs here)
- Vietnamese, lives in Vietnam (Hanoi area), currently studies **Mechatronics (Bachelor)**
  at the **Vietnamese-German University (VGU)** (taught in English).
- **GOAL (decided 2026-10-31): start a NEW Bachelor in Germany as a freshman**
  (Erstsemester), probably **Maschinenbau / Mechanical Engineering** or another
  engineering major. Main need: **money for living costs** ("Stipendium zum Bleiben").
  Exchange semesters / VGU-to-Germany programmes are NOT the main goal any more.
- German level: **around B1, not yet certified**. Plans to take **ÖSD B1** later
  (ÖSD centre in Hanoi: IVES, Cau Giay – offers ZB1).
- Unknown yet (ask once, then record here): how many years passed at VGU, GPA,
  high-school grades (Vietnamese 10-point scale), English test score, target start
  semester, German- or English-taught programme, target cities.

## What matters for this goal
- Admission route Vietnam → German Bachelor: APS certificate (+ TestAS for Bachelor),
  direct subject-restricted access after 2 passed study years in Vietnam, otherwise
  Studienkolleg (T-Kurs). Always check anabin / uni-assist for the current rules.
- Language: German-taught Bachelor ≈ C1 (DSH-2 / TestDaF 4×4); English-taught
  Bachelor needs IELTS/TOEFL. Track both routes.
- **Owner wants to stop at a B1 certificate (2026-10-31).** So track Studienkollegs
  that admit with **B1** (confirmed: Studienkolleg Konstanz, T-Kurs; Bavaria allows a
  Vorkurs with B1). Most others need B2. Studienkolleg teaching is B2/C1 and the final
  exam expects ~C1, so German keeps improving there. Alternative without more German:
  English-taught Bachelor with direct access (2 passed VGU years).
- Most foundations need B2–C1 and enrolment in Germany. So prioritise: (1) things
  open to first-semester internationals (Deutschlandstipendium with admission letter,
  Studienstiftung self-application in 1st/2nd semester, university scholarships,
  STIBET), (2) cost savers (tuition-free states, free state Studienkollegs),
  (3) legal work (140 full / 280 half days per year, Minijob limit), (4) foundation
  scholarships for later Bachelor semesters once German is C1.

## Language rule (important)
- Talk to the owner in **simple German at B1 level**: short sentences, Präsens/Perfekt,
  common words.
- **Vocabulary glossing (owner's instruction, 2026-10-31):** write the English meaning
  in brackets **directly after every word that is B1 or B2 level (or harder)**,
  e.g. *prüfen (to check)*, *Frist (deadline)*, *Bewerbung (application)*.
  Do this in every reply and every daily summary, also in `scholarships.md`.
  Simple A1/A2 words (Geld, Jahr, studieren, gut …) get no gloss.
- **Known words:** `bekannte-woerter.md` lists words the owner already knows.
  Do NOT gloss those words any more. When the owner says they know a word, add it there.
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
6. Prefer things for a **first Bachelor year in Germany as an international student**
   over Master/PhD items, but keep Master items in their own section.
7. Be honest: full living-cost scholarships for international first-year Bachelor
   students are rare. Don't oversell; say what each item really covers.

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
