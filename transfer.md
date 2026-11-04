# transfer.md – handoff for the next session

## Current state (2026-11-04, daily run)
- Goal: new Bachelor in Germany as a freshman (Maschinenbau or other engineering),
  German B1 only, needs living-cost money. See AGENTS.md profile.
- `scholarships.md` has sections 1-6 plus "Neu gefunden". Daily run 2026-11-04 found:
  **Studienkolleg Frankfurt** accepts B1 (T-Kurs, semester fee only, 100 EUR exam, uni-assist,
  about 25 Mar-1 May, test in person in Frankfurt). KIT T-Kurs B1 (undated 2025 document).
  **Kassel Studienkolleg closes** after 2026/27.
  **HS Schmalkalden Mechatronics & Robotics B.Eng.**: English only, no German, IELTS 6.5 /
  TOEFL 86 only, APS, April start only, 1 Sep-15 Nov, direct application, 50 EUR, 303.80 EUR
  semester fee. **HAW Hamburg Mechanical Engineering is April start only** (tracker lacked
  this); needs APS + uni-assist VPD (up to 8 weeks). So both English April routes mean
  April 2028 realistically. TUHH Engineering Science: WS only, 1 Jun-15 Jul, restricted.
  **UDE**: deadline 1 May-31 Jul confirmed, programme unrestricted per DAAD, BUT the general
  UDE page says most applicants need DSH-2 vs ISE page B1: unresolved conflict.
  Deutschlandstipendium added: Schmalkalden (future freshmen ok, 2025: 1 Apr-15 May),
  Frankfurt UAS (needs enrolment certificate), Heilbronn (May 2027).
- Fixed section 3: sdw, Cusanus, Villigst now "nein" (matched the 2026-10-31 correction).
- Blocked account: unchanged, bill in committee, no vote date. Bill figures from 2026-11-03
  stand. 13,284 EUR/year is our own calculation, no embassy announcement exists.
  Portal only: 1,091 EUR/month for Studienbewerber visas.
- Bavaria fees from 2026-11-02 and TUM WS 2027/28 fees from 2026-11-03 stand.
- DAAD winter/summer courses "mittel": need a certified B1 (max 1 year old),
  2 finished study years, enrolment abroad; joint/double degrees with German
  participation excluded (VGU may be affected - check).
- **Daily scheduled task** "Tägliche Stipendien-Suche" runs every day at 06:47
  (Asia/Ho_Chi_Minh), id `trig_01NHy4DuzJLeXd3TY1gtSCiP`. Runs are dated by Vietnam time
  (the container clock is UTC, one day behind at run time).
- Conversation language: B1 German with English gloss after every B1/B2 word;
  known words in `bekannte-woerter.md` (still empty).
- **Website (artifact)**: https://claude.ai/artifact/AUAVpvAkhbAWwTyM4LFArx
  (source copy `website/stipendien-maschinenbau.html`, data in the `DATA` array,
  `{…}` = gloss). NOT yet updated with the daily finds since 2026-10-31.
- Source check notes: Studienstiftung, Walter Blüchert, sdw, Villigst, Cusanus = not
  eligible. APS 150 USD + TestAS; 2 full study years -> direct subject-restricted access.
- Search note: searches for OESD B1 dates return spam sites selling certificates. Ignore
  them; use IVES or osd.at only.

## Open questions for the owner (ask once, record in AGENTS.md profile)
1. How many years at VGU will be passed before applying? (2 passed years → direct,
   subject-restricted access; otherwise Studienkolleg.)
2. High-school grades (6 relevant subjects ≥ 6.5/10, none below 4?) and English score.
3. German-taught (needs C1) or English-taught programme? Target start: WS 2027/28?
4. Target cities / states (tuition-free vs Baden-Württemberg / TUM).

