---
name: "fungal-isolation-and-culturing"
description: "Use this skill for any question involving isolating, culturing, or growing fungi; selecting or preparing culture media; collecting fungi from field samples (soil, water, wood, insects, animals, marine or estuarine substrata, deep sea); preserving or storing fungal cultures; identifying the appropriate isolation technique for a specific fungal group; aquatic, marine, freshwater, or deep-sea fungi; voucher preparation; molecular methods for fungi; culture collections or shipping regulations for biological materials; or any lab question about how to grow or work with an unusual or exotic fungal taxon.\n"
---

# Fungal Isolation and Culturing Skill

## How to Use This Skill

When a question falls into the above categories, consult the appropriate reference file before responding. Do not rely solely on training data for specific protocols, media recipes, or taxon-specific advice — the source textbook is the authoritative reference for this lab.

### Reference File Index

```
fungal-culturing/
├── SKILL.md                          ← This file
└── references/
    ├── media-recipes.md              ← All culture media formulas (Appendix II)
    ├── isolation-protocols.md        ← General isolation methodology by sample type
    ├── preservation-storage.md       ← Ch. 3: all preservation methods + shipping regulations
    ├── marine-water-column-supplement.md  ← ★ NEW: water column, iChip, and advanced marine
    │                                          methods synthesized from 35 papers (2002–2025)
    └── taxon-specific/
        ├── aquatic-fungi.md             ← ★ PRIORITY: Ch. 23, 24, 26 (freshwater, marine, deep-sea)
        ├── deep-sea-fungi.md            ← Thin stub; supplement with marine-water-column-supplement.md
        ├── macrofungi.md                ← Ch. 8: macrofungi (mushrooms, brackets, resupinates)
        ├── soil-fungi.md                ← Ch. 13: saprobic soil fungi
        ├── endophytes.md                ← Ch. 12: endophytic fungi
        ├── extremophiles.md             ← Ch. 14: thermophilic, psychrophilic, halophilic,
        │                                   xerophilic, alkalophilic, oligotrophic, rock-inhabiting,
        │                                   phoenicoid (post-fire) fungi
        ├── lichens.md                   ← Ch. 9: lichenized fungi (field survey; mycobiont culture)
        ├── coprophilous.md              ← Ch. 21: dung fungi
        ├── yeasts.md                    ← Ch. 16: yeasts (isolation from all habitats incl. marine)
        ├── sequestrate-fungi.md         ← Ch. 10: truffles/hypogeous fungi
        ├── insect-associated.md         ← Ch. 18: Trichomycetes, Laboulbeniales, bark beetle fungi
        ├── invertebrate-parasites.md    ← Ch. 19: fungal parasites of rotifers and nematodes
        ├── vertebrate-associated.md     ← Ch. 20: medical/veterinary mycology
        ├── arbuscular-mycorrhizal.md    ← Ch. 15: AM fungi (cannot culture without host)
        ├── myxomycetes.md               ← Ch. 25: mycetozoans (slime molds)
        ├── anaerobic-zoosporic.md       ← Ch. 22: rumen fungi (strictly anaerobic; Hungate technique)
        ├── microfungi-wood.md           ← Ch. 11: microfungi on wood and plant debris
        └── fungicolous-fungi.md         ← Ch. 17: fungicolous/mycoparasitic fungi

★ = Priority files for this lab's focus
```

---

## Lab Context

This skill serves an aquatic/marine mycology lab with a focus on:
- **Aquatic fungi** broadly (freshwater and marine)
- **Deep-sea fungi cultivation** (developing capability — this field is nascent)
- **Unusual and exotic taxa** — students regularly attempt to grow challenging species
- **iChip and in situ cultivation** — lab beginning iChip work; see marine-water-column-supplement.md

When students ask how to grow something, always check the taxon-specific and isolation protocol files. For media formulas, always check media-recipes.md rather than generating a recipe from memory. For marine water column, iChip, or advanced cultivation questions, always read marine-water-column-supplement.md.

---

## Key Source References

**Primary textbook:**
> **Foster, M.S., Bills, G.F. & Mueller, G.M. (eds.) (2004).** *Biodiversity of Fungi: Inventory and Monitoring Methods.* Academic Press, Burlington, MA. 777 pp.

This textbook is the ground-truth knowledge base for this skill. All protocols in the core reference files derive from this source.

**Primary literature supplement (marine-water-column-supplement.md):**
Synthesized from 35 papers including Mitchison-Field & Gladfelter 2021, Gauthier et al. 2025 (JoVE iChip protocol), Berdy et al. 2017, Nichols et al. 2010, Hagestad et al. 2020, Overy et al. 2019, Li et al. 2023, Zhang et al. 2024, and 27 additional papers covering water column filtration, marine media, iChip construction, advanced culturomics, and metagenomics-guided isolation.

---

## Quick-Reference Decisions

### "What medium should I use for [taxon/sample]?"
→ See **media-recipes.md** and **taxon-specific/[group].md**

