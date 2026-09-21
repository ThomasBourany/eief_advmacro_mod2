# Advanced Macroeconomics - Part 2

## Fall 2026 - RoME and RED

This course studies macroeconomic frameworks with heterogeneous agents and market frictions. These models are central to the study of business cycles, inequality, shock transmission, and the design of fiscal and monetary policy.

| | |
|---|---|
| **Instructor** | [Thomas Bourany](https://thomasbourany.github.io/) |
| **Affiliation** | EIEF |
| **Email** | [thomas.bourany@eief.it](mailto:thomas.bourany@eief.it) |
| **Term** | Fall 2026 |
| **Programme** | RoME and RED |

To get to know you better, please fill [this survey](https://docs.google.com/forms/d/e/1FAIpQLSdjLK0sITIgqSm1rVTAFKzGOV15HE3dPRMG3QKmjwqLdx0IGg/viewform?usp=dialog) - so that we know your background and interests better. 

## Course goals

By the end of the course, students should be able to:

- work with an important class of heterogeneous-agent macroeconomic models;
- solve these models numerically and use them in quantitative research; and
- engage critically with frontier macroeconomic research.

The course begins with heterogeneity, welfare, and the case for policy; introduces methods for heterogeneous-agent models with aggregate shocks; studies firm heterogeneity and frictions; and then focuses on HANK (Heterogeneous-Agent New Keynesian) models and their implications for monetary and fiscal policy.

## Readings and preparation

The slides are the primary course reference.

\* Required reading. Links point to the journal record when available, or otherwise to the official working-paper page.

- Lars Ljungqvist and Thomas Sargent, *Recursive Macroeconomic Theory* (latest edition).
- Nancy Stokey, Robert Lucas, and Edward Prescott, *Recursive Methods in Economic Dynamics* (1989).
- Marina Azzimonti, Per Krusell, Alisdair McKay, and Toshi Mukoyama, [*Macroeconomics: A Modern Dynamic Approach*](https://phdmacrobook.org/). We may use Chapters 10, 11, 21, and 22, with Chapters 6 and 9 as review. Students are expected to be familiar with Chapters 1-9.

Survey and review articles are strongly encouraged, especially for students preparing a master's thesis or considering PhD research.

## Assessment

| Component | Weight |
|---|---:|
| In-class participation | 10% |
| In-class quizzes | 15% |
| Problem sets and coding exercises | 15% |
| Research proposal or project | 10% |
| Referee report on a recent research article | 5% |
| Final exam | 45% |

### Coursework and submission

- **Participation.** Prepare the assigned readings and participate actively in class, including Friday assignment-review sessions.
- **Quizzes.** Short in-class quizzes cover lectures, previous homework, and required readings.
- **Problem sets and coding exercises.** Students may work alone or in pairs; pairs must identify both authors. Familiarity with a statistical package or programming language such as Matlab, Julia, or Python is expected. LLMs may be used as an aid, but students must remain responsible for the work and must not delegate the assignment to an AI tool.
- **Submission.** Email an individual copy of each problem set with the subject line `Macro Problem Set [#] [your name]`. Late submissions receive a penalty. For a LaTeX-generated submission, include both the PDF and `.tex` source. Paper submissions may be handed in at the instructor's desk on the third floor of the EIEF main building.
- **Research project.** Develop an original idea that could inform a master's thesis or later research. It must set out a well-motivated question and include either an empirical strategy with the required data, a theoretical model and derivation, or a quantitative model to simulate, together with preliminary results.
- **Referee report.** Write a report on an article from a designated list. The report should explain the paper's main contribution and provide constructive criticism and suggestions. Choosing a paper related to the research project is encouraged.
- **Final exam.** The exam is individual and closed-book.

## Course outline

### Theme 1 - Week 1

#### Introduction: heterogeneity, market failures, and frictions

- General-equilibrium theory: welfare theorems, the Negishi theorem, market failures, and efficiency.
- Heterogeneity and aggregation.
- Welfare decomposition: efficiency, redistribution, and insurance. One required reading: \* [Bhandari, Evans, Golosov, and Sargent (2026)](https://www.nber.org/papers/w34907); or [Dávila and Schaab (2025)](https://www.journals.uchicago.edu/doi/10.1086/736211).
- Wedges, shocks, and business cycles.
- If time permits: the scope for fiscal, monetary, industrial, climate, development, and trade policy. Suggested industrial-policy readings include Juhasz, Lane, and Rodrik, *The New Economics of Industrial Policy*, and Bartelme, Costinot, Donaldson, and Rodriguez-Clare, *The Textbook Case for Industrial Policy*.

### Theme 2 - Week 2

#### Heterogeneous-agent models and aggregate dynamics

- Foundations of heterogeneous-agent models and transition paths.
- First-order perturbation, sequence-space Jacobians, Dynare, MIT shocks, and certainty equivalence.
- If time permits: second-order perturbation and global methods with aggregate risk.
- Application: the dynamics of income and wealth inequality.

**Homework 1:** Transition paths and the dynamics of income and wealth distributions in heterogeneous-agent models.

Computational methods for heterogeneous-agent models with and without aggregate risk are covered more extensively in Sara Casella's course.

### Theme 3 - Weeks 3 and 4

#### Firm heterogeneity and frictions: misallocation and market power

- Misallocation: \* [Hsieh and Klenow (2009)](https://academic.oup.com/qje/article/124/4/1403/1917179), alongside related work on firm dynamics and wedges.
- Aggregate trends: rising markups, the declining labor share, concentration, and productivity dispersion. Required reading: \* [De Loecker, Eeckhout, and Unger (2020)](https://academic.oup.com/qje/article/135/2/561/5714769).
- Market power and endogenous markups: \* [Atkeson and Burstein (2008)](https://www.aeaweb.org/articles?id=10.1257/aer.98.5.1998); and \* [Edmond, Midrigan, and Xu (2023)](https://www.journals.uchicago.edu/doi/10.1086/722986).
- If time permits: production networks, Hulten's theorem, and misallocation in networks. \* [Baqaee and Farhi (2020)](https://academic.oup.com/qje/article/135/1/105/5573281).
- If time permits: financial frictions, macrofinance, and empirical work on firm dynamics with financial frictions.

**Homework 2:** A model with a firm-size distribution, productivity and markup heterogeneity, and calibration to firm-level data (Compustat).

Models and empirics of firm dynamics are covered more extensively in Bernardo Ribeiro's course.

### Theme 4 - Weeks 4 to 6

#### Household heterogeneity, nominal rigidities, and HANK policy analysis

- Baseline HANK model: \* [Auclert (2025)](https://www.aeaweb.org/articles?id=10.1257/pandp.20251114).
- Aggregate demand and aggregation: \* [Werning (2015)](https://www.nber.org/papers/w21448); \* [Farhi and Werning (2016)](https://onlinelibrary.wiley.com/doi/10.3982/ECTA11883).
- Quantitative HANK models, including work by McKay, Kaplan, Moll, Violante, and Auclert, Rognlie, and Straub.
- Applications to credit constraints, precautionary saving, redistribution, monetary and fiscal policy, and marginal propensities to consume.
- Optimal policy in HANK models. \* One reading from the indicated set will be selected later.
- Modern empirical work on monetary and fiscal policy.

**Homework 3:** Shock transmission in HANK models and the design of fiscal and monetary policy.

## Course materials

Lecture slides, readings, homework, and other course materials will be made available in this repository during the semester.

## Deadlines

Unless otherwise noted, deadlines are in Rome time. Research-project tasks are due before the Monday lecture of the indicated week.

### Week 0 — week of September 14

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, September 14, 10:00 am | [Homework 0: Onboarding](Homework_0/) | Complete the ungraded review assignment before the morning class. |

### Week 1 — week of November 9

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, November 9, 10:00 am | [Research project — Task 1](Research_project/) | Read at least two research-advice guides, identify a field and keywords, select 3–5 close reference papers in a shared document, and read their introductions carefully. |
| Wednesday, November 11 | In class Quiz 1 | Material from the Homework 0, and the lectures from the week 1 | 

### Week 2 — week of November 16

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, November 16, 10:00 am | [Research project — Task 2](Research_project/) | For each selected paper, write a concise P→R→A: positioning statement, research question, and answer. Use this comparison to develop possible research ideas. |
| Wednesday, November 18 | In class Quiz 2 | Material from the lectures from the week 1 and 2 | 

### Week 3 — week of November 23

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, November 23, 10:00 am | [Research project — Task 3](Research_project/) | Write the ideal P→R→A for your own project and a brief (about half-page) outline of the methodology you would use to answer the question. |
| Tuesday, November 24, 8:00 pm | [Homework 1: Transition dynamics in heterogeneous-agent models](Homework_1_Inequality/) | Submit the assignment on simulating a heterogeneous-agent model and distributional transition dynamics. |
| Wednesday, November 25 | In class Quiz 3 | Material from the lectures from the week 2 and 3 and homework 1. | 


### Week 4 — week of November 30

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, November 30, 10:00 am | [Research project — Task 4](Research_project/) | Refine the P→R→A and methodological outline after further reading and advisor discussions, developing a 2–3 page proposal. |
| Wednesday, December 2 | In class Quiz 4 | Material from the lectures from the week 3 and 4. | 

### Week 5 — week of December 7

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, December 7 | [Research project — Task 5](Research_project/) | Review a colleague’s P→R→A and methodology outline, then submit constructive feedback in a 1–2 page referee-style report. |
| Tuesday, December 8, 8:00 pm | [Homework 2: Heterogeneous firms](Homework_2_HetFirms/) | Submit the assignment on a firm-heterogeneity models. |
| Wednesday, December 9 | In class Quiz 5 | Material from the lectures from the week 4 and 5, and homework 2. | 

### Week 6 — week of December 14

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, December 14 | [Research project — Task 6](Research_project/) | Use advisor discussions, further reading, and peer feedback to revise and expand the proposal to about 4–5 pages. |
| Wednesday, December 16 | In class Quiz 6 | Material from the lectures from the week 5 and 6. | 

### Week 7 — week of December 21

| Due | Item | What to submit or complete |
|---|---|---|
| Monday, December 21, 8:00 pm | [Homework 3: HANK policy analysis](Homework_3_HANK/) | Submit the assignment on monetary and fiscal policy in RANK and HANK models. |

### After the course — January

| Due | Item | What to submit or complete |
|---|---|---|
| Wednesday, January 6, 2027, 8:00 pm | [Referee report](Referee_report/) | Submit a 3–4 page report on a paper from the designated list, summarizing its contribution and offering constructive, actionable comments. |
| TBC, January  | Final Exam | Full content of the class and the homeworks. |
| 1–2 weeks after the final exam (date TBA) | [Research project — final expansion](Research_project/) | Incorporate additional feedback and literature, expanding the proposal into a 5–10 page research-project document. |
