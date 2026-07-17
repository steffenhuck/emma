EMMA — revision notes after first build review
INSTRUCTIONS: First, save this entire document verbatim into the repo
as EMMA-REVISIONS.md and commit it, so the revision rationale travels
with the volume. Then apply the revisions below to the existing emma
html in place. The PRESERVE section is binding. When done, run the four
checks at the bottom and report the results before committing the
revised build.
Scope: revise the existing emma html in place. Do not rebuild, do not
restructure the graph, do not touch anything listed under PRESERVE.
EMMA.md and PROMPT.txt remain in force; these notes correct one doctrinal
failure and two small defects in the current implementation.
PRESERVE — verified correct, do not modify

* Menu narrowing via veils (vE, vJ, vH): unthinkable options replaced by pleasanter occupations, never shown-and-locked. Correct throughout.
* Box Hill under S.f.flirt: the one-button insult node. Keep exactly as is.
* Corridor gating (sA1 behind veils()<=1, eB1 behind flirt && !vJ, pP1 behind veils()>=2) and the early planted flash "I who have never seen it!" seeding the sea corridor. Correct.
* The three-way routing of the n34 refusal (pP1 / endAM / endHA). Keep: the endings narrate why the same act means differently, which makes the belief-gates-outcome mechanism legible rather than sneaky.
* The Martin branch (S.f.martin) as an alternate spine that rejoins and reshapes subsequent nodes. Keep; its doctrinal status is deferred.
* Ledger, evidence marginalia, ghost line in two states, frag corridors with lacunae, two-register prose generally.
DEFECT 1 (doctrinal, must fix): readings-forks are decorative
The avoidance-forks write durable state; the readings-forks write only S.mark, which the next node consumes and discards. Consequence: a player who took every clear reading still receives the fully self-deceived frame-voice at the punctures. n13 performs "It was the wine, of course" to a player who watched the compliments land on the artist, carried Knightley's warning, and sat with John Knightley's unease — a belief that player never held. n31 tells the player who left the haircut as an open sum and watched Jane's face at the alphabets that "the shame of the morning was not ignorance — it was rereading," when that player feels vindication. This violates the core rule of EMMA.md: the frame-voice is exactly as reliable as the player's beliefs, and an inference that only tints the next paragraph is not a fork.
FIX — per-strand clarity counters, read only at the punctures:

* Add to state: c:{elton:0, frank:0}. Increment c.elton on the clear readings of the Elton strand (n03 plain, n05 artist, n09 heed / heedM, n11 sat). Increment c.frank on the clear readings of the Frank/Jane strand (n15 armour, n17 noted, n18 sum, n19 campbell / weymouth, n21 broken, n22 poverty / price, n26 message, n27 onecause).
* n13 renders the denial performance in three registers by c.elton: BLIND (0–1): the current text entire — wine, then message-for-Harriet, then the crack. Keep as written. HALF-KNOWING (2): the denials attempted and abandoned faster — the wine offered in one clause and withdrawn in the next; the strain visible, the crack quick. FORESEEN (3+): no denial at all. The proposal narrated as a thing long half-dreaded arriving on schedule — not vindication's comfort but its own distinct dread: she had seen where the compliments landed, and had gone on riding in carriages. The anger is at him alone; the ledger entry for Elton–Harriet still strikes through (Harriet's hope was real regardless), unless S.f.martin.
* n31 renders the overthrow in three registers by c.frank, same logic: BLIND (0–1): current text (both existing variants by S.f.vJ). HALF-KNOWING (2–3): the architecture groans briefly and gives way; the rereading-shame text, but shortened — some pages were half-read. FORESEEN (4+): no overthrow. The news lands as confirmation: the open sum closes, the watched face is explained, the broken sentence completes itself. The register here is quiet — the strange loneliness of having been right about everyone and having said nothing. Then let the one running-ahead thought (Harriet / Knightley per existing flags) land harder for arriving into a mind that is otherwise calm.
* Do NOT thread the counters anywhere else. No other node reads them; no meter, no display, no mention. Frame-voice ratification of flattering readings in intermediate nodes stays exactly as written — ratification is the mechanism; only the punctures must know how often it was refused.
Also, same defect in miniature at n09 (S.f.martin branch): the player who chose heedM ("keep the vicar at a civil distance") must not later be told at n13 that she "let it play about her like weather." Condition that clause on the mark: for heedM, the carriage scene's preamble should note the civil distance kept — and breached anyway, the man undeterred, which is worse.
DEFECT 2: the divergence record miscounts
S.div keeps only the first off-canon reading, and endUNION says "Once — you stepped off her path" to a player who may have strayed a dozen times. The prose comparison replaced the fidelity score so it could tell the truth; it must not miscount.
FIX: add a divergence counter (S.divN, incremented on every canon:false choice; S.div still keeps the first, for the naming). endUNION grades the sentence in three registers: strayed once (current text, now truthful); strayed a few times (2–4: "more than once you stepped off her path, and each time it waited"); strayed habitually (5+: "you doubted her at every riddle, and married where she married anyway" — the comedy as undertow). The other endings use S.div for the parting-point only, which remains correct; check each ending's phrasing still reads true when S.divN is large.
DEFECT 3: rec.walnuts is set and never read
Either surface it or delete it. Preferred: surface it in endAM — the existing "walnuts in the parlour every autumn" clause should appear only if rec.walnuts (the player let Harriet talk in the lane, so the chronicle knows what walnuts meant); otherwise the harvest-supper sentence runs without it. A planted flash paying off in an ending, for the player who chose to hear it, is exactly the house style.
Checks after revision

1. Play the all-clear line (every clear reading, both avoidances refused) through n13 and n31: no sentence anywhere performs a self-deception the player refused. This is the acceptance test for Defect 1.
2. Play the all-canon line: text identical to the current build everywhere except the endUNION grading. Nothing else may change for the canonical player.
3. Play the S.f.martin + heedM line through n13.
4. Confirm no new UI, no new state displays, no counter ever named or shown, node count unchanged.
