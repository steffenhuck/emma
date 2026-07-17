# EMMA — volume-specific notes
# Read PROMPT.txt first. It is the authority on architecture. These notes
# extend it; where they conflict, these notes win for this volume only.

## Dramatic question (volume-specific)

The series asks: can you leave the path the author wrote? Emma sharpens it:
can you leave the path your own ego wrote? The canon path IS the motivated
path — Emma's trajectory through the novel is what a motivated reasoner
does. Escaping requires, at some node, wanting the unflattering truth.

## The two registers split in reliability

- The frame-voice is Emma-shaped: only as reliable as the player's current
  belief state. It does not lie; it misframes. After every flattering
  reading the player takes, the frame-voice ratifies it as obvious.
- The quoted flashes are the truth channel: Austen's actual sentences,
  objective, unfiltered. The attentive player learns to trust the flashes
  over the voice. This is free indirect discourse rendered as mechanics.
- Consequence: flash placement is an epistemic decision, not a texture
  decision. A bad flash choice is a fairness bug. See Stage 1 deliverables.

## Fork taxonomy (closed — do not invent further types)

1. READINGS-FORKS. The player chooses among interpretations of a concrete
   evidence object (the charade, the portrait sitting, the rescue, the
   pianoforte). Never label a fork as a belief ("conclude that...").
   Both readings must be genuinely constructible from what is on screen
   (Kunda's constraint; Austen built the evidence to support this). The
   flattering reading is the wanted one. After the pick, the frame-voice
   ratifies it — that ratification is the asymmetric updating.
2. AVOIDANCE-FORKS. The player chooses between rival positive goods; one
   branch quietly suppresses a truth-channel flash from the record. Never
   label the avoidance as avoidance — no "don't ask", no "look away".
   Costume it as Austen does: as tact, delicacy, or the presence of
   something pleasanter to do ("begin planning the portrait" vs "press
   Miss Bates about Jane's letter"). Scarcity rule: at most 3–4 true
   avoidance-forks in the whole spine, embedded among forks that are mere
   social colour, so the pattern cannot be metagamed. Prying carries its
   own tonal cost (the Box Hill principle): the frame-voice registers
   flinches — Jane's withdrawal, Miss Bates's flutter. Both directions of
   the fork must be genuinely uncomfortable.
3. Ordinary connective tissue per PROMPT.txt.

## Belief dynamics

- ESCALATING PUNCTURES. Beliefs are assets; defence escalates with tenure
  (Rabin–Schrag, Bénabou–Tirole). A contradiction arriving early against a
  young belief can be small. The same contradiction arriving late, against
  a belief the player has ratified repeatedly, must be undeniable — and
  the frame-voice should visibly strain to absorb it before cracking
  (narrate the carriage proposal for a beat as inexplicable rudeness
  before the reframe fails). Emma's revisions are effortful; instant
  corrections are a fidelity error.
- ONE BELIEF PER PUNCTURE. Each fixed point falsifies exactly one belief,
  legibly. Never let a puncture land while three wrong beliefs are live.
- TWO PUNCTURE TEXTURES. (a) Punctured with the evidence on record: the
  flash was quoted; the shame is rereading. (b) Punctured blind: the flash
  was suppressed by an earlier avoidance; the shame is the player's own
  hand in the not-knowing. Same event, different shame. The ledger carries
  the difference (see design object).
- FORECLOSURE. Holding one belief makes rival readings unaffordable
  (dissonance logic). Implement ONLY through menu-shaping and narration-
  filtering: a foreclosed reading never appears as an option at the later
  fork; the flash that would support it is narrated past as insignificant.
  No belief-state bookkeeping, no inspectable state machine.
- ACTION SUPPRESSION. Beliefs suppress informative actions. Emma never
  asks Harriet what Elton precisely said; the direct question is the one
  action that could bankrupt the asset. Implement as UNTHINKABLE options:
  absent from the menu entirely, never shown-and-locked. This is fair by
  construction — the player cannot resent losing an option she never saw,
  just as Emma cannot resent not asking a question that never occurred to
  her. Menu width is thereby a diegetic display of belief state: the
  attentive player who notices direct questions have stopped appearing
  has diagnosed her own position from inside it.

## Escape corridors

- Corridors are gated by preserved thinkability. A player who has taken
  every flattering reading and every graceful avoidance arrives late with
  a menu as narrow as Emma's: the corridors have foreclosed themselves and
  the canon is simply all that is left. Escape is available only to the
  player who chose discomfort early. The comedy does not punish escape;
  it makes escape rare.
- Corridors darken, but as genuine elsewheres, never punishments. The dark
  exits are already standing inside Highbury as warnings the comedy walks
  past: Jane Fairfax's governess fate, Miss Bates's garrulous poverty. An
  escape ending in the Bates parlour is not a mistake; it is the novel's
  own shadow. Corridor premises remain uncurated per PROMPT.txt.

## Strands and node budget

Spine: 30–40 nodes. Three error strands, unequal treatment:
- ELTON: full treatment (setup, misreading, puncture). It comes first, is
  cleanest, teaches the mechanic, and sets the asset base that determines
  late-game menu width.
- FRANK/JANE: compressed — the player has learned to distrust the voice.
- EMMA'S OWN HEART: belief and fixed point collapse into a single node
  ("It darted through her..."). No scaffolding.
Discard whole plot-lines as needed to hold the spine. Early nodes do
double duty: teaching the mechanic AND setting the foreclosure base.

## Design object and diegetic state

- Object imitated: the riddle-book. Emma is a novel of word games misread
  (the charade, the alphabet puzzle, Box Hill).
- State-carrier: Emma's private ledger of matches made. Reality
  progressively strikes entries through. Struck-through entries mark
  punctures-with-evidence; entries never written mark punctured-blind.
  No meter, no number, ever.
- Second state display: menu width itself (see action suppression).

## No economics leakage

No fork may read as an information-acquisition decision with a price. The
player must be able to play the whole game without ever seeing the
machinery named. The self-deception works only while unobserved.

## Stage 1 deliverables (in addition to PROMPT.txt's list)

1. FLASH PLAN: which Austen sentences enter the truth channel, at which
   nodes, and which avoidance-forks can suppress which flashes.
2. FORECLOSURE TABLE: which early choices foreclose which late readings,
   options, and corridors. This cannot be patched after the graph is
   drawn; it gates approval.
3. FAIRNESS CHECK per fixed point: either (a) the puncturing evidence
   appeared in an earlier flash the player saw, or (b) it was suppressed
   by an avoidance-fork the player chose. No third case.
4. PUNCTURE ESCALATION CHECK: for each belief, the sequence of
   contradictions it meets, ordered by the belief's tenure.

## Genre note

The canon ending is the happy one. This volume inverts the series default
without moralising it: following the author is neither maximised nor
punished; it is what motivated reasoning does when left alone.
