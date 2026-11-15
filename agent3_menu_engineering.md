# Agent 3 — Menu Engineering & Pricing Psychology
### Research input for redesigning an Indian restaurant's A4 menu card
Compiled: November 2026. Research only — no design decisions are made here.

---

## 0. How to read this report

**Evidence labels used throughout**

| Label | Meaning |
|---|---|
| **[SCIENCE]** | Peer-reviewed, replicated or meta-analysed; effect direction is reliable |
| **[FIELD]** | Peer-reviewed but a single field study / single site; direction plausible, size uncertain |
| **[LAB]** | Peer-reviewed controlled experiment, usually students/hypothetical menus; direction plausible, real-menu size usually smaller |
| **[PRACTICE]** | Industry/consultant claim. Not evidence. Useful as hypothesis only |
| **[MISSING]** | No usable evidence found. Explicitly flagged, never filled with a guess |

**Three facts that frame everything below**

1. Menu-engineering arithmetic (price − cost × units) is **accounting, not psychology**. It is reliable *given* good cost and sales data. Almost all the disagreement in the literature is about the data, not the maths. [SCIENCE]
2. The behavioural "menu psychology" effects that get quoted at seminars are **small on average**. The best available meta-analysis of menu-design experiments reports an overall effect size of 0.39 (95% CI 0.34–0.45) with significant heterogeneity, and finds item position, description and label effects only *marginal* (Ip & Chark, 2023, IJHM 108:103353). [SCIENCE]
3. A large share of the numbers circulating in menu-design content ("right-justified prices +12%", "decoys shift 20–30%", "menu engineering +10–15% profit") have **no traceable primary source**. Section 12 lists them. Do not put them in a client document.

---

## 1. Menu engineering and the Stars / Plowhorses / Puzzles / Dogs model

### Key findings

- The model is **two-dimensional**: popularity (units sold, or sales mix %) × profitability (**contribution margin** = menu price − direct item cost), not food-cost percentage. Kasavana's own later writing is explicit that low food-cost % is not the same as profitability, and that operators who promote low-food-cost items usually promote their *cheapest* items and lower the average check. [PRACTICE, but from the model's author]
- **Canonical definitions** (Kasavana & Smith, 1982):
  - **Star** = high popularity + high contribution margin
  - **Plowhorse** = high popularity + low contribution margin
  - **Puzzle** = low popularity + high contribution margin
  - **Dog** = low popularity + low contribution margin
- **Popularity threshold**: the rule attributed to Kasavana & Smith is *70% of an equal share*, not 70% of average sales. With 10 items in a category, equal share = 10%, so the cut-off is 7%. This distinction is widely garbled in secondary sources; a menu with 6 items has a 11.7% cut-off, so the same dish can be a Star on one menu length and a Plowhorse on another. [SCIENCE for the rule as written; PRACTICE for the variants]
- **Contribution margin must include more than food**: the author's later guidance is to include waste, incremental labour for in-house prep/plating, condiments and packaging. Most operators use food cost only, which systematically mis-ranks labour-heavy Indian dishes (biryanis, tandoor items, freshly fried breads). [PRACTICE]
- **Canonical prescriptions** (as taught, not as tested):
  - Star → protect, keep visible, do not discount
  - Plowhorse → re-engineer cost/portion first; only then test price
  - Puzzle → reposition, rename, describe, train servers to suggest
  - Dog → remove or replace
- **The model's known failure**: it assumes items are independent. They are not. Raising a Plowhorse's price pushes guests to its sibling; removing a Dog can move demand to a *lower*-margin item. A 2020 field study using two years of data from **48 outlets of a US steakhouse chain** built a five-stage framework around own- and cross-price elasticities and reported positive net revenue effects from pricing/placement decisions that account for within-category substitution (Noone & Cachia, 2020, IJHM 87:102504). [SCIENCE — strongest empirical upgrade to classic ME]
- Earlier work had already flagged one interdependency: loss-leader pricing distorts menu-mix analysis (Cohen, Ghiselli & Schwartz, 2007, as reviewed in Noone & Cachia 2020). [SCIENCE]
- Menu-analysis literature also criticises ME for using only food cost and sales counts and **ignoring labour/time** — a dish with a high contribution margin that hogs the tandoor for 20 minutes may be worse than a lower-margin dish that turns in 8. [SCIENCE, DEA-based menu-analysis literature, IJHM 2011]
- Adoption is not universal: Kasavana (2025) reports roughly **40% of restaurants self-report using menu engineering**. Treat as an industry survey figure, not a measured population statistic. [PRACTICE]

### Evidence/source summary

Kasavana & Smith (1982), *Menu Engineering: A Practical Guide to Menu Analysis*, Hospitality Publications — the primary source; a 1990 revision exists. Kasavana (2025), "The Power of Menu Engineering – Part One", AHLEI — the author restating definitions, costing scope and the food-cost-percentage trap. Noone & Cachia (2020) — the substitution-aware extension, field-tested across 48 units. Cohen et al. (2007) — loss leaders. DEA menu-analysis work (IJHM, 2011) — labour omission.

Note on naming: "Plowhorse" (US) and "Plough horse" (UK/Indian usage) are the same quadrant; pick one spelling and use it consistently.

### Practical recommendation for organizing items and prices

1. **Build the matrix from the restaurant's own POS data before touching the layout.** 8–12 weeks of item counts, not one month: on a small A4 menu with ~35–45 dishes and modest covers, one week's counts are noise, and the 70%-of-equal-share cut-off will flip items between quadrants.
2. **Cost every dish fully** — food + waste + incremental labour + packaging + condiments. Then compute contribution margin in ₹, not %.
3. Classify per **category**, not across the whole menu (starters compete with starters). Record the threshold you used; it changes the answer.
4. Expect the typical Indian pattern to be: breads/rice and some veg gravies = Plowhorses; tandoori kebabs, biryanis, signature curries, desserts = Stars/Puzzles; long-tail "international" dishes and low-selling specials = Dogs. **This is a hypothesis to test, not a finding — no published Indian dataset exists.** [MISSING]
5. Treat the four boxes as *conversation starters with the kitchen*, not verdicts: a Dog that is a loss leader, a kids' dish, or the only Jain/vegan option is not a Dog for removal.

