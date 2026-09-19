# OCR Quality Baseline Report

**Generated**: 2026-09-18T22:56:35.191334

**Methodology**: Sampled every 20th page. Graded A(Good)/B(Partial)/C(Poor)/D(Failed) based on OCR output.

## Summary

| Metric | Value |
|--------|-------|
| Total pages sampled | 166 |
| Comprehensible (A+B) | 118 (71.1%) |
| Incomprehensible (C+D) | 48 (28.9%) |

## Grade Distribution

| Grade | Description | Count | % |
|-------|-------------|-------|---|
| A | Good - coherent translation | 40 | 24.1% |
| B | Partial - some meaningful content | 78 | 47.0% |
| C | Poor - mostly garbled | 27 | 16.3% |
| D | Failed - no useful content | 21 | 12.7% |

## Per-Text Breakdown

### W1CZ1000 (Uchen woodblock)
- Total pages: 662
- Sampled: 34
- **Comprehensible: 58.8%**
- A=1 | B=19 | C=7 | D=7
- Distribution: `█▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░░░░·······`
  - █=A(Good) ▓=B(Partial) ░=C(Poor) ·=D(Failed)

### W4CZ332378 (Derge cursive)
- Total pages: 1111
- Sampled: 56
- **Comprehensible: 66.1%**
- A=10 | B=27 | C=11 | D=8
- Distribution: `██████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░░░░░░░░········`
  - █=A(Good) ▓=B(Partial) ░=C(Poor) ·=D(Failed)

### W00EGS1016835 (Ume mixed)
- Total pages: 1508
- Sampled: 76
- **Comprehensible: 80.3%**
- A=29 | B=32 | C=9 | D=6
- Distribution: `█████████████████████████████▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓░░░░░░░░░······`
  - █=A(Good) ▓=B(Partial) ░=C(Poor) ·=D(Failed)

## Content Type Distribution (A+B pages only)

| Type | Count |
|------|-------|
| ritual | 52 |
| prayer | 27 |
| narrative | 19 |
| philosophy | 18 |
| catalog | 2 |

## Key Findings

1. **W00EGS1016835 (Ume mixed)** has the clearest printing and best OCR results
2. **W4CZ332378 (Derge cursive)** is the most challenging due to heavy cursive ligatures
3. **W1CZ1000 (Uchen woodblock)** falls in between — woodblock print is readable but resolution limits accuracy
4. Most 'B' grade pages contain useful Buddhist terminology and topic identification even when full translation fails
5. The OCR pipeline consistently identifies script type and provides honest quality assessments

## Detailed Sample Log

### W1CZ1000

| Page | Grade | Type | Tib.Syl | Chi.Chars |
|------|-------|------|---------|-----------|
| 0001 | D | - | 1 | 14 |
| 0020 | B | ritual | 7 | 78 |
| 0040 | C | - | 0 | 75 |
| 0060 | C | - | 0 | 27 |
| 0080 | C | - | 0 | 28 |
| 0100 | B | narrative | 4 | 75 |
| 0120 | B | ritual | 6 | 164 |
| 0140 | D | - | 0 | 4 |
| 0160 | B | ritual | 5 | 98 |
| 0180 | B | philosophy | 4 | 78 |
| 0200 | D | - | 0 | 4 |
| 0220 | B | ritual | 0 | 70 |
| 0240 | D | - | 0 | 4 |
| 0260 | B | philosophy | 5 | 90 |
| 0280 | B | ritual | 4 | 48 |
| 0300 | B | narrative | 8 | 88 |
| 0320 | B | philosophy | 5 | 72 |
| 0340 | D | - | 4 | 4 |
| 0360 | A | ritual | 11 | 55 |
| 0380 | B | narrative | 8 | 39 |
| 0400 | C | - | 5 | 92 |
| 0420 | B | ritual | 0 | 79 |
| 0440 | D | - | 0 | 4 |
| 0460 | C | - | 6 | 4 |
| 0480 | B | ritual | 6 | 66 |
| 0500 | B | prayer | 4 | 32 |
| 0520 | B | narrative | 6 | 87 |
| 0540 | C | - | 3 | 85 |
| 0560 | B | prayer | 4 | 108 |
| 0580 | B | narrative | 12 | 36 |
| 0600 | B | ritual | 7 | 111 |
| 0620 | D | - | 0 | 4 |
| 0640 | B | prayer | 5 | 36 |
| 0660 | C | - | 9 | 28 |

### W4CZ332378

