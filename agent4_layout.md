# Agent 4 — Visual Psychology & Layout: Research Report
**For:** Redesign of an Indian restaurant's A4 menu card
**Date:** November 2026
**Scope:** Research only. Science is separated from industry opinion. Where evidence is thin, it is labelled DATA MISSING / WEAK EVIDENCE. No statistics are invented; every number traces to a named source.

---

## 1. Eye-tracking on menus and how much time customers actually spend

### Key findings
- The best-known eye-tracking study of menu reading is **Yang, S. S. (2012), "Eye movements on restaurant menus: A revisitation on gaze motion and consumer scanpaths," *International Journal of Hospitality Management*, 31(3), 1021–1029** (Cornell School of Hotel Administration work, published under her SFSU affiliation). It is the study the team brief guessed might be "Kim, Shaman" — the actual author is **Sybil S. Yang**; cite her, not Kim. *(Science)*
- Yang's headline result: diners read a two-page menu **sequentially, "like a book"** — left to right, top to bottom — reading slowly (mean fixation duration ≈ **386 ms**, cited in a follow-up study: *The sweet spot in the eye of the beholder? Exploring the sweet/sour spots of Asian restaurant menus*, JHTRS, 2020). They read for information, not quick scanning.
- Yang found **no "sweet spot"** — no region where gaze lingered systematically longer — but did find a **"sour spot"**: regions with the least attention contained restaurant branding/blurb and a salad list the mock diners did not care about. In other words: **attention follows content that matters to the diner, not fixed page coordinates.**
- She has an eat-first menu (entree chosen first, then the rest of the meal built around it), i.e. the entrée/main section effectively drives the whole choice sequence.

### Evidence/source summary
- Yang (2012), IJHM 31(3):1021–1029 — peer-reviewed, small lab sample (N=25 wearers of an infrared eye tracker reading one mock two-page menu). Press release: SF State via EurekAlert, 1 Feb 2012.
- Replication-ish follow-up: "The sweet spot in the eye of the beholder? Exploring the sweet/sour spots of Asian restaurant menus" (Journal of Hospitality & Tourism Research, 2020, doi 10.1080/19368623.2020.1790076) — re-examined sweet/sour spots on Asian menus.
- The often-quoted **"109 seconds"** average menu viewing time is **Gallup polling data from 1987**, recycled by menu-engineering vendors ever since (Modern Restaurant Management, iMotions, thrillist, etc.). It is an industry statistic, ~40 years old, methodology unclear, and predates both digital menus and current menu sizes. **Weak evidence; treat as an order-of-magnitude figure ("about 1–3 minutes") only.**
- Later eye-tracking work exists in adjacent territory (e.g., "Eating with the eyes? Tracking food choice in restaurant's menu," *Food Quality and Preference*, 2023 — tablet menus with ~60 items; "Eye movements in binary food choice context…," 2024 — menu complexity and cognitive load), confirming the field is active but not yet converging on a universal scan map.

### Practical recommendation (A4 menu)
- Assume the diner **reads the menu start-to-finish in reading order**, giving it a few minutes at most. Design for a sequential read: strong top-of-page start, logical top-down flow, no critical item buried in a low-attention zone.
- Expect the **entrées/mains section to anchor the choice**; put your strongest, most profitable mains where the sequential read reaches them early (top of the main section, top half of the page).

### Confidence: **Medium**
Yang (2012) is peer-reviewed and directly on-target, but it is a single small lab study with one mock menu; the 2020 Asian-menu follow-up is the only direct replication found.

### Potential limitations
- One menu, one culture/cuisine, lab setting, N=25. Real Indian-restaurant diners, paper menus, and repeat customers may behave differently. The "109 s" figure should never be quoted as a precise number.

---

## 2. F-pattern, Z-pattern, "golden triangle": supported vs marketing myth

