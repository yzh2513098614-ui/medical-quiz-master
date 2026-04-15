# Medical Quiz Master - Medical Quiz Practice Skill

> A medical knowledge quiz practice skill supporting medical board exam review, self-directed learning for medical students, and medical knowledge assessment

## Features

- **Quiz System** - One question at a time with progressive difficulty
- **Instant Feedback** - Correct/incorrect judgment, detailed explanations, memory tips
- **Progress Tracking** - Real-time accuracy stats, weakness analysis
- **Wrong Answer Notebook** - Auto-recording, targeted reinforcement
- **High-Frequency Key Points Cheat Sheet** - CSF differentiation, time windows, first-line drugs, characteristic signs

## Project Structure

```
medical-quiz-master/
├── SKILL.md                           # Main skill file
└── references/
    ├── 306_exam_outline.md           # 306 exam outline details
    ├── document_import.md             # Document import guide
    ├── memory_aids.md                # 80 memory aids
    ├── question_templates.md          # Question templates
    └── subjects/                      # 26 subject quick reference
        ├── anatomy.md                 # Anatomy
        ├── anesthesiology.md          # Anesthesiology
        ├── biochemistry.md           # Biochemistry
        ├── dermatology.md            # Dermatology
        ├── diagnostics.md            # Diagnostics
        ├── emergency.md              # Emergency Medicine
        ├── ent.md                   # ENT (Otorhinolaryngology)
        ├── geriatrics.md             # Geriatrics
        ├── immunology.md            # Immunology
        ├── infectious_disease.md     # Infectious Disease
        ├── internal_med.md          # Internal Medicine
        ├── laboratory_medicine.md   # Laboratory Medicine
        ├── medical_humanities.md    # Medical Humanities
        ├── neurology.md             # Neurology
        ├── obstetrics_gynecology.md # Obstetrics & Gynecology
        ├── oncology.md             # Oncology
        ├── ophthalmology.md         # Ophthalmology
        ├── parasitology.md          # Parasitology
        ├── pathology.md            # Pathology
        ├── pediatrics.md            # Pediatrics
        ├── pharmacology.md          # Pharmacology
        ├── physiology.md            # Physiology
        ├── preventive_medicine.md   # Preventive Medicine
        ├── psychiatry.md            # Psychiatry
        ├── rehabilitation.md        # Rehabilitation Medicine
        └── surgery.md              # Surgery
```

## Coverage

| Category | Number of Subjects |
|----------|-------------------|
| Basic Medical Sciences | 5 (Physiology, Biochemistry, Pathology, Anatomy, Pharmacology) |
| Clinical Medicine | 16 (Internal Medicine, Surgery, Neurology, Pediatrics...) |
| Other | 5 (Diagnostics, Infectious Disease, Medical Humanities...) |
| **Total** | **26 Subjects** |

## Usage

### Trigger the Skill

Enter any of the following in Claude Code:

```
出题 (Generate questions)
练习医学知识 (Practice medical knowledge)
考我 (Quiz me)
做几道题 (Do a few questions)
医学quiz (Medical quiz)
神经病学问答 (Neurology Q&A)
```

### Interaction Commands

| Command | Function |
|---------|----------|
| 继续 / 下一题 (Continue / Next) | Show next question |
| 记录错题 (Record wrong answer) | Update wrong answer notebook |
| 复习错题 (Review wrong answers) | Randomly select from wrong answer notebook |
| 停止 / 结束 (Stop / End) | End practice and show summary |

## Question Types

| Type | Description |
|------|-------------|
| Cause/Diagnosis | Asking for causes or pathogenic factors |
| Clinical Presentation | Asking for typical symptoms or signs |
| Differential Diagnosis | Distinguishing similar diseases |
| Test/Diagnosis | Asking for first-choice or confirmatory tests |
| Treatment Principles | Asking for first-choice treatment plans |
| Drug Selection | Asking for first-line drugs |
| Time Window | Asking for critical time points |
| Prognosis | Asking for prognostic factors |

## High-Frequency Key Points Cheat Sheet

### CSF Differentiation Table

| Disease | Appearance | Cells | Glucose | Protein |
|---------|-----------|-------|---------|---------|
| Purulent meningitis | Rice soup-like | Neutrophils ↑↑ | ↓↓↓ | ↑↑↑ |
| Tuberculous meningitis | Ground glass-like | Lymphocytes ↑ | ↓ | ↑ |
| Viral meningitis | Clear | Lymphocytes ↑ | Normal | Normal or slightly ↑ |

### Time Window Summary

| Disease | Time Window |
|---------|------------|
| rt-PA thrombolysis for cerebral infarction | 4.5 hours |
| Arterial thrombolysis for cerebral infarction | 6 hours |
| Mechanical thrombectomy | 6-24 hours (specific conditions) |

### Characteristic Signs/Antibodies

| Disease | Characteristic Marker |
|---------|----------------------|
| Wilson's disease | Kayser-Fleischer ring |
| Neuromyelitis optica | Anti-AQP4 antibody |
| Myasthenia gravis | Anti-AChR antibody |
| Miller-Fisher syndrome | Anti-GQ1b antibody |
| GBS | Albumin-cytologic dissociation |

## Example

```
User: 出题 (Generate questions)
Assistant: 📝 Question #1 (Parkinson's disease)

The three main signs of Parkinson's disease are:

A. Resting tremor, bradykinesia, micrographia
B. Resting tremor, rigidity, festinating gait
C. Resting tremor, rigidity, bradykinesia
D. Rigidity, bradykinesia, masked facies

Please select your answer (A/B/C/D):
```

## Development Info

- **Version**: v1.0
- **Maintainer**: Claude
- **Created**: April 15, 2026
- **Use Cases**: Medical board exams, graduate exam review, self-directed medical learning

## License

MIT