| Page | Grade | Type | Tib.Syl | Chi.Chars |
|------|-------|------|---------|-----------|
| 0001 | D | - | 1 | 8 |
| 0020 | D | - | 0 | 4 |
| 0040 | C | - | 0 | 26 |
| 0060 | B | ritual | 10 | 52 |
| 0080 | C | - | 7 | 32 |
| 0100 | D | - | 0 | 4 |
| 0120 | B | philosophy | 6 | 48 |
| 0140 | D | - | 0 | 4 |
| 0160 | B | prayer | 9 | 50 |
| 0180 | B | narrative | 14 | 107 |
| 0200 | C | - | 0 | 22 |
| 0220 | B | prayer | 7 | 85 |
| 0240 | D | - | 0 | 4 |
| 0260 | B | ritual | 5 | 77 |
| 0280 | D | - | 0 | 4 |
| 0300 | B | narrative | 5 | 73 |
| 0320 | B | prayer | 8 | 79 |
| 0340 | B | ritual | 7 | 89 |
| 0360 | A | ritual | 16 | 76 |
| 0380 | C | - | 3 | 22 |
| 0400 | C | - | 5 | 33 |
| 0420 | A | narrative | 28 | 110 |
| 0440 | B | prayer | 3 | 98 |
| 0460 | D | - | 0 | 4 |
| 0480 | B | ritual | 0 | 115 |
| 0500 | B | narrative | 10 | 103 |
| 0520 | A | ritual | 13 | 53 |
| 0540 | A | narrative | 13 | 67 |
| 0560 | B | ritual | 0 | 112 |
| 0580 | B | ritual | 5 | 69 |
| 0600 | B | ritual | 5 | 83 |
| 0620 | C | - | 0 | 25 |
| 0640 | D | - | 0 | 4 |
| 0660 | A | narrative | 30 | 190 |
| 0680 | C | - | 4 | 23 |
| 0700 | B | philosophy | 0 | 53 |
| 0720 | B | catalog | 6 | 81 |
| 0740 | B | prayer | 11 | 95 |
| 0760 | B | prayer | 6 | 35 |
| 0780 | B | ritual | 11 | 86 |
| 0800 | B | narrative | 6 | 50 |
| 0820 | B | ritual | 7 | 81 |
| 0840 | C | - | 9 | 69 |
| 0860 | C | - | 0 | 28 |
| 0880 | B | ritual | 7 | 90 |
| 0900 | B | ritual | 5 | 89 |
| 0920 | A | narrative | 21 | 137 |
| 0940 | B | ritual | 0 | 98 |
| 0960 | C | - | 1 | 17 |
| 0980 | A | ritual | 19 | 138 |
| 1000 | A | prayer | 17 | 132 |
| 1020 | C | - | 10 | 12 |
| 1040 | A | prayer | 11 | 115 |
| 1060 | A | ritual | 24 | 172 |
| 1080 | B | narrative | 6 | 50 |
| 1100 | B | philosophy | 0 | 32 |

### W00EGS1016835

| Page | Grade | Type | Tib.Syl | Chi.Chars |
|------|-------|------|---------|-----------|
| 0001 | D | - | 1 | 11 |
| 0020 | B | philosophy | 5 | 54 |
| 0040 | A | prayer | 29 | 238 |
| 0060 | A | narrative | 14 | 149 |
| 0080 | C | - | 8 | 126 |
| 0100 | B | philosophy | 8 | 61 |
| 0120 | C | - | 8 | 77 |
| 0140 | B | ritual | 0 | 68 |
| 0160 | A | prayer | 12 | 65 |
| 0180 | B | philosophy | 0 | 31 |
| 0200 | B | ritual | 6 | 35 |
| 0220 | B | ritual | 6 | 131 |
| 0240 | B | philosophy | 6 | 55 |
| 0260 | A | ritual | 15 | 146 |
| 0280 | A | ritual | 15 | 139 |
| 0300 | B | ritual | 4 | 51 |
| 0320 | B | prayer | 5 | 142 |
| 0340 | A | narrative | 26 | 138 |
| 0360 | A | ritual | 24 | 125 |
| 0380 | C | - | 1 | 23 |
| 0400 | B | ritual | 5 | 114 |
| 0420 | A | ritual | 22 | 173 |
| 0440 | B | ritual | 5 | 62 |
| 0460 | D | - | 0 | 4 |
| 0480 | B | prayer | 0 | 87 |
| 0500 | B | ritual | 29 | 150 |
| 0520 | B | philosophy | 8 | 84 |
| 0540 | B | ritual | 5 | 102 |
| 0560 | B | philosophy | 10 | 125 |
| 0580 | B | philosophy | 4 | 108 |
| 0600 | A | ritual | 27 | 178 |
| 0620 | B | narrative | 7 | 64 |
| 0640 | B | prayer | 3 | 89 |
| 0660 | B | ritual | 3 | 102 |
| 0680 | B | ritual | 3 | 39 |
| 0700 | B | ritual | 4 | 83 |
| 0720 | B | narrative | 4 | 53 |
| 0740 | A | prayer | 26 | 120 |
| 0760 | A | ritual | 31 | 179 |
| 0780 | C | - | 8 | 58 |
| 0800 | A | ritual | 25 | 228 |
| 0820 | A | ritual | 12 | 84 |
| 0840 | B | philosophy | 7 | 76 |
| 0860 | C | - | 0 | 24 |
| 0880 | B | ritual | 5 | 85 |
| 0900 | A | ritual | 25 | 212 |
| 0920 | D | - | 0 | 4 |
| 0940 | D | - | 0 | 4 |
| 0960 | B | ritual | 6 | 78 |
| 0980 | B | prayer | 4 | 79 |
| 1000 | B | catalog | 8 | 96 |
| 1020 | A | prayer | 26 | 193 |
| 1040 | A | ritual | 13 | 144 |
| 1060 | D | - | 0 | 4 |
| 1080 | A | prayer | 18 | 114 |
| 1100 | A | philosophy | 17 | 120 |
| 1120 | B | philosophy | 6 | 86 |
| 1140 | A | prayer | 13 | 111 |
| 1160 | B | narrative | 9 | 68 |
| 1180 | B | ritual | 8 | 94 |
| 1200 | A | philosophy | 16 | 131 |
| 1220 | A | ritual | 22 | 134 |
| 1240 | A | prayer | 12 | 117 |
| 1260 | A | ritual | 21 | 166 |
| 1280 | A | prayer | 24 | 184 |
| 1300 | B | philosophy | 6 | 48 |
| 1320 | A | ritual | 21 | 181 |
| 1340 | C | - | 5 | 42 |
| 1360 | A | prayer | 25 | 231 |
| 1380 | C | - | 5 | 40 |
| 1400 | A | prayer | 25 | 183 |
| 1420 | C | - | 9 | 81 |
| 1440 | A | prayer | 27 | 227 |
| 1460 | C | - | 10 | 72 |
| 1480 | D | - | 0 | 4 |
| 1500 | A | prayer | 34 | 208 |