### Confidence level
**High** for the arithmetic and quadrant definitions; **Medium** for the prescriptions (they follow from the arithmetic, but the "what to do" step is untested as a bundle); **Low** for any specific uplift figure.

### Potential limitations
Threshold arbitrariness; food-cost-only costing in most implementations; independence assumption; ignores labour and seat time; ignores demand elasticity; a "Dog" may be strategically necessary (dietary, cultural, supply chain); POS data quality is usually the binding constraint. **Source caveat:** the 1982 Kasavana & Smith book itself was not inspected directly (not digitised/openly available); the formulas, quadrant names and the 70%-of-equal-share threshold were confirmed across multiple independent secondary sources and the author's own 2025 restatement.

---

## 2. Profitability vs popularity: the real trade-off

### Key findings

- **Popularity is not profitability and margin is not popularity — but on a menu they trade against each other through price.** The classic error is treating a Plowhorse as a pricing problem. It is usually a *costing* problem first: portion, garnish, plate cost, prep labour, or a side that is given away.
- **Price changes move demand to siblings.** In a category of five curries, a ₹40 increase on one does not remove ₹40 of demand; it moves demand sideways. This is why item-by-item price tests overstate the damage and understate the gain (Noone & Cachia, 2020). [SCIENCE]
- **Cost-plus pricing is not demand-based pricing.** Kiefer, Kelly & Burdett (1994) ran a live-restaurant experiment to estimate a menu item's demand curve and showed that markup-over-cost rules ignore the demand response that determines profit (JBES 12(3):329–337; a companion practitioner version appeared in *Cornell Hotel & Restaurant Administration Quarterly*). [FIELD]
- **Guests' willingness to pay is measurable without changing prices**: price-sensitivity measurement (PSM) surveys identify an acceptable price range and indifference/optimal points per item (Raab, Mayer, Kim & Shoemaker, 2009, *Journal of Hospitality & Tourism Research* 33(1):93–105). Useful when POS history is thin (new menu, new restaurant). [SCIENCE — method, not effect size]
- **Price is a weak quality signal in restaurants.** A field experiment in an upscale Tel Aviv restaurant manipulated prix-fixe prices without diners' or servers' knowledge: higher prices did **not** produce the expected higher demand, and the researchers describe the effects as "too small to matter" (Heffetz & Shayo, 2009, *AEJ: Applied* 1(4)). This is the single most useful corrective to "charge more to look premium". [FIELD]
- **Cutting a Dog is not free**: removal changes the *comparison set* for the remaining items and can reduce perceived variety. There is no field evidence quantifying this on restaurant menus. [MISSING]

### Evidence/source summary

Kiefer et al. (1994); Raab et al. (2009); Noone & Cachia (2020); Heffetz & Shayo (2009). All peer-reviewed. None is Indian; none is a full-menu optimisation trial.

### Practical recommendation for organizing items and prices

1. **Sequence of levers, cheapest first**: (a) re-cost and re-portion Plowhorses, (b) re-describe and reposition Puzzles, (c) test price on Plowhorses in small steps (₹20–30, one sub-category at a time, 4–6 weeks), (d) remove Dogs only after checking they are not serving a dietary/strategic role.
2. **Judge price tests on gross profit and mix, not revenue.** A price rise that loses 8% of units but gains 15% margin per unit is a win that a revenue report hides.
3. **Never change every price at once.** On an A4 card you have one shot per print run; change one category per run so you can attribute the effect.
4. **Do not price by food-cost percentage targets alone** (e.g., "30% food cost"). It pushes the menu toward cheap ingredients and small plates, and it is the exact error Kasavana warns about.

### Confidence level
**High** that profitability and popularity must be managed jointly and that substitution matters; **Medium** that small stepped price tests are sufficient to detect the effect at typical covers; **Low** on any expected profit uplift.

### Potential limitations
Elasticity estimates need volume the restaurant may not have; price tests are confounded by seasonality, festivals, weather and menu print cycles; no Indian elasticity benchmarks exist publicly [MISSING].

---

## 3. Price anchoring on menus

### Key findings

- **Anchoring itself is one of the most robust findings in behavioural economics** — an initial number shifts subsequent judgements, including willingness to pay. [SCIENCE, general]
- **On restaurant menus, the field evidence is thin.** The best-known menu-specific claims come from consultants: "put a ₹1,200 dish at the top so the ₹450 dish looks reasonable". The mechanism is plausible and the lab evidence for context effects on choice is strong (see §6, §8), but there is very little *real-order* evidence that adding a high-priced item raises total spend.
- The most direct recent attempt is a **2026 conference paper** using ~3,000 orders over four weeks from three mid-range Beijing restaurants plus a difference-in-differences design and eye-tracking on 100 customers, around restaurants that routinely carry a high "anchor" item. It is a low-tier proceedings chapter, single market, and the abstract reports a welfare/behavioural argument rather than a clean causal uplift estimate. Treat as suggestive only. [FIELD — weak]
- **A high-priced anchor does not automatically raise sales.** A correlational study of **270 US wine lists** found that a "Reserve" section was associated with higher wine sales, but the study is cross-sectional and cannot separate the anchor from the restaurant's positioning (Yang & Lynn, 2009, Cornell CHR 9(11)). [FIELD — correlational]
- **The "premium item makes everything look cheap" story fails when the premium item is implausible.** Price–quality inference is weak in real restaurants (Heffetz & Shayo, 2009), so an anchor that guests read as "not for people like me" or "absurd" changes nothing, and may damage trust.
- **Anchoring works on the *range*, not the average.** The realistic claim is that a visible top price shifts where guests think "normal" sits — which is exactly what the compromise-effect field data supports (see §6).

