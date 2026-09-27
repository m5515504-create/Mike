# From 312 records to the studies you actually need

**Review:** Topical versus oral NSAIDs for symptomatic knee OA, with an exploratory network node for concurrent topical-plus-oral therapy
**Inputs:** `Included_Studies_Ranked_Deduped.csv` (312 records), the screening workbook (25,845 records), and 7 reference meta-analyses (MAs)
**Files in this folder:** `Download_List.csv` (what to download), `Record_Map_312.csv` (what happens to each of the 312 records, for the PRISMA flow diagram), `Reference_MAs.csv`, and `Study_Selection.xlsx` (all three as sheets)

---

## 1. Bottom line

| What | Studies | Download? |
|---|---|---|
| **Primary MA: head-to-head topical vs oral RCTs** | **18 candidates** (10 used by the reference MAs + 8 found only by your search) | Yes |
| Exploratory combination node (topical + oral) | 6 more studies (Simon 2009 and Liu 2025 also add combination arms) | Yes |
| Non-randomised safety stream (NRSI) | 7 candidates | Yes |
| Retrieve only to confirm eligibility | 10 | Check, most will be excluded |
| Registry-only records (no paper) | 8 | No, just check the registry for results |
| ANCHORED stream (NSAID vs placebo only) | 266 records | **No: set aside by protocol amendment** |

So you download about **31 papers instead of 312**. The primary meta-analysis will probably end with **about 12 to 16 trials** after full-text screening (my estimate, not a fact). That is in line with the reference MAs (7 to 8 head-to-head trials). Yours is a little larger because your search also found non-English trials and trials published after those reviews.

---

## 2. Why "312" was never comparable to "the MA included 8"

1. **312 counts records, not studies.** One trial can appear 2 to 5 times (full paper, conference abstract, registry entry, pooled re-analysis). In the 312, Conaghan 2013 appears twice, and Tugwell 2004 + Simon 2009 appear 8–9 times between them (full papers, abstracts, a probable registry entry and 4 Roth & Fuller pooled analyses).
2. **312 is a title/abstract (T/A) result.** T/A screening is meant to be over-inclusive; your own Guide sheet says any Include or Unclear goes to full text. The numbers reported by MAs come *after* full-text screening. Chen 2025 went from 77 full texts to 12 studies. Wolff 2021 went from 65 to 18. Zeng 2021 screened 10,943 reports.
3. **86% of the 312 (268 records) are the ANCHORED stream:** a topical NSAID vs vehicle, or an oral NSAID vs placebo, with no topical-vs-oral comparison. That stream is what inflates the number.

Only 44 of the 312 records (DIRECT, COMBINATION, NRSI) address your question directly. They collapse to about 30 distinct studies.

---

## 3. What the 7 reference MAs did

| MA | Question | Included | Head-to-head topical vs oral |
|---|---|---|---|
| Zeng 2018, *BJSM* | Topical NSAIDs vs placebo or each other, any OA joint | 36 RCTs + 7 observational | 0 |
| Persson 2018, *OAC* | Topical NSAIDs vs capsaicin (via placebo) | 28 RCTs | 0 |
| Honvo 2019, *Drugs Aging* | Safety of topical NSAIDs vs placebo | 25 qualitative / 19 in MA | 0 |
| Chen 2025, *BMC MSD* | Topical diclofenac forms vs placebo, knee | 12 RCTs | 0 |
| Wolff 2021, *Phys Sportsmed* | Topical NSAIDs, knee OA, placebo or active control | 18 RCTs | 4 (+ Gor 2016, a combination trial) |
| **Zeng 2021, *OAC*** | Acetaminophen vs topical vs oral NSAIDs, knee OA (NMA) + THIN cohort | 122 RCTs | **7** |
| **Wang 2022, *Medicine*** | **Topical vs oral NSAIDs (pairwise)** | **8 RCTs** | **8** |

What this shows:
- The MAs that ask **your** question used **7 to 8 head-to-head RCTs**. Across all 7 reviews the head-to-head trials add up to **10 unique trials**, and **all 10 are in your 312.** Your search did not miss them.
- The only one that pooled placebo-anchored oral trials (Zeng 2021) needed **122 RCTs to add 115 indirect trials** to 7 direct ones. Its node-splitting test found **no significant disagreement between direct and indirect evidence** for topical vs oral. In other words, the ANCHORED approach has already been done and did not change the direct answer.
- **Zeng 2021 excluded NSAIDs "combined with other drugs"**, so no one has synthesised a topical-plus-oral node. That node is what is new in your review, and it does not need the ANCHORED stream.

---

## 4. The reduction method (every step is a documented rule, not a target number)

