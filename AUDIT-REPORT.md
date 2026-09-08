# Complete Editorial, Linguistic, Pedagogical, and CEFR-Alignment Audit - deutsch-book (A1 + A2)

---

## A. Executive summary

**Overall quality judgment:** This is a genuinely strong, self-study-oriented German textbook. Its pedagogical spine - teach direct chunks, drill with hidden answers, log mistakes with re-test dates, end every file with an actionable cheat sheet - is coherent, learner-friendly, and above the average of AI-assisted course materials. The vast majority of files are well-scoped, correctly labelled, and linguistically accurate.

**Overall CEFR-alignment judgment:** Good but imperfect. The A1 section has a small number of real A2-overload spots (four files), and the A2 section is well-scoped with model "receptive vs active" labelling (genitive, n-Deklination, Futur). No B1 grammar is taught as required A2 mastery.

**Greatest strengths:** the A1 to A2 mistake-log system (A1-M.../A2-M... entries with re-test dates), the sentence-bank/skeleton drilling method, the honest "receptive vs active" framing in A2 genitive and n-Deklination, the consistent chunk-first pedagogy, and the exam-survival files that map grammar directly to telc task types.

**Most urgent problems:**

1. **One fabricated German example** in A2 n-Deklination (section 5, "Mann-en" forms) - the only *linguistically wrong rule table* in the book.
2. **Umlaut-stripped German in an A1 exam file** (speaking-survival.md) - learners memorize wrong forms as exam German ("Mochten Sie?", "Konnte ich...?", "heisst", "naturlich").
3. **A1 word-order.md teaches the whole A2 connector system** (dass/ob/als/damit/bevor/um...zu, als + Präteritum) as A1 production material, duplicating A2 files that teach the same system properly.
4. A handful of factual errors (fünf vor neun = 8:55 not 8:50; three wrong article genders: das Betreff, das Hort, der Familientradition, die Gewitter).

**Is controlled revision needed?** Yes - but it is **local**, not structural. No major rewrite is required. Roughly 8 files need targeted fixes; ~30 need nothing.

**Problem is local or structural:** Local. The skeleton, navigation, and pedagogy are sound. The problems are concentrated in specific files.

**Recommended revision strategy:** (1) fix the linguistic errors first (Section G), (2) relabel/slim the four A1 overload files with explicit "A2 bridge" boxes rather than deleting content, (3) fix the two internal contradictions (Betreff/Hort/Familientradition article tables vs their own examples; nachdem answers vs the M7 rule), (4) leave everything else untouched.

---

## B. Method and limitations

- **Inspected:** all 112 markdown files in `docs/` - every A1 and A2 lesson, INDEX, index, practice log; plus `mkdocs.yml`, `.RULES-FORMATTING.md`, `.RULES-VISUAL.md`, `media/custom.css`, `media/custom.js`. `README.md` does not exist.
- **Every file read:** Yes. Every content file was read in full (some large files like `07-grammar-essentials.md` ~1700 lines were read in full during the session).
- **External standards consulted:** None directly browsable in this session. Placement judgments rely on established German-coursebook sequencing (Goethe-Institut and telc A1/A2 syllabi as commonly published) and are labelled with confidence levels. Where placement is curriculum-dependent (genitive, comparative, two-way prepositions, n-Deklination), the report says so rather than asserting a CEFR law.
- **Files that could not be accessed:** `README.md` (does not exist). Logo/favicon binaries not inspected.
- **Uncertainty:** For "actual level" judgments on features that vary by curriculum I use "typically A2" / "varies". No claim is made that any placement is an absolute CEFR statute.

---

## C. Complete existing-book hierarchy

### Root / shared
- `docs/index.md` (home), `mkdocs.yml` (nav), `.RULES-FORMATTING.md`, `.RULES-VISUAL.md`, `AGENTS.md`, `media/custom.css`, `media/custom.js`.

### A1 (declared A1 unless noted)
| Part | Files | Declared to actual level |
|---|---|---|
| 01-Foundations | 01-numbers-dates, 02-time-words | A1 to A1 (1 factual error in 01) |
| 02-Grammar-Core | 01-cases-articles (A1-A2), 02-possessive, 03-demonstratives, 04-adjective-endings, 05-prepositions (A1-A2), 06-negation, 07-grammar-essentials, 08-indefinite-pronouns | mostly A1; **cases-articles and prepositions include A2 depth** |
| 03-Verbs | 01-conjugations, 02-dative-verbs, 03-accusative-verbs, 04-imperative, 05-tenses, 06-future-werden | A1 to A1 (modal-Perfekt reference table is acceptable reference) |
| 04-Sentence-Building | 01-word-order (A1-A2), 02-question-words, 03-comparative, 04-da-wo-compounds | **01 and 04 include substantial A2 content** |
| 05-Vocabulary-Topics | 01-vocabulary-modules, 02-opposites | A1 to A1 |
| 06-Daily-Communication | 01-daily-conversations, 02-speaking-survival, 03-question-bank | A1 to A1 (02 has umlaut errors) |
| 07-Exam-Mastery | 01-exam-cheat-sheet, 02-exam-writing, 03-writing-survival, 04-horen-survival, 05-lesen-survival, 06-telc-sample-tests | A1 to A1 |
| 08-Practice-Lab | 01-mistakes, 02-sentences, 03-sentence-skeletons, 04-daily-practice (3 logs) | A1 to A1 |