### Evidence/source summary

General anchoring: Tversky & Kahneman (1974), *Science* — [SCIENCE]. Menu-specific: Dong (2026), *Proceedings of ICHCH 2025*, Springer, pp. 532–540, doi:10.2991/978-2-38476-585-0_59 — [FIELD, weak]. Wine lists: Yang & Lynn (2009), Cornell CHR 9(11), 270 lists, 46 attributes — [FIELD, correlational]. Counter-evidence on price→quality: Heffetz & Shayo (2009).

**Explicitly:** no peer-reviewed field experiment was located that randomly adds a high-priced anchor item to a restaurant menu and measures total spend. That study does not appear to exist yet. [MISSING]

### Practical recommendation for organizing items and prices

1. **Use a real premium option, not a fake one.** One genuinely available, genuinely good high-priced item per major category (a large seafood/tandoor platter, a chef's tasting thali, a premium biryani) is defensible; a dish engineered never to sell is not (see §8).
2. **Place the premium item where it will be read but not first** — top of a category or the top-right of a spread is the consultant convention; the evidence for position is marginal (Ip & Chark, 2023), so treat placement as a design choice, not a revenue lever.
3. **Do not expect an uplift you can measure.** Anchor effects, if any, will be inside normal week-to-week variance on an A4 menu.
4. **Keep anchors *within* plausible reach of the target item.** A top price 5–8× the category median reads as a different restaurant; 1.5–2.5× reads as "the special occasion option".

### Confidence level
**Medium** that a genuine premium tier shifts the perceived price range; **Low** that it raises average spend; **High** that fake/absurd anchors are a risk with no documented upside.

### Potential limitations
Almost all menu anchoring claims are consultant folklore recycled across blogs; the one field study is a low-tier publication; wine-list evidence is correlational; menu context effects may be much weaker than lab context effects because guests have external reference prices (Zomato/Swiggy, peers, previous visits).

---

## 4. Removing currency symbols (the Cornell study)

### Key findings — with the citation corrected

- **The paper is Yang, Kimes & Sessarego (2009), not "Yang, Kimes & Gallo".** No author named Gallo appears on it. Sources citing "Yang, Kimes & Gallo (2009)" are mis-citing; the third author is Mauro M. Sessarego (then of the Culinary Institute of America).
  - Yang, S. S., Kimes, S. E., & Sessarego, M. M. (2009). *Effects of Menu-price Formats on Restaurant Checks.* Cornell Hospitality Report, Vol. 9, No. 8.
  - Companion journal article: Yang, S. S., & Kimes, S. E. (2009). "Menu price presentation influences on consumer purchase behavior in restaurants." *International Journal of Hospitality Management*, 28(1).
- **Design**: 201 diners at a café at the Culinary Institute of America (Hyde Park, NY), described as "upscale casual", randomly given one of three menus with identical food and identical prices in three formats: `$20.00`, `20.`, `twenty dollars`.
- **Result**: guests who saw **numerals without a currency symbol spent about $5.55 more per person — roughly 8% more** than guests who saw the `$` format. Spending under `$20.00` and under `twenty dollars` did **not** differ significantly. [FIELD]
- **Authors' interpretation**: references to dollars — symbol or word — remind people of the "pain of paying"; numerals alone do not.
- **Partial corroboration, correlational**: in the 270-wine-list study, restaurants whose lists omitted the dollar sign had higher wine sales (Yang & Lynn, 2009). Cross-sectional, so restaurant tier may explain both. [FIELD, correlational]
- **What the study did not show**: it did not show *which* items guests chose, whether they added courses or traded up, whether profit rose (no cost data), or whether the effect persisted beyond one visit. It also did not test an Indian rupee menu.

### Evidence/source summary

Yang, Kimes & Sessarego (2009), CHR 9(8); Yang & Kimes (2009), IJHM 28(1); Cornell Chronicle, 9 Dec 2009 (author interview, confirms n = 201, café at CIA, ~8%/$5.55). One field study, one site. **No published direct replication was located.** [MISSING for replication]

### Practical recommendation for organizing items and prices

1. **Removing the ₹ symbol is the single best-supported formatting change available** — but treat the 8% as a ceiling from one US café in 2009, not a forecast.
2. **Keep the numbers obviously prices.** `249` at the end of a description is fine; a bare `249` floating in white space is ambiguous and can read as a typo. Number + consistent position does the work.
3. **Drop decimals as well** (₹249, not ₹249.00). The tested "numerals only" format was `20.`, i.e. no cents. Indian menus already usually do this, so the remaining lever is the symbol itself.
4. **Test it on one section, one print run** — e.g., remove ₹ from mains only — and compare mix and spend for 4–6 weeks. This is cheap and reversible.
5. **Check optics and compliance locally.** An Indian guest may read a symbol-free menu as upscale/foreign (fine) or as unclear (not fine). Also confirm the restaurant's tax-display obligation with its accountant — display rules for menu prices in India have been contested (GST-inclusive vs exclusive; the 2022 service-charge guidelines), and a formatting experiment must not create a compliance problem. [MISSING — legal question, out of scope here]

### Confidence level
**Medium.** The effect is real in the one study that tested it, in the expected direction, and corroborated correlationally — but it is a single site, 201 diners, 2009, US, and unreplicated.

### Potential limitations
Single operation and single price level; possible novelty effect from an unusual menu format; spend per person ≠ profit; USD context with no ₹ equivalent; possible confound in that `20.` with a trailing period is an unusual US format, which may itself have drawn attention away from price; the ₹ symbol was only adopted in 2010, so there is no Indian analogue of this study at all [MISSING].

---

## 5. Price placement: aligned with descriptions vs right-aligned column

### Key findings — including a citation that does not check out

- **The widely repeated "Kern study" could not be located.** Searches across hospitality journals, RePEc/EconPapers, Google-indexed scholarship and citation trails returned **no peer-reviewed menu price-placement study by an author named Kern**. Every source that cites it gives no journal, year, volume or sample — only the claim, usually with a number attached ("right-justified prices raise willingness to pay by up to 12%"). [MISSING — treat as apocryphal until someone produces a full citation]
- **Most likely explanation**: a garbled reference to **Kimes** (Cornell), whose actual 2009 work with Yang is about currency symbols (§4), *not* alignment. That is an inference, not a finding.
- **What the real literature says**: menu-design experiments have been meta-analysed, and **item position, description and label produce only marginal effect sizes**; the overall menu-design effect (0.39) is driven mainly by other dimensions such as menu-card characteristics (Ip & Chark, 2023, IJHM 108:103353). A companion p-curve analysis finds the menu-design literature as a whole does have evidential value (right-skewed p-curve, z = −13.65) but is built on small samples (Chark & Ip, 2023, IJHM 108:103378). [SCIENCE]
- **No study was found that randomly assigns aligned-vs-column price placement and measures spend.** [MISSING]
- **Industry practice is split, and confidently contradictory**: one camp says columns create a "price trail" that makes guests shop on price; another says right-aligned columns look professional and speed scanning. Both are asserted without data. Kasavana (2025), relaying practitioner material, states that "placing menu item prices in a column causes customers to focus on price, not food" — this is the strongest statement available and it is [PRACTICE], not evidence.
- **A real constraint that outranks the folklore**: alignment consistency. Ragged prices make a menu look careless; whether they are columned or inline matters far less than whether the choice is executed consistently with the type hierarchy.

### Evidence/source summary

No primary source for the Kern/12% claim. Ip & Chark (2023) and Chark & Ip (2023) for the meta-level state of the field. Kasavana (2025) for the practitioner view. Yang, Kimes & Sessarego (2009) is about symbols, not alignment, and should not be quoted for alignment.

### Practical recommendation for organizing items and prices

1. **Pick one system and be consistent.** Two defensible systems:
   - **Inline (nested) price** at the end of the description, same size or slightly smaller than body text, lighter weight, same colour as body: `...slow-cooked overnight, finished with saffron. 420`
   - **Right-aligned column** at a fixed x-position, numerals only, unbolded: best when items have no descriptions or very short ones.
2. **For an A4 card with descriptions, inline pricing is the lower-risk default** — it removes the vertical price column that consultants warn about, and it survives awkward line breaks better than a column. This is a design judgement with **no experimental support**; say so.
3. **No leader dots.** They create a visual price track and belong to the column system's worst version. [PRACTICE]
4. **Never mix the two systems on one card.** Mixed placement reads as an error, and it destroys any chance of learning anything from a test.
5. **If the restaurant wants a decision rather than a default**: print one run of each section in each style on a small insert and compare 4-week mix. That is the only way to answer it locally.

### Confidence level
**Low.** There is no reliable evidence on this question, and the confident numbers in circulation are unsourced. The one thing that can be said with confidence is that the "12% from Cornell/Kern" claim should not be repeated.

### Potential limitations
Absence of evidence here is genuine absence, not proof of no effect — placement probably matters a little, in interaction with type size, weight, colour and description length, all of which are Agent 4's and Agent 5's territory. Any single-factor test will be confounded by those.

---

## 6. Good-Better-Best tiered pricing

### Key findings

- **Extremeness aversion / the compromise effect is one of the better-supported context effects**: middle options are chosen disproportionately more often, and a meta-analysis confirms the direction while showing substantial variation in strength across settings (Neumann, Böckenholt & Sinha, 2016, *Journal of Consumer Psychology* 26(2):193–212). [SCIENCE]
- **It survives in a real restaurant.** Using cashier data from a German specialties restaurant — **more than 88,000 individual choices over seven years** — options that became the compromise after a change in the choice set gained **on average 5% market share** (Pinger, Ruhmer-Krell & Schumacher, 2016, *JEBO* 128:14–34). [FIELD — the best field evidence in this whole report]
- **Critical nuance for an Indian restaurant**: in the same study the compromise effect was **pronounced in groups and statistically insignificant for single diners**. Indian full-service dining is heavily group/family-based, which makes this finding more relevant here than its German origin suggests — but that transfer is an inference, not a tested result. [FIELD + inference]
- **Three tiers is a convention, not a law.** The "good-better-best" framing is a practitioner framework (Mohammed, 2018, *Harvard Business Review*, Sept–Oct) built on the observation that price-insensitive and price-sensitive guests can be served from one list. The three-tier number comes from the compromise-effect literature, not from the HBR article's evidence. [PRACTICE + SCIENCE]
- **Tiers must be legible.** If guests cannot instantly see *what* they get for the extra money (portion, protein, number of dishes, premium ingredient), the middle tier has no reason to exist.

### Evidence/source summary

Neumann et al. (2016) — meta-analysis; Pinger et al. (2016) — 88,000+ real choices, seven years, one restaurant; Mohammed (2018) — practitioner framework. No restaurant-specific study of *menu* tiering (as opposed to product-line tiering) was found. [MISSING]

### Practical recommendation for organizing items and prices

1. **Three visible tiers per major category**, not across the whole menu: e.g. a plain / signature / premium version of the same dish family (veg / chicken / prawn; half / full; regular / large thali). This keeps tiers comparable, which is what the compromise effect requires.
2. **Make the middle tier the one you want to sell** — it will be chosen disproportionately anyway; make sure its margin is not the worst of the three.
3. **Give each tier a one-line reason to exist.** "Same gravy, extra portion" is not a tier; "same gravy, prawn instead of paneer" is.
4. **Do not create a tier you would be embarrassed to serve**, purely to make the middle look good. That is a decoy (§8), with all the same risks.
5. **Watch the bottom tier.** If the cheapest option is conspicuously poor value, guests may leave rather than trade up; if it is conspicuously good value, it cannibalises the middle.

### Confidence level
**High** that middle options are over-chosen (meta-analytic + field); **Medium** that a 3-tier structure on an A4 Indian menu captures the effect at a useful size (~5% share shift is the realistic benchmark); **Low** on revenue outcome without cost data per tier.

### Potential limitations
The +5% figure is share shift within a choice set, not profit; German cuisine and a specialties restaurant; single-diner null result means counter/lunch/quick-service formats may see nothing; tiering increases menu length, which fights the A4 constraint.

---

## 7. Bundle psychology: combos, thalis, meal deals

### Key findings

- **Bundles work by changing the comparison, not by maths.** A bundle is evaluated against the sum of its parts and against other bundles, so bundle *presentation* matters as much as bundle *price*. In a hospitality study, the effect of price-bundling presentation on bundle choice was **moderated by the consumer's certainty about quality** — when guests were unsure what they were getting, the framing mattered more (Kwon & Jang, 2011, IJHM 30(2):337–344). [SCIENCE — lab]
- **What drives meal choice inside a bundle** is not just price: a study of meal choice in a bundling context found bundle attributes (including the composition and the relative price of components) shape selection, and noted that a component priced high à la carte can be used to make the bundle look better value (Myung, McCool & Feinstein, 2008, IJHM 27(1):119–125). [SCIENCE — survey/experiment]
- **Thali is India's native bundle** and is culturally pre-solved: one price, many components, no decision fatigue. There is **no peer-reviewed study of thali pricing or thali choice** that this search could locate. All thali advice in circulation is [PRACTICE]. [MISSING]
- **Bundle discount ≠ perceived discount.** Work on combo meals has found consumers do not necessarily perceive the discount as larger than its monetary value — i.e. there is no free "deal glow" that lets you cut less than you claim. [SCIENCE, bundling literature]
- **Bundles can cannibalise Stars.** If the thali contains a Star dish at a discount, you have just discounted your best margin item. Bundle the Plowhorses and Puzzles, not the Stars.

### Evidence/source summary

Kwon & Jang (2011); Myung et al. (2008); general price-bundling literature (mixed-leader/mixed-joint bundling effects on value perception). All lab/survey, none Indian, none thali-specific.

### Practical recommendation for organizing items and prices

1. **Two or three bundles maximum on an A4 card** — typically a lunch thali, a vegetarian thali, and one group/family platter. More than that turns the menu into a promotions leaflet and dilutes the à la carte.
2. **Price the bundle below the sum of parts by a visible, honest margin** (roughly 10–20% is the common practice; there is no evidence for an optimal number) and make sure the bundle's contribution margin is at or above the menu average. [PRACTICE]
3. **Build bundles from Plowhorses and Puzzles**, plus a small quantity of one desirable item (a kebab, a dessert) to give the bundle a reason to be chosen.
4. **Name the bundle by occasion or content**, not by discount ("Lunch Thali", "Family Table") — this keeps the value framing on the food rather than on the saving.
5. **Keep bundle composition stable for at least a quarter.** Changing components resets the comparison and makes results unreadable.

### Confidence level
**Medium** for the mechanics (bundles shift choice; quality certainty moderates framing); **Low** for any specific uplift or discount depth; **Low/Very Low** for thali-specific claims, because the evidence base is empty.

### Potential limitations
Almost all bundle research is on product bundles or lab menus; restaurant bundles interact with sharing behaviour, which is central in Indian dining and unstudied; bundle discounts can train guests to wait for deals; food-cost creep in bundles is common and invisible.

---

## 8. Premium anchors and decoy items

### Key findings

- **Decoy (asymmetric dominance) effect**: adding an option that is clearly worse than one alternative but only slightly worse than another shifts choice toward the dominating option (Huber, Payne & Puto, 1982, *JCR* 9(1)). [SCIENCE — original lab]
- **The decoy effect is fragile outside the lab.** A series of experiments with real products and real money found the attraction effect frequently failed to appear, and concluded its practical scope is much narrower than the textbook version (Frederick, Lee & Baskin, 2014, *Journal of Marketing Research* 51(4):487–507). [SCIENCE]
- **On menus specifically, the evidence is mixed and mostly null.**
  - A conceptual/demonstration paper proposed adding items "that virtually no one ever chooses" to improve the price–value perception of the line (Shoemaker, 1994, *Journal of Restaurant & Foodservice Marketing* 1(1):89–101). [SCIENCE — conceptual]
  - Two online menu trials testing priced decoys for sustainable choices found **no main effect** of decoy presence (study 1 OR 1.08; study 2 replicated across seven menu conditions with a more expensive decoy, again no main effect) (Attwood et al., 2020, *Appetite*). [SCIENCE — null]
  - A 2024/2025 *International Hospitality Review* paper reports four experiments in which decoy pricing increased choice of more expensive bundles in restaurant and hotel contexts — lab/scenario designs, not real orders. [LAB]
- **Why decoys underperform on a real menu**: a menu is a repeated-purchase, socially visible, constrained-space medium. A dish nobody ever orders is a line of type that costs rent, invites questions from staff, and signals that the menu was engineered. On a single A4 sheet, that cost is higher than on a 12-page menu.
- **Anchors and decoys are not the same thing.** An anchor changes the reference price; a decoy changes the relative attractiveness of two specific options. Most practitioner writing conflates them, which is why the claims are unfalsifiable.

### Evidence/source summary

Huber, Payne & Puto (1982); Frederick, Lee & Baskin (2014); Shoemaker (1994); Attwood et al. (2020); *International Hospitality Review* (2024/2025), doi:10.1108/IHR-04-2024-0023 (author list not verified from the paywalled source page). No real-restaurant field experiment with a decoy dish was found. [MISSING]

### Practical recommendation for organizing items and prices

1. **Do not put a dish on the card that you do not intend to serve well and sell sometimes.** On an A4 card, space is the scarcest resource; a dead decoy costs a line of type, a menu slot and staff credibility.
2. **If you want the effect, use a *real* premium item as the upper reference** (§3) and a *real* mid tier as the compromise (§6). Those two effects have field support; the decoy does not.
3. **If a decoy is used anyway**, make it a genuine variant that a minority will order (e.g. a very large sharing platter) rather than an implausible dish, and review its sales after one quarter.
4. **Never let the decoy be the item the kitchen hates making.** It will show in the food.

### Confidence level
**High** that decoys are unreliable outside controlled settings; **Medium** that they are a net negative on a small menu (a judgement, not a measured result); **Very Low** for any specific decoy uplift claim.

### Potential limitations
Null results come from online trials, which may under-power the effect; some real menus do appear to benefit; the mechanism may work for wine/spirits lists (long, high-involvement, unfamiliar) where it has never been cleanly tested either.

---

## 9. Nine-ending vs round pricing in restaurants

### Key findings

- **The left-digit effect is real but narrow.** Nine-ending prices are perceived as smaller than a price one cent higher **only when the leftmost digit changes** (e.g. 2.99 vs 3.00), across five experiments (Thomas & Morwitz, 2005, *JCR* 32(1):54–64). [SCIENCE]
  - Direct consequence for a rupee menu: **₹299 vs ₹300 works; ₹349 vs ₹350 does not** (leading digit 3 in both). Most Indian menus use the second pattern far more than the first.
- **In retail field experiments, $9 endings increased demand in all three experiments, and more strongly for new items than for established ones** (Anderson & Simester, 2003, *Quantitative Marketing and Economics* 1(1):93–110). [FIELD]
- **The average effect on purchase is small.** A preregistered meta-analysis (k = 69 studies, 362 effect sizes, N = 40,541) estimates the just-below vs round effect on purchase decisions at **g = 0.13 (95% CI 0.01–0.25)** — about a quarter the size of a typical marketing effect — while the effect on *price underestimation* is much larger (Troll, Frankenbach, Friese & Loschelder, 2024, *Journal of Consumer Psychology*). [SCIENCE]
- **A 2026 preregistered, high-powered test found endings did not reliably affect quality image or purchase intention**; what did differ is that **precise prices had the best price image and were most likely to be underestimated in recall**, ahead of just-below, ahead of round (Escher et al., 2026, *Frontiers in Behavioral Economics*). [SCIENCE — recent, and a caution against over-reading 9-endings]
- **Restaurant-specific field evidence exists but is thin**: in a small French pizzeria-grill, making one target pizza a nine-ending price while other items ended in zero increased choice of that pizza; the authors describe the study as a research note (Guéguen, Jacob, Legoherel & Ngobo, 2009, IJHM 28(1):170–172). [FIELD — small]
- **The effect is relative, not absolute.** Guéguen's design worked because the 9-ending target *contrasted* with round-priced neighbours. On a menu where every price ends in 9, the contrast — and the effect — disappears. [SCIENCE, inference from design]
- **Round prices signal something else.** Rounded numbers are processed more fluently and encourage reliance on feelings, which helps hedonic/emotional purchases and can suit premium positioning (Wadhwa & Zhang, 2015, *JCR* 41(5):1172). [LAB]
- **India-specific evidence: none found.** ₹99/₹199/₹299 endings are visibly standard in Indian menus, and a 2025 survey-style paper reports ~70% of respondents finding ₹99 endings more attractive than round figures — but that is a small, non-peer-reviewed-quality sample, not a demand study. [MISSING / weak]

### Evidence/source summary

Thomas & Morwitz (2005); Anderson & Simester (2003); Troll et al. (2024); Escher et al. (2026); Guéguen et al. (2009); Wadhwa & Zhang (2015). No Indian restaurant field study exists. [MISSING]

### Practical recommendation for organizing items and prices

1. **Choose one pricing system and apply it consistently across the card.** Mixed endings (₹349, ₹420, ₹375, ₹450) read as arbitrary and undermine the premium signal either way.
2. **If the restaurant is mid-market / value-led**: use 9-endings **at decade breaks** where the left digit actually changes (₹299, ₹399, ₹499). That is where the evidence is strongest. Do not bother converting ₹345 into ₹349 — the left digit is unchanged and you have only made the number look more calculated.
3. **If the restaurant is premium / experience-led**: use round numbers (₹450, ₹650, ₹850). This is defensible on fluency/hedonic grounds and on market convention, and it avoids the "discount restaurant" read.
4. **Do not use `.00` after round numbers.** `₹450.00` looks like software output; `₹450` looks like a decision.
5. **Do not expect a 9-ending change to move the business.** At g ≈ 0.13 the effect is smaller than the noise in a month of covers. It is a consistency choice, not a growth strategy.

### Confidence level
**High** that left-digit logic is real and conditional on the leading digit; **Medium** that 9-endings produce a small positive effect on an Indian menu; **Low** that any specific ending outperforms another on this restaurant's menu; **Very Low** that round-vs-9 matters more than price level and item quality.

### Potential limitations
Nearly all evidence is Western retail/lab; restaurant menus have strong external reference prices (delivery apps) that may swamp ending effects; Indian cultural number symbolism (auspicious digits) is asserted in practice but unstudied [MISSING]; a menu-wide change in endings is confounded with a price change, so it cannot be tested cleanly without holding prices constant.

---

## 10. Cross-cutting: how much should we trust menu "psychology" at all?

### Key findings

- Meta-analysis: overall menu-design effect **0.39 (95% CI 0.34–0.45)**, significant heterogeneity; position, description and label **marginal**; effects concentrated in specific dimensions and study designs (Ip & Chark, 2023). [SCIENCE]
- p-curve analysis: the menu-design literature shows **evidential value overall** (right-skewed p-curve, full z = −13.65, half z = −15.75, both p < 0.001), i.e. it is not purely p-hacked — but the studies are small and heterogeneous (Chark & Ip, 2023). [SCIENCE]
- Practical reading: **menu design is a real but modest lever.** On an A4 card, the variables with the largest expected effect are not the famous tricks — they are (a) correct costing and mix, (b) fewer, better items, (c) descriptions that are accurate, (d) legibility at arm's length in restaurant light.
- The strongest, most transferable findings in this entire report are: **currency-symbol removal (one field study, ~8%)**, **compromise/extremeness aversion (meta-analysis + 88,000-choice field data, ~5% share)**, and **small 9-ending effects (g ≈ 0.13)**. Everything else is either correlational, lab-only, or folklore.

### Confidence level
**High** for the meta-level conclusion that effects are real but small.

### Evidence/source summary
Ip & Chark (2023), IJHM 108:103353 — meta-analysis of menu-design experiments. Chark & Ip (2023), IJHM 108:103378 — p-curve analysis of the same literature.

### Practical recommendation for organizing items and prices
Budget the design effort accordingly: spend most of the decision time on which items are on the card and what they cost, and treat typographic psychology as a tie-breaker between otherwise equal layouts. Do not promise a client a percentage uplift from formatting.

### Potential limitations
Meta-analyses pool studies with different outcomes (attitudes, intentions, hypothetical choice, real purchases), so the pooled effect over-states what a printed A4 card will do; publication bias cannot be fully excluded even with a right-skewed p-curve; almost none of the pooled studies are Indian.

---

## 11. Consolidated guidance for an A4 card (research synthesis, not design)

| # | Rule | Basis | Confidence |
|---|---|---|---|
| 1 | Classify every dish by popularity × contribution margin before editing the card | Kasavana & Smith 1982 | High (arithmetic) |
| 2 | Cost fully: food, waste, incremental labour, packaging | Kasavana 2025 | High |
| 3 | Use 70% of *equal share* as the popularity cut-off, per category, on 8–12 weeks of data | Kasavana & Smith 1982 | High |
| 4 | Re-engineer Plowhorses' cost before raising their price | ME logic + elasticity | Medium |
| 5 | Change one category's prices per print run | Noone & Cachia 2020 | High (method) |
| 6 | Drop the ₹ symbol; keep the numerals unmistakably prices | Yang, Kimes & Sessarego 2009 | Medium |
| 7 | Prefer inline prices at the end of descriptions when descriptions exist; one system, no leader dots | No direct evidence; practice | Low |
| 8 | Do not repeat the "Kern/12% right-justified" claim | Not verifiable | — |
| 9 | Structure 3 tiers per major category; make the middle tier the intended sale | Neumann et al. 2016; Pinger et al. 2016 | High / Medium |
| 10 | 2–3 bundles; build from Plowhorses/Puzzles; real, visible saving | Kwon & Jang 2011; Myung et al. 2008 | Medium |
| 11 | One genuine premium item per category as the upper reference; no fake decoys | Yang & Lynn 2009; Frederick et al. 2014; Attwood et al. 2020 | Medium |
| 12 | 9-endings only at decade breaks (₹299/₹399) or round numbers throughout — never mixed | Thomas & Morwitz 2005; Troll et al. 2024 | Medium |
| 13 | Expect single-digit-percent effects from formatting, not double-digit ones | Ip & Chark 2023 | High |

**Data the restaurant must supply before any of this is usable**: recipe-level costs, 8–12 weeks of item-level sales counts by daypart, current price list with tax treatment, cover counts, and the dietary/strategic role of each dish. Without those, the matrix cannot be built and any "Star/Plowhorse" label would be invented. [MISSING until supplied]

---

## 12. Claim hygiene — numbers in circulation and their status

| Circulating claim | Status |
|---|---|
| "Cornell found that removing the dollar sign raises spend ~8%" | **Real.** Yang, Kimes & Sessarego (2009); one café, 201 diners. |
| "Yang, Kimes & Gallo (2009)" | **Wrong citation.** Third author is Sessarego. |
| "Right-justified prices raise willingness to pay up to 12% (Cornell / Kern)" | **No primary source found.** Do not use. |
| "Menu engineering lifts profit 10–15% (or 8–12%)" | **Industry claim, unsourced.** No peer-reviewed figure located. |
| "Decoys shift 20–30% of purchases" | **Unsourced.** Contradicted by null menu trials (Attwood et al. 2020). |
| "Photos increase sales by up to 30%" | Kasavana (2025) relays "research indicates… as much as 30%" without citation. **Unverified.** |
| "7 ± 2 items per category" | **Misapplied.** Miller's 1956 memory span, not menu choice. No menu test. |
| "9-endings boost sales 24%" | **Unsourced** (appears to be a garbled retail/catalogue figure). Meta-analytic estimate is g ≈ 0.13. |
| "~40% of restaurants use menu engineering" | Kasavana (2025) self-report survey. **Industry statistic, not measured.** |
| "A high-priced anchor reliably raises average check" | **Not established.** One weak 2026 conference study; no clean field experiment. |

---

## 13. Gaps that matter for this project

1. **India-specific price research is essentially absent.** No field study of currency symbols, price endings, or anchoring on Indian menus was located. Every finding above is a transfer from US/EU/Chinese data. [MISSING]
2. **No thali/combination-meal pricing study.** [MISSING]
3. **No study of price placement (inline vs column) with real orders.** [MISSING]
4. **No replication of the currency-symbol result.** [MISSING]
5. **No published data on Indian restaurant contribution-margin patterns by dish type** — so any "your biryani is a Star" expectation is a hypothesis.
6. **GST/menu-display compliance** is a live legal question in India and was out of scope here; verify before changing how prices are displayed.

---

## 14. References

**Menu engineering**
- Kasavana, M. L., & Smith, D. I. (1982). *Menu Engineering: A Practical Guide to Menu Analysis.* Hospitality Publications, Lansing/Okemos, MI. (rev. 1990)
- Kasavana, M. L. (2025, 8 April). "The Power of Menu Engineering – Part One." AHLEI. https://ahlei.servsafebrands.com/resources-overview/news-and-insights/the-power-of-menu-engineering-part-one
- Noone, B. M., & Cachia, G. (2020). "Menu engineering re-engineered: Accounting for menu item substitutes in pricing and menu placement decisions." *International Journal of Hospitality Management*, 87, 102504. doi:10.1016/j.ijhm.2020.102504
- Cohen, E., Ghiselli, R., & Schwartz, Z. (2007) — loss-leader pricing and menu-mix analysis, as reviewed in Noone & Cachia (2020).
- DEA-based menu-analysis critique: *International Journal of Hospitality Management* (2011), "Validating a DEA-based menu analysis model using structural equation modeling."

**Pricing and elasticity**
- Kiefer, N. M., Kelly, T. J., & Burdett, K. (1994). "Menu Pricing: An Experimental Approach." *Journal of Business and Economic Statistics*, 12(3), 329–337.
- Raab, C., Mayer, K., Kim, Y.-S., & Shoemaker, S. (2009). "Price-Sensitivity Measurement: A Tool for Restaurant Menu Pricing." *Journal of Hospitality & Tourism Research*, 33(1), 93–105.
- Heffetz, O., & Shayo, M. (2009). Price–quality inference experiments (lab + Tel Aviv restaurant field experiment). *American Economic Journal: Applied Economics*, 1(4).

**Price presentation and endings**
- Yang, S. S., Kimes, S. E., & Sessarego, M. M. (2009). *Effects of Menu-price Formats on Restaurant Checks.* Cornell Hospitality Report, 9(8).
- Yang, S. S., & Kimes, S. E. (2009). "Menu price presentation influences on consumer purchase behavior in restaurants." *International Journal of Hospitality Management*, 28(1).
- Yang, S. S., & Lynn, M. (2009). *Wine List Characteristics Associated with Greater Wine Sales.* Cornell Hospitality Report, 9(11). (270 wine lists, 46 attributes)
- Guéguen, N., Jacob, C., Legoherel, P., & Ngobo, P. (2009). "Nine-ending prices and consumer's behavior: A field study in a restaurant." *International Journal of Hospitality Management*, 28(1), 170–172.
- Thomas, M., & Morwitz, V. (2005). "Penny Wise and Pound Foolish: The Left-Digit Effect in Price Cognition." *Journal of Consumer Research*, 32(1), 54–64.
- Anderson, E. T., & Simester, D. I. (2003). "Effects of $9 Price Endings on Retail Sales: Evidence from Field Experiments." *Quantitative Marketing and Economics*, 1(1), 93–110.
- Troll, E. S., Frankenbach, J., Friese, M., & Loschelder, D. D. (2024). "A meta-analysis on the effects of just-below versus round prices." *Journal of Consumer Psychology*. doi:10.1002/jcpy.1353
- Escher, Y. A., et al. (2026). "How consumers evaluated precise, just-below, and round prices: evidence from two high-powered, preregistered experiments." *Frontiers in Behavioral Economics*. doi:10.3389/frbhe.2026.1828446
- Wadhwa, M., & Zhang, K. (2015). "This Number Just Feels Right: The Impact of Roundedness of Price Numbers on Product Evaluations." *Journal of Consumer Research*, 41(5), 1172.

**Context effects, tiers, bundles, decoys**
- Pinger, P., Ruhmer-Krell, I., & Schumacher, H. (2016). "The Compromise Effect in Action: Lessons from a Restaurant's Menu." *Journal of Economic Behavior & Organization*, 128, 14–34. (88,000+ choices, 7 years)
- Neumann, N., Böckenholt, U., & Sinha, A. (2016). "A Meta-Analysis of Extremeness Aversion." *Journal of Consumer Psychology*, 26(2), 193–212.
- Mohammed, R. (2018). "The Good-Better-Best Approach to Pricing." *Harvard Business Review*, Sept–Oct.
- Kwon, S., & Jang, S. (2011). "Price bundling presentation and consumer's bundle choice: The role of quality certainty." *International Journal of Hospitality Management*, 30(2), 337–344.
- Myung, E., McCool, A. C., & Feinstein, A. H. (2008). "Understanding attributes affecting meal choice decisions in a bundling context." *International Journal of Hospitality Management*, 27, 119–125. (Indexes disagree on issue 1 vs 2; volume and pages are consistent.)
- Huber, J., Payne, J. W., & Puto, C. (1982). "Adding Asymmetrically Dominated Alternatives." *Journal of Consumer Research*, 9(1).
- Frederick, S., Lee, L., & Baskin, E. (2014). "The Limits of Attraction." *Journal of Marketing Research*, 51(4), 487–507.
- Shoemaker, S. (1994). "A Proposal to Improve the Overall Price Value Perception of a Product Line." *Journal of Restaurant & Foodservice Marketing*, 1(1), 89–101.
- Attwood, S., et al. (2020). "Menu engineering to encourage sustainable food choices when dining out: An online trial of priced-based decoys." *Appetite*. (PII S0195666319308335) — null main effect.
- "Anchoring decisions: the role of decoy pricing in consumer choices." *International Hospitality Review* (2024/2025). doi:10.1108/IHR-04-2024-0023 (author list not verified; paywalled).

**Evidence quality**
- Ip, M. M. H., & Chark, R. (2023). "The effect of menu design on consumer behavior: A meta-analysis." *International Journal of Hospitality Management*, 108, 103353.
- Chark, R., & Ip, M. M. H. (2023). "Is menu design effective? A p-curving analysis." *International Journal of Hospitality Management*, 108, 103378.

**Weak / low-tier (cited only as suggestive)**
- Dong, Q. (2026). "Mechanism of Price Anchoring in Dining Consumption Decision-Making." In *Proceedings of ICHCH 2025*, Springer, 532–540. doi:10.2991/978-2-38476-585-0_59

---

*Prepared as research input. No layout, typography, colour or final pricing decisions are contained in this document.*