| Step | Rule | Records left |
|---|---|---|
| 0 | T/A Includes (deduplicated) | 312 |
| 1 | **Protocol amendment:** drop the ANCHORED stream (placebo/vehicle-only trials). The network is built only from trials that randomise at least two of {topical, oral, topical + oral}; their placebo arms stay in. | 46 (44 + 2 reclassified, see Step 2) |
| 2 | **Fix misfiled records:** Dehghan 2019 and Dehghan 2018 were tagged ANCHORED, but *every* arm took an oral NSAID, so "NSAID gel vs placebo gel" is really **combination vs oral alone**. Move them to COMBINATION. | 46 |
| 3 | **Collapse records into studies:** merge conference abstracts, registry entries and pooled re-analyses into their parent trial. Never count the Roth & Fuller pooled analyses as separate studies; Zeng 2021 also excluded pooled analyses. | about 35 study entities |
| 4 | **Registry stubs with no results:** do not download; check the registries for posted results and list them as ongoing or unpublished (this feeds your reporting-bias assessment). | about 31 studies to download + 10 to check |
| 5 | **Full-text screening** (your normal eligibility criteria) | probably 12–16 primary + 6–8 combination + 4–6 NRSI |

---

## 5. The download list (details and links in `Download_List.csv`)

### Primary MA: head-to-head RCTs used by the reference MAs (10)
1. **Dickson 1991**: piroxicam gel vs oral ibuprofen, n = 235
2. **Sandelin 1997**: eltenac gel vs oral diclofenac vs placebo gel, n = 290
3. **Tugwell 2004**: Pennsaid vs oral diclofenac, n = 622, 12 wk
4. **Rother 2007**: IDEA-033 ketoprofen vs celecoxib vs placebo, n = 397, 6 wk
5. **Simon 2009**: 5 arms, including a **topical + oral** arm, n = 775, 12 wk (the key trial for the combination node)
6. **Doi 2010**: NSAID plasters vs oral NSAIDs, open-label, n = 165
7. **Tiso 2010**: oral vs topical ibuprofen, pilot, n = 20
8. **Conaghan 2013**: IDEA-033 vs celecoxib vs vehicle vs placebo, n = 1,395, 12 wk
9. **Mu 2016**: loxoprofen patch vs tablet, n = 169
10. **Shinde 2017** *(conditional)*: mixed musculoskeletal pain; keep only if knee-OA data are reported separately

### Primary MA: eligible head-to-head RCTs that none of the 7 MAs included (8)
11. **Underwood 2008 (TOIB)**: advice to use topical vs oral ibuprofen, RCT arm n = 282 (knee pain, age ≥ 50; run a sensitivity analysis without it)
12. **Rother, Yeoman & Ekman 2013**: IDEA-033 vs naproxen vs placebo, n = 837; *conference abstract only so far*
13. **Takagishi 1985**: ketoprofen ointment vs oral ketoprofen, double-dummy, n = 185 (Japanese)
14. **Tsuyama 1985**: L-141 ointment vs oral "FB" tablet, n = 275 (Japanese)
15. **Özgen 2011**: Flector plaster vs oral diclofenac SR vs no treatment, n = 28 (Turkish)
16. **Liu 2025**: oral loxoprofen vs flurbiprofen patch vs **both**, n = 90 (Chinese; also feeds the combination node)
17. **Kageyama 1986**: ketoprofen ointment vs oral ketoprofen (Japanese, no abstract)
18. **Nagaya 1984**: piroxicam gel vs capsule (Japanese, no abstract; joint site not stated)

### Exploratory combination node (6 more)
19. **Sun 2026**: celecoxib + flurbiprofen patch vs celecoxib, n = 90
20. **Wang 2023**: celecoxib + diclofenac cream vs celecoxib, n = 128 (Chinese)
21. **Zhang 2011**: oral diclofenac + diclofenac gel vs oral diclofenac, n = 120 (Chinese)
22. **Dehghan 2019**: diclofenac gel + celecoxib vs placebo gel + celecoxib, n = 120 *(reclassified from ANCHORED)*
23. **Dehghan 2018**: piroxicam jelly + oral diclofenac vs placebo jelly + oral diclofenac, n = 120 *(reclassified; check randomisation)*
24. **Sasaki 2021**: S-flurbiprofen plaster alone vs oral + topical, n = 222 *(check that allocation was randomised)*

*Excluded, but name it in your excluded-studies table:* **Gor 2016** (7 days, below your 2-week minimum). Wolff 2021 included it, so reviewers may ask.

### NRSI safety stream (7)
25. **Zeng 2021 THIN cohort** *(ADD: currently excluded as REVIEW-LIST, but the paper contains an original propensity-matched knee-OA cohort of topical vs oral initiators, 14,218 per group. You already have this PDF.)*
26. Silverman 2022 (+ its 2021 EULAR abstract), 27. Keshwani 2026, 28. Pontes 2018, 29. Kikuchi 2021 (was Unclear), 30. Schöffski 2000 (only if it reports adverse events), 31. Sinnott 2020 (optional; its outcome is pneumonia)