### A2 (declared A2 unless noted)
| Part | Files | Declared to actual level |
|---|---|---|
| 01-Verbs-Tenses | 01-prateritum, 02-perfekt-deep, 03-plusquamperfekt, 04-futur, 05-konjunktiv-II, 06-partizipien | A2 to A2 |
| 02-Sentences-Clauses | 01-zeitangaben, 02-grund-zweck, 03-dass-ob-indirekt, 04-relativsaetze, 05-meinung-connectoren, 06-man-wortstellung, 07-vergleiche-voll | A2 to A2 (1 grammar error in 06) |
| 03-Cases-Articles | 01-wechsel, 02-adjektive-voll, 03-verben-praepositionen, 04-nomen-praepositionen, 05-genitiv, 06-demo-indefinit, 07-n-deklination, 08-zeit-praepositionen | A2 to A2 (07 has fabricated example; genitiv model scoping) |
| 04-Reflexive-Passive | 01-reflexive-basis, 02-reflexive-praepositionen, 03-passiv, 04-passiv-alternativen | A2 to A2 |
| 05-Vocabulary-Topics | 01-15 themed vocab files | A2 to A2 (3 article errors; 1 unnatural chunk) |
| 06-Daily-Communication | 01-alltagsgespraech, 02-telefonieren, 03-reklamation, 04-arzt-bank-amt, 05-kleine-geschichten | A2 to A2 |
| 07-Exam-Mastery | 01-exam-cheat-sheet, 02-lesen, 03-hoeren, 04-schreiben, 05-sprechen, 06-telc-sample-tests, 07-exam-day-pack, 08-timed-mock-test | A2 to A2 |
| 08-Practice-Lab | 01-mistakes, 02-sentences, 03-sentence-skeletons | A2 to A2 (1 answer-key inconsistency) |

**Material whose intended level is unclear:** none found. Every file declares its level in its title or part index.

---

## D. Recommended A1.1-A2.2 curriculum hierarchy (comparison)

Recommended placement of the disputed topics, with current location:

| Topic | Recommended stage | Expected depth | Current location | Action |
|---|---|---|---|---|
| V2, W-questions, yes/no, time-before-place, sentence bracket | A1.1-A1.2 | active production | word-order.md sections 1-5 | **Stay** |
| weil / wenn verb-final | A1.2 | active production | word-order.md section 6 | **Stay** |
| dass, ob, als (past), damit, bevor | A2.1 (dass/ob in A1.2 as recognition) | recognition at A1, production at A2 | word-order.md section 6; A2 02-01/02/03 | **Relabel as A2 bridge** in A1 file |
| um ... zu / ohne zu / anstatt zu | A2.1 | active production at A2 | word-order.md section 6e; A2 02-02 | **Move to A2 bridge box** |
| als + Präteritum (strong) | A2.1 | production at A2 | word-order.md section 6c | **Remove production item from A1** |
| Adjective endings after der / ein | A1.2 | active production | cases-articles sections 7a-7c (der/ein rows) | **Stay** |
| Adjective endings without article (strong) | A2.1 | recognition at A1 | cases-articles sections 7a-7c (no-article rows); A2 02-adjektive-voll | **Mark no-article column as A2** |
| Two-way prepositions Wo/Wohin | A2.1 (chunks at A1.2) | chunk use at A1, system at A2 | prepositions section 3; A2 03-01-wechsel | **Relabel section 3 + complete lists as A2 bridge** |
| da-/wo-compounds | Late A2 / B1 system; 3-5 high-frequency chunks usable at A1 | recognition + chunk memorization | da-wo-compounds.md | **Keep chunks, mark full table + spoken forms A2/reference** |
| Modal double infinitive in Perfekt | A2.2 | reference at A1 (never produced) | tenses.md modal-Perfekt tables | **Stay as reference** (correctly framed) |
| Genitive (names) + von+Dativ | A2.1 | active (names + von), receptive (des Mannes) | A2 05-genitiv | **Stay** (model case) |
| n-Deklination | A2.2 | recognition | A2 07-n-deklination | **Stay, fix fabricated examples** |
| Plusquamperfekt, Futur I, Konjunktiv II, Passiv, Relativsaetze | A2.2 | active production | A2 01-03/04/05, 04-03, 02-04 | **Stay** |
| Pronominal da-forms (spoken drauf/drüber) | Late A2 / daily register | recognition | da-wo-compounds section 4 | **Keep as spoken-register box** |

The A1 files are ~90% in the right place; the fix is *progressive disclosure* (label A2 material as bridges inside the A1 files), not deletion - preserving the book's richness per the project's editorial rules.

---

## E. Coverage matrix (selected topics)

