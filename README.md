# BDOIDS Round 1 Tasks

Welcome to the official repository for **Round 1** of the **Bangladesh Olympiad in Informatics Discord Server (BDOIDS)** contest.

As the Problem Setter and Contest Coordinator, I designed the algorithmic tasks, generated rigorous test cases, and managed the technical infrastructure for this event.

This contest was organized for the BDOI Discord community to foster competitive programming skills among students preparing for IOI. We have an amazing family of **600+ members**!

---

## Contest Summary

| Metric | Value |
|---|---|
| Registered Participants | 30+ |
| Submissions | 100+ |
| Official Ranklist | [View here](https://officialrankingbdoids1.vercel.app/) |

---

## Repository Structure

```
├── blackmath/
│   ├── checker/                # checker.cpp, testlib.h
│   ├── solutions/
│   │   ├── incorrect/          # wrong.cpp, wrong1.cpp
│   │   ├── model_solution/     # correct1.cpp
│   │   └── time_limit/         # partial1.cpp, partial2.cpp
│   ├── subtasks/                # 00-samples.json ... 06-6.json
│   ├── tests/                   # 0-01.in/.out ... 6-40.in/.out (200+ files)
│   └── problem.json
│
├── groupchat/
│   ├── checker/                 # checker.cpp, testlib.h
│   ├── solutions/
│   │   └── model_solution/      # correct1.cpp
│   ├── subtasks/                 # 00-samples.json ... 04-4.json
│   ├── tests/                    # 0-01.in/.out ... 4-44.in/.out (180+ files)
│   └── problem.json
│
├── statements/
│   ├── groupchat.pdf
│   ├── math.pdf
│   └── summand.pdf
│
└── summand/
    ├── checker/                  # checker.cpp, testlib.h
    ├── solutions/
    │   ├── model_solution/       # correct1.cpp
    │   ├── partially_correct/    # 50.cpp
    │   └── time_limit/           # brute.cpp, brute50.cpp
    ├── subtasks/                  # 00-samples.json ... 07-st7.json
    ├── tests/                     # 0-01.in/.out ... 7-31.in/.out (280+ files)
    └── problem.json
```

For each problem in this repository, you will find:

1. **Problem Statement** — The exact framing and constraints provided to contestants.
2. **Test Data** — The hidden input/output files used by the grading server to validate participant logic and time complexity.
3. **Reference Solutions** — The optimal code written to verify the problem limits and act as a benchmark for the grading system.

---

## Getting Started

To explore the problems or test your own solutions against the official test cases, clone this repository:

```bash
git clone https://github.com/nabeulislam/BDOIDS-Round1-Tasks.git
cd BDOIDS-Round1-Tasks
```
