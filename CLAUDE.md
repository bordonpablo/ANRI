# CLAUDE.md — ANRI Repository Guide

This file provides context for Claude Code about the structure and conventions of this repository.

---

## What This Repo Is

Course repository for **Advanced Geophysical Methods in Natural Resource Investigation (ANRI)**, Module 14506, taught by Prof. Dr. rer. nat. Rainer Herd at BTU Cottbus-Senftenberg (Faculty 2 — Environment and Natural Sciences). Master Environmental and Resource Management (PO 2021). 6 ECTS, max 15 students, taught in English, every semester.

---

## Repository Structure

```
ANRI/
├── README.md           ← main course presentation (permanent)
├── SYLLABUS.md         ← learning outcomes, unit contents, software, references (permanent)
├── ASSESSMENT.md       ← grading criteria, exam modalities, late policy (permanent)
│
├── Units/              ← permanent theoretical content, one folder per unit
│   ├── Unit_01_Introduction_to_Applied_Geophysics/
│   ├── Unit_02_Ground_Penetrating_Radar/
│   ├── Unit_03_GIS_Fundamentals/
│   ├── Unit_04_Magnetometry/
│   ├── Unit_05_Electrical_Resistivity_Tomography/
│   ├── Unit_06_Airborne_Magnetics_and_Radiometrics/
│   └── Unit_07_Additional_Topic/
│
└── Semesters/          ← semester-specific content (schedule, assignments, announcements)
    ├── 2025_SS/        ← past (1st offering) — README only
    ├── 2025-2026_WS/   ← past (2nd offering) — README only
    └── 2026_SS/        ← active semester
        ├── README.md
        ├── SCHEDULE.md
        ├── Announcements/
        │   └── README.md
        └── Assignments/
            └── README.md
```

---

## Two Types of Content

| Type | Location | Changes? |
|------|----------|----------|
| **Permanent** | `README.md`, `SYLLABUS.md`, `ASSESSMENT.md`, `Units/` | Rarely — only when course content changes |
| **Semester-specific** | `Semesters/<semester>/` | Every semester |

---

## Semester Naming Convention

- Summer semester: `YYYY_SS` (e.g., `2026_SS`)
- Winter semester: `YYYY-YYYY_WS` (e.g., `2025-2026_WS`)

When a new semester starts, create a new folder under `Semesters/` with the full structure:
```
Semesters/YYYY_SS/
├── README.md           ← semester overview
├── SCHEDULE.md         ← 15-week table linked to unit READMEs
├── Announcements/
│   └── README.md       ← placeholder; announcements added as individual .md files
└── Assignments/
    └── README.md       ← placeholder; assignments added as individual .md files
```

Past semesters keep only a `README.md` noting the offering number and that materials are not archived.

---

## Unit README Template

All `Units/Unit_XX_.../README.md` files follow this standard structure:

```markdown
# Unit XX — [Title]

## Overview
## Learning Objectives
## Key Concepts
## References
```

---

## Course Units (in order)

1. Introduction to Applied Geophysics
2. Ground Penetrating Radar (GPR)
3. GIS Fundamentals
4. Magnetometry
5. Electrical Resistivity Tomography (ERT)
6. Airborne Magnetics and Radiometrics
7. Additional Topic *(selected each semester)*
