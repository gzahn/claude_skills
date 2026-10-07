# Fungal Isolation and Culturing Skill

## Triggering Description

Use this skill when a question or task involves any of the following:
- Isolating, culturing, or growing fungi (including unusual or exotic taxa)
- Selecting or preparing fungal culture media
- Collecting fungi from field samples (soil, water, wood, insects, animals, marine/estuarine substrata, deep sea)
- Preserving or storing fungal cultures (short-term or long-term)
- Identifying the appropriate isolation technique for a specific fungal group
- Aquatic, marine, freshwater, or deep-sea fungi
- Voucher preparation and documentation for fungal specimens
- Molecular methods for fungi (DNA extraction from cultures, field material)
- Questions about specific culture collections, repositories, or shipping regulations for biological materials
- Any question from lab members about how to grow or work with an unusual or exotic fungal taxon

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
    └── taxon-specific/
        ├── aquatic-fungi.md             ← ★ PRIORITY: Ch. 23, 24, 26 (freshwater, marine, deep-sea)
        ├── deep-sea-fungi.md            ← Thin stub; supplement with primary literature
        ├── macrofungi.md                ← Ch. 8: macrofungi (mushrooms, brackets, resupinates)
        ├── soil-fungi.md                ← Ch. 13: saprobic soil fungi
        ├── endophytes.md                ← Ch. 12: endophytic fungi
        ├── extremophiles.md             ← Ch. 14: thermophilic, psychrophilic, halophilic,
        │                                   xerophilic, alkalophilic, oligotrophic, rock-inhabiting,
        │                                   phoenicoid (post-fire) fungi
        ├── lichens.md                   ← Ch. 9: lichenized fungi (field survey; mycobiont culture)
        ├── coprophilous.md              ← Ch. 21: dung fungi (Myxomycetes, Zygomycetes,
        │                                   Ascomycetes, Basidiomycetes on dung)
        ├── yeasts.md                    ← Ch. 16: yeasts (isolation from all habitats incl. marine)
        ├── sequestrate-fungi.md         ← Ch. 10: truffles/hypogeous fungi (collection, live culture)
        ├── insect-associated.md         ← Ch. 18: Trichomycetes, Laboulbeniales, bark beetle
        │                                   fungi, ambrosia beetle fungi
        ├── invertebrate-parasites.md    ← Ch. 19: fungal parasites of rotifers & nematodes
        │                                   (baiting, Baermann funnel, pure culture)
        ├── vertebrate-associated.md     ← Ch. 20: medical/veterinary mycology; dermatophytes,
        │                                   systemic pathogens, environmental isolation
        ├── arbuscular-mycorrhizal.md    ← Ch. 15: AM fungi/Glomales (cannot culture without host;
        │                                   pot culture protocols, spore extraction)
        ├── myxomycetes.md               ← Ch. 25: mycetozoans (slime molds) — all groups:
        │                                   Myxomycetes, Dictyostelia, Protostelia, Acrasids
        ├── anaerobic-zoosporic.md       ← Ch. 22: rumen fungi/Neocallimasticales (strictly
        │                                   anaerobic; glove-box isolation; Hungate technique)
        ├── microfungi-wood.md           ← Ch. 11: microfungi on wood and plant debris
        │                                   (direct observation, moist chambers, particle washing)
        └── fungicolous-fungi.md         ← Ch. 17: fungicolous/mycoparasitic fungi
                                            (SCIF, lichenicolous fungi, biocontrol taxa)