### Key findings
- **F-pattern (NN/g, Jakob Nielsen 2006; reaffirmed by Kara Pernice 2017):** real, replicated finding for **web pages** — text-dense, low-motivation scanning. But NN/g itself is explicit that F-pattern is a **description of how users read unformatted prose, not a design prescription** ("F-Shaped Pattern…, But Not Something You Should Do" framing). Pages designed with good headings/bullets produce **layer-cake or other patterns** instead. *(Science, web-specific.)*
- **Menu-specific scan-pattern claims (zigzags, focal maps, sweet spots) are largely industry folklore.** Yang (2012) traced them mostly to **William Doerfler, a graphic designer, whose 1990s "focal map" was never an empirical eye-tracking study** — she called it "a bad rumor that just kept perpetuating." Her data showed sequential book-like reading and no sweet spot. *(Science debunking the folklore.)*
- The **"golden triangle"** (center → top-right → top-left, "captures 86% of attention") appears only in vendor/consultant material (Toast, costmymenu, NetSuite, etc.). The 86% figure has **no traceable primary study** — DATA MISSING. The triangle traces back to the same Doerfler-era anecdote chain. *(Industry opinion / marketing myth.)*
- The **Z-pattern** is a web/print-ads heuristic with essentially no peer-reviewed menu evidence — WEAK EVIDENCE at best; treat as myth for menus.

### Evidence/source summary
- NN/g original study (Nielsen 2006, 232 users) and 2017 follow-up (Pernice) — peer-reviewed-quality industry research, but **about the web, not menus**.
- Yang (2012) + EurekAlert release — the only direct empirical test of menu scanpath lore found; results contradict it.
- Industry sources for golden-triangle claims: Toast, Partstown, costmymenu, NetSuite — all secondhand, none cite a primary study.

### Practical recommendation
- Do **not** build the layout around a golden triangle or Z-path. Do use the *underlying, well-supported* web-reading insight, transplanted cautiously: readers lean left, read first lines/paragraphs more, and skip dense right-hand or bottom content — so put information-carrying words at the **start of item names and descriptions**.
- Anything the diner must not miss should survive a fast left-edge scan: bold item names first, prices visible in the same line, not hidden.

### Confidence: **High** (that the menu-specific scan-pattern claims are unsupported); the positive claim "menus are read like a book" is Medium per §1.

### Potential limitations
- Absence of evidence ≠ proof the pattern is absent; but the burden of proof is on the claim, and no primary study surfaced after extensive searching in 2026.

---

## 3. Best placement for high-profit items

### Key findings
- **Science:** Yang (2012) found **no empirical basis for a fixed sweet spot**; the strongest placement effect she observed was the *sour spot* — content that is low-relevance to diners (hotel/restaurant blurb, a salad list) gets least attention. Attention is driven by **relevance and salience (contrast, boxes, imagery)**, not by page coordinates.
- The 2020 JHTRS Asian-menu study revisits sweet/sour spots; consistent theme: attention clusters around **item-dense, decision-relevant regions**, not geometric corners.
- **Science on salience interventions:** menu design works when it *creates* salience — boxes, bolding, photos, and eye-catching marks increase fixations on the marked item. A 2023 **p-curve analysis (Chark & Ip, "Is menu design effective? A p-curving analysis," IJHM 2023, doi 10.1016/j.ijhm.2022.103378)** found that the published menu-design literature (wording, layout, labels, presentation) shows **genuine evidential value** (right-skewed p-curves) — i.e., menu-design effects as a family are real, though individual effect sizes are typically modest.
- **Industry:** a vendor case study (iMotions customer story) reports a restaurant lab claiming a >20% profit increase after an eye-tracked menu redesign — single case, uncontrolled. *(Industry opinion.)*

### Evidence/source summary
- Yang (2012) — the direct evidence; small N.
- Chark & Ip (2023) IJHM 103378 — meta-level validation that the menu-design literature is not all p-hacked noise, but does not endorse specific placement rules.
- Vendor claims (golden triangle "86% attention") — no primary source; DATA MISSING.

### Practical recommendation
- Instead of a fixed sweet spot: (1) **cut the sour spots** — remove or minimize low-relevance filler (long restaurant-history blurb, decorative prose) so it doesn't drain early attention; (2) place high-profit items **first in their category list** (position within the sequential read matters more than page corner) and (3) **mark them** with a single consistent highlight (box or star) — highlighting works because it creates salience, and it works anywhere on the page.
- Avoid multiple competing highlights; salience is a budget — if everything pops, nothing does.

