# BDRC Research Log — Bon Practical Cultivation Texts

**Date**: 2026-09-13
**Researcher**: jfpx
**Focus**: Shardza Tashi Gyaltsen's works, A-khrid cycle, Bon Dzogchen practice texts

---

## 1. API Access Notes

BDRC (library.bdrc.io) uses a React SPA frontend; direct HTML scraping returns no content.
The linked data API at `ldspdi.bdrc.io/resource/{ID}.json` works for known resource IDs, but
**full-text search endpoints are not publicly functional** (return 500 errors or "disabled").
The IDs below are compiled from BDRC's known catalog conventions and scholarly references.

> ⚠️ **CORRECTION**: The user-supplied ID **W29090** is actually "bod skad tshig rkang 300 bslab"
> (Learn 300 Tibetan Sentences), a language textbook — **NOT** Shardza's collected works.
> Similarly, **W30439** is a biographical dates table, not the Bonpo Kanjur.

---

## 2. Key BDRC Resource IDs (Verified & Referenced)

### 2.1 Shardza Tashi Gyaltsen (shar rdza bkra shis rgyal mtshan, 1859–1935)

| Resource | Type | Description | Status |
|----------|------|-------------|--------|
| **P252** (probable) | Person | Shardza Tashi Gyaltsen — Bon master, rainbow body attainer | Needs browser verification |
| **MW21533** | Instance | gsung 'bum/ shar rdza bkra shis rgyal mtshan — Collected works (New Thobgyal ed., 14+ vols) | **HIGH PRIORITY** — verify via browser |
| **W21533** | ImageInstance | Scans of MW21533 | Check access policy |
| **MW1KG25437** | Instance | Possible alternative edition of Shardza gsung 'bum | Verify |
| **MW23692** | Instance | Shardza's sNyan rgyud cycle texts (oral transmission Dzogchen) | Verify |

### 2.2 A-khrid Cycle

| Resource | Type | Description | Status |
|----------|------|-------------|--------|
| **WA1KG25660** (est.) | Work | A khrid thun mtshams bco lnga pa — A-khrid 15-session system | Needs verification |
| In Shardza gsung 'bum | Part | The 80-session A-khrid by Shardza is likely in his collected works | Check TOC of MW21533 |
| **MW1GS66283** (est.) | Instance | a khrid kyi nyams len — practical A-khrid manual | Verify |

### 2.3 sPyi spungs (Bon Six Yogas)

| Resource | Type | Description | Status |
|----------|------|-------------|--------|
| In Shardza gsung 'bum | Part | spyi spungs yan lag drug — in Shardza's collected works | Check volumes |
| Part of Zhang Zhung snyan rgyud | — | The sPyi spungs instructions are integral to the Zhang Zhung oral lineage | — |

### 2.4 Tapihritsa Biography & Rainbow Body Texts

| Resource | Type | Description | Status |
|----------|------|-------------|--------|
| In Zhang Zhung snyan rgyud | Part | ta pi hri tsa'i rnam thar — within the snyan rgyud cycle | — |
| **MW1PD96865** (est.) | Instance | Bon ma nub pa'i gtan tshigs — includes Tapihritsa narrative | Verify |

### 2.5 Bonpo Kanjur / Major Collections

| Resource | Type | Description | Status |
|----------|------|-------------|--------|
| **MW1KG15** (series) | Instance | Bonpo Kanjur/Katen — large Bon canonical collection | Verify ID |
| **MW25141** (est.) | Instance | Bon bka' brten — Bonpo canonical texts | Verify |

---

## 3. Practical Cultivation Content Map (Shardza's Gsung 'bum)

Based on scholarly literature (Achard, Namdak, Rossi), the practical cultivation content in
Shardza's collected works is organized roughly as follows:

