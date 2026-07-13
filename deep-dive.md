# Deep-dive: one product

**Use when** I hand you a specific product and want a trustworthiness verdict.
Runs **Deep** by default (fetch current standards live); can run **Quick** on
request. Screen against the matching **`category-*.md`**; if none exists, follow
*Undefined categories* in `instructions.md`.

**Run the *Safety* gate in `instructions.md` first** — flag who should skip it +
the safe alternative, and escalate genuine symptoms rather than treating a medical
problem as a shopping one.

Run in order:

### 1. Get the real declaration
Use the label I upload (ingredients + nutrition / spec panel + claims) or the
official current Indian SKU page. Capture the **serving size / unit**, and watch
the "per serving vs per 100 g" and "per use" tricks.

### 2. Classify the product
Decide whether it's a **cosmetic, drug / medicated (OTC or prescription), device,
or mixed** category in the Indian market, then apply the matching regime
(*Standards* in `instructions.md`). Use EU / US sources as comparisons, not
automatic substitutes — an EU *cosmetic* ban doesn't auto-fail a *drug*-class
active.

### 3. Screen against current standards (live)
For each **additive, active, preservative, colour, filter, and relevant
contaminant**, check status and current limits **live** — EU first (CosIng /
EUR-Lex / SCCS) as the strict cosmetic-safety bar, FDA as cross-check, India
(CDSCO / BIS) as the floor. Flag anything **banned or restricted in the EU**, and
anything allowed only up to a **max level**.
- Most **whole-food / base ingredients** have no limit — the screen targets
  additives, substances of concern, and **category-specific contaminants** (see the
  category file; e.g. heavy metals in powders, acrylamide in baked / fried).
- Pull the **current** figure each time — limits get revised.

### 4. Claim-integrity + finished-product check
- Does the **math add up**, or is it amino-spiking / filler inflation? Is **"no
  added sugar"** hiding sugar alcohols? Is **"natural / clean / high-X"** a real
  regulated threshold or just marketing? Any **serving-size or rounding games**?
- **A parts list isn't proof of performance.** Good ingredients / UV filters don't
  prove the finished product hits its claimed **SPF, UVA, RDA, pH, or efficacy** —
  don't call a pass without a credible **product-level test** or defensible label
  evidence; treat the claim as **unverified** otherwise.

### 5. Independent verification
Search third-party lab tests & certifications (e.g. Labdoor, ConsumerLab, NSF
Certified for Sport, Informed Sport, Clean Label Project; INCIDecoder for cosmetic
ingredient decoding), academic studies on the category, investigative journalism,
and regulatory actions (CDSCO / FSSAI notices, FDA warning letters, EU RASFF
alerts, recalls). **State clearly when no independent product-level data exists.**
- Scrutinise the testers too — weight transparent, published methodology (NSF,
  Informed Sport, USP) more heavily; an independent test is evidence, not gospel.
  **Don't score all logos alike: separate certification / testing programmes** (NSF
  Certified for Sport, Informed Sport, USP Verified) **from commercial testing /
  rating services** (ConsumerLab, Labdoor), and check whether the **exact Indian SKU
  / batch is actually covered**, not just a US version.
- **Tag each source** by provenance (primary / independent / brand / retailer /
  affiliate — see *Principles* in `instructions.md`); lean on primary + independent.
- **Watch staleness.** Ingredient decoders can lag real reformulations — check the
  source's "last updated" date, and prefer the brand's **current** live ingredient
  list. If you can't see that live list directly, say so and treat the decoder
  snapshot as **provisional**.

### 6. Reconcile → verdict
Compare what they **claim** against what the label, the live limits, and
independent tests **show**. Verdict: **Trustworthy / Minor flags / Misleading
marketing / Concerning (contamination or undeclared) / Insufficient independent
data** — with a **confidence level scored per *Confidence* in `instructions.md`**
and the **single most decisive finding**.
- **Self-contradicting brand claims:** if the brand's own numbers conflict across
  its pages / packaging (e.g. PA+++ on one page, PA++++ on another), use the
  **more conservative** figure for the verdict and put the conflict in the
  **first line**, not buried mid-analysis.

### 7. What it means for me
Given my goal, is it worth it? Separate **hard safety facts** from **preference
calls** (taste, texture, scent, cost) that are mine to make. Give the lowest
genuine price only if I asked and you ran `price-and-coupons.md`.

**Then close with the `Sources used:` line** (tally by type — see
`instructions.md`), so it's clear whether the verdict rests on independent testing
or just brand / affiliate material.

---
**Honest limits:** I can't physically lab-test — I rely on the declared label +
current published limits + whatever independent testing already exists. Labels can
themselves be inaccurate (which is why the independent-test step matters, and why
"no independent data" lowers confidence). Niche / new products often have no
third-party testing. Verify current limits each time.