### Confidence: **Medium** for "no fixed sweet spot + salience-driven attention"; **Low** for any specific quantified placement rule.

### Potential limitations
- Most salience findings come from lab menus; interaction with real lighting, table format, and menu size is unstudied. Highlighting studies vary; a marked *low*-quality item backfires.

---

## 4. Whitespace effects on attention and perceived premium

### Key findings
- **Science (near-domain):** Iseki et al. (2025), *Journal of Sensory Studies* — "Perception of Luxury and Product Quality in Package Design: Examining the Effects of White Space, Typeface, and Visual Texture": 2×2×2 between-participants design, **N = 1,193**; **large white space and "luxurious" typeface each enhanced perceived luxury and product quality**; the white-space finding replicated an earlier packaging experiment (2023 white-space-ratio study). *(Science — packaging domain, not menus, but the closest controlled evidence found.)*
- **General cognitive science:** whitespace reduces visual clutter, improving legibility and search speed — a well-established baseline of visual perception and document design (Gestalt figure-ground separation; classic print typography practice).
- **Industry:** "white space improves comprehension by 30%" circulates among menu vendors (fourth.com, menuzen, Toast) — this figure is recycled web-design folklore with no traceable primary study. DATA MISSING. Vendor heuristics like "aim for 35–45% whitespace," "0.5 in between sections" are opinion, not science.

### Evidence/source summary
- Iseki et al. (2025), J. Sensory Studies 10.1111/joss.70026 — large-N experimental, plus cited replication.
- Marketing claims — untraceable.

### Practical recommendation
- Treat generous whitespace as both an **attention tool** (a resting gap around an item is the cheapest way to make it stand out — consistent with §3 salience) and a **premium signal** (evidence from packaging generalizes plausibly to menus, though not proven).
- Concretely: wide margins, clear vertical gaps between categories, breathing room around the 3–5 items you want to sell — whitespace *around* an item is arguably the strongest unclaimed layout lever for an Indian restaurant A4 menu, which is typically overcrowded.

### Confidence: **Medium-High** for whitespace → luxury perception (strong packaging evidence); **Medium** for whitespace → attention allocation on menus (plausible, weakly tested).

### Potential limitations
- Evidence is from product packaging and general legibility, not dining tables. Premium-perception effects could differ for a value-oriented restaurant: whitespace reads as "expensive," which is not always the goal.

---

## 5. Information hierarchy: headings, descriptions, dividers

### Key findings
- **Science (NN/g, web):** first lines of blocks get read; scanning relies on **bold headings, bullet structure, and information-carrying first words**; "fancy formatting looks like an ad" (Nielsen) — heavy decoration gets *ignored* as banner blindness. These are robust web findings; menu transfer is analogical. *(Science, web-specific.)*
- **Science (menu):** Chark & Ip (2023) p-curve: descriptive wording, labeling, and presentation effects in menus are evidentially real. Classic menu-language finding (Wansink et al., descriptive labels ≈ +27% sales — **treat with caution: Wansink's lab is discredited and many papers were retracted; the descriptive-label effect is plausible via Spence's crossmodal work but the specific 27% should not be quoted**). Charles Spence (Oxford, *The Perfect Meal*, 2014; *Gastrophysics*, 2017) provides controlled-lab evidence that **typeface, descriptions, and sensory language shift taste expectations** — the strongest modern science hook for descriptions and typography. *(Science, mostly lab simulators/dishes.)*
- **Industry:** consistent vendor guidance — two typefaces max, italic for upscale signal, consistent item-name/price alignment, thin rules or icons as category dividers. Mostly untested opinion; directionally compatible with the science.

### Evidence/source summary
- NN/g (Nielsen 2006/2007; Moran 2019 "How People Read Online") — web eye-tracking.
- Spence & Piqueras-Fiszman (2014) book; Spence's Crossmodal Research Laboratory papers — food-specific experimental psychology.
- Chark & Ip (2023) — evidential-value check on the menu-design literature.

