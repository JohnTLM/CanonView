# Rewordings: rebirth affirmed conventionally (canon point 20)

**Status: applied** on the website (live site version 70, 2026-10-22). Items 1a–1c are in the Word find-and-replace list,
`drift-replacements-sw-ae.md`, items 5–7.

Canon Part I point 20 affirms karma and rebirth conventionally: one life conditions the next, "as one flame lights
another", with nothing carried and nothing cut off. It does not present rebirth as something emptiness proves. Two texts
stay neutral where the canon now affirms. Both already refuse a carrier, so the changes are small: each keeps the
refusal and adds the conventional affirmation.

Each item gives the place, the current text (verbatim from the live site) and the proposed text. Changed words are
described under "What changes".

---

## 1. *The Logical Necessity of a Substrateless World*, Chapter 8

### 1a. "Death as a Conventional Designation", third paragraph

**Current:**

> The same holds for continuity across death. Whether a continuum is said to go on, and in what form, is answered
> within a paradigm: a physical account traces the dispersal of matter and energy; a Buddhist account traces the karmic
> continuity of a mental stream. Within its own framework, each account can be applied correctly or incorrectly. But
> neither the ending posited by the one nor the continuing posited by the other is found under ultimate analysis. On
> this view there is no production and no cessation other than what is conventionally designated in context;
> ultimately, both are empty.

**Proposed:**

> The same holds for continuity across death. A physical account traces the dispersal of matter and energy, and it is
> right about what it traces. The Buddhist account, which this book follows, traces something the physical one does not
> look for: the karmic continuity of a mental stream, in which one life conditions the next as one flame lights
> another. Each account can be applied correctly or incorrectly, by its own criteria. But neither the ending posited by
> the one nor the continuing posited by the other is found under ultimate analysis. On this view there is no production
> and no cessation other than what is conventionally designated; ultimately, both are empty.

**What changes:** the book now says which account it follows. The physical account is kept as correct about what it
traces, so nothing is claimed against physics. "In context" is dropped from the last sentence, because it read as "true
only within a framework". The emptiness of both the continuing and the ending is unchanged.

### 1b. "Objection: Doesn't This Evade the Question of Rebirth?"

**Current, first sentence:**

> A Buddhist reader may object that treating continuity beyond death as paradigm-relative evades the tradition's
> central claims about karma and rebirth.

**Proposed:**

> A Buddhist reader may object that treating continuity beyond death as designated rather than found evades the
> tradition's central claims about karma and rebirth.

**Current, end of the second paragraph:**

> …there is no birth and no death found from their own side either. Within the Buddhist paradigm, karmic continuity is
> designated across lives and governs practice; a physical paradigm traces continuity through matter and energy. What
> this book claims is only what holds in every framework: whatever is designated as continuing, or as ending, is not
> found when sought.

**Proposed:**

> …there is no birth and no death found from their own side either. This does not leave rebirth in doubt. The book
> follows the tradition: actions bear fruit, in this life and beyond it, and one life conditions the next, as one flame
> lights another. That continuity is affirmed in the same way that the person who wakes is said to be the person who
> fell asleep: conventionally, as designated, and reliably. It is not a conclusion drawn from emptiness. Emptiness
> removes only the objection that rebirth would need a carrier, since nothing has ever had one. What the analysis adds
> holds for every account of death, Buddhist or physical: whatever is designated as continuing, or as ending, is not
> found when sought.

**What changes:** "paradigm-relative" goes, and so does the sentence that set the Buddhist and physical accounts side by
side as equals. The affirmation is stated, and the limit on what emptiness proves is kept (as in *Anatta to Emptiness*,
"At the Edges of Science", "Ordinary Magic"). The last sentence, the book's own claim, stays.

### 1c. Chapter 1, "Rebirth as a traveller" (optional, one phrase)

**Current:**

> Chapter 8 takes up Nāgasena's lamp, which makes the same point—nothing passes over—and shows that death and continuity
> alike are designated within a paradigm.

**Proposed:**

> Chapter 8 takes up Nāgasena's lamp, which makes the same point—nothing passes over—and shows that death and continuity
> alike are designated, not found.

**What changes:** matches 1b. The next sentence, "The tradition affirms rebirth, but not as a journey", already fits the
canon and stays.

---

## 2. Bonus article *Death and Continuity*

### 2a. "Why Experience Needs No Carrier", last sentence of the fourth paragraph

**Current:**

> Death is not the loss of a stored experience by a stored self. It is the ending of a set of conditions for a
> particular vividness.

**Proposed:**

> Death is not the loss of a stored experience by a stored self. It is the ending of a set of conditions for a
> particular vividness, and, as the tradition teaches, a condition for what comes next, as one flame lights another.

**What changes:** death stays an ending of conditions, not a loss suffered by a holder. The added clause stops it from
reading as a full stop.

### 2b. "What Changes in the Dying", second paragraph

**Current:**

> The view does not remove the fear of pain, which is a fear about conditions and can be met by care. It does not make
> the loss of someone we love painless. It does not promise that anything of the person continues as the person, and a
> book that promised that would be claiming a carrier after all. What it removes is one particular dread: the image of
> an experience that is held, a holder who is taken away, and a holding left unfinished.

**Proposed:**

> The view does not remove the fear of pain, which is a fear about conditions and can be met by care. It does not make
> the loss of someone we love painless. It does not promise that the person continues as a carrier, the same one
> travelling on, and a book that promised that would be claiming a self after all. What it affirms, with the tradition,
> is continuity without a carrier: actions bear their fruit, and one life conditions the next, as the flame of the last
> watch follows from the flame of the first. What it removes is one particular dread: the image of an experience that
> is held, a holder who is taken away, and a holding left unfinished.

**What changes:** "anything of the person continues as the person" read as a denial of rebirth. The new wording denies
only the carrier, and states the conventional affirmation with the candle image the article already uses.

### 2c. Last paragraph (no change proposed)

> The view asks nothing of the dying about what comes after…

This can stay. It is about what the dying are asked to believe, not about whether anything follows, and with 2a and 2b
in place it no longer reads as agnostic.

---

## After approval

- **Website:** apply 1a–1c in the `t-sw-8` and `t-sw-1` templates and 2a–2b in the *Death and Continuity* section of
  `index.html`, then rebuild with `split_chapters.py`, test, publish and record the publish in `prog-spec.md`
  (`prog-spec.md` section 6).
- **Word:** add 1a–1c to `drift-replacements-sw-ae.md` for the *Substrateless World* manuscript.
- **Drive:** the *Death and Continuity* Markdown copy then needs uploading again.
- **Canon:** move the two passages in Part III from "still open" to "fixed".
