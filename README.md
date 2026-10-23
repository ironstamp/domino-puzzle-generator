# Domino Chain Puzzle Generator

A free, browser-based tool for creating printable domino chain matching puzzles for mathematics classrooms. Built with teachers in mind — no installation, no account, no cost.

**[Try it live →](https://ironstamp.github.io/domino-puzzle-generator)**

---

## What is a Domino Chain Puzzle?

Students are given a set of shuffled cards. Each card has an **answer on the left** and a **question on the right**. Students must arrange the cards into a chain so that each answer connects to the matching question on the next card — one card starts the chain and one ends it.

It's an engaging, low-stakes activity that gets students talking, checking each other's work, and reviewing key concepts without it feeling like a worksheet.

---

## Features

- **MathJax rendering** — type equations using `$...$` syntax (e.g. `$x^2 + 3x$`, `$\frac{a}{b}$`, `$\log_2 8$`)
- **Image upload** — attach graphs, diagrams, or worked examples to either side of any card
- **Smart layout** — automatically switches between 3-column (short expressions) and 2-column (images or longer text) based on content
- **Uniform card heights** — all cards in a set are the same size regardless of content length
- **Automatic pagination** — cards flow cleanly across multiple A4 pages with no splitting mid-row
- **Shuffled output** — cards are randomly shuffled each time you generate, so each class gets a different arrangement
- **No reshuffling on reprint** — clicking Print Cards multiple times gives the same shuffle
- **Separate print buttons** — Print Cards for students, Print Key for the teacher (answer key never accidentally goes to students)
- **Answer key** — shows the correct card order (e.g. C → F → A → D…) plus a full detail table

---

## How to Use

### 1. Enter your pairs
Type a question and its matching answer for each row in the sidebar. You can add or remove pairs using the **+ Add Pair** and **✕** buttons.

### 2. Write maths using `$...$`
Wrap any mathematical expression in dollar signs:

| What you type | What appears |
|---|---|
| `$x^2 + 3x - 4$` | x² + 3x − 4 |
| `$\frac{a}{b}$` | a/b (fraction) |
| `$\log_2 8$` | log₂ 8 |
| `$\sqrt{144}$` | √144 |
| `$3^{-2}$` | 3⁻² |

### 3. Upload images (optional)
Click the 📎 button beneath any question or answer field to attach an image — useful for graphs, diagrams, or tables. The image appears on the card alongside any text.

### 4. Configure settings
- **Title / Subtitle** — appears at the top of the printed sheet
- **Student Instructions** — printed below the title
- **Shuffle** — randomises card order before printing (recommended)
- **Include answer key** — adds a teacher-only page with the correct chain order

### 5. Generate and print
Click **Generate ▶** to preview the puzzle. Then use:
- **🖨 Print Cards** — prints only the student cards (answer key hidden)
- **🗝 Print Key** — prints only the answer key page

The puzzle won't reshuffle when you click print — only when you click **Generate ▶** again.

---

## Tips

- Aim for **8–12 pairs** for a typical class activity (10–20 minutes)
- The START and END cards are automatically created — you don't need to add them
- Cards are labelled A, B, C… on the printed sheet; the answer key shows the correct order using these labels
- If you change any pairs or settings, click **Generate ▶** again before printing to rebuild the puzzle

---

## Maths Quick Reference

```
Superscript / power:    $x^2$        $2^{10}$
Subscript:              $\log_2 x$
Fraction:               $\frac{a}{b}$
Square root:            $\sqrt{x}$
nth root:               $\sqrt[3]{x}$
Greek letters:          $\pi$   $\theta$   $\alpha$
Multiplication dot:     $3 \times 4$
Division:               $\frac{a}{b}$
Plus/minus:             $\pm$
Infinity:               $\infty$
```

For a full LaTeX maths reference see [LaTeX Math Symbols](https://www.cmor-faculty.rice.edu/~heinken/latex/symbols.pdf).

---

## Built With

- [MathJax 3](https://www.mathjax.org/) — mathematical typesetting
- Vanilla HTML, CSS, and JavaScript — no frameworks, no dependencies beyond MathJax
- Designed for A4 printing

---

## Licence

Free to use, share, and adapt for educational purposes. If you improve it, please share your version!

---

## More classroom tools

- [Classroom Manager](https://ironstamp.github.io/classroom-tool): post, schedule and copy Google Classroom courses
- [Group Allocator](https://ironstamp.github.io/group-picker): randomly split a class into groups
- [Score Tracker](https://ironstamp.github.io/scoretracker): live projected scores with a countdown timer
- [Tarsia Puzzle Generator](https://ironstamp.github.io/tarsia-generator): printable triangle-matching puzzles

---

*Made by Paul Carter, mathematics teacher, New Zealand.*