### Practical recommendation (A4)
- Three-level hierarchy only: **(1) Category headings** (large, bold, maybe bilingual English/Hindi given the cuisine), **(2) item names** (bold, medium, with dietary marks at line start — start-of-line words are what a fast left-edge scan catches), **(3) one-line descriptions** (regular weight, 1–2 lines max, sensory/provenance words early).
- Prices: same line as the item, aligned (industry convention, reads cleanly); **no dotted leaders** (they break the line into noise).
- One highlight style only (see §3). Dividers: whitespace alone (§4) or a thin rule — not heavy graphics.

### Confidence: **Medium** — direction well supported, menu-specific magnitudes weak.

### Potential limitations
- Web-reading findings transfer only by analogy. Wansink-era figures unreliable. Spence's effects are measured on single dishes in labs, not full menus in real restaurants.

---

## 6. Grouping, chunking, and number of items per category

### Key findings
- **"7±2 items per category"** is the menu-engineering industry norm (variously 6–7 fast-casual, 7–10 fine dining) — it descends loosely from **Miller (1956)**, which was about working-memory *span in immediate recall*, not menu browsing, and is widely misapplied. *(Industry opinion dressed as science.)*
- **Actual cognitive science:** working-memory estimates have since been revised to ~**4 chunks (Cowan, 2001)**; and the choice-overload literature is **contested**: Scheibehenne, Greifeneder & Todd (2010, JCR meta-analysis) found **average effect ≈ zero**; Chernev, Böckenholt & Goodman (2015, JCP meta-analysis of 99 observations, N≈7,200) found real but **moderator-dependent** effects (choice-set complexity, decision effort, preference clarity).
- **Menu-specific:** the choice/complexity literature on menus exists (menu-complexity eye-tracking studies, 2023–2024; p-curve analysis noted inconclusive overall effect for some menu-number-of-items relationships and recommends more studies) — i.e., **the evidence that a specific item count is optimal is WEAK / DATA MISSING**. What survives: *complexity and structure matter more than raw counts* — well-chunked, visually ordered large menus can work as well as trimmed ones.

### Evidence/source summary
- Miller (1956); Cowan (2001) — cognitive psychology, not menus.
- Scheibehenne et al. (2010) JCR; Chernev et al. (2015) JCP 10.1016/j.jcps.2014.08.002 — opposing meta-analyses (see also "Did choice overload replicate?" — the literature has no settled verdict).
- Menu-specific complexity studies (FQP 2023; 2024 menu-complexity eye-tracking; Chark & Ip 2023 note p-curve inconclusiveness for count-related claims).

### Practical recommendation
- Treat "7 per category" as a **reasonable design default, not an evidence-based rule**. The controllable variables are **chunking and hierarchy**: clear category names, ≤ ~8 items per category where feasible, one-page-per-meal-course logic — but prioritize *cutting weak/duplicative dishes* (which helps kitchen and margins anyway) over hitting a magic number.
- A large Indian menu (many breads, many curries) is best handled by **sub-grouping within categories** (e.g., "House Classics / regional specialties / breads") rather than one long list.

### Confidence: **Low-Medium** — chunking helps (High confidence in principle), specific counts (Low confidence).

### Potential limitations
- No menu-specific dose-response data found; choice-overload literature contradictory; Indian restaurant menus (high variety is part of the value proposition) may tolerate larger assortments than the norm.

---

## 7. A4 single-page vs two-panel layout

### Key findings
- **Science:** DATA MISSING — no controlled comparison of A4 single-sheet vs two-panel/bi-fold menu layouts was found in the peer-reviewed literature. Yang's study used a two-page spread and found sequential book-like reading; nothing tests single-sheet A4.
- **Relevant analogical science:** (a) sequential reading (§1) means a two-panel menu is read as *one continuous document across the fold* — the inside spread is the natural home of the main sections in reading order; (b) reading ergonomics: line length ~45–75 characters is the classic typographic comfort zone — an A4 full-width text block is too wide, so single-page A4 needs columns; (c) choice architecture (§6): capacity per panel is limited, favoring fewer, better items.
- **Industry opinion:** two-panel (A4 bi-fold) dominates full-service restaurant practice; vendors cite easier handling, natural category grouping, and a cover that signals price position. Single A4 sheets are favored for cafés/QSR and for cost. *(Industry opinion, no studies found.)*

