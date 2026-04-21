# TPR Pilot — Paper-Ready Supplementary Section

## 1. Pilot Design and Scope

**Artifact:** Safety bicycle  
**Period:** 1876–1892  
**Commits:** 4 (A–D) + 1 subcomponent lineage (tire: solid → pneumatic)  
**Sources:** 15 (patents, museum objects, period ads/commentary, modern scholarship)

**Scope boundaries:** Human-powered chain-driven bicycles only; excludes high-wheelers, tricycles, motorcycles. Tightly bounded to demonstrate framework without overreach.

## 2. Evidence Sources

| ID | Title | Year | Type | Role |
|----|-------|------|------|------|
| LAWSON_PATENT_1876 | Patent 2649: Lever-driven safety | 1876 | patent | specification, causal claim |
| LAWSON_PATENT_1879 | Patent 3924: Chain-driven Bicyclette | 1879 | patent | specification, causal claim |
| SMITH_BICYCLETTE | Lawson 'Bicyclette', 1879 (Science Museum) | 1879 | museum object | specification, provenance |
| ROVER_SMMT | Rover 'Safety' Bicycle, 1885 (Science Museum) | 1885 | museum object | specification, chronology |
| ROVER_AD_1885 | 1885 Rover bicycle advertisement | 1885 | period ad | subjective, market evidence |
| DUNLOP_PRESS | From discomfort to joy: Dunlop’s pneumatic tyre | 1888 | technical history | chronology, causal claim |
| ONLINE_MUSEUM_PNEU | THE PNEUMATIC TYRE (Online Bicycle Museum) | 1888+ | museum blog | chronology, specification |
| WHEELING_MAG | Wheeling Magazine commentary | 1900 | period magazine | subjective, market evidence |
| BICYCLE_FACE_REA | Bicycle Face (Readex/Historical Newspapers) | 1895 | newspaper | subjective (perception) |
| WOMEN_ADV_GMTMA | Bicycles, Women, and Advertising (GMTMA) | 2018 | cultural history | subjective, cultural |
| GRACE_LAWSON | Henry John Lawson: Bicycle (Graces Guide) | 1876–1895 | secondary reference | chronology, specification |
| PREMIER_1886_MUSEUM | "Premier" safety, Hillman, Herbert & Cooper | 1886 | museum record | specification |
| GRACE_PREMIER | Hillman, Herbert and Cooper (Graces Guide) | 1886 | trade history | chronology |
| LAWSON_PATENT_1876_ALT | 1874 HJ Lawson 'Sussex Dwarf' (Online Bicycle Museum) | ~2016 | museum blog | specification |
| PERF_BIKE_BLOG | Evolution of the Bicycle (1817–1899) | post-2000 | secondary synthesis | chronology |

Full reliability notes and evidence roles in `source_register_clean.md`.

## 3. Reconstructed Lineage

```
A: Lawson Lever Safety        (1876–1878)  [lever drive, low frame]
B: Lawson Bicyclette           (1879–1884)  [chain drive rear]
C: Rover Safety diamond frame  (1885–1887)  [equal wheels, diamond frame]
D: Pneumatic-tire Safety       (1888–1892)  [pneumatic tires]
```

See `visual_clean.md` for complete pressure mapping.

## 4. Core Demonstration: Transition C → D

### Change
Replacement of solid rubber tires with Dunlop's pneumatic design (1888). Physical effect: cushioned ride, lower rolling resistance, less vibration.

### Objective Pressures
- **Comfort improvement** – Tire absorbs shocks, reduces fatigue. Evidence: Dunlop race demo (1889), *Wheeling* Magazine. (Direct, high)
- **Speed increase** – Lower rolling resistance improves times. Evidence: engineering theory + race results. (Mixed, medium)

### Subjective Pressures
- **Reduced safety anxieties** – Public health debate (“bicycle face,” 1895) shows perceived risks were salient; pneumatic tires promoted as healthier. Evidence: *Boston Daily Advertiser*, *Wheeling* Magazine. (Direct, medium)
- **Social acceptability for women** – Comfort made cycling compatible with Victorian femininity; advertisers targeted women explicitly. Evidence: GMTMA cultural study. (Mixed, medium)
- **Aspirational modernity** – Pneumatic safeties signaled progressive technology. Evidence: magazine tone. (Inferred, low)

### Evidence Summary

| Source | Type | Direct/Inferred |
|--------|------|-----------------|
| DUNLOP_PRESS | Technical history | Direct |
| ONLINE_MUSEUM_PNEU | Museum blog | Inferred |
| WHEELING_MAG | Period magazine | Direct |
| BICYCLE_FACE_REA | Newspaper | Direct |
| WOMEN_ADV_GMTMA | Cultural history | Inferred |

### Uncertainty
- **Known:** Pneumatic tires improved comfort/speed; widely adopted by early 1890s.
- **Inferred:** Comfort change drove women's cycling boom; pneumatic tires alleviated “bicycle face” anxieties (correlated, not proven).
- **Ambiguous:** Relative weight of subjective vs. objective drivers; direction of marketing vs. perception.

### Why Hybrid Annotation Adds Value Here
An objective-only account would credit pneumatic tires with engineering benefits but miss their role in *democratizing* cycling. The subjective pressure annotation explains why a component upgrade triggered a mass social phenomenon (1890s boom, women's participation) rather than a niche technical improvement.

## 5. Validation Overview

**Strong claims:** Physical specs of commits A–C; Dunlop invention and benefit; women's expanded participation in 1890s. (High/medium-high confidence)

**Medium claims:** Rover “safety” marketing aided diffusion; “bicycle face” debates reflect genuine anxieties that pneumatic tires helped mitigate; comfort improvements enabled women's adoption. (Medium)

**Weak claims:** Fashion/status signaling as early Rover driver; exact diffusion pace of pneumatic tires; counterfactual about Lawson's potential success. (Low)

Overall: Reconstruction is historically credible at demonstrative scale. Subjective pressures are plausible and necessary for explaining adoption patterns, but evidence is less granular than for objective specifications. Pilot meets all success criteria: ≥3 commits, ≥12 sources, clear objective/subjective separation, disciplined confidence, and at least one transition where subjective pressure materially improves explanation.

---

**Deliverables:** `tpr-pilot-clean/` (clean artifact package)  
**Core transition selected:** C → D (pneumatic-tire introduction)  
**Comparison memo:** `pressure_comparison_clean.md` (Outcome B: hybrid slightly better overall)
