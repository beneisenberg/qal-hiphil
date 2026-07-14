# פָּעַל ⇄ הִפְעִיל — Qal / Hiphil Scene Recognition Game

An interactive, communicative drill for the **qal (active) vs. hiphil (causative)** stem
distinction in Biblical Hebrew. Students match illustrated scenes to conjugated verb
forms — and forms to scenes — across the full range of conjugations (qatal, yiqtol,
vayyiqtol, participle, imperative).

> **Created to supplement [Aleph with Beth](https://freehebrew.online/) Lessons 132–133**
> of their free Biblical Hebrew video program, which introduce the hiphil stem through
> these same active/causative verb pairs. This project is an independent study aid and
> is not affiliated with or endorsed by Aleph with Beth.

## The verbs

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

## Game modes

1. **מֶה הָיָה? (Scene → Form)** — An illustrated scene appears with a pattern label
   (קָטַל, יִקְטֹל, וַיִּקְטֹל, בֵּינוֹנִי, or צִוּוּי). Choose the one form out of four
   (both stems × two conjugations) that says exactly what the scene shows.
2. **מָה הַתְּמוּנָה? (Form → Scene)** — A conjugated form appears; tap the matching
   scene out of four (both stems of two different roots), so root *and* stem both matter.
3. **פָּעַל אוֹ הִפְעִיל? (Speed sort)** — Sixty seconds. Forms in every person and
   conjugation (118 forms total) fly at you; sort each onto the qal or hiphil pile.
   Keyboard: `1`/`←` for qal, `2`/`→` for hiphil.

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
  determinate: the yiqtol/vayyiqtol of עלה (qal יַעֲלֶה = hiphil יַעֲלֶה; וַיַּעַל = וַיַּעַל),
  the qal participles of בא and מת (spelled like the qatal 3ms), and the qal imperative
  of מות.

## Running it

It is a single self-contained `index.html` — no build step, no dependencies beyond
Google Fonts (Noto Serif Hebrew / Spectral) loaded from a CDN.

- **Locally:** open `index.html` in any modern browser.
- **GitHub Pages:** Settings → Pages → deploy from the repository root of the main
  branch. The game will be served at `https://<user>.github.io/<repo>/`.