| Topic | A1 coverage | A2 coverage | Depth | Progression | Missing/duplicated | Recommendation |
|---|---|---|---|---|---|---|
| Cases (N/A/D) | cases-articles, grammar-essentials | wechsel, adjektive-voll | full | solid | A1 teaches strong declension early | mark strong column A2 |
| Verb tenses | Perfekt + 3 Präteritum | full Präteritum, PQP, Futur, KII | full | solid | - | keep |
| Subordination | weil/wenn + full system | full system | A1 teaches too much | duplicated | word-order section 6 duplicates A2 02-01/02/03 | relabel A1 section 6 as bridge |
| Prepositions | chunks + full lists | wechsel, temporal | A1 teaches complete lists | duplicated | prepositions sections 3/4 overlap A2 03-01, 03-08 | mark A2 sections as bridge |
| da-/wo-compounds | full system | verbs+prepositions, reflexive+prep | A1 too full | duplicated | da-wo vs A2 03-03, 04-02 | slim to chunks at A1 |
| Adjective endings | der/ein/no-article | all three systems | A1 teaches all three | duplicated | cases-articles vs A2 adjektive-voll | reduce A1 to der/ein |
| Genitive | von+Dativ active, genitive receptive | names active, rest receptive | correct | model | - | keep |
| n-Deklination | - | recognition | shallow but right | fine | - | fix examples |
| Comparative | basic (größer als) | full (als/wie, super) | correct | solid | - | keep |
| Exam skills | telc A1 full pack | telc A2 full pack | complete | solid | - | keep |

---

## F. CEFR-placement findings (the four hypotheses + new ones)

### Hypothesis 1 - `A1/04-Sentence-Building/01-word-order.md` - **CONFIRMED (partly intentional)**
- Title line 1: "Word Order - The Complete Guide **(A1 - A2)**" - the scope is declared, so placement is intentional. But the file is in the A1 path and its section 10 practice demands **active production** of A2 forms.
- Line 111: "Connectors **weil, dass, wenn, ob, als, damit, bevor** send the verb to the END of their clause."
- Line 113: "**The complete list you need at A1/A2**" - dass/ob/als/damit/bevor are typically A2 in Goethe/telc sequencing.
- Section 6c (lines 152-160): teaches **als + strong Präteritum** - "Als ich gestern **ankam**, regnete es" - while `05-tenses.md` line 415 explicitly says "At A1, you do not need to actively use every Präteritum form." **Cross-file contradiction.**
- Section 6e (lines 165-180): teaches **um ... zu + Infinitiv** with production examples.
- Section 10 practice item 13: "When I was little, I played football. **(als + Präteritum)**" to answer "Als ich klein war, **spielte** ich Fußball." - **tested as required A1 production.**
- **Verdict:** weil/wenn = legitimately A1. dass/ob/als/damit/bevor/um...zu = A2 taught and *practised* at A1. Confidence: high.
- **Recommended action:** Relabel sections 6d-6e and the als-Präteritum production item as an explicit "A2 bridge" (recognition), keep weil/wenn active. Cost: none - the A2 files teach the same system fully; benefit: A1 learners stop being tested on forms they are told elsewhere they don't need.

### Hypothesis 2 - `A1/02-Grammar-Core/01-cases-articles.md` - **CONFIRMED (partly intentional)**
- Title line 1: "Cases & Articles - The Complete Guide **(A1 - A2)**".
- Sections 7a-7c (lines 114-147): "Each tab shows ONE gender across **all three systems** (after der, after ein/mein, **after no article**)" with full strong declension: line 122 "no article | alt**er** Mann | alt**en** Mann | alt**em** Mann".
- The A2 file `02-adjektive-voll.md` exists precisely to teach the complete system; the A1 sister file `04-adjective-endings.md` already covers the der/ein basics.
- **Verdict:** the der/ein systems are A1; the no-article (strong) system is A2 taught fully at A1. The section 7d dative-preposition rule ("always -en") is genuinely useful A1/A2 bridge material. Confidence: high.
- **Recommended action:** keep sections 7a-7c but visibly mark the "no article" rows and the complete Dativ paradigm as "A2 bridge - recognize it"; keep 7d active. Benefit: removes false A1 mastery expectation without losing reference value.

### Hypothesis 3 - `A1/04-Sentence-Building/04-da-wo-compounds.md` - **CONFIRMED**
- The file teaches the entire pronominal-adverb system: section 2 "Complete table - the 10 you will hear at A1" (all 10 da-/wo- compounds), section 3 question forms ("**Worauf** freust du dich?"), section 4 spoken short forms (drauf/drüber), and section 6 practice requiring production ("Worauf wartest du?").
- da-/wo-compounds are typically late-A2/B1; telc A1 does not require them. The file itself notes "Highlight the 5 you need first", implicitly acknowledging overload.
- **Verdict:** taught for active production at A1 - confirmed. However the file explicitly ties compounds to already-known chunks (sich freuen auf to darauf), which is pedagogically sound. Confidence: high (breadth), medium (whether 3-5 chunks are acceptable at A1 - some coursebooks do expose Ich freue mich darauf at A1 as a chunk).
- **Recommended action:** reframe as "A1 chunks (darauf, dafür, damit, darüber, davon) + A2 bridge: full table and question forms". Keep the chunk-memorization practice, mark the production of wo-forms (Worauf...?) as A2.

### Hypothesis 4 - `A1/03-Verbs/05-tenses.md` - **REJECTED (correctly handled reference)**
- Lines 1230-1235 do teach the modal double infinitive in full: "Ich **habe** gestern arbeiten **müssen**."
- But line 1707 explicitly says: "At A1 you normally use the Präteritum instead: konnte, musste, wollte, durfte, sollte, mochte", and line 415 states the A1 Präteritum limitation.
- **Verdict:** the modal-Perfekt tables are **reference material with an explicit A1 workaround** - exactly the "complete table as reference" case the audit brief says may protect learners. No exercise tests the double infinitive at A1. Confidence: high.
- **Recommended action:** keep unchanged. Optionally add one line at the top of each modal-Perfekt table: "Reference - at A1 use konnte/musste...", which is already implied.