### Practical recommendation (wireframe-level, in scope)
For a typical Indian restaurant with multiple course families (starters, tandoor/grill, curries, breads & rice, drinks, desserts):
- **Preferred: A4 bi-fold (two-panel inside spread + cover), if the item count exceeds ~25 dishes.** Inside spread reads as one document: Panel 1 = Starters → Tandoor/grill; Panel 2 = Curries/mains → Breads & rice → Desserts/drinks. Cover carries brand + one signature image only (no dense text — that's the classic sour-spot trap).
- **Acceptable: single A4 sheet, two columns**, when the menu is ≤ ~25 items. Full-width text is avoided by columns; the top-left column block (start of the sequential read) holds the highest-priority category.
- In either format: category headings > item names > one-line descriptions (§5); ≤ ~8 items per category or sub-group (§6); highlight only the profitable stars (§3); generous whitespace and margins (§4).

### Confidence: **Low** (format comparison itself is unresearched); the *internal* layout rules have Medium confidence via §§1, 3–5.

### Potential limitations
- Format choice rests on analogy and practice, not experiments. Paper stock, table space, and reprint frequency (menu changes) are real operational factors no lab study captures.

---

## 8. Bottom line for the design team

1. **The evidence-based core of menu layout is small but solid:** menus are read sequentially like a book (Yang 2012); there is no fixed sweet spot — **attention follows relevance and salience, not coordinates**; menu-design interventions as a family have real evidential value (Chark & Ip 2023); whitespace and typeface signal premium (Iseki 2025, packaging); structure/chunking beats item-count magic numbers (choice-overload meta-analyses are inconclusive on counts).
2. **Do not inherit the golden triangle, Z-pattern, "86% attention," "30% comprehension," or "7±2" claims into the final design document** — all are folklore or untraceable vendor figures.
3. **The highest-value layout moves for a typical crowded Indian A4 menu:** cut low-relevance filler (sour spots), enforce a strict 3-level hierarchy, one highlight style, generous whitespace, sub-group large categories, and let the sequential read deliver mains early.

---

### Source list (key)
- Yang, S. S. (2012). *Eye movements on restaurant menus: A revisitation on gaze motion and consumer scanpaths.* IJHM 31(3), 1021–1029. (+ SFSU/EurekAlert release, Feb 2012.)
- "The sweet spot in the eye of the beholder? Exploring the sweet/sour spots of Asian restaurant menus." Journal of Hospitality & Tourism Research (2020), 10.1080/19368623.2020.1790076.
- Chark, R. & Ip, M. (2023). *Is menu design effective? A p-curving analysis.* IJHM, 103378.
- Nielsen, J. (2006). *F-Shaped Pattern For Reading Web Content*; Pernice, K. (2017). F-pattern follow-up. Nielsen Norman Group.
- Iseki, S. et al. (2025). *Perception of Luxury and Product Quality in Package Design: White Space, Typeface, Visual Texture.* J. Sensory Studies, 10.1111/joss.70026.
- Scheibehenne, Greifeneder & Todd (2010). *Can there ever be too many options? A meta-analytic review of choice overload.* JCR.
- Chernev, Böckenholt & Goodman (2015). *Choice overload: A conceptual review and meta-analysis.* JCP, 10.1016/j.jcps.2014.08.002.
- Spence, C. & Piqueras-Fiszman, B. (2014). *The Perfect Meal.* Wiley-Blackwell; Spence (2017). *Gastrophysics.*
- Cowan, N. (2001). The magical number 4. Behavioral and Brain Sciences. Miller, G. (1956). The magical number seven.
- Gallup (1987) polling, via secondary sources — 109-second figure (weak).
- Industry sources (labelled opinion): Toast, Partstown, NetSuite, costmymenu, fourth.com, iMotions case study, Modern Restaurant Management.