## Next steps
1. Update the website artifact with the finds since 2026-10-31 (read it, edit DATA, republish with url).
2. UDE ISE: resolve B1 vs DSH-2 (ask ISE office), whether OESD B1 and a VGU Medium-of-Instruction letter count, semester fee.
3. Frankfurt Studienkolleg: does OESD B1 count; WS 2027/28 dates and test date. KIT T-Kurs: current dates, fees. Other state Studienkollegs with B1 (Marburg, Hamburg, Halle, Koethen etc.).
4. HAW Hamburg: official non-EU deadline (myHAW; portal says 30 Nov). THWS, Aalen: portal deadlines conflict.
5. Blocked account: watch committee hearing, Bundestag vote, embassy / Auswaertiges Amt announcement of the new amount. Check Studienbewerber amount.
6. NRW: official source for "no non-EU fee" still missing. Check fees at other Bavarian HAWs; re-check Kaiserslautern and OVGU for service fees; TUHH costs and English level.
7. Festo Bildungsfonds: not listed. TU Clausthal page says up to 40,000 EUR with CareerConcept, income-based repayment (not a gift); GradGermany ties it to HDBW only. bildungsfonds.de not reached. FH Muenster page failed to load. Confirm before listing.
8. TestAS: exact registration dates for 25 Feb / 18 Mar 2027 and whether a centre exists in Hanoi/HCMC (still unknown).
9. Ask uni-assist / anabin whether VGU Mechatronics counts as related to Maschinenbau; APS rules for a second Bachelor; DAAD course rule for VGU.
10. More first-year money: company scholarships (MTU Stiftung and others on TU Clausthal list: no details yet), dual-study providers accepting non-EU; THM is+i details. Duales search found only job ads, no non-EU statement.
11. Watch: Frankfurt Studienkolleg test 16 Jan 2027 (SS only), OVGU budget scholarship 25 Mar 2027, Kaiserslautern Studienkolleg 14 Apr 2027, THM uni-assist 1 Apr-15 Jul, Konstanz and Frankfurt Studienkolleg 1 May 2027, UDE May-Jul, Deutschlandstipendium rounds spring/summer 2027, uni-assist WS 2027/28 (usually 15 July), DAAD Hochschulwinterkurse (1 Jun - 31 Jul 2027), Schmalkalden 1 Sep-15 Nov 2027.

## Background
- Full living-cost scholarships for international first-year Bachelor students are
  rare; realistic plan = no tuition + 300 € scholarships + legal work
  (140 full / 280 half days; 2026: Minijob 603 €/month, min. wage 13.90 €/h;
  from 1 Jan 2027: 633 €/month, 14.60 €/h)
  + bigger foundation scholarship later with C1.
- Blocked account for a student visa: 992 €/month = 11,904 €/year (check embassy; may rise with the 2027 BAföG reform).
- Duales Studium (company pays salary during study) is worth researching – usually
  needs good German (B2–C1).

## Log
- 2026-10-31 – Repo set up, first research round, daily task created.
- 2026-10-31 – Goal changed to new Bachelor in Germany; list, AGENTS.md and daily task updated.
- 2026-10-31 – Sources checked one by one; corrections (Studienstiftung, Walter Blüchert); vocabulary-gloss rule added.
- 2026-10-31 – Owner wants only B1: Studienkollegs with B1 admission researched (Konstanz confirmed, Bavaria Vorkurs).
- 2026-10-31 – Maschinenbau scholarship research; website published; sdw/Villigst/Cusanus marked not eligible.
- 2026-10-31 – Daily run: TU Darmstadt Studienstart, STIBET OTH, NORDAKADEMIE dual, TestAS dates added; e-fellows entry flagged unconfirmed.
- 2026-11-02 – Daily run: Bavarian non-EU fees (THWS, OTH, TH Nürnberg, FAU), OVGU scholarships, 2027 wage/Minijob, TestAS rules added; DAAD courses downgraded; expired items moved.
- 2026-11-03 – Daily run: possible blocked-account rise (BAföG bill), UDE ISE and THM bilingual routes, Deutschlandstipendium UDE/THM/Dortmund, e-fellows ING confirmed, HAW excellence ruled out, TUM WS 2027/28 fees.
- 2026-11-04 – Daily run: Studienkolleg Frankfurt/KIT B1, Kassel closing, Schmalkalden Mechatronics & Robotics, HAW Hamburg April-only correction, TUHH, UDE deadline confirmed but B1/DSH-2 conflict, 3 more Deutschlandstipendium entries; section 3 nein fixes.