### New finding 1 - `A1/02-Grammar-Core/05-prepositions.md` - **CONFIRMED (moderate)**
- Title: "Prepositions - The Complete Guide **(A1 - A2)**".
- Section 3 teaches the complete two-way Wo/Wohin system with production practice ("Er legt das Buch auf den Tisch" / "Das Bild hängt an der Wand" as drill items 12-13). Two-way prepositions are typically A2 (telc A1 covers the fixed chunks am/im/um/mit/zu...).
- Section 4 gives complete accusative-only and dative-only lists including **entlang, gegenüber, außer** - beyond A1 scope.
- **Verdict:** the fixed-chunk core (sections 1, 2, 5c nach/zu Hause, 6 contractions) is model A1. Section 3's system and section 4's complete lists are A2. Confidence: high on section 3; medium on section 4 (complete reference lists can be defensible as reference - but they sit in the A1 core path, not a reference file).
- **Recommended action:** keep sections 1/2/5/6 as core; label sections 3 and 4 "A2 bridge - full system in A2 Part 03".

### New finding 2 - `A2/02-Sentences-Clauses/06-man-wortstellung.md` line 16 - **grammar error, not a level issue**
- "Konjunktiv II | **Man** würde nicht **angenommen**. | One would not be accepted." - as written this is not grammatical German (mixing würde + participle without the passive infinitive). See Section G.

### Correctly-scoped advanced material (must NOT be moved)
- `A2/03-Cases-Articles/05-genitiv.md`: titled "A2, Receptive-Active"; produces name-genitive + von+Dativ, recognizes the rest. **Model case.**
- `A2/03-Cases-Articles/07-n-deklination.md` line 3: "At A2 you **recognize** it when you read it" - correct expectation (fix only the fabricated examples).
- `A1/03-Verbs/06-future-werden.md` line 101: "For A1 exam, present + time word is enough. Futur I is your A2 bridge" - **model case.**
- `A1/02-Grammar-Core/01-cases-articles.md` section 8 Genitive + section 9 Relative clauses: "At A1/A2 you do not actively need Genitive... Genitive is B1" and "Relative clauses are A2 - at A1 just recognize them" - **model cases.**
- A1 `07-Exam-Mastery/03-writing-survival.md` line 432 ("könnten wir uns nächste Woche treffen? Ich hätte gerne einen Termin"): polite Konjunktiv II as *fixed A1 exam chunks* - acceptable; telc A1 Sprechen requires exactly these polite formulas. Confidence: medium.

### Late/missing prerequisites
- **No A2 lesson assumes an A1 concept that is missing** - the A2 files consistently reference their A1 foundation (e.g., A2 Part-01 INDEX: "At A1 you learned Perfekt basics, war/hatte/konnte...").
- **No important A1/A2 topic appears entirely missing.** If anything, A1 is over-inclusive (see above). Listening comprehension has no standalone A1/A2 audio component, but that is a resource limitation, not a scoping defect - the Hören-survival files give strategy.

---

## G. Linguistic errors and corrections

