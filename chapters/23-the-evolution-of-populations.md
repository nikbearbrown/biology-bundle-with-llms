# Evolution of Populations

**Suggested titles:**
1. How Populations Change: The Invisible Hand of Allele Frequencies
2. The Mathematics of Evolution: Why Populations Drift, Select, and Shift
3. Reading Evolution in the Numbers: What Allele Frequencies Tell Us About Populations

**TL;DR:** A population's genetics are not static. Allele frequencies shift due to five mechanisms — natural selection, genetic drift, gene flow, mutation, and nonrandom mating — and you can detect whether evolution is occurring by comparing real populations to the mathematical baseline called Hardy-Weinberg equilibrium.

---

## Opening Scene: The Moth That Changed Color

In 1848, a peppered moth appeared in Manchester, England with a dark pelt instead of the pale, speckled surface of every other moth in the region. One insect. One visible mutation in a population of thousands.

By 1895, nearly all the peppered moths in Manchester were dark.

What happened in those forty-seven years was not that moths developed dark coloration because they needed it. It was not Lamarckian inheritance — the inheritance of acquired traits. A dark individual did not live and darken further over its life, then pass that darkening to its offspring. Instead, the dark insect, by accident of birth, survived better in the industrial world that Manchester had become. Soot from factories coated trees. Dark bark favored dark moths. Predatory birds spotted pale moths against it. Those dark moths bred more. Their dark offspring bred more. A rare allele — a variant of a gene — became common. Then dominant. Then nearly universal.

This was not a species becoming better adapted to its environment. This was a population's genetic makeup, described in numbers, shifting radically in the span of a few decades.

To understand how populations evolve — not how species transform, but how the gene pool itself changes — you need one tool above all others: the ability to count alleles. Everything that follows rests on that simple habit: counting frequencies.

---

## Part 1: What Are Allele Frequencies and Why Count Them

Mendel showed us how individual genes are inherited. A parent passes one allele to each offspring. The offspring carries two. But Mendel worked with single organisms, single crosses, single generations. A population is different. A population is the sum of all the alleles, all the variants of all the genes, in all the individuals of a group.

Start with the ABO blood type system in humans. There are three alleles for the ABO gene — I^A, I^B, and I^0. Each person carries two. They can be:

- I^A I^A or I^A I^0 (type A)
- I^B I^B or I^B I^0 (type B)
- I^A I^B (type AB)
- I^0 I^0 (type O)

Now zoom out. Take a population of 1,000 people. Each person carries two alleles. That's 2,000 alleles total in the population's gene pool. When scientists surveyed Jordanians, they found that I^A made up 26.1% of all ABO alleles in the population. I^B: 13.4%. I^0: 60.5%. The frequencies sum to 100%.

The key insight: if those frequencies change from generation to generation, the population is evolving.

That is the whole definition of evolution at the population level — a change in allele frequencies over time. Not the appearance of a new species. Not a dramatic shift in body size or behavior. A shift in the proportion of genetic variants. That shift is what drives everything else.

### Why Allele Frequencies Matter More Than Genotypes

You might think the thing that matters is what each individual looks like — the distribution of genotypes. A population with more dark moths looks different than one with more pale moths. But genotypes are temporary. They exist in an individual and vanish when that individual dies. Alleles persist. An allele lives in a population across generations. It can be rare, common, or fixed (present in every individual). If you want to know whether a population is evolving, count alleles, not phenotypes.

Here's why this matters: imagine a population where 100 individuals carry the allele for sickle-cell hemoglobin. Then a disease — malaria — strikes. Individuals without the sickle allele die. The ones who carry it survive. Now 80 of those 100 still carry it. The allele frequency just went from 100 to 80 individuals. The population's phenotype has changed *because* its allele frequency changed. The phenotype is the shadow. The allele frequency is the thing casting it.

### Sources of Genetic Variation

Populations only evolve if there is variation to act upon. Three things create and maintain that variation:

