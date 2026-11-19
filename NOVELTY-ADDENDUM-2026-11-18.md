# Novelty Addendum — Nalanda (received-numbers, §3)

*Scrub run 2026-11-18, prompted by an external reviewer's critique citing a 2022 working paper. Method per `research_novelty_scrub`: claim stated and split first, closest prior verified at its source, each part graded, one widened search before calling any part open.*

## The cited prior — verification result

**The citation as given could NOT be verified.** No 2022 academic working paper hosted by a "South Asian Studies Center" tabulating Nalanda's sources (Xuanzang "several thousand" / Huili 10,000 / Daoxuan 4,000) was found across six searches (distinctive-value queries, host-name queries, journal-name variants, working-paper queries). The reviewer's reference appears garbled in its year/host details.

**Its substance, however, verifies independently — and from older sources than 2022:**

1. **The three-way source distinction is standard, old scholarship.** Beal's translations carry the contrast directly: *Si-Yu-Ki* (1884) — Xuanzang's priests "to the number of several thousands"; *The Life of Hiuen-Tsiang* (1911), Book III pp. 111–112 — Huili's 10,000, residents and visitors together. Sukumar Dutt, *Buddhist Monks and Monasteries of India* (1962), already flags Huili's figure as exaggerated against Xuanzang's own "some thousand brethren."
2. **The Daoxuan 4,000 figure is real — at the primary source.** Daoxuan's biography of Xuanzang in the *Xu Gaoseng Zhuan* (T 2060, juan 4) states, of Nalanda: "There are more than four thousand resident monks. Including both monks and laypeople, the number of residents and visitors… reaches tens of thousands." (Attwood's 2024 translation, academia.edu — the first English translation of that biography.) Two nuances the reviewer's table flattens: Daoxuan pairs his >4,000 residents with a myriad-scale total, so he is not a clean "low" witness; and he was never an eyewitness to Nalanda — he reports at one remove.
3. **A closer scholarly prior than Beal alone:** Max Deeg, "Setting the 'Records' Straight: Textual Sources on Nālandā and Their Historical Value," in *Records, Recoveries, Remnants and Inter-Asian Interconnections* (ISEAS–Yusof Ishak Institute, Nalanda-Sriwijaya Centre series, 2018), pp. 105–140 — a critical, source-by-source treatment of exactly these Chinese records and their uncritical digestion from Beal onward.
4. **Architectural objections predate us — verified.** Frederick M. Asher (2015), as quoted in the standard references: the excavated viharas "simply cannot support 10,000 or more student monks. The total number of known rooms and their small size is such that either the number of monks must have been far less than Xuanzang's claims or the Nalanda site was many times larger than numerous excavations have so far discovered." The *Indian Express* "History Headline" piece on Nalanda in the Chinese pilgrims' words (23 June 2024) likewise postdates the objection, not originates it.

## A defect this scrub found in OUR build

§3.1 states: "Every population number for Nalanda's peak comes from exactly three men in one 50-year window." **That is wrong.** Daoxuan (d. 667) is a fourth contemporary, number-bearing witness (>4,000 resident monks), and he appears nowhere in the Nalanda dataset (`numbers.csv`, 49 rows) or the source census in `NALANDA-STATS.md`. The census's completeness claim ("every number the sources give") does not survive its own criterion until Daoxuan is added and graded (suggested grade: PROBABLE-to-RHETORIC — contemporary, well-placed, but second-hand for Nalanda and internally split between 4,000 residents and a myriad total).

## Per-part grades

### (a) The attribution correction (10,000 is Huili's, not Xuanzang's)
**Grade: ALREADY PUBLISHED.** Forcing priors: Beal 1884/1911; Dutt 1962; Deeg 2018.
Note: the paper itself already concedes this — §1.1: "None of this is new in the primary literature: Beal's translations already carry the contrast… and we claim no novelty for the attribution itself"; §3.2: "the Huili-not-Xuanzang attribution is already in Beal (1884; 1911) and is not a finding of this audit." The novelty failure the reviewer identifies is real only in the **site/dashboard presentation**, which headlines the attribution as a finding (see wording changes below).