| Severity | File and location | Existing text | Problem | Corrected version | Explanation |
|---|---|---|---|---|---|
| **Critical** | `A2/03-Cases-Articles/07-n-deklination.md` section 5, lines 100-103 | "Ich sehe den **Mann-en** / Ich helfe dem **Mann-en** / das Auto des **Mann-en** / die **Mann-en**" | Fabricated forms; **Mann is not an n-Deklination noun** | "Ich sehe den **Jungen** / Ich helfe dem **Jungen** / das Auto des **Jungen** / die **Jungen**" (or use Herr/Kunde/Student) | n-Deklination applies to a closed class (Junge, Herr, Kunde, Student, Kollege, Nachbar, Polizist...). Mann declines regularly: den Mann, dem Mann, des Mannes, die Männer. Teaching Mann-en teaches a false rule. |
| **High** | `A1/06-Daily-Communication/02-speaking-survival.md` lines 226, 504, 516 | "**Mochten** Sie einen Kaffee?" / "**Mochten** Sie auch etwas essen?" | Umlaut stripped *and* wrong tense: mochten = past "liked", not a polite offer | "**Möchten** Sie einen Kaffee?" | This is an exam file; learners memorize these lines as exam German. Both the umlaut and the tense are wrong. |
| **High** | same file, lines 255, 396, 698, 718 | "**Konnte** ich bitte einen Kaffee haben?" | Konnte = Präteritum; polite request needs Konjunktiv II | "**Könnte** ich bitte einen Kaffee haben?" | Exactly the hätte/hadde-type trap the book itself warns about in A2-M2. |
| **High** | same file, lines 118, 141, 157 | "Wie **heisst** ..." | Missing ß | "Wie **heißt** ..." | Spelling. |
| **High** | same file, lines 281, 417, 556 | "**naturlich**" | Missing ü | "**natürlich**" | Spelling. |
| **High** | same file, line 326 | "Ich muss kurz **uberlegen**." | Missing ü | "**überlegen**" | Spelling. |
| **High** | same file, line 548 | "Danke **schon**" | Missing ö | "Danke **schön**" | Spelling. |
| **High** | `A1/01-Foundations/01-numbers-dates.md` line 277 | "fünf vor neun \| 8:50" | Wrong time | "8:55" | Five to nine = 8:55. (Line 278, "zehn vor neun \| 8:50", is correct.) |
| **High** | `A2/02-Sentences-Clauses/06-man-wortstellung.md` line 16 | "**Man** würde nicht **angenommen**." | Ungrammatical: würde + participle without passive infinitive | "**Man** würde nicht angenommen **werden**." (or active: "Man würde einen nicht annehmen.") | würden as passive auxiliary needs werden at the end. |
| **Medium** | `A2/05-Vocabulary-Topics/04-aemter-behoerden.md` line 59 | "**das** Betreff ... **Der** Betreff ist 'Anmeldung'" | Wrong article in table, contradicts its own example | "**der** Betreff" | der Betreff is masculine; the table contradicts itself one column over. |
| **Medium** | `A2/05-Vocabulary-Topics/08-schule-ausbildung.md` line 66 | "**das** Hort ... Das Kind ist **im** Hort." | Wrong article, contradicts example | "**der** Hort" | der Hort; "im Hort" (= in dem) already shows it. |
| **Medium** | `A2/05-Vocabulary-Topics/15-familie.md` line 132 | "**der** Familientradition ... **unsere** Familientradition" | Wrong article, contradicts example | "**die** Familientradition" | feminine (die Tradition). |
| **Medium** | `A2/05-Vocabulary-Topics/01-medien-wetter-termine.md` line 53 | "**die** Gewitter ... **Das** Gewitter ist gefährlich" | Wrong article, contradicts example (and 13-natur-umwelt.md line 25 correctly has das Gewitter) | "**das** Gewitter" | Cross-file gender inconsistency. |
| **Low** | `A2/05-Vocabulary-Topics/09-gesundheit-arzt.md` (Krankmeldung) | "Ich habe **Arbeitsunfähigkeit**." | Unnatural; not how Germans say it | "Ich bin **arbeitsunfähig**." / "Ich brauche eine **Arbeitsunfähigkeitsbescheinigung**." | Abstract-noun construction is non-idiomatic here. |
| **Low** | `A2/05-Vocabulary-Topics/02-verkehr-reisen.md` line 19 | "**die Einfache** Fahrkarte" | Capitalization (and "Hin und Rückfahrt" lacks the required hyphen) | "die **einfache** Fahrkarte"; "die **Hin- und Rückfahrt**" | Compound spelling. |
| **Low** | `A2/05-Vocabulary-Topics/02-verkehr-reisen.md` | Table "Hin und Rückfahrt, bitte" vs practice answer "**Hin und zurück**, bitte" | Inconsistent answer forms | harmonize to "Hin und zurück" | Both are correct German; pick one. |

**No further genuine errors were found** across the other ~90 files. Sentences, answer keys, conjugations, and declension tables checked out. A small number of stylistic preferences (e.g., regional "auf die Hochschule" for "an die Hochschule") are noted as optional, not errors.

---

## H. Pedagogical findings

**What works exceptionally well (must be preserved):**
- **The mistake-log system.** A1-M1... and A2-M1... entries pair a *rule* with Wrong/Right lines and explicit re-test schedules (Day+1/+3/+7). This is genuine spaced-repetition pedagogy, rare in coursebooks.
- **Hidden-answer drilling** (`??? success "Antworten - expand to check"`): forces retrieval before checking - the single best self-study device in the book.
- **Sentence skeletons** (fill-the-slot, one skeleton per conversation): teaches syntactic frames without translationese.
- **Receptive/active honesty** in A2 genitive, n-Deklination, Futur, relative clauses: learners always know what to produce vs recognize.
- **Chunk-first philosophy** ("Learn the chunk, the case sticks"): consistent across prepositions, verbs-with-prepositions, da-forms, and hobby verbs (A2 11-freizeit-sport is a model file - "Ich mache gern Lesen" is explicitly killed with correct alternatives).
- **Real-life context packaging** (Munich, Erika-Mann-Straße 12, Check24, telc tasks) without being forced.
- **Exam mapping:** every survival file ties grammar to a specific telc task type (Teil 1/2/3), with strategies ("Listen ONLY for: Gleis, time, delay, town name").

**Overload risks (measured, not fatal):**
- The four A1 files in Section F teach "complete systems" at A1. They are internally honest about the A1-A2 range in their titles, but a beginner cannot tell reference from required when the same section has both. The fix is labelling, not deletion.
- "Complete guide" titles recur (cases-articles, prepositions, word-order) - fine for reference, risky as the A1 core path. Recommend a "Core vs Bridge" split per file.
- `07-grammar-essentials.md` (~1700 lines) is a genuine reference appendix - its size is justified by function.

**Cognitive load:** generally well-managed. Sections are short, one teaching point per section (rule 15.3 is respected), every section ends actionably.

**Balance of skills:** grammar, vocab, reading, speaking, writing, exam practice all present. Listening is strategy-only (no audio) - acceptable for a text book, worth a note.

---

## I. Cross-file consistency findings

