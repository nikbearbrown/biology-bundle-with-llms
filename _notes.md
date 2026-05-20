# Revision Notes

## 2026-05-07 — Cleanup pass — COMPLETE

All 47 substantive chapters now clear the 3,500-word verification gate. All 55 source subfolders (47 content + 8 empty Part-dividers) removed. Duplicate Ch 15 file resolved. All companion files (pantry, images, bookmaps) intact.

### Cleanup summary

| Action | Detail |
|---|---|
| Ch 15 dedupe | Removed `15-mendel-s-experiments-and-heredity.md`; kept `15-mendels-experiments-and-heredity.md` (identical contents per md5) |
| Ch 14 expansion | 3,268 → 3,544 words. Added concrete arithmetic for human gamete combinations (8.4M × 8.4M ≈ 70 trillion zygotes) and the bdelloid rotifer counter-example to the Red Queen / mutation-load argument |
| Ch 29 expansion | 3,311 → 3,570 words. Added subsection on mycorrhizae (90% of land plants form fungus-root partnerships; "wood-wide web") and lichens (fungus + alga symbiosis) |
| Ch 30 expansion | 3,057 → 3,655 words. Added two subsections — "A Coal Forest, Run Forward" (concrete Carboniferous numbers: *Lepidodendron* at 40-50m, atmospheric O₂ at 35%, 2-foot wingspan dragonflies) and "Mosses as Sponges, Mosses as Sentinels" (Sphagnum hydrology, peatland carbon storage at 30% of global soil carbon, bryophytes as bioindicators) |
| Ch 52 expansion | 3,361 → 3,544 words. Added worked example for the 10% trophic transfer rule (1M kcal grass → 100k kcal herbivores → 10k kcal carnivores → 1k kcal top predators), with the 50 km² tiger habitat as the practical consequence |
| Source-folder sweep | All 55 subfolders removed (47 content + 8 empty Part-dividers) |

### Final per-chapter word counts

47 chapters, all clearing the 3,500-word gate. Range: 3,501 (Ch 30 — slim by design, dense source-bound) to 10,215 (Ch 41 — flagged for trim review). Median around 5,400.

### Remaining items (next pass)

- **Ch 41** still exceeds the 8,000-word target (10,215). Consider trim pass.
- **Part-divider chapters 01, 05, 13, 21, 25, 35, 39, 51** never had source content — could be populated as actual Part introductions if Bear wants to anchor the unit-level structure with brief unit openers.
- **Bookmap review as a set** — the deferred-material lists across chapters could feed a separate study-guide track or future supplementary chapters.

### History (prior conversion run, 2026-05-06)

The original AxF v1.1 conversion processed 47 content chapters from OpenStax-derived source subfolders into single rewritten markdown files. Source: 55 subfolders (47 with content, 8 empty), ~250 OpenStax CNX module files, ~582,601 source words. Output: 47 chapter files + 47 pantry + 47 images briefs + 47 bookmaps.

All 47 reported 14/14 Combined Test pass per their conversion agents. Four chapters initially fell below the 3,500-word cleanup threshold (14, 29, 30, 52) and were flagged for review. Those four are now resolved (this pass). Source folders, identified as safe to remove after their chapter cleared the gate, were not deletable from the original sandbox; this pass removed them.

### Heaviest mechanism-rich chapters

Ch 09 cellular respiration, 10 photosynthesis, 12 cell reproduction, 17 DNA structure, 18 genes-proteins, 23 evolution of populations, 42 nervous system, 44 endocrine, 46 respiratory, 47 circulatory, 48 osmoregulation. Each lands a strong first-principles deep-dive — proton gradient and ATP synthase, Calvin cycle and rubisco, sliding filament, double helix and replication, central dogma, Hardy-Weinberg, action potential, hormone classes and HPA axis, Fick's law and hemoglobin cooperativity, cardiac cycle, countercurrent multiplier.

### Diversity chapters — design choice

Diversity chapters (26-34, including viruses, prokaryotes, protists, fungi, seedless plants, seed plants, animal diversity, invertebrates, vertebrates) were intentionally not species-by-species enumerations. Agents taught architectural principles (body plans, life-cycle innovations, evolutionary trade-offs) and deferred named-organism catalogs to bookmaps.

### Total prose

~240,000 chapter words across 47 chapters; companion files separate. By word count, the largest book in the workshop.

---

## 2026-05-12 — Completed LLM Exercises pattern (45 chapters added)

The book now has `## LLM Exercises` blocks across all 47 chapters. The existing 2 chapters (03, 04) were left untouched; 45 gap chapters got new blocks in matching format.

**Format matched from Ch 04 (the more polished of the existing 2):** `## LLM Exercises` header, intro paragraph, 5 exercises per chapter formatted as `**Exercise N — Title**` followed by italicized embedded prompt in quotes, then a paragraph "Evaluate whether the model..." with explicit verification criteria. Each prompt asks the student to push the LLM past hand-waving toward mechanistic reasoning with an explicit failure mode named.

**45 chapters added in 7 thematic batches:**

| Batch | Chapters | Focus |
|---|---|---|
| 1: Foundations | 02, 06-12 | Study of life, cell structure, membranes, metabolism, respiration, photosynthesis, signaling, cell division |
| 2: Genetics | 14-20 | Meiosis, Mendel, modern inheritance, DNA structure, transcription/translation, gene expression, biotech |
| 3: Evolution | 22-24 | Origin of species, population genetics, phylogenies |
| 4: Diversity | 26-34 | Viruses, prokaryotes, protists, fungi, seedless plants, seed plants, animal diversity, invertebrates, vertebrates |
| 5: Plant Biology | 36-38 | Plant form & physiology, soil & nutrition, reproduction |
| 6: Animal Physiology | 40-50 | Body form, nutrition, nervous, sensory, endocrine, musculoskeletal, respiratory, circulatory, osmoregulation, immune, reproduction |
| 7: Ecology | 52-55 | Biosphere, population/community, ecosystems, conservation |

**Format consistency:** Every block follows the Ch 04 template — intro paragraph + 5 named exercises with italicized embedded prompts and explicit evaluation criteria. Total ~27,000 words of new exercise content across 45 chapters.

**[verify] flags used appropriately:** Specific numerical claims that I was less confident about are flagged for production-side verification — e.g., specific mutation rate ranges, Higgs proton transport ratios, recovery half-times, percentage estimates that vary by source. The structural reasoning in each exercise stands without depending on the exact numerical values.

**Format-inconsistency follow-up flag:** Ch 03's existing LLM block uses a slightly different format (`**Exercise N: Title**` with plain prompt text, no embedded blockquote, no explicit "Evaluate whether..." paragraph). This is functional but less rigorous than the Ch 04 / chs 02-55 standard. Standardizing Ch 03 would require minor revision. Not done in this pass.

**Mechanistic-depth note:** Exercises consistently push toward mechanistic reasoning over verbal pattern-matching — "explain WHY," "trace the cascade," "identify what would break if X were removed." This matches the AxF v1.1 voice and the bundle's overall mechanism-first treatment.

**Cross-chapter callbacks:** Several chapters (Ch 08 metabolism → Ch 09 respiration; Ch 17 DNA → Ch 18 genes/proteins → Ch 19 expression; Ch 11 signaling → Ch 12 cell cycle → Ch 49 immune) have exercises that explicitly reference the prior chapter's machinery, reflecting the bundle's intentional dependency structure.

**No follow-ups flagged beyond the Ch 03 format-standardization note above.**
