# פָּעַל ⇄ הִפְעִיל — Qal / Hiphil Scene Recognition Game

An interactive, communicative drill for the **qal (active) vs. hiphil (causative)** stem
distinction in Biblical Hebrew. Students match illustrated scenes to conjugated verb
forms — and forms to scenes — across the full range of conjugations (qatal, yiqtol,
vayyiqtol, participle, imperative).

The opening menu offers **two lessons**; each is a self-contained set of qal ⇄ hiphil
pairs with its own deck, legend, and all three game modes. Pick a lesson, play, then
use **← שִׁעוּרִים** to switch to the other.

> **Level 6, Lesson 8** supplements [Aleph with Beth](https://freehebrew.online/)
> Lessons 132–133, which introduce the hiphil stem through these active/causative verb
> pairs. **Level 6, Lesson 9** adds six more high-frequency pairs in the same style.
> This project is an independent study aid and is not affiliated with or endorsed by
> Aleph with Beth.

## The verbs

### Level 6 · Lesson 8

| Root | Qal (active) | Hiphil (causative) |
|------|--------------|--------------------|
| מ־ל־ך | מָלַךְ — to reign | הִמְלִיךְ — to make king |
| שׁ־כ־ב | שָׁכַב — to lie down | הִשְׁכִּיב — to lay (someone) down |
| ר־כ־ב | רָכַב — to ride | הִרְכִּיב — to set (someone) riding |
| ק־ר־ב | קָרַב — to draw near | הִקְרִיב — to bring near / offer |
| ע־ל־ה | עָלָה — to go up | הֶעֱלָה — to bring up |
| י־ר־ד | יָרַד — to go down | הוֹרִיד — to bring down |
| ב־ו־א | בָּא — to come | הֵבִיא — to bring |
| מ־ו־ת | מֵת — to die | הֵמִית — to put to death |

### Level 6 · Lesson 9

| Root | Qal (active) | Hiphil (causative) |
|------|--------------|--------------------|
| י־שׁ־ב | יָשַׁב — to sit / dwell | הוֹשִׁיב — to seat / settle (someone) |
| י־צ־א | יָצָא — to go out | הוֹצִיא — to bring (someone) out |
| ע־מ־ד | עָמַד — to stand | הֶעֱמִיד — to make (someone) stand / station |
| י־ד־ע | יָדַע — to know | הוֹדִיעַ — to make (it) known / inform |
| ה־ל־ך | הָלַךְ — to walk / go | הוֹלִיךְ — to lead / cause to walk |
| י־ל־ד | יָלַד — to bear / give birth | הוֹלִיד — to beget / father a child |

Each Lesson 9 scene keeps the house visual grammar: sitting on a stool (יָשַׁב) vs. seating
another on it (הוֹשִׁיב); walking out of a doorway (יָצָא) vs. leading another out (הוֹצִיא);
standing at a post (עָמַד) vs. raising another to stand (הֶעֱמִיד); a lit "knowing" spark over
one figure (יָדַע) vs. passing that spark to another over a tablet (הוֹדִיעַ); walking a path
(הָלַךְ) vs. leading another along it (הוֹלִיךְ); cradling a newborn (יָלַד) vs. begetting one
through a second parent (הוֹלִיד).

## Game modes

1. **מֶה הָיָה? (Scene → Form)** — An illustrated scene appears with a pattern label
   (קָטַל, יִקְטֹל, וַיִּקְטֹל, בֵּינוֹנִי, or צִוּוּי). Choose the one form out of four
   (both stems × two conjugations) that says exactly what the scene shows.
2. **מָה הַתְּמוּנָה? (Form → Scene)** — A conjugated form appears; tap the matching
   scene out of four (both stems of two different roots), so root *and* stem both matter.
3. **פָּעַל אוֹ הִפְעִיל? (Speed sort)** — Sixty seconds. Forms in every person and
   conjugation fly at you (Lesson 8 draws on 118 forms, Lesson 9 on 93); sort each onto
   the qal or hiphil pile. Keyboard: `1`/`←` for qal, `2`/`→` for hiphil.

## Pedagogical design

- **Visual grammar of causation.** In every scene, one dark figure acting alone = qal;
  a dark figure acting on a second (blue) participant, marked with a gold arrow, = hiphil.
  The same color code carries through the answer feedback and the sorting piles.
- **Leitner-style repeat queue.** Scene modes run as a 16-card session (every root ×
  both stems). A missed card silently re-enters the queue a few cards later and must be
  answered correctly to retire. In speed mode, missed words circle back into the stream.
- **Grade.** Every session ends with a percentage grade, score, and a review list of
  missed forms with full parsing (stem, conjugation, person, root, gloss).
- **No ambiguous forms.** Cross-stem homographs are excluded so every answer is
  determinate. In Lesson 8: the yiqtol/vayyiqtol of עלה (qal יַעֲלֶה = hiphil יַעֲלֶה;
  וַיַּעַל = וַיַּעַל), the qal participles of בא and מת (spelled like the qatal 3ms), and the
  qal imperative of מות. In Lesson 9 every I-yod / I-guttural qal is visibly distinct from
  its הוֹ־/הֶעֱ־ hiphil, so no pairs are dropped; the qal of ילד omits the (rare) participle
  and imperative and is glossed "give birth," with the hiphil הוֹלִיד as the causative
  "beget." The scene shows the qal parent cradling the newborn and the hiphil parent
  begetting one through a second (blue) parent — if you would rather present the qal with
  a feminine subject (יָלְדָה) instead of the default 3ms, that is a one-line change in the
  data table.

## Running it

It is a single self-contained `index.html` — no build step and no dependencies beyond
Google Fonts (Noto Serif Hebrew / Spectral) loaded from a CDN. The Lingua Deo Gloria logo
is embedded directly in the file, so there is no separate image asset to upload.

- **Locally:** open `index.html` in any modern browser.
- **GitHub Pages:** Settings → Pages → deploy from the repository root of the main
  branch. The game will be served at `https://<user>.github.io/<repo>/`.

## Credits & license

Created by Ben Eisenberg for [Lingua Deo Gloria](https://www.linguadeogloria.com/) and
shared freely — copy, use, and pass it on. If it serves you, you can
[support the work here](https://www.linguadeogloria.com/donate).
