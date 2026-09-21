# Masaaki Manabe

BEng Computing at Imperial College London, 2025 to 2028. I work on machine learning, systems programming and competitive programming, and I build mobile apps.

## Experience

**Data Specialist Intern, Indeed (Recruit Group)**, Tokyo, July to August 2026
- Distilled a teacher model into an open-source LLM text classifier for Indeed's job search, cutting inference cost from 13.8 to 2.7 USD per 1,000 classifications while matching the teacher's ROC AUC (0.75 against 0.74, up from 0.60).
- Replaced Cohen's kappa with linear-weighted kappa so that adjacent-class errors cost less than distant ones; reached 0.79 against a 0.83 ceiling set by label consistency.
- Built an LLM agent harness in Python that automated the experiment cycle across 10+ open-source base models and RAFT and TRACT training objectives.
- Shipped bug fixes to a separate production product through its Git, Docker and GitHub Actions CI/CD flow.

**Research Member, National Institute of Informatics / JST STELLA Program**, 2024 to 2025
- Estimated which of five guitar effects were applied to a recording, and their parameters, directly from the audio with no clean reference signal.
- Designed a multi-task CNN whose classification outputs gate the regression branch for end-to-end training: 80.7% all-correct accuracy, 20.9% mean absolute error on the parameters.
- Built the PyTorch data-generation and evaluation pipeline over about 40k samples produced with amp simulators.

**Project & Business Intern, VNET Group**, 2024
- Market research and investment evaluation for a data-centre operator's entry into Japan; Japanese-English interpretation with industry executives.

## Projects

**ARMv8 AArch64 emulator and assembler in C**, Imperial College London, 2026
- Group of four. I wrote the emulator's system-state definition and accessors that the rest of the code was built on, and the assembler's two-pass loop and label symbol table.
- Worked through a GitLab merge-request flow with peer review; finished my emulator component early and handled most of the merges.

**[Sando: social calendar application](https://github.com/JOIMathProject/calendar_sharing)**, May 2024 to January 2025
- Top 24 of 1,000+ applicants in Appli Koushien, a national app development competition in Japan.
- Led a team of three, later four, recruited from Japanese Olympiad in Informatics finalists. Built the Flutter frontend and the Google Calendar integration: OAuth 2.0, Calendar API, push notifications over polling, so users keep their existing calendar.
- Scheduling constrained by weather, participants and time; in-app chat; free/busy-only sharing.

**[Competitive programming](https://github.com/Romasa102/CompetitiveProgramming)**
- C++ solutions from AtCoder and other contests, ongoing.

## Awards

- Japanese Olympiad in Informatics, Final Round B rank, 2024: top 104 of 1,366 second-round entrants.
- Canadian Senior Mathematics Contest, International Student Honour Roll, 2024.
- AMC 12, AIME Qualifier, 2023.
- Deep Learning course, Matsuo-Iwasawa Lab, University of Tokyo, 2024.

## Languages and tools

- Primary: C++, Python
- Also: C, JavaScript, Kotlin, Haskell, SQL, Dart with Flutter, C#, HTML
- ML: PyTorch, LLM fine-tuning and distillation, natural language processing, CNNs
- Infrastructure: Unix/Linux, Git, Docker, GitHub Actions CI/CD, Google Cloud (GCS, Workbench, BigQuery)

## Contact

- masaaki.manabe25@imperial.ac.uk
- [LinkedIn](https://www.linkedin.com/in/masaaki-manabe-217745317/)