### (b) The persistence claim ("textbooks still credit Xuanzang")
**Grade: NARROWED BUT OPEN — and currently asserted beyond our evidence on the site.**
The paper does *not* assert it: §3.2 ends "the underlying records contain no textbook survey; we flag that documentation as a gap (§6) rather than assert it," and limitation (8) repeats this. The site and dashboard README *do* assert it, as a headline, with no survey behind it. Spot checks during this scrub show the phenomenon is real in educational/popular materials — exam-prep sites (testbook, Brainly, careericons) attribute "10,000 students" to Hiuen Tsang as an exam answer; a Marcellus/Print long-read says "Xuanzang claims there were nearly 10,000 resident disciples" — but anecdotes are not the survey the claim's wording implies. Surviving seam: a small, defined textbook/exam-material survey would make this claim properly; until then it must be worded as unsurveyed observation, not finding.

### (c) The capacity reconstruction (ceiling <2,000; peak 2,500–4,500 centred 3,000–3,500)
**Grade: NARROWED BUT OPEN.** Forcing prior: Asher 2015 — the *qualitative* capacity objection (excavated rooms cannot hold 10,000) is his, and must be cited as prior, not implied as ours.
What no prior found (after the widened search) does: the quantified reconstruction itself — 205 plaque-counted cells in 6 of 11 viharas extrapolated to an estimated 450–650 cells site-wide; design capacity 450–650 at one monk per cell; absolute ceiling below 2,000 even at 3-per-cell crowding; the independent endowment cross-check (epigraphic rate ~6–12 monks/village from Devapāla's plate vs Huili's implied 100/village — Huili refuted by Huili's own endowment); the measured master-to-disciple inflation coefficient (~3.3) located in the Xuanzang→Huili step; and the graded interval peak (2,500–4,500, centred 3,000–3,500) assembled from the surviving witnesses. This, plus the set-level audit of 49 graded quantities, is the surviving seam of the Nalanda section.

## Is the reviewer's "Remove" verdict fair?

**Fair for the attribution, as a discovery claim — and the paper never made that claim.** Partly unfair applied to the Nalanda section as a whole: the quantified capacity reconstruction and the audit-as-a-set survive, narrowed by Asher. Where the verdict lands cleanly is on the **portfolio presentation**: the site features "Nalanda's numbers" under the attribution headline, which is exactly the part that is 140 years old. The fix is re-heading, not removal.

## Exact wording changes required

1. **Site card + dashboard README heading** — replace:
   > "Textbooks still credit Xuanzang with a number he never gave"
   with:
   > "Nalanda's excavated plant cannot hold its received number"
   and replace the body sentence "…yet modern textbooks still credit it to Xuanzang himself" with:
   > "The attribution itself is old scholarship (Beal, 1884/1911); what this audit adds is the test: a plaque-counted capacity ceiling below 2,000 residents and a graded peak of 2,500–4,500, centred on 3,000–3,500. The 10,000 is still routinely credited to Xuanzang in exam-prep and popular materials — a persistence we document anecdotally; no textbook survey has been run."
2. **Site highlights line** — replace "Nalanda's 10,000 traced — to Huili's biography, not to Xuanzang, where textbooks put it" with "Nalanda's 10,000 tested — Huili's figure (Beal, 1911) against a sub-2,000 excavated capacity ceiling."
3. **Paper §3.3 (capacity)** — add Asher as the prior for the qualitative objection, e.g. after the ceiling statement: "(The qualitative form of this objection — that the excavated rooms cannot house 10,000 — is Asher's (2015); the quantification here, and the endowment cross-check in §3.4, are this build's.)"
4. **Paper §3.1 + dataset** — correct "exactly three men" to four witnesses; add Daoxuan (*Xu Gaoseng Zhuan*, T 2060 juan 4: >4,000 resident monks; residents-and-visitors total in the tens of thousands) to §3.1's witness list, §3.2's comparison, and `numbers.csv`, graded, before any re-issue.
5. **Paper references** — add: Asher (2015) on Nalanda's testimony and plant; Deeg (2018), "Setting the 'Records' Straight," pp. 105–140; Daoxuan, *Xu Gaoseng Zhuan* (T 2060), Nalanda passage.

*Addendum prepared 2026-11-18. No files were edited beyond this addendum; the wording changes above are specified, not applied.*