**Mutation** is the primary source of new alleles. DNA replication is not perfect. Sometimes an error occurs. The result is a new variant of a gene. Most mutations are neutral or harmful. A few are beneficial. But all of them are the raw material. Without mutation, a population would eventually exhaust its genetic variation. With mutation, novel alleles appear constantly, even at low rates (roughly 10^-8 to 10^-9 per base pair per generation).

**Sexual recombination** shuffles existing alleles in new arrangements. A parent carries one copy of allele A and one of allele a. The other parent carries the same. Their offspring might be AA, Aa, or aa — three genotypes from two parents. Over many generations, recombination redistributes alleles in the population, creating combinations that natural selection can then act upon.

**Gene flow** — migration of individuals between populations — introduces alleles that evolved elsewhere. A bird flies from one island to another. A pollen grain travels on the wind. An allele present in population X becomes present in population Y. The frequencies in both populations shift.

Without variation, natural selection has nothing to select. This is the hardest part for people to grasp: *selection does not create variation; it shapes what is already there*.

---

## Part 2: Hardy-Weinberg Equilibrium — The Null Hypothesis for Evolution

In the early 1900s, two scientists — English mathematician Godfrey Hardy and German physician Wilhelm Weinberg — proved something strange. In a large population with no mutations, no migration, random mating, and no natural selection, allele frequencies would not change. Generation after generation: the same frequencies. The same genotypes. Stability.

This seems backwards. Why would a population ever be stable? Yet the mathematics are unassailable. Here is the proof.

Let's say a locus has two alleles: p (frequency of allele 1) and q (frequency of allele 2). By definition, p + q = 1. All alleles in the population must be one or the other.

Now, what are the genotype frequencies? If individuals mate randomly, the probability of drawing two alleles at random from the gene pool is the same as drawing two beads from a jar. The probability of getting p and p is p². The probability of getting p and q is 2pq (you can get p first then q, or q first then p). The probability of getting q and q is q².

Thus:

$$p^2 + 2pq + q^2 = 1$$

This is the **Hardy-Weinberg equation**. It says: if these five conditions hold (large population, no mutation, no migration, random mating, no selection), the genotype frequencies will follow this formula forever.

### The Conditions Are Never Met

No natural population satisfies all five conditions. All populations are finite (so genetic drift happens). All have mutation. Many have migration. Mating is almost never random. And selection is everywhere.

But that is not the point. The Hardy-Weinberg equation is a *null hypothesis* — a baseline of no evolution. Compare real populations to it. If the real frequencies match the prediction, fine: no detectable evolution. If they deviate, something is changing the allele frequencies. Something is happening.

### Using Hardy-Weinberg to Detect Evolution

**Worked example:** Violet flower color (V) is dominant over white (v). In a population of 500 plants, you observe 400 white flowers and 100 violet flowers. What do the allele frequencies tell you?

White flowers have genotype vv. If 400 out of 500 are vv, then q² = 400/500 = 0.8. Taking the square root: q = √0.8 ≈ 0.894. Then p = 1 − q ≈ 0.106.

Now apply Hardy-Weinberg. You expect:
- p² = 0.011 (about 5.6 VV plants)
- 2pq = 0.189 (about 94.6 Vv plants)
- q² = 0.8 (about 400 vv plants)

You predicted 100 Vv + VV (violet flowers) and observed 100. The math checks. The population is in equilibrium—at least for this locus, no obvious evolutionary force is driving change.

But if you return in ten years and find 350 white and 150 violet, the frequencies have shifted. q² = 350/500 = 0.7, so q ≈ 0.837. The allele frequencies have changed. Evolution is occurring. Now your job is to figure out which mechanism — selection, drift, migration, mutation, or nonrandom mating — is driving it.

---

## Part 3: The Four Mechanisms of Evolution

Every change in allele frequency falls into one of four categories. Most populations experience more than one simultaneously, which makes the real world messy. But each mechanism has a signature.

### Mechanism 1: Natural Selection

Natural selection is the only mechanism that tends to increase adaptation. It acts because some individuals survive and reproduce more than others, and their success is heritable.

**Relative fitness** is what matters. You do not care if an individual produces five offspring in absolute terms. You care if five is more than the population average. If the average is three, the individual's relative fitness is 5/3 ≈ 1.67. If the average is six, the relative fitness is 5/6 ≈ 0.83. The population is selecting *against* this individual.

Selection has several modes, each producing a different outcome:

**Stabilizing selection** favors individuals near the population average and selects against extremes. Imagine mice living in a forest where the leaf litter is uniformly brown. Pale mice stand out; dark mice stand out; medium brown mice vanish into the background. Predators catch more extremes. Medium-colored mice breed more. Over generations, the population becomes more uniform. Genetic variation *decreases*. The bell curve gets narrower.

**Directional selection** occurs when the environment changes and one end of the spectrum becomes advantageous. Peppered moths: pale moths were common until industrial soot darkened the trees. Dark moths now survived better. They bred more. The dark allele increased in frequency. The population's average shifted. This is the classic story of adaptation — the population becomes more like the new environment.

**Diversifying selection** favors *both* extremes over the middle. A population of beach mice might have light individuals (matching sand) and dark individuals (matching grass patches). Medium-colored mice match nothing and get eaten. Both pale and dark alleles increase. Genetic variation *increases*. The bell curve becomes bimodal — two peaks.

An example: Male side-blotched lizards come in three throat colors — orange, blue, and yellow. Orange males are strong and win fights for females. Blue males form pair bonds and guard their mates. Yellow males sneak copulations by looking female-like. Like rock-paper-scissors, orange beats blue, blue beats yellow, and yellow beats orange in the competition for females. Orange beats blue (fights them off). Blue beats yellow (guards against them). Yellow beats orange (sneaks past them). Like rock-paper-scissors, none is universally advantageous. When orange is common, blue does well. When blue is common, yellow does well. When yellow is common, orange does well. The population cycles through a stable rotation of frequencies, maintaining variation.

### Mechanism 2: Genetic Drift — Evolution by Chance

This is the hardest mechanism to intuit because it has no direction and no adaptive logic. Genetic drift is *random sampling error in reproduction*.

Consider a small population of ten individuals. Let's say five carry allele A and five carry allele a. The allele frequency is 0.5 for both. Now, by chance, three of the five A-carriers have offspring. The two a-carriers do not. A increases to 6 out of 10. Next generation, the A carriers again happen to be the ones who breed. Now A is 7 out of 10.

No one allele is "better." It is not selected. Chance alone is shifting frequencies.

Drift is stronger in small populations and weaker in large ones. If one individual in a population of 10 dies without reproducing, it removes 1/10 of the gene pool. If one individual in a population of 10,000 dies, it removes 1/10,000. The impact on allele frequencies is proportionally larger in the small population.

**The bottleneck effect** is drift magnified by catastrophe. A natural disaster — earthquake, hurricane, disease outbreak — randomly kills a large fraction of the population. The survivors are an unrepresentative sample of the original gene pool. The population's genetic makeup lurches to match the survivors' makeup, not because they are better, but because they are all that is left. Cheetahs passed through a severe bottleneck thousands of years ago; today they have almost no genetic variation. They are nearly clones of one another.

**The founder effect** is drift in the founding moment. A small group of individuals colonizes a new habitat — an island, a new valley. They are not a random sample of the original population; they carry whatever alleles happened to be in those few individuals. A Spanish ship carrying colonists arrived at the Americas carrying a disease allele at much higher frequency than in Spain. That allele now appears at elevated frequency in certain New World populations. The Amish of Pennsylvania descended from a small founding population; they carry rare deleterious mutations at much higher frequency than the general population because a founder happened to carry them.

Drift and selection operate simultaneously in most populations. A large population can overcome drift through selection's directional pressure. A tiny population is governed by drift; selection is too weak to overcome random noise.

### Mechanism 3: Gene Flow (Migration)

Alleles move. A bird migrates and brings its genes to a new population. Pollen drifts on the wind from one flower patch to another. A human moves to a new country and has children.