★ = Priority files for this lab's focus
```

---

## Lab Context

This skill serves an aquatic/marine mycology lab with a focus on:
- **Aquatic fungi** broadly (freshwater and marine)
- **Deep-sea fungi cultivation** (developing capability — this field is nascent)
- **Unusual and exotic taxa** — students regularly attempt to grow challenging species

When students ask how to grow something, always check the taxon-specific and isolation protocol files. For media formulas, always check media-recipes.md rather than generating a recipe from memory.

---

## Key Source Reference

**Foster, M.S., Bills, G.F. & Mueller, G.M. (eds.) (2004).** *Biodiversity of Fungi: Inventory and Monitoring Methods.* Academic Press, Burlington, MA. 777 pp.

This textbook is the ground-truth knowledge base for this skill. All protocols, media recipes, and methodology described in the reference files derive from this source.

Additional primary literature will be added to `/references/` as supplemental files (named by topic or author).

---

## Quick-Reference Decisions

### "What medium should I use for [taxon/sample]?"
→ See **media-recipes.md** and **taxon-specific/[group].md**

Key groupings:
- Marine/estuarine fungi: Seawater Agar (SA), Serum Seawater Agar (SSA), KMV medium
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

### "How do I preserve cultures of [taxon]?"
→ See **preservation-storage.md**

Recommended permanent methods:
1. **Lyophilization** — best for sporulating fungi with small spores (≤10 µm)
2. **Liquid nitrogen** (–196°C) — best for all fungi; essential for non-sporulating taxa

### "Can I ship this culture to [destination]?"
→ See **preservation-storage.md** → Distribution and Shipping Regulations

### "Is there a specific marine fungal medium?"
→ See **media-recipes.md** → Priority Media for Aquatic Fungi section; and **taxon-specific/aquatic-fungi.md** → Media Summary table

---

## Critical Taxon-Specific Cautions

These errors are commonly made with unusual taxa — flag these proactively:

1. **Marine Oomycetes (Halophytophthora):** Do NOT use full-strength seawater — use dilute seawater (15 g salts/L). Do NOT use pimaricin (*H. spinosa* is killed by it). Do NOT use high concentrations of chloramphenicol (toxic to oomycetes). Do NOT use streptomycin.

2. **Freshwater zoosporic fungi (chytrids, Peronosporomycetes):** CFD water (charcoal-filtered distilled water) is not the same as plain distilled water — charcoal filtration is needed to promote zoospore formation.

3. **Aquatic hyphomycetes:** Are extremely temperature-sensitive — always incubate at stream/habitat collection temperature, not a standard lab temperature.

4. **Basidiomycetes in distilled water:** Do not store at 20°C (only 26% survival). Store at 5°C.

5. **Oomycetes generally:** Serial transfer on agar is the most reliable long-term method (liquid nitrogen works for some but not all species). Mite infestation is a major hazard in water culture — use glycerin moats.

6. **Lyophilization:** Only for fungi with small spores (≤10 µm). Large or delicate spores collapse and do not recover. Most oomycetes cannot be lyophilized.

7. **Marine fungi:** Dissolved oxygen is a critical limiting factor. Stagnant, low-O₂ environments (anaerobic sediments, minimum oxygen zones) inhibit/prevent growth. Deep-sea cultivation must account for this.

---

## Deep-Sea Fungi Notes

> *This section is intentionally thin — the field of deep-sea fungal cultivation is nascent and the 2004 source textbook has limited coverage. This section should be supplemented with primary literature.*

What is known from the source:
- Indigenous marine fungi have been collected as deep as 5,315 m (Kohlmeyer 1977)
- Dissolved oxygen is the primary limiting factor for marine fungal distribution
- No growth observed in "minimum oxygen zones" at 0.30 ml O₂/L; growth occurred at 1.26 ml O₂/L

Key gaps to fill with primary literature:
- Pressure tolerance and cultivation under elevated pressure
- Temperature requirements for psychrophilic deep-sea isolates
- Nutrition requirements (oligotrophic conditions)
- Culture media adapted for deep-sea isolates (likely dilute/low-nutrient)
- Sampling methods (Niskin bottles, sediment corers, ROV-based collection)

**Suggested media starting points for deep-sea isolates** (extrapolating from principles in source):
- Dilute nutrient media (1/10 BHI is specifically described as a "low-nutrient source" that supports only limited colony development but is nearly transparent for detecting minute growth)
- Silica-gel medium (described in source for oligotrophic fungi — very low nutrient)
- Seawater-based media (SSA, KMV, SA) with lower nutrient concentrations
- Incubation at low temperature (4°C or close to collection temperature)