| Severity | Finding | Location |
|---|---|---|
| Medium | word-order.md tests **als + Präteritum production** while tenses.md says A1 need not actively use Präteritum beyond sein/haben/modals | A1 word-order sections 6c/10 vs A1 tenses line 415 |
| Medium | Sentence-bank answers use **Perfekt in nachdem main clauses** ("Nachdem er angekommen war, **haben wir angefangen**") while the book's own rule A2-M7 states "Main clause = **Präteritum**", and skeleton 03 matches the rule | A2 08-Practice-Lab/02-sentences.md block 3 vs 01-mistakes.md A2-M7 |
| Low | `01-conjugations.md` line 150 says the future tense "is B1", while `06-future-werden.md` presents Futur I as the A2 bridge | A1 03-Verbs |
| Low | das Betreff / das Hort / der Familientradition / die Gewitter tables contradict their own example columns | A2 vocab files (see G) |
| Low | "Hin und Rückfahrt" vs "Hin und zurück" answer mismatch | A2 02-verkehr-reisen |
| Positive | A2 Part indexes state their A1 prerequisite and what comes next; rule 15.8 satisfied - **no** "(planned)" files listed as readable | all A2 INDEX files |
| Positive | No broken `.md` links found (checked all relative link targets resolve) | whole docs tree |

---

## J. Strengths worth protecting

1. The **mistake-log + re-test** system (both levels) - never simplify or automate it away.
2. **Hidden-answer drill format** with chunk-based English to German prompts.
3. The **receptive/active labelling model** of A2 genitive, n-Deklination, Futur, relative clauses.
4. The **exam-survival files** and telc task mapping.
5. The **"right verb per hobby"** and chunk-first vocab files (A2 05-11, 03-03, 03-04).
6. The **visual standard** (admonitions, tabs, mark, task lists) - the book renders consistently because of it.
7. The A1 **spoken-vs-exam dialect split** (rule 15.5) executed in daily-conversations and exam files.

---

## K. Prioritized revision backlog

### 1. Accuracy corrections (do first)
| Priority | File(s) | Action | Risk if unchanged |
|---|---|---|---|
| 1 | A2 07-n-deklination section 5 | Replace Mann-en with real n-Deklination nouns | Learners memorize false German |
| 1 | A1 02-speaking-survival (all umlaut/tense spots) | Restore ä/ö/ü/ß; mochten to möchten; Konnte to Könnte | Exam file teaches wrong German |
| 1 | A1 01-numbers-dates line 277 | 8:50 to 8:55 | Factual error in a time table |
| 2 | A2 06-man-wortstellung line 16 | Add "werden" | Grammatically wrong rule table |
| 2 | 4 vocab article errors (Betreff, Hort, Familientradition, Gewitter) | Fix genders; align table+example | Learners internalize wrong genders |
| 3 | A2 09-gesundheit "Arbeitsunfähigkeit" | More idiomatic chunk | Unnatural German in a memorized list |

### 2. Level and labelling corrections
| Priority | File(s) | Action | Risk if unchanged |
|---|---|---|---|
| 1 | A1 word-order sections 6c-6e + practice item 13 | Mark dass/ob/als/damit/bevor/um...zu as "A2 bridge"; keep weil/wenn active; drop als+Präteritum production | A1 tested on A2 grammar it's told it doesn't need |
| 2 | A1 cases-articles sections 7a-7c | Mark no-article (strong) column as A2 bridge | False A1 mastery expectation |
| 2 | A1 prepositions sections 3 + 4 | Mark Wo/Wohin system + complete case lists as A2 bridge | Overload; duplicates A2 03-01 |
| 3 | A1 da-wo-compounds | Reframe as "5 core chunks at A1 + A2 bridge system" | A2-level system demanded at A1 |

### 3. Structural/progression changes
- None required. Navigation, order, and prerequisites are sound. The A1-A2 bridge boxes above are the only structural change needed, and they are in-place relabels, not moves.

### 4. Exercise and answer-key improvements
| Priority | Item |
|---|---|
| 2 | Align A2 sentences.md block-3 answers with the A2-M7 Präteritum rule (or soften M7 to allow Perfekt in speech - pick one and state it) |
| 3 | Harmonize "Hin und zurück" / "Hin und Rückfahrt" |

### 5. Optional polish
- `01-conjugations.md` "future is B1" vs `06-future-werden.md` "A2 bridge" - harmonize wording.
- "auf die Hochschule" to "an die Hochschule" (standard register).
- Remove the duplicated `---` separators in prepositions.md sections 6/7.

---

## L. File-by-file audit ledger (every inspected file)

*Status legend: no issue / minor edit / needs level relabelling / needs partial revision / needs substantial revision / merge candidate / move candidate*

