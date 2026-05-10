# Images and Figures: Chapter 20 — Biotechnology and Genomics

## Figure 1: Plasmid Cloning

**Caption:** Restriction enzyme (EcoRI) cuts both plasmid and target gene, creating sticky ends. The gene anneals to the plasmid. DNA ligase seals the join. Recombinant plasmid is transformed into bacteria, which replicate it.

**Elements to show:**
- Plasmid circle with EcoRI recognition sites marked
- Target gene (human insulin) with same EcoRI sites
- Staggered cuts leaving 5' overhangs (sticky ends) on both
- Annealing step: gene inserted into plasmid
- DNA ligase sealing the phosphodiester bonds
- Transformed bacteria replicating the recombinant plasmid
- Result: billions of copies within hours

**Key labels:** Sticky ends, phosphodiester bond, recombinant DNA, transformation

---

## Figure 2: PCR Cycle (Three Steps, Repeated 30 Times)

**Caption:** Polymerase chain reaction amplifies a target DNA sequence exponentially. Each cycle (denaturation, annealing, extension) doubles the number of copies.

**Elements to show:**
- Step 1 (94°C): Denaturation — double helix separates into single strands
- Step 2 (50–65°C): Annealing — primers (short DNA probes) bind to matching sequences on each strand
- Step 3 (72°C): Extension — DNA polymerase synthesizes new complementary strands
- One full cycle shown, with arrows indicating the doubling
- Overlay showing cycle count: 1 copy → 2 → 4 → 8 ... → 2^30 (about 1 billion)

**Key labels:** Primer, denaturation, annealing, extension, target sequence

---

## Figure 3: Sanger Sequencing

**Caption:** Chain termination sequencing uses fluorescently labeled dideoxynucleotides (ddNTPs) to stop DNA synthesis at each position. Gel electrophoresis separates fragments by size. Detector reads fluorescent color to determine sequence.

**Elements to show:**
- Template DNA strand
- Primer bound to template
- DNA polymerase extending the new strand
- Regular dNTPs being added (most common)
- Occasional ddNTPs being incorporated (chain termination) — labeled red (A), green (G), blue (C), yellow (T)
- Resulting fragments of different lengths (25, 26, 27, ... base pairs)
- Gel showing a "ladder" of bands, each labeled with its color
- Detector reading colors from bottom to top
- Resulting sequence: ATGCTAGG... (read from color order)

**Key labels:** ddNTP, chain termination, gel electrophoresis, fluorophore, sequence read

---

## Figure 4: Three Types of Genome Maps (Comparison)

**Caption:** Genetic maps (based on linkage), physical maps (nucleotide distance), and sequence maps (actual bases) provide complementary views of genome organization.

**Elements to show (for one chromosome region):**

**Panel A — Genetic Map:**
- Genes labeled as colored dots (Gene A, Gene B, Gene C)
- Distances shown as recombination frequencies (e.g., "A-B: 10 cM" = 10% recombination)
- Linked genes clustered together, unlinked genes far apart

**Panel B — Physical Map:**
- Same genes shown with actual nucleotide distances
- "A-B: 1.2 million bp" 
- More precise than genetic map
- May show cytogenetic bands (colored regions from stained chromosomes)

**Panel C — Sequence Map:**
- Magnified view showing actual DNA bases
- ATGCTAGCGATAGC...
- Most precise; shows every base pair
- Only possible after sequencing

**Connecting element:** Arrow from genetic → physical → sequence showing increasing resolution and precision

---

## Figure 5: Modern High-Throughput Sequencing Workflow

**Caption:** Whole-genome sequencing produces millions of short reads (fragments) that are assembled by finding overlaps.

**Elements to show:**
- DNA sample
- Fragmentation (random breaking into pieces of 150–500 bp)
- Each fragment gets sequencing adapters (short sequences that allow sequencing chemistry to work)
- Millions of fragments on a chip, being read in parallel
- Output: millions of sequences, each 150 bases long, color-coded (A=green, C=blue, G=yellow, T=red)
- Assembly step: overlapping reads stitched together
- Example: Fragment 1 ends with "CGAT", Fragment 2 starts with "CGAT" → they are adjacent
- Final assembled sequence emerging from the overlaps

**Key labels:** Fragmentation, sequencing adapter, parallel sequencing, overlap, assembly, contig

---

## Figure 6: Cost of Whole-Genome Sequencing Over Time

**Caption:** Sequencing cost per genome has dropped ~100,000-fold in two decades, following Moore's Law (doubling every 2 years).

**Elements to show:**
- Y-axis: Cost in dollars (log scale, from $1 to $10,000,000)
- X-axis: Years (2001–2020)
- Data points:
  - 2001: Human Genome Project draft = $3 billion
  - 2007: First high-throughput sequencer = $500,000 per genome
  - 2010: $10,000 per genome
  - 2015: $3,000 per genome
  - 2020: $1,000 per genome
- Downward-sloping line (exponential decay)
- Overlay Moore's Law curve for comparison (shows sequencing is tracking Moore's Law)

**Key labels:** Cost per genome, high-throughput sequencing era, routine clinical sequencing threshold

---

## Figure 7: Interpretation Gap — From Variant to Meaning