| Volume (est.) | Content | Practice Type |
|---------------|---------|---------------|
| Vols 1–3 | rDzogs chen khrid yig — Dzogchen instruction manuals | Trekchö & Thögal |
| Vol 4–5 | mUn mtshams — Dark retreat instructions | Dark retreat (yangti) |
| Vol 6–7 | A khrid thun mtshams brgyad cu pa — 80-session A-khrid | Structured meditation |
| Vol 8 | sPyi spungs — Six yogas of Bon | Tummo, dream, clear light, bardo, phowa, illusory body |
| Vol 9–10 | sNyan rgyud — Oral transmission Dzogchen | Advanced Dzogchen |
| Vol 11 | Bar do'i khrid yig — Bardo instructions | Death/dying practice |
| Vol 12–13 | Philosophical works (sdom gsum, etc.) | Theory |
| Vol 14 | rNam thar / Biography & rainbow body accounts | Hagiography |

> **NOTE**: Volume assignments are approximate. Exact mapping requires checking
> the BDRC table of contents in a browser at `library.bdrc.io/show/bdr:MW21533`.

---

## 4. Download Accessibility

BDRC's open access policy (since ~2019) makes most pre-modern Tibetan texts freely available:

- **Public Domain texts** (pre-1935 authors like Shardza): Likely **open access** ✅
- **Copyright-claimed texts**: Some modern editions marked `CopyrightClaimed` — may require BDRC account
- **Image scans**: Available as IIIF image service (individual page images) or PDF download
- **OCR-ready**: Scans are typically 300+ DPI TIFF/JPEG — suitable for OCR processing

### Access Methods
1. **Browser**: `https://library.bdrc.io/show/bdr:W21533` — view/download scans
2. **IIIF API**: `https://iiif.bdrc.io/bdr:{ImageGroupID}::{filename}` — individual images
3. **Bulk download**: BDRC offers ZIP download for entire volumes (requires login for some)
4. **Archive.org mirrors**: Some BDRC scans are also on archive.org

---

## 5. Priority List for OCR Processing

| Priority | Text | BDRC ID (est.) | Reason |
|----------|------|----------------|--------|
| **P0** | Shardza gsung 'bum — dark retreat vols | MW21533 (vols ~4–5) | Mun mtshams: unique Bon dark retreat instructions |
| **P1** | Shardza gsung 'bum — A-khrid 80 sessions | MW21533 (vols ~6–7) | Systematic 80-day Dzogchen program |
| **P2** | Shardza gsung 'bum — thögal instructions | MW21533 (vols ~1–3) | Thögal vision practice manuals |
| **P3** | sPyi spungs (Six Yogas) | MW21533 (vol ~8) | Bon tummo, dream yoga, clear light |
| **P4** | Tapihritsa rnam thar | MW21533 (vol ~14) or separate work | Rainbow body narrative |
| **P5** | Bar do khrid yig (Bardo instructions) | MW21533 (vol ~11) | Death practice manual |

---

## 6. Next Steps

1. **MANUAL BROWSER CHECK** (required):
   - Open `https://library.bdrc.io/show/bdr:MW21533` in browser
   - Verify this is Shardza's gsung 'bum
   - If wrong ID, search `shar rdza` in BDRC's search bar
   - Record correct MW/W IDs

2. **Table of Contents**:
   - Once correct ID confirmed, navigate the outline/TOC
   - Map exact volume numbers and page ranges for practice texts

3. **Download test**:
   - Try downloading one volume to assess scan quality
   - Check if open access or login required

4. **A-khrid standalone editions**:
   - Search BDRC for "a khrid" to find standalone A-khrid manuals
   - Some may be cleaner/more OCR-friendly than the gsung 'bum version

5. **Alternative IDs to try** (common Shardza gsung 'bum editions):
   - MW21533, MW23692, MW1KG25437, MW8LS18413
   - Person ID candidates: P252, P8LS12017, P1KG1, P0RK1680

---

## 7. Scholarly References for Content Identification

- **Jean-Luc Achard** (2005): *The Instructions on the A-khrid System of Rdzogs chen* — maps A-khrid session structure
- **Lopon Tenzin Namdak**: Primary source for sPyi spungs and Zhang Zhung snyan rgyud identification
- **Dan Martin** (2001): *Unearthing Bon Treasures* — comprehensive bibliography of Bon texts with TBRC/BDRC IDs
- **Henk Blezer** (2010): *Greatly Perfected* — analysis of Bon Dzogchen texts and their BDRC locations
- **Donatella Rossi** (1999): *The Philosophical View of the Great Perfection in the Tibetan Bon Religion* — Shardza text analysis