**A1**
- 01-Foundations/01-numbers-dates - minor edit (8:55 fix)
- 01-Foundations/02-time-words - no issue
- 02-Grammar-Core/00-INDEX - no issue
- 02-Grammar-Core/01-cases-articles - needs level relabelling (no-article column to A2 bridge); Genitive/Relative-clause sections already model
- 02-Grammar-Core/02-possessive-articles - no issue
- 02-Grammar-Core/03-demonstratives - no issue
- 02-Grammar-Core/04-adjective-endings - no issue
- 02-Grammar-Core/05-prepositions - needs level relabelling (sections 3/4 to A2 bridge) + minor edit (duplicate separator)
- 02-Grammar-Core/06-negation - no issue
- 02-Grammar-Core/07-grammar-essentials - no issue (model reference; modal-Perfekt tables correctly framed)
- 02-Grammar-Core/08-indefinite-pronouns - no issue
- 03-Verbs/00-INDEX - no issue
- 03-Verbs/01-conjugations - minor edit ("future is B1" wording)
- 03-Verbs/02-dative-verbs - no issue
- 03-Verbs/03-accusative-verbs - no issue
- 03-Verbs/04-imperative - no issue
- 03-Verbs/05-tenses - no issue (double infinitive = correctly framed reference)
- 03-Verbs/06-future-werden - no issue (model bridge)
- 04-Sentence-Building/00-INDEX - needs level relabelling (mirrors word-order scope)
- 04-Sentence-Building/01-word-order - needs level relabelling (sections 6d-6e, als-Präteritum item to A2 bridge)
- 04-Sentence-Building/02-question-words - no issue
- 04-Sentence-Building/03-comparative - no issue
- 04-Sentence-Building/04-da-wo-compounds - needs level relabelling (core chunks vs full system)
- 05-Vocabulary-Topics/01-vocabulary-modules - no issue
- 05-Vocabulary-Topics/02-opposites - no issue
- 06-Daily-Communication/01-daily-conversations - no issue (incidental spoken KII chunks acceptable)
- 06-Daily-Communication/02-speaking-survival - needs partial revision (umlaut/tense repairs; ~10 lines)
- 06-Daily-Communication/03-question-bank - no issue
- 07-Exam-Mastery/01-exam-cheat-sheet - no issue
- 07-Exam-Mastery/02-exam-writing - no issue
- 07-Exam-Mastery/03-writing-survival - no issue (fixed KII chunks appropriate for A1 telc)
- 07-Exam-Mastery/04-horen-survival - no issue
- 07-Exam-Mastery/05-lesen-survival - no issue
- 07-Exam-Mastery/06-telc-sample-tests - no issue
- 08-Practice-Lab/00-INDEX - no issue
- 08-Practice-Lab/01-mistakes - no issue (model)
- 08-Practice-Lab/02-sentences - no issue
- 08-Practice-Lab/03-sentence-skeletons - no issue
- 08-Practice-Lab/04-daily-practice (3 logs) - no issue

**A2**
- 01-Verbs-Tenses/00-INDEX - no issue (model prerequisite statement)
- 01-Verbs-Tenses/01-prateritum - no issue
- 01-Verbs-Tenses/02-perfekt-deep - no issue
- 01-Verbs-Tenses/03-plusquamperfekt - no issue
- 01-Verbs-Tenses/04-futur - no issue
- 01-Verbs-Tenses/05-konjunktiv-II - no issue
- 01-Verbs-Tenses/06-partizipien - no issue
- 02-Sentences-Clauses/00-INDEX - no issue
- 02-Sentences-Clauses/01-zeitangaben - no issue
- 02-Sentences-Clauses/02-grund-zweck - no issue
- 02-Sentences-Clauses/03-dass-ob-indirekt - no issue
- 02-Sentences-Clauses/04-relativsaetze - no issue
- 02-Sentences-Clauses/05-meinung-connectoren - no issue
- 02-Sentences-Clauses/06-man-wortstellung - minor edit (line 16 "werden")
- 02-Sentences-Clauses/07-vergleiche-voll - no issue
- 03-Cases-Articles/00-INDEX - no issue
- 03-Cases-Articles/01-wechsel - no issue
- 03-Cases-Articles/02-adjektive-voll - no issue
- 03-Cases-Articles/03-verben-praepositionen - no issue
- 03-Cases-Articles/04-nomen-praepositionen - no issue
- 03-Cases-Articles/05-genitiv - no issue (model receptive/active scoping)
- 03-Cases-Articles/06-demo-indefinit - no issue
- 03-Cases-Articles/07-n-deklination - needs partial revision (replace Mann-en examples; scoping itself correct)
- 03-Cases-Articles/08-zeit-praepositionen - no issue
- 04-Reflexive-Passive/00-INDEX - no issue
- 04-Reflexive-Passive/01-reflexive-basis - no issue
- 04-Reflexive-Passive/02-reflexive-praepositionen - no issue
- 04-Reflexive-Passive/03-passiv - no issue
- 04-Reflexive-Passive/04-passiv-alternativen - no issue
- 05-Vocabulary-Topics/00-INDEX - no issue
- 05-Vocabulary-Topics/01-medien-wetter-termine - minor edit (die Gewitter to das)
- 05-Vocabulary-Topics/02-verkehr-reisen - minor edit (einfache Fahrkarte; Hin- und Rückfahrt; answer harmonization)
- 05-Vocabulary-Topics/03-wohnung-umzug - no issue
- 05-Vocabulary-Topics/04-aemter-behoerden - minor edit (der Betreff)
- 05-Vocabulary-Topics/05-beruf-bewerbung - no issue
- 05-Vocabulary-Topics/06-einkaufen-kleidung - no issue
- 05-Vocabulary-Topics/07-arbeit-kommunikation - no issue (model duzen/siezen)
- 05-Vocabulary-Topics/08-schule-ausbildung - minor edit (der Hort; optional an die Hochschule)
- 05-Vocabulary-Topics/09-gesundheit-arzt - minor edit (Arbeitsunfähigkeit chunk)
- 05-Vocabulary-Topics/10-bank-geld - no issue
- 05-Vocabulary-Topics/11-freizeit-sport - no issue (model verb-per-hobby file)
- 05-Vocabulary-Topics/12-nomen-verb-verbindungen - no issue
- 05-Vocabulary-Topics/13-natur-umwelt - no issue
- 05-Vocabulary-Topics/14-gefuehle - no issue
- 05-Vocabulary-Topics/15-familie - minor edit (die Familientradition)
- 06-Daily-Communication/00-INDEX - no issue
- 06-Daily-Communication/01-alltagsgespraech - no issue
- 06-Daily-Communication/02-telefonieren - no issue
- 06-Daily-Communication/03-reklamation-beratung - no issue
- 06-Daily-Communication/04-arzt-bank-amt-erweitert - no issue
- 06-Daily-Communication/05-kleine-geschichten - no issue
- 07-Exam-Mastery/00-INDEX - no issue
- 07-Exam-Mastery/01-exam-cheat-sheet - no issue
- 07-Exam-Mastery/02-lesen-survival - no issue
- 07-Exam-Mastery/03-hoeren-survival - no issue
- 07-Exam-Mastery/04-schreiben-survival - no issue
- 07-Exam-Mastery/05-sprechen-survival - no issue
- 07-Exam-Mastery/06-telc-sample-tests - no issue
- 07-Exam-Mastery/07-exam-day-pack - no issue
- 07-Exam-Mastery/08-timed-mock-test - no issue
- 08-Practice-Lab/00-INDEX - no issue
- 08-Practice-Lab/01-mistakes - no issue (model; note M7 rule vs sentences.md answer)
- 08-Practice-Lab/02-sentences - minor edit (block 3 answers vs M7)
- 08-Practice-Lab/03-sentence-skeletons - no issue