Key groupings:
- Marine/estuarine fungi: Seawater Agar (SA), Serum Seawater Agar (SSA), KMV medium
- Marine water column (Gladfelter lab): MEA + seawater, PDA + seawater, YPD + seawater
- Arctic marine fungi: ASMEA, ASCMA, 1.0ASAsco (see marine-water-column-supplement.md)
- Alga-associated fungi: CMASW, FASW, PASW (host-extract media)
- Halophytophthora / marine Oomycetes: **A/T Oomycote Medium** (selective; see exact formula)
- Freshwater Oomycetes / Peronosporomycetes: VP3 Agar (selective)
- Freshwater ascospores/conidia: AWA (Antibiotic Water Agar)
- Aquatic hyphomycetes: 0.1% MEA or AWA
- Chytrids / zoosporic fungi: CFD water or 0% Czapek's agar
- Soil basidiomycetes: LGB medium (lignin-guaiacol-benomyl)
- Halophilic fungi: MY5-12 or MY10-12 agar
- General isolation: PDA, MEA, CMA, DRBC, YPSS, PYG
- Thermophilic/extremophile: Emerson YS agar, MYPG agar
- Endophytes: Starch-milk agar, AWA

### "How do I isolate [taxon] from [sample]?"
→ See **taxon-specific/[group].md** → Isolation section

### "How do I do iChip / in situ cultivation?"
→ See **marine-water-column-supplement.md** → Section V (In Situ Cultivation)
The modified 96-well plate protocol (Gauthier et al. 2025) is the recommended starting point.

### "How do I isolate fungi from ocean water?"
→ See **marine-water-column-supplement.md** → Section I (Water Column) and Section II (Media)
Use 0.22 µm PES filter unit; three parallel treatments; MEA/PDA/YPD in seawater.

### "How do I preserve cultures of [taxon]?"
→ See **preservation-storage.md**

Recommended permanent methods:
1. **Lyophilization** — best for sporulating fungi with small spores (≤10 µm)
2. **Liquid nitrogen** (–196°C) — best for all fungi; essential for non-sporulating taxa

### "Can I ship this culture to [destination]?"
→ See **preservation-storage.md** → Distribution and Shipping Regulations

---

## Critical Taxon-Specific Cautions

These errors are commonly made with unusual taxa — flag these proactively:

1. **Marine Oomycetes (Halophytophthora):** Do NOT use full-strength seawater — use dilute seawater (15 g salts/L). Do NOT use pimaricin (*H. spinosa* is killed by it). Do NOT use high concentrations of chloramphenicol (toxic to oomycetes). Do NOT use streptomycin.

2. **Freshwater zoosporic fungi (chytrids, Peronosporomycetes):** CFD water (charcoal-filtered distilled water) is not the same as plain distilled water — charcoal filtration is needed to promote zoospore formation.

3. **Aquatic hyphomycetes:** Are extremely temperature-sensitive — always incubate at stream/habitat collection temperature, not a standard lab temperature.

4. **Basidiomycetes in distilled water:** Do not store at 20°C (only 26% survival). Store at 5°C.

5. **Oomycetes generally:** Serial transfer on agar is the most reliable long-term method (liquid nitrogen works for some but not all species). Mite infestation is a major hazard in water culture — use glycerin moats.

6. **Lyophilization:** Only for fungi with small spores (≤10 µm). Large or delicate spores collapse and do not recover. Most oomycetes cannot be lyophilized.

7. **Marine fungi:** Dissolved oxygen is a critical limiting factor. Stagnant, low-O₂ environments inhibit or prevent growth. Deep-sea cultivation must account for this.

8. **Thraustochytrids:** Are NOT fungi (they are Labyrinthulomycetes/Stramenopiles). Use 18S not ITS for molecular ID. Pine pollen baiting is standard isolation method.

9. **iChip for fungi vs. bacteria:** Standard 0.03 µm membrane blocks fungal ingrowth entirely. Use 0.05 µm (spore capture) or 0.4–0.6 µm (hyphal ingrowth). See marine-water-column-supplement.md Section VI for full details.

---

## Deep-Sea Fungi Notes

> *Updated with primary literature — see marine-water-column-supplement.md Sections V, VIII, IX for detailed protocols.*

Key facts from primary literature (supplements the thin textbook coverage):
- Indigenous marine fungi collected as deep as 5,315 m (Kohlmeyer 1977; source textbook)
- Dissolved oxygen is the primary limiting factor for marine fungal distribution
- Deep-sea methane cold-seep sediments harbor early-diverging fungal lineages (Chytridiomycota, LKM11 clade) as dominant taxa — most not recoverable by standard plating (Nagahama et al. 2011)
- Hadal fungi (Challenger Deep, ~11,000 m) cultivated under 100 MPa hydrostatic pressure; genera include *Acremonium*, *Aspergillus*, *Aureobasidium*, *Cladosporium*, *Exophiala* (Chen et al. 2021)
- Culture-dependent + culture-independent together reveal far more diversity than either alone (Singh et al. 2012)

Suggested media starting points for deep-sea isolates:
- Dilute nutrient media (1/10 BHI), silica-gel medium, SSA/KMV/SA
- Incubate at low temperature (4°C or close to collection temperature)
- Pressurized vessel required for true piezophilic taxa