**Caption:** Of millions of genetic variants found in one person's genome, only a tiny fraction have clear functional consequences.

**Elements to show (as a funnel diagram):**
- Top: "4 million variants per person" (all differences from reference genome)
- Filter 1: "10,000 in protein-coding regions"
- Filter 2: "100 predicted to disrupt protein"
- Filter 3: "10 with known disease association"
- Filter 4: "3 medically actionable"
- Bottom (small): "Interpretable variants"
- Side annotation: "3.99 million variants: unknown function"

**Key labels:** Variant classification, coding region, functional consequence, pathogenicity, actionability

---

## Figure 8: Gene Delivery Methods

**Caption:** Three main approaches to deliver a therapeutic gene to patient cells: viral vectors, lipid nanoparticles, and ex vivo editing.

**Elements to show (three side-by-side panels):**

**Panel A — Viral Vector (AAV):**
- Virus (shown as icosahedron) with therapeutic gene packaged inside
- Virus binds to cell surface
- Gene released into nucleus
- Integration into genome (or episomal persistence)
- Gene expressed as protein

**Panel B — Lipid Nanoparticles (mRNA):**
- Lipid bilayer sphere containing mRNA
- mRNA wrapped in lipid coat
- Nanoparticle fuses with cell membrane
- mRNA released into cytoplasm
- mRNA translated into protein by ribosomes
- mRNA degraded within days (no genome change)

**Panel C — Ex Vivo Editing:**
- Patient cell removed
- CRISPR system cuts target gene
- New gene template inserted
- Edited cells expanded in culture
- Re-infused into patient
- Edited cells now produce correct protein

**Key labels:** Payload, cell penetration, expression, genome integration, transient vs. permanent

---

## Figure 9: Bt Crop and Herbicide Resistance Trade-off

**Caption:** Bt crops reduce insecticide spraying but increase herbicide reliance in Roundup Ready plants, which created herbicide resistance.

**Elements to show:**
- Left panel — Traditional corn: frequent pesticide spray (red arrows), high chemical input
- Middle panel — Bt corn: less pesticide spray (fewer red arrows), lower input
- Right panel — Roundup Ready corn: frequent herbicide spray (blue arrows), genetic resistance to glyphosate allows heavy use

**Timeline overlay (bottom):**
- 1990s: GMO crops introduced, pesticide reduction
- 2000s: Glyphosate-resistant weeds emerge
- 2010s: Farmers spray more herbicide, not less

**Key labels:** Pest pressure, insecticide, herbicide, resistant weeds, unintended consequence

---

## Figure 10: Precision Medicine — Population Risk vs. Individual Outcome

**Caption:** A genetic variant associated with 1.5× increased disease risk in a population study may translate to minimal absolute risk increase for an individual.

**Elements to show:**
- Population 1 (no variant): baseline 4% risk of heart disease
- Population 2 (variant carriers): 1.5 × 4% = 6% risk
- Arrow showing the ~2% absolute difference is not clinically dramatic
- Individual person with variant shown alongside: might develop disease or might not
- Distributions showing overlap: many carriers never get disease; many non-carriers do
- Text label: "Population association ≠ individual prediction"

**Key labels:** Relative risk, absolute risk, population vs. individual, variance in outcome

---

## Figure 11: Gene Expression and Post-Translational Modification

**Caption:** Same genome, different proteins: gene regulation and post-translational modification create cell-type-specific protein sets.

**Elements to show (two cell types):**

**Liver cell:**
- Same DNA (same genes)
- Transcription factors binding to regulatory regions → expression of liver-specific genes
- mRNA for liver enzymes (cytochrome P450, albumin, etc.)
- Ribosomes translating mRNA
- Protein modifications: phosphorylation, glycosylation
- Final proteome: liver enzymes, not neurotransmitter receptors

**Brain cell:**
- Same DNA
- Different transcription factors active
- mRNA for neurotransmitter receptors, synaptic proteins
- Same modification machinery
- Final proteome: neuronal proteins

**Connecting elements:**
- Curved arrows showing gene regulation differs
- Box showing post-translational modification happens in both
- Outcome: different proteomes from same genome

**Key labels:** Gene regulation, chromatin remodeling, alternative splicing, post-translational modification, cell-type specificity

---

## Figure 12: Systems Biology — Layers of Information

**Caption:** Genomics alone is insufficient; understanding requires data from multiple layers of biological organization.

**Elements to show (pyramid):**
- Bottom (foundation): **Genome** — DNA sequence (3 billion base pairs, static)
- Layer 2: **Transcriptome** — which genes expressed when/where (dynamic, context-dependent)
- Layer 3: **Proteome** — proteins actually made, modified, and functional (dynamic, unstable)
- Layer 4: **Metabolome** — small molecule metabolites present in cells/tissues (dynamic, fastest to change)
- Layer 5: **Phenotype** — observable traits, disease states, outcomes (integrated result of all layers + environment)
- Arrows showing feedback and interaction between layers

**Callout box:** "Genomics gives you the instruction manual. Systems biology shows you the building being constructed, modified, and used in real time."

**Key labels:** DNA, mRNA, proteins, metabolites, systems integration, environment