**Root/shared:** docs/index.md - no issue / levels/A1/index.md - no issue / levels/A2/index.md - no issue / mkdocs.yml - no issue / .RULES-FORMATTING.md - no issue / .RULES-VISUAL.md - no issue / media/custom.css - no issue / media/custom.js - no issue / README.md - does not exist (nothing references it).

---

## M. Final verdict

1. **Is the book genuinely suitable for A1 and A2 learners?** Yes. With the 8 small fixes in Section G it would be error-free; even today, >95% of its German is correct, and its method (chunks + hidden drills + mistake log) is unusually well-suited to self-study.

2. **Is the A1 section independently safe and appropriately scoped?** Largely yes, with four exceptions: word-order (sections 6d-6e), cases-articles (no-article declension), prepositions (sections 3/4), and da-wo-compounds teach or test A2 material as A1. None are linguistically wrong; all need relabelling rather than removal. One exam file (speaking-survival) needs umlaut/tense repairs.

3. **Is the A2 section independently complete and appropriately scoped?** Yes. It is complete for its declared scope, contains no B1 grammar as required A2, and models the receptive/active distinction better than most commercial books. One fabricated rule table (n-Deklination Mann-en) and one ungrammatical sentence (man-wortstellung) must be fixed.

4. **Are advanced previews clearly distinguished from required learning?** In the A2 files and in the A1 files' Genitive/Relative/Futur sections, yes - model cases. In word-order, cases-articles, prepositions, and da-wo-compounds, no - the A2 material sits unlabelled inside the A1 core path. That is the single clearest systemic fix.

5. **Are the reported violations confirmed, partly confirmed, or rejected?**
   - word-order.md: **confirmed** (with the qualification that the "(A1 - A2)" title makes it intentional - which is itself the problem).
   - cases-articles.md: **confirmed** (no-article/strong declension; der/ein systems fine).
   - da-wo-compounds.md: **confirmed** (full system + production at A1; core-chunk rationale is legitimate but the file doesn't stop at it).
   - tenses.md modal double infinitive: **rejected as a violation** - it is correctly framed reference with an explicit A1 workaround and no A1 exercise.

6. **Does the book require local corrections, moderate restructuring, or a major rewrite?** **Local corrections.** Eight files need targeted fixes; four need in-place relabelling (no moves, no deletions). No restructuring of the navigation or progression is required.

7. **What should be done first?** (1) Fix the n-Deklination Mann-en examples and the speaking-survival umlaut/tense errors (the only places the book teaches wrong German); (2) fix the three time/gender factual errors; (3) then add the four "A2 bridge" labels.

8. **What should be preserved unchanged?** The mistake-log system, hidden-answer drills, sentence skeletons, the receptive/active framing of A2 genitive/n-Deklination/Futur, the exam-survival files, the visual standard, and the A1 spoken-vs-exam dialect split.

---

### Proposed revision sequence (awaiting approval - no files changed)

1. **Accuracy pass** (Section G rows 1-7): n-Deklination section 5, speaking-survival, numbers-dates, man-wortstellung, four article errors, Arbeitsunfähigkeit chunk.
2. **Consistency pass**: sentences.md block-3 answers vs A2-M7; conjugations "B1 future" wording; verkehr-reisen answers.
3. **Level-labelling pass**: add "A2 bridge" boxes in the four A1 files (keep all content, mark scope).
4. **Optional polish**: register fixes ("an die Hochschule"), duplicate separator cleanup.