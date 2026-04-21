# Supplementary Section: Empirical Pilot — Safety Bicycle Lineage

## 1. Pilot Design and Scope

To test whether a material artifact lineage can be represented as a commit-based repository with structured selection pressures, we selected a single, tightly bounded artifact family: the **safety bicycle**. The pilot covers the formative period **1876–1892**, tracing the evolution from early lever-driven “safety” prototypes to the pneumatic-tired machines that precipitated the 1890s cycling boom.

Scope constraints:
- **Artifacts:** Human-powered, chain-driven bicycles excluding high-wheelers, tricycles, and motorcycles.
- **Commits:** 4 distinct design states identified where physical changes are source-attested.
- **Subcomponents:** 1 (tire) to demonstrate shallow recursion without scope explosion.
- **Sources:** 15 total (patents, museum objects, period advertisements, newspapers, modern scholarship).

Goal: Demonstrate that a small, provenance-rich, versioned representation is feasible, and that subjective pressures can be disciplined rather than speculative.

## 2. Evidence Base

Sources were categorized to ensure mixed representation:

- **Patents:** UK Patent 2649/1876 (Lawson lever safety); UK Patent 3924/1879 (Lawson chain-driven Bicyclette). Primary specifications of mechanism and inventor intent.
- **Museum collections:** Science Museum Group objects for the 1879 Bicyclette and 1885 Rover. Direct physical artifact records.
- **Period trade/marketing:** 1885 Rover advertisement (C.T.C.); Graces Guide secondary summaries.
- **Contemporary commentary:** *Wheeling* Magazine (1900); “Bicycle Face” debate in *Boston Daily Advertiser* (1895) reflecting health/safety perceptions.
- **Modern scholarship:** GMTMA analysis of women's bicycle advertising (2018); The History Press account of Dunlop's pneumatic tire (technical history).

Every major claim is traceable to ≥1 source; confidence labels reflect evidential strength (high for artifact specs, medium for inferred causal weight, low for speculative cultural signaling).

## 3. Reconstructed Lineage

The commits are:

| Commit | Name | Dates | Key Physical Change |
|--------|------|-------|---------------------|
| A | Lawson Lever Safety | 1876–1878 | Lever drive; low frame; smaller wheels |
| B | Lawson Bicyclette | 1879–1884 | Chain drive to rear wheel |
| C | Rover Safety (diamond frame) | 1885–1887 | Equal wheels; standardized diamond frame |
| D | Pneumatic-tire Safety | 1888–1892 | Inflatable rubber tires |

Each commit includes structured metadata: date range, parent, component references, objective/subjective pressures, diff summary, provenance, and confidence. The tire subcomponent is tracked separately with two mini-commits (solid → pneumatic).

## 4. Core Demonstration: The Pneumatic-Tire Transition (C→D)

We highlight C→D as the strongest illustration of hybrid explanatory value.

### Change
Replacement of solid rubber tires with Dunlop's pneumatic design (1888). Physical impact: smoother ride, lower rolling resistance, less vibration.

### Objective Pressures
- **Comfort.** Directly evidenced by Dunlop's race demonstration (Willie Hume, 1889) and period descriptions of reduced fatigue. (High)
- **Speed/performance.** Lower rolling resistance improved times; supported by engineering expectation and race outcomes. (Medium)

### Subjective Pressures
- **Reduced safety anxieties.** The “bicycle face” controversy (1895 newspapers) shows that perceived health effects were a public concern; pneumatic tires were seen as mitigating those risks. (Medium)
- **Social acceptability for women.** Cultural analysis (GMTMA) shows deliberate advertising that made the bicycle compatible with late-Victorian femininity; comfort improvements were central to that repositioning. (Medium)
- **Aspirational modernity.** The new technology signaled progressiveness; known from magazine tone. (Low)

### Evidence Summary
Direct sources: DUNLOP_PRESS, ONLINE_MUSEUM_PNEU, WHEELING_MAG, BICYCLE_FACE_REA. Inferred elements: exact magnitude of subjective effects relative to objective ones.

### Uncertainty
Known: Pneumatic tires objectively improved ride quality and became standard. Inferred: That comfort change was the primary driver of women's cycling boom; that marketing and perception shifts were necessary rather than epiphenomenal. Ambiguous: relative weight of subjective vs. objective factors remains unquantified.

### Why Hybrid Matters Here
An objective-only account would credit pneumatic tires with engineering improvements but miss their role in *democratizing* cycling. The subjective pressure annotation explains why a component upgrade triggered a mass social phenomenon rather than a niche performance tweak.

## 5. Validation and Limitations

**Strong claims** (high confidence): dates and physical specs of commits A–C; Dunlop tire invention and comfort benefit; women's expanded participation in the 1890s.

**Medium claims:** That marketing (“safety”) accelerated Rover adoption; that “bicycle face” debates reflect real safety anxieties that pneumatic tires alleviated.

**Weak claims:** Fashion/status signaling as an early driver; exact causal ordering of perception vs. material improvement.

Limitations: lack of quantitative adoption curves; reliance on advertising rhetoric for subjective pressures; single-artifact limits generalizability.

Overall, the pilot meets the success criteria: ≥3 commits, ≥12 sources, clear objective + subjective separation, disciplined confidence labeling, and one transition where subjective pressure changes interpretation.