Gene flow has two effects: it *introduces* alleles from elsewhere and it *homogenizes* populations, reducing differentiation. Over many generations, gene flow between neighboring populations erodes the genetic differences that would accumulate if populations were isolated. This is why species living across a continent show gradual transitions (clines) rather than sharp boundaries. Warm-blooded animals tend to be larger in cold climates (Bergmann's rule) — a latitudinal cline. Flowering plants bloom at different times on a mountain's slope — an altitudinal cline. These gradients exist because gene flow is slow enough to allow local selection to maintain some differentiation, but fast enough to prevent hard boundaries.

### Mechanism 4: Nonrandom Mating

If mating were random, every individual's probability of breeding would depend only on its survival. But animals choose mates.

**Assortative mating** is preference for similarity. Tall people tend to mate with tall people. Peahens prefer peacocks with larger tails. This does not change *which* alleles are present, but it changes how they are packaged into individuals. Assortative mating increases the frequency of homozygotes (AA or aa) and decreases heterozygotes (Aa). The population becomes more inbred.

**Inbreeding depression** is the cost of this packaging. Rare deleterious recessive alleles can hide in heterozygotes, undetected. In a large, outbred population, the chance that two carriers of a rare recessive mate is low. Their offspring might inherit the allele from both parents and show the disease. But this is rare. In a small inbred population, two carriers are likely to encounter each other. Deleterious mutations accumulate as homozygotes. The population becomes sickly. Zoo managers carefully control breeding to avoid this: they maintain genetic diversity by mating individuals who are least related.

**Sexual selection** is mate choice based on traits that aid reproduction rather than survival. A peacock's tail makes the male more visible to predators and slower at escaping — it impairs survival. Yet peahens prefer large tails. Why?

The **handicap principle** offers one explanation: if a trait is costly to survival, only the healthiest males can afford it. A large tail signals health. Peahens are reading that signal. They choose males with the biggest tails because those males must be extraordinarily fit to survive carrying them.

The **good genes hypothesis** is similar: females choose males with impressive traits because those traits signal the male's ability to resist disease, metabolize efficiently, or fight infection. By choosing such males, females ensure their offspring inherit genetic superiority. Fewer, healthier offspring may outperform many weak ones.

Both explanations assume that ornamental traits are honest signals of male quality. The empirical evidence is mixed, but the logic is sound: if a female invests heavily in offspring (as many do), choosing a genetically superior mate can increase her inclusive fitness.

---

## Part 4: How Mechanisms Interact

Evolution in the real world is not one mechanism in isolation. A population experiences selection, drift, mutation, and gene flow all at once. The net result depends on their relative strengths.

**Selection is strongest when:**
- The fitness difference between alleles is large
- The population is large (so drift noise does not drown out selection's signal)
- The beneficial allele is already common enough to encounter selection (rare beneficial alleles can be lost to drift before selection helps them spread)

**Drift is strongest when:**
- The population is small
- Alleles have similar fitness (selection cannot distinguish them)

**Gene flow is strongest when:**
- Migration rates are high
- Allele frequencies differ between populations (if two neighboring populations have the same alleles at the same frequencies, migration does not change anything)

**Mutation is weak on short timescales** (10 to 1,000 generations) but provides the raw material for selection and drift to act upon on longer timescales.

The peppered moths again: in industrial Manchester, directional selection was powerful. Dark alleles had a huge fitness advantage. Even though the population was finite and drift was present, selection was so strong that the dark allele went from rare to nearly fixed in less than 50 years. But when factories closed and air pollution decreased, that same population reversed. Selection now favored pale moths again. Genetic drift alone would never reverse the trend; it would lock the population into whatever allele frequency existed at the bottleneck moment. But strong directional selection could and did.

Contrast this with Amish genetic diseases. The Amish population is small. Many deleterious alleles are rare. Drift, not selection, dominates. Mutations that would be eliminated by selection in a large population persist in the Amish at elevated frequency purely because the founding population happened to carry them and drift has not yet erased them (or never will, if they reach fixation).

In humans globally, gene flow is enormous. Different human populations have accumulated some different alleles due to isolation and local selection (adaptation to environment, to disease pressure). But global migration is now so high that these differences are being homogenized. Allele frequencies that might have differed by 20% between distant populations fifty years ago may differ by only 5% today.

### The Limits of Adaptation

Natural selection can generate populations exquisitely adapted to their environments. But it has hard limits.

First, selection can only work with *existing* variation. If a beneficial allele does not exist, selection cannot create it. If a population has lost an allele to drift, mutation must reintroduce it. Mutation is slow.

Second, selection acts on individuals, not alleles. An individual might carry ten beneficial alleles and five harmful ones. If the net fitness is positive, the individual thrives and passes on all fifteen. The harmful alleles hitch along. Over time, beneficial alleles can actually decrease in frequency if they are linked to bad ones — physically close on the chromosome and inherited together. This is linkage disequilibrium: nearby genes tend to be inherited as a block. A good allele buried next to a bad one will spread or decline with its neighbor.

Third, a population might become trapped in a local optimum. Imagine mice on a beach with two habitats: light sand and dark grass. Light mice match sand; dark mice match grass. Medium mice match neither and get eaten. The population might split into two groups — some light, some dark. But a medium mouse cannot gradually shift to either light or dark without first becoming even more exposed (medium) and getting eaten. The intermediate phenotype is a dead end. Selection cannot traverse it.

Finally, not all evolution is adaptive. Genetic drift introduces deleterious alleles. Gene flow can bring maladaptive alleles from other populations. Nonrandom mating can concentrate harmful recessive mutations. Evolution is the *sum* of all forces, not a unidirectional march toward perfection.

---

## Synthesis: Reading a Population's Future

When you observe a population, you are seeing a snapshot of ongoing evolution. To know what will happen next, you need to know the allele frequencies, the population size, the mutation rate, the migration rate, and the strength of selection. No single factor determines the outcome. 

A population small enough to be governed by drift will evolve randomly, losing alleles by chance. A population large enough to resist drift will evolve according to selection — if selection pressures are strong. A population receiving heavy gene flow will become genetically similar to its neighbors. A population with high mutation rates will maintain variation even under selection.

The Hardy-Weinberg equation gives you the baseline. Compare the population to it. If the frequencies deviate, you know something is changing the alleles. Now figure out what. Is the population shrinking? (Drift.) Are individuals not mating randomly? (Nonrandom mating.) Has the environment changed? (Selection.) Are new alleles appearing? (Mutation.) Has migration increased? (Gene flow.)

The method is simple: count alleles. Compare to the expectation. Explain the deviation.

This is how we know evolution is not just a historical event, not just something that happened to dinosaurs or to bacteria. Evolution is happening *now*, in measurable shifts in allele frequencies, in populations we can observe and count. It is happening in the Amish and the Afrikaner, in peppered moths and side-blotched lizards, in your own species as populations mix and environments change.

The machinery is visible. The math is not hard. The only requirement is the willingness to think in terms of frequencies — to see a population not as a collection of individuals, but as a distribution of alleles, shifting and drifting and selecting across generations.

---

## Graduated Exercises

**Warm-up:**
1. A gene has two alleles, A and a. In a population of 500 individuals, you count the alleles and find 600 copies of A and 400 copies of a. What are the allele frequencies?

2. In the same population, what would you expect the genotype frequencies to be (AA, Aa, aa) if the population is in Hardy-Weinberg equilibrium?

3. You observe the actual genotypes: 200 AA, 300 Aa, 0 aa. Does this match your expectation? What might explain the deviation?

**Application:**
4. A population of plants has a flower-color gene with two alleles: R (red) is dominant, r (white) is recessive. In a sample, you observe 360 red flowers and 40 white flowers (total 400). Calculate the allele frequencies. If the population is in HWE, how many of each genotype would you expect in a population of 10,000 plants?

5. An island population of birds is founded by ten individuals, five males and five females. Two of the males carry a rare allele. Over the next five generations, genetic drift operates (assume no selection). Would you expect this rare allele to be more common, less common, or about the same in generation five? Explain.

**Synthesis:**
6. A disease is caused by a rare recessive allele (frequency = 0.01). In a large outbred human population, how many individuals would you expect to show the disease phenotype? Now consider a small isolated population of 100 people where the same allele was carried by the founder at the same frequency. Would you expect the disease to be more common or rarer in the isolated population after ten generations? Why?

7. Peppered moths in England show directional selection toward dark coloration during industrialization, then reversal toward light coloration when factories closed. Explain what mechanism (selection, drift, mutation, gene flow, nonrandom mating) is driving each phase. Would the direction have reversed if the population had been very small (say, ten moths)?

---

## Summary

Evolution at the population level is a change in allele frequencies. These frequencies shift because of five mechanisms: natural selection (favoring beneficial alleles), genetic drift (random change, especially strong in small populations), gene flow (migration of alleles between populations), mutation (introduction of new variants), and nonrandom mating (choice of mates affecting genotype packaging).

The Hardy-Weinberg equation provides a mathematical baseline — a prediction of what should happen if none of these mechanisms operate. Deviations from Hardy-Weinberg signal that evolution is occurring. By measuring the deviation and understanding the population's size, environment, and mating patterns, you can infer which mechanisms are active.

Selection is the only mechanism that tends to increase adaptation. But selection is not the only force shaping populations. Drift dominates in small populations. Gene flow homogenizes neighboring populations. Mutation provides variation. Nonrandom mating concentrates alleles in particular genotypes.

Most populations experience multiple mechanisms simultaneously. The outcome depends on their relative strengths. A population can be tracked across generations by counting alleles — not a metaphorical journey toward fitness, but a literal ledger of genetic frequencies, rising and falling, driven by the interplay of randomness and selection, death and reproduction, isolation and flow.

---

## Connections Forward

The mechanisms of evolution operate not just on single loci, but across the entire genome. When populations diverge — when they stop gene flow and experience different selection pressures — allele frequencies can change so dramatically that reproductive isolation evolves. After many generations, a population becomes so genetically different that it can no longer interbreed with its parent population. This is speciation. Evolution of populations becomes evolution of species.

Sexual selection, a subset of natural selection, can produce traits that seem maladaptive yet persist — antlers in deer, songs in birds, ornamental plumage in males. These traits do not aid survival; they aid reproductive success. Understanding them requires understanding that selection acts not just on survival, but on mating, and that mating decisions themselves are heritable and can be selected.

Inbreeding depression shows that population size matters not just for the mechanics of drift, but for the long-term health of a population. Conservation biology uses allele-frequency thinking to preserve endangered species: maintain population size to limit drift, maintain connectivity between populations to maintain gene flow, and maintain behavioral flexibility to allow adaptation to changing environments.

---

## What Would Change My Mind

If strong gene flow between populations maintained constant allele frequencies despite strong directional selection, it would suggest that gene flow is a more powerful mechanism than I have described. Current evidence supports that selection can overcome moderate gene flow, but overwhelming gene flow (very high migration rates) can indeed prevent local adaptation. I would revise upward my emphasis on gene flow as a limiting factor on selection in open populations.

---

## Still Puzzling

I do not fully understand why populations in the wild do not collapse more often under inbreeding depression. Small populations should accumulate deleterious mutations and show declining fitness. Some do (cheetahs, Arabian oryx, California condors). But many wild populations persist at small sizes for extended periods. Either purging of deleterious mutations happens faster than theory predicts, or populations are rescued by immigration, or the mutations are not as deleterious as lab studies suggest. The empirical gap remains.

---

## Tags

allele-frequencies, Hardy-Weinberg-equilibrium, genetic-drift, natural-selection, gene-flow, founder-effect, bottleneck-effect, sexual-selection, directional-selection, population-genetics

---

*Author: Nik Bear Brown*
*This chapter was drafted for pedagogical clarity in the Feynman tradition: mechanism-first, variation preserved, jargon translated. It is a work in progress and has been reviewed by the author before publication.*