---

## 6. Your network without the ANCHORED stream

Class-level nodes: **Topical**, **Oral**, **Topical + Oral**, **Placebo/vehicle**

- Topical ↔ Oral: all primary trials (up to 18)
- Topical + Oral ↔ Oral: Simon 2009, Liu 2025, Sun 2026, Wang 2023, Zhang 2011, Dehghan 2019, Dehghan 2018
- Topical + Oral ↔ Topical: Simon 2009, Liu 2025 (+ Sasaki 2021 if randomised)
- Placebo arms (from multi-arm trials): Sandelin 1997, Rother 2007, Simon 2009, Conaghan 2013, Rother 2013

The network is **connected and has closed loops** (topical, oral and combination via Simon 2009 and Liu 2025), so node-splitting is possible without a single placebo-only trial.

*Recommendation (my judgement):* the combination trials are mostly 2 weeks long, while the head-to-head trials run 4 to 12 weeks. Pre-specify the time point for the network (for example, "at or nearest to 2 weeks") separately from the pairwise primary time point, and report the difference in duration as a transitivity threat.

---

## 7. Ready-to-paste protocol amendment (PROSPERO / OSF)

> **Amendment [date], made after title/abstract screening and before full-text screening or data extraction.**
> The supplementary ANCHORED stream (topical NSAID vs vehicle, or oral NSAID vs placebo, without a topical-vs-oral comparison) has been removed from the review. Rationale: (1) the review question is comparative, and randomised head-to-head evidence for topical vs oral NSAIDs exists; (2) a network meta-analysis combining head-to-head and placebo-anchored trials for exactly this comparison has already been published (Zeng et al., *Osteoarthritis Cartilage* 2021; 122 RCTs, 7 head-to-head) and found no significant inconsistency between direct and indirect evidence; (3) including about 266 placebo-controlled records would make indirect evidence dominate the effect estimate and add transitivity concerns (different eras, formulations and control types) without addressing the review's novel question, the concurrent topical-plus-oral node. The exploratory network is therefore restricted to trials that randomise at least two of {topical NSAID, oral NSAID, topical plus oral NSAID}; placebo/vehicle arms within these trials are retained. Records removed by this amendment are reported in the PRISMA flow diagram.

**Important:** this is a protocol deviation and must be declared as one. It is defensible because the rationale is scientific and it is applied *before* full-text screening. It must not be presented as "to get the number down".

---

## 8. Problems found in the current screening

| Problem | Fix |
|---|---|
| Dehghan 2019 (S05874) and Dehghan 2018 (S04875) are tagged ANCHORED but are combination-vs-oral trials | Reclassify to COMBINATION |
| The Zeng 2021 paper (S24435) was excluded as a review, but it contains an original knee-OA cohort | Add to the NRSI stream |
| Dickson 1991: the CSV says n = 118 | The abstract says 235 randomised (118 is one arm) |
| 4 Roth & Fuller pooled analyses ranked #3–5 and #20 as if they were separate studies | They re-analyse Tugwell 2004 + Simon 2009; never count them as studies |
| Gor 2016 (included by Wolff 2021) was excluded | Correct under the 2-week rule, but list it with its reason |

A scan of all 25,280 excluded records for topical + oral + knee terms found **no other wrongly excluded head-to-head knee trial**. The other matches were hand OA, pharmacokinetic studies, post-arthroplasty pain, opioid trials and commentaries.

---

## 9. If you want it even smaller (with the trade-offs)

- **Wang-2022-style rules** (peer-reviewed full text only, no abstracts, knee OA only, no mixed populations, any language): remove Rother 2013 (abstract) and Shinde 2017 (mixed population). That leaves about **14–16 primary trials**.
- **English only as well**: about **10 trials** (Dickson, Sandelin, Tugwell, Rother 2007, Simon, Doi, Tiso, Conaghan, Mu, Underwood). *Not recommended:* it drops 5–6 eligible randomised trials (Japanese, Chinese, Turkish) and introduces language bias that Cochrane guidance warns against.

---

## 10. What is verified and what is not

- **Verified from the files:** every count, the included-study lists and the eligibility rules of the 7 MAs, every abstract quoted above, and the record-to-study mapping.
- **Inferences (check at full text):** that NCT00108992 is Simon 2009's registration, that NCT00317733 relates to Rother 2007, and that jRCTs021180050 is Sasaki 2021's registration; the identity of the "L-141" and "FB" drugs; the expected final count of 12–16.
- **Not verified:** whether a full paper of Rother/Yeoman/Ekman 2013 or results of the TDS-943 trials exist. The PubMed tool failed during this session, so search ClinicalTrials.gov (NCT00211549, NCT00546507, NCT00546832) manually.
- These decisions draft Reviewer 1's work. Under your protocol they still need the second reviewer's agreement.
