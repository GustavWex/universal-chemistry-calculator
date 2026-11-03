# Universal Chemistry Calculator

**An offline calculator for DTU course 26022 Kemi (Polyteknisk grundlag).**
One HTML file covering every calculation in the course, showing the working for each
answer rather than just the number. It runs in any browser with the network switched off.

**[Open it in your browser](https://GITHUB_USER.github.io/universal-chemistry-calculator/)**, or
download [`universal-chemistry-calculator.html`](universal-chemistry-calculator.html) and
double-click it.

> A study aid written by a student, not affiliated with or endorsed by DTU. Check what it gives
> you against your own working, and follow your course's rules on which aids are allowed.

## Why it exists

The 26022 exam is multiple choice and allows offline aids. Most online chemistry
calculators are a separate page per formula, need an internet connection, and stop at the
number. This one:

- **Works offline, in one file.** No installation, no network, no storage. It behaves the
  same on an exam laptop with everything locked down.
- **Lets one equation drive every tool.** Type a reaction once and the balancer,
  stoichiometry, equilibrium, ICE table, Kc/Kp and enthalpy tools all use it.
- **Shows its working.** Every result comes with the formula used, the substituted numbers,
  and a note when an approximation is involved or a common trap is near.
- **Searches in Danish and English.** Paste the wording of a question into the index and it
  finds the tool for it.
- **Is checked against past exams.** All 160 questions from eight past 26026/26027/26028
  exam sets (2016 to 2024) were run through it. Every calculation question gives the answer
  in the key.

## What it covers

97 tools in 17 tabs, following OpenStax *Chemistry 2e* and the 26022 syllabus:

| Tab | Examples |
|---|---|
| Composition, Name | Molar mass, percent composition, hydrates, nomenclature both ways |
| Atoms, Quantum | Isotopes, average atomic mass, electron configurations of atoms, ions and compounds, s/p/d/f counts, quantum numbers, photons, photoelectric effect, Bohr, de Broglie |
| Bonding | Lewis structures with formal charges and expanded octets, VSEPR shape and polarity, MO bond order, bond enthalpies, ionic character, lattice energy |
| Balance, Stoichiometry | Balancing, including redox in acidic or basic solution; limiting reactant, yield, gas volumes and air requirement |
| Solutions | Molarity, dilution, titration, Henry's law, colligative properties (with hydrates and ranking several solutions), osmotic pressure |
| Gases | Ideal and real gases, gas laws, Dalton, effusion, vapour pressure, phase changes, unit cells and crystal density |
| Kinetics | Rate laws from data, integrated rate laws, half-life, Arrhenius (fit, two-point, prediction) |
| Equilibrium | K expressions, Q and direction, exact ICE solutions, Kc/Kp, coupled reactions, Le Châtelier for gases, saturated salts and linked equilibria |
| Acids | pH, weak acids and bases, buffers and buffer capacity, salts, titration curves, Ksp, solubility and pH, precipitation, complex ions |
| Electro | Galvanic cells with balanced overall equations, Nernst, a table of 54 reduction potentials, oxidising-agent ranking |
| Complexes, Organic | Naming, crystal field splitting and unpaired electrons, isomers, colour; IUPAC names to structures and back, functional groups |
| Thermo, Analysis | Calorimetry, Hess's law, formation enthalpies, ΔG, K and Q, combustion analysis, empirical formulas |

## Using it

1. Type a formula or an equation in the box at the top of the page.
2. Pick the tab, or search the index for the words in the question.
3. In most tools you **leave the box you want empty**, and it is calculated from the others.
   Change any input and the answer follows.

Every constant the tool fills in (Ksp, Ka, E°, Kf …) can be overwritten. If the exam prints
its own value, type that one in.

To run it from the source, open `universal-chemistry-calculator.html` directly. There is
nothing to build.

## Data and credits

Thermodynamic tables and reference data are from [OpenStax *Chemistry 2e*](https://openstax.org/details/books/chemistry-2e),
licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Any transcription
errors are this project's.

## Licence

[MIT](LICENSE) © 2026 Gustav Bonnesen Wex. Corrections and issue reports are welcome.
