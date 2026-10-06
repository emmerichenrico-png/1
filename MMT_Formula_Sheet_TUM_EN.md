# Formula Sheet: MMT Admission Test (M.Sc. Management & Technology, TUM)

**As of:** 06 Oct 2026, preparation for the make-up date on 07 Oct 2026
**Based on:** official TUM information (statutes, "How does the assessment procedure work WS 26/27") and test-taker reports in the WiWi-TReFF thread "MMT TUM neuer Eignungstest WS 26/27"

German terms are given in parentheses where the test may use them.

---

## 0. What is known about the test

| Item | Info | Source |
|---|---|---|
| Size | approx. 40–50 questions, **max. 40 points** | official |
| Sections | **4 × 25 %**: ① Math & Statistics ② Business Administration & **Accounting** ③ **Micro & Macro** ④ **Free text** on economics & technology | official |
| Formats | single/multiple choice **and other answer types** (e.g. typing in a number) | statutes |
| Aids | **no calculator** | test-takers |
| Math | fairly theoretical, not too hard: **4×4 matrix**, **properties of functions**, simple **probability** | test-takers |
| Statistics | basic knowledge, no hard tasks | test-takers |
| Business | e.g. **Big Five**: what personality does an ideal sales representative have? | test-takers |
| Free text | previously e.g. on **Trump's tariffs**; hints that the text is in **English**, so be ready for both languages | test-takers |

**What this means:**
- The free text counts **25 %, i.e. about 10 of 40 points**. It is the section you can prepare for most reliably (section 5).
- Micro/macro and accounting each count as much as math/statistics, so don't just cram math.
- No calculator means the numbers are "clean". If you end up with messy intermediate results, you have probably made a mistake.
- About leaked questions: none of it can be verified, and anyone caught using it loses their application. Stay away from it.

---

## 1. Mathematics

### 1.1 Mental arithmetic without a calculator
- e ≈ 2.718 · ln 2 ≈ 0.693 · ln 3 ≈ 1.099 · ln 10 ≈ 2.303 · √2 ≈ 1.414 · √3 ≈ 1.732
- 1.1² = 1.21 · 1.1³ = 1.331 · 1.05² = 1.1025 · 1.2² = 1.44 · 1/1.1 ≈ 0.909 · 1/1.21 ≈ 0.826
- **Rule of 70:** doubling time ≈ 70 / growth rate in % (7 % → 10 years)
- Percentages: +20 % then −20 % gives 0.96, i.e. **−4 %** (not 0)

### 1.2 Powers and logarithms
- aᵐ·aⁿ = aᵐ⁺ⁿ · (aᵐ)ⁿ = aᵐⁿ · a⁻ⁿ = 1/aⁿ · a^(1/n) = ⁿ√a · a⁰ = 1
- ln(xy) = ln x + ln y · ln(x/y) = ln x − ln y · ln(xᵃ) = a·ln x · ln 1 = 0 · ln e = 1 · e^(ln x) = x

### 1.3 Derivatives
| f(x) | f′(x) |
|---|---|
| xⁿ | n·xⁿ⁻¹ |
| eˣ / e^(g(x)) | eˣ / g′(x)·e^(g(x)) |
| ln x / ln g(x) | 1/x / g′(x)/g(x) |
| aˣ | aˣ·ln a |
| u·v | u′v + uv′ |
| u/v | (u′v − uv′)/v² |
| f(g(x)) | f′(g(x))·g′(x) |

- **Elasticity:** ε = f′(x)·x / f(x). For f(x) = c·xᵃ, ε = a (constant).
- **Integrals:** ∫xⁿ dx = xⁿ⁺¹/(n+1) (n ≠ −1) · ∫1/x dx = ln|x| · ∫eˣ dx = eˣ

### 1.4 Properties of functions (reported as tested)
- **Increasing:** f′ ≥ 0. **Strictly** increasing ⇒ invertible (injective).
- **Convex:** f″ ≥ 0, the secant lies above the graph (cost functions). **Concave:** f″ ≤ 0 (production, utility, diminishing marginal returns).
- **Extremum:** necessary f′ = 0; sufficient f″ < 0 (max) or f″ > 0 (min). If f″ = 0, check the sign change of f′.
- **Inflection point:** f″ changes sign; **f″ = 0 alone is not enough** (x⁴ at 0 is a minimum).
- **Saddle point:** f′ = 0 and inflection point (x³ at 0).
- **Domain:** ln x for x > 0 · √x for x ≥ 0 · 1/x for x ≠ 0
- eˣ: always > 0, strictly increasing, convex. ln x: strictly increasing, concave, ln 1 = 0.
- **Differentiable ⇒ continuous**, but not the other way round (|x| has a kink at 0).
- **Growth as x → ∞:** ln x ≪ xⁿ ≪ eˣ
- **Even:** f(−x) = f(x) (x², cos). **Odd:** f(−x) = −f(x) (x³, sin).
- **Homogeneous of degree r:** f(tx, ty) = tʳ·f(x, y). Cobb-Douglas xᵃyᵇ has r = a + b. r > 1: increasing, r = 1: constant, r < 1: decreasing returns to scale.
- Concave ⇒ quasi-concave; the converse does not hold.

### 1.5 Several variables and optimization
- Partial derivatives f_x, f_y. Stationary point: f_x = f_y = 0.
- **Hessian** H = [[f_xx, f_xy], [f_xy, f_yy]]: det H > 0 and f_xx < 0 gives a **max**, det H > 0 and f_xx > 0 a **min**, det H < 0 a **saddle point**.
- **Lagrange:** L = f(x, y) − λ·(g(x, y) − c), set all partial derivatives to 0. **λ = shadow price**, i.e. how much the optimal value changes when c rises by 1.

### 1.6 Linear algebra (a 4×4 matrix was asked!)
**Basic rules**
- (m×n)·(n×p) = m×p. **AB ≠ BA** in general.
- (AB)ᵀ = BᵀAᵀ · (AB)⁻¹ = B⁻¹A⁻¹ · (Aᵀ)⁻¹ = (A⁻¹)ᵀ
- 2×2 inverse: [[a, b], [c, d]]⁻¹ = 1/(ad − bc) · [[d, −b], [−c, a]]

**Determinant**
- 2×2: ad − bc. 3×3: **rule of Sarrus** (Sarrus works **only** for 3×3, not 4×4!)
- 4×4: **Laplace (cofactor) expansion** along the row or column with the most zeros. Sign pattern (−1)^(i+j):
  ```
  + − + −
  − + − +
  + − + −
  − + − +
  ```
- **Triangular or diagonal matrix:** det = product of the diagonal.
- **Block diagonal:** det = det(block 1) · det(block 2).
- **det = 0** if there is a zero row or column, two rows are equal or proportional, or one row is a linear combination of others.
- Swapping rows: sign flips · row times k: det times k · adding a multiple of one row to another: **no change**
- det(Aᵀ) = det A · det(AB) = det A · det B · det(A⁻¹) = 1/det A
- **Trap: det(cA) = cⁿ·det A**, so for 4×4 it is **c⁴**·det A
- ⚠ det(A + B) ≠ det A + det B

**Equivalent for an n×n matrix A** (all true or all false together):
det A ≠ 0 ⇔ A invertible ⇔ rank A = n ⇔ rows/columns linearly independent ⇔ Ax = 0 has only x = 0 ⇔ Ax = b has a unique solution ⇔ no eigenvalue is 0

**Solvability of Ax = b** (rank criterion):
- rank A = rank(A|b) = n: exactly one solution
- rank A = rank(A|b) < n: infinitely many solutions (n − rank free parameters)
- rank A < rank(A|b): no solution

**Eigenvalues:** det(A − λI) = 0
- **Sum of eigenvalues = trace** (sum of the diagonal) · **product = det A**
- Triangular matrix: eigenvalues = diagonal entries
- Symmetric matrix: all eigenvalues are real
- **Definiteness** (symmetric): all EV > 0 positive definite · all < 0 negative definite · mixed signs indefinite
- Orthogonal: AᵀA = I, det = ±1 · Idempotent: A² = A, EV ∈ {0, 1}

**Example 1 (Laplace).** A = [[2,0,1,3], [0,1,0,0], [1,0,1,2], [0,4,0,5]]
Expand along row 2 (only one non-zero entry, position (2,2), sign +): det A = 1 · det[[2,1,3], [1,1,2], [0,0,5]]
Expand this 3×3 along row 3: 5 · det[[2,1], [1,1]] = 5 · (2 − 1) = **5**

**Example 2 (see it instead of computing).** B = [[1,2,3,4], [0,1,1,1], [2,4,6,8], [1,0,0,1]]
Row 3 = 2 · row 1, so **det B = 0**, B is not invertible, rank < 4 (here 3).

**Example 3.** Upper triangular matrix with diagonal 1, 2, 3, −1: det = −6 · det(2A) = 16 · (−6) = −96 · det(A⁻¹) = −1/6 · eigenvalues 1, 2, 3, −1 → indefinite (if symmetric)

### 1.7 Sequences and series
- Arithmetic: Σ = n·(a₁ + aₙ)/2 · Gauss: 1 + 2 + … + n = n(n+1)/2
- Geometric: Σ_{k=0}^{n−1} a·qᵏ = a·(1 − qⁿ)/(1 − q) · infinite (|q| < 1): a/(1 − q)

---

## 2. Statistics and probability

### 2.1 Descriptive statistics
- **Scales:** nominal (mode only) → ordinal (+ median) → metric (+ mean, variance)
- The **median** is robust to outliers; the mean is not. Right-skewed: mean > median.
- Population variance: σ² = (1/n)·Σ(xᵢ − x̄)² · sample: s² = 1/(n−1)·Σ(xᵢ − x̄)²
- **Shortcut formula:** Var X = E(X²) − (E X)²
- Coefficient of variation: σ/μ (unit-free)

### 2.2 Rules
- E(aX + b) = a·E X + b · **Var(aX + b) = a²·Var X** (b drops out!)
- E(X + Y) = E X + E Y (always)
- Var(X ± Y) = Var X + Var Y **± 2 Cov(X, Y)**. Under independence Cov = 0, and even for X − Y the variances are **added**.
- Cov(X, Y) = E(XY) − E X · E Y · ρ = Cov/(σ_X·σ_Y) ∈ [−1, 1]
- **Independent ⇒ uncorrelated**, but not the other way round (ρ only measures linear association).

### 2.3 Probability
- P(A ∪ B) = P(A) + P(B) − P(A ∩ B) · P(Aᶜ) = 1 − P(A)
- P(A | B) = P(A ∩ B)/P(B) · **independent:** P(A ∩ B) = P(A)·P(B)
- **Disjoint ≠ independent:** disjoint events with P > 0 are always **de**pendent.
- **Law of total probability:** P(B) = Σ P(B | Aᵢ)·P(Aᵢ)
- **Bayes:** P(A | B) = P(B | A)·P(A) / P(B)
- **"At least once":** 1 − (1 − p)ⁿ

**Bayes example:** disease 1 %, test detects 99 % of sick people, 1 % false positives.
P(sick | +) = 0.99·0.01 / (0.99·0.01 + 0.01·0.99) = **50 %**. The base rate matters!

### 2.4 Combinatorics (k out of n)
| | without repetition | with repetition |
|---|---|---|
| order matters | n!/(n−k)! | nᵏ |
| order doesn't matter | (n choose k) = n!/(k!(n−k)!) | (n+k−1 choose k) |

(5 choose 2) = 10 · (6 choose 3) = 20 · (10 choose 2) = 45 · 0! = 1

### 2.5 Distributions
| Distribution | E X | Var X |
|---|---|---|
| Bernoulli(p) | p | p(1−p) |
| Binomial(n, p) | np | np(1−p) |
| Poisson(λ) | λ | λ |
| Continuous uniform [a, b] | (a+b)/2 | (b−a)²/12 |
| Exponential(λ) | 1/λ | 1/λ² |
| Normal(μ, σ²) | μ | σ² |

- Binomial: P(X = k) = (n choose k)·pᵏ·(1−p)ⁿ⁻ᵏ
- **Normal distribution:** μ ± 1σ: 68 % · ± 2σ: 95 % · ± 3σ: 99.7 % · symmetric, Φ(0) = 0.5, Φ(−z) = 1 − Φ(z)
- Standardize: Z = (X − μ)/σ · z-values: 1.645 (90 % two-sided / 95 % one-sided) · **1.96 (95 % two-sided)** · 2.576 (99 %)
- **Central limit theorem:** X̄ ≈ N(μ, σ²/n), **standard error σ/√n**. Quadrupling n halves the standard error.

### 2.6 Estimation and testing
- Confidence interval: x̄ ± z·σ/√n. Larger n → narrower; higher confidence level → wider.
- **Type I error (α):** H₀ rejected although true. **Type II error (β):** H₀ kept although false. **Power** = 1 − β.
- **p-value < α → reject H₀.** The p-value is **not** the probability that H₀ is true.
- Smaller α → larger β (for fixed n).

### 2.7 Regression (simple, OLS)
- β̂₁ = Cov(x, y)/Var(x) · β̂₀ = ȳ − β̂₁·x̄ · The line passes through (x̄, ȳ).
- R² ∈ [0, 1] = share of variance explained. Simple regression: R² = r².
- log-log: β = **elasticity** · log-lin (ln y on x): β·100 = % change in y per unit of x
- Correlation ≠ causation (confounders, reverse causality)

---

## 3. Business administration and accounting

### 3.1 Balance sheet, income statement, bookkeeping
- **Assets = Liabilities + Equity** (Aktiva = Passiva): assets = equity + debt
- Assets: fixed assets (Anlagevermögen), current assets (Umlaufvermögen) · Liabilities side: equity, provisions (Rückstellungen), payables/liabilities
- Journal entry "**debit to credit**" (Soll an Haben). Asset account: increase on the debit side. Liability account: increase on the credit side. Expenses on the debit side, income on the credit side.
- **Four pairs of terms (German accounting):**
  - Auszahlung/Einzahlung = cash outflow/inflow
  - Ausgabe/Einnahme = expenditure/receipts (monetary assets incl. receivables/payables)
  - Aufwand/Ertrag = expense/income (income statement, financial statements)
  - Kosten/Leistung = costs/output (operational, cost accounting)
- Example: buying raw materials on credit is an expenditure (Ausgabe) but not yet a cash outflow (Auszahlung). The cash outflow only happens on payment.
- **Straight-line depreciation:** (acquisition cost − residual value)/useful life · declining balance: fixed % of the remaining book value
- **German GAAP (HGB) principles:** prudence · realization principle (gains only when realized) · imparity principle (anticipated losses immediately) · lower-of-cost-or-market principle (strict for current assets)
- Income statement: **total cost method** (Gesamtkostenverfahren: by type of expense, incl. inventory changes) vs. **cost of sales method** (Umsatzkostenverfahren: by function, only costs of units sold)
- **Cash flow (indirect)** ≈ net income + depreciation + increase in provisions − increase in working capital
- EBIT = earnings before interest and taxes · EBITDA = EBIT + depreciation & amortization

### 3.2 Cost accounting
- C(x) = C_f + c_v·x · unit cost c = C_f/x + c_v · economies of scale from fixed costs: c falls as x rises
- **Contribution margin** (Deckungsbeitrag) per unit: cm = p − c_v · total CM = cm·x · profit = CM − C_f
- **Break-even:** x* = C_f/(p − c_v)
- **Price floor:** short-run = c_v · long-run = c (full unit cost)
- **Bottleneck:** rank products by **relative CM** = cm per unit of the bottleneck (not by absolute cm!)
- Make or buy: external price vs. **relevant** (variable or avoidable) costs. Ignore sunk costs.
- Cost types → cost centers (overhead allocation sheet, BAB) → cost objects · direct costs assigned directly, overheads via surcharge rates

### 3.3 Ratios
- Equity ratio = equity/total capital · debt-to-equity = debt/equity
- Return on equity = profit/equity · return on total capital = (profit + interest on debt)/total capital · return on sales = profit/revenue
- **ROI (DuPont)** = return on sales × capital turnover = (profit/revenue)·(revenue/total capital)
- **Leverage effect:** r_E = r_TC + (r_TC − i)·D/E. More debt boosts return on equity as long as r_TC > i (risk rises too).
- Liquidity ratio 1 (cash ratio) = cash/short-term liabilities · ratio 2 (quick ratio): + receivables · ratio 3 (current ratio): + inventories (all current assets)
- **Golden balance sheet rule:** fixed assets financed long-term (equity + long-term debt ≥ fixed assets)

### 3.4 Investment and finance
- **Net present value:** NPV = −I₀ + Σ CFₜ/(1 + r)ᵗ. NPV > 0 → invest.
- **Internal rate of return (IRR):** r such that NPV = 0. For mutually exclusive projects, the **NPV** decides in case of conflict.
- **Perpetuity:** PV = C/r · **growing (Gordon):** PV = C₁/(r − g), only if r > g
- **Annuity factor:** (1 − (1+r)⁻ⁿ)/r · annuity payment = present value / annuity factor
- Future value: K·(1 + r)ⁿ · continuous: K·e^(rt)
- **Payback period:** I₀/annual CF. Ignores time value and cash flows after payback.
- **CAPM:** r_E = r_f + β·(r_M − r_f). β > 1: riskier than the market.
- **WACC** = E/V·r_E + D/V·r_D·(1 − t)
- Diversification only eliminates **unsystematic** risk. Only systematic risk (β) is priced.
- Types of financing: internal (retained earnings, depreciation, provisions) vs. external (equity financing = equity, loans = debt)

### 3.5 Strategy, marketing, operations
- **Porter's Five Forces:** rivalry, new entrants, substitutes, supplier power, buyer power
- **Porter's generic strategies:** cost leadership · differentiation · focus (risk: "stuck in the middle")
- **BCG matrix** (market growth × relative market share): Stars (high/high) · Cash Cows (low/high) · Question Marks (high/low) · Poor Dogs (low/low)
- **Ansoff:** market penetration · market development · product development · diversification
- SWOT (S/W internal, O/T external) · PESTEL · value chain (Porter) · product life cycle: introduction, growth, maturity, saturation, decline
- Marketing mix **4Ps:** Product, Price, Place, Promotion
- **Economic order quantity (Andler/EOQ):** q* = √(2·annual demand·fixed cost per order / holding cost per unit and year)

### 3.6 Organization and HR (reported as tested)
- **Big Five (OCEAN):** Openness · Conscientiousness · Extraversion · Agreeableness · Neuroticism
  - **Conscientiousness** is the most stable predictor of job performance across occupations.
  - **Sales:** high conscientiousness + high extraversion + low neuroticism (emotionally stable). Agreeableness and openness barely predict sales success.
- **Herzberg:** hygiene factors (pay, working conditions, security) prevent dissatisfaction but do not create satisfaction. **Motivators** (recognition, responsibility, the work itself, advancement) create satisfaction.
- **Maslow** (bottom up): physiological → safety → social → esteem → self-actualization. Deficiency vs. growth needs.
- **McGregor:** Theory X (people are lazy, need control) vs. Theory Y (intrinsically motivated, seek responsibility)
- **Leadership styles (Lewin):** authoritarian, cooperative/democratic, laissez-faire · situational (Hersey/Blanchard: style depends on employees' maturity level)
- **Organizational structures:** functional · divisional (business units, profit centers) · **matrix** (two lines of authority, potential for conflict) · line-and-staff · single-line vs. multi-line system · span of control
- **Principal-agent:** hidden information → **adverse selection** (before the contract; remedies: signaling, screening) · hidden action → **moral hazard** (after the contract; remedies: incentive contracts, monitoring)
- **German legal forms:** GmbH (LLC) €25,000 share capital · UG from €1 · AG (stock corporation) €50,000 share capital (management board, supervisory board, shareholders' meeting) · OHG (general partnership): all partners fully liable · KG (limited partnership): general partner fully liable, limited partner only up to their contribution
- Shareholder vs. stakeholder approach

---

## 4. Micro- and macroeconomics

### 4.1 Micro: demand and elasticities
- **Price elasticity** ε = (dQ/dP)·(P/Q). |ε| > 1 elastic: a price cut **raises** revenue. |ε| < 1 inelastic: a price increase raises revenue. Revenue is maximized at |ε| = 1.
- Linear demand: elasticity is **not** constant (elastic at the top, inelastic at the bottom).
- **Cross-price elasticity:** > 0 substitutes · < 0 complements
- **Income elasticity:** < 0 inferior · 0–1 normal/necessity · > 1 luxury good
- Giffen good: inferior, income effect larger than substitution effect, demand rises with price

### 4.2 Households
- Optimum: **MRS = MU_x/MU_y = p_x/p_y** (budget m = p_x·x + p_y·y)
- **Cobb-Douglas** U = xᵃyᵇ → x* = a/(a+b)·m/p_x, y* = b/(a+b)·m/p_y (fixed budget share)
- Perfect substitutes (U = x + y): corner solution, only the relatively cheaper good · Perfect complements (U = min{x, y}): x = y

### 4.3 Firms and markets
- **Profit maximum always at MR = MC**
- **Perfect competition:** p = MC. Short run: produce as long as p ≥ min AVC (shutdown point). Long run: p = min AC (break-even point), zero profit.
- MC crosses AC and AVC at their respective **minimum**.
- **Monopoly:** with P = a − bQ, MR = a − 2bQ (twice the slope). Lower quantity and higher price than under competition, creating a **deadweight loss**.
- **Lerner index:** (P − MC)/P = 1/|ε|. A monopolist never operates in the inelastic range.
- **Cournot** (2 firms, P = a − bQ, MC = c): qᵢ = (a − c)/(3b) · Bertrand (homogeneous): P = MC · Stackelberg: leader (a − c)/(2b), follower (a − c)/(4b)
- First-degree price discrimination: perfect, no consumer surplus, no deadweight loss
- Production: MRTS = MP_L/MP_K = w/r at the cost minimum

### 4.4 Welfare and the state
- Consumer surplus = area between demand curve and price · producer surplus = area between price and supply curve
- **Tax incidence:** the **less elastic** side of the market bears more, regardless of who formally pays.
- Price ceiling below equilibrium → excess demand · price floor above equilibrium → excess supply (e.g. minimum wage → possibly unemployment)
- **Externalities:** negative → overproduction. **Pigouvian tax** = marginal damage at the optimum. **Coase:** with clear property rights and no transaction costs, parties bargain to the efficient outcome.
- **Types of goods:**

  | | rival | non-rival |
  |---|---|---|
  | excludable | private good | club good (streaming) |
  | non-excludable | common resource (fish stocks) | **public good** (national defense) |

- **Game theory:** Nash equilibrium: no one wants to deviate unilaterally. Dominant strategy: best response to everything. **Prisoner's dilemma:** the Nash equilibrium is not Pareto optimal.

### 4.5 Macro: national accounts, money, inflation
- **Y = C + I + G + NX** (NX = exports − imports)
- Nominal vs. real GDP · **GDP deflator** = nominal/real·100 · GNI = GDP + primary income from abroad − primary income paid abroad
- **S − I = NX** (with government: S_priv + (T − G) − I = NX)
- **Fisher:** i ≈ r + π (real rate = nominal rate − inflation)
- **Quantity equation:** M·V = P·Y → %ΔM + %ΔV ≈ %ΔP + %ΔY
- **Money multiplier** (simple): 1/reserve requirement ratio
- ECB: target **2 % inflation over the medium term (symmetric)**. Instruments: key interest rates (deposit facility, main refinancing rate, marginal lending facility), open market operations, QE/QT. Look up the current deposit rate before the test.
- Unemployment rate = unemployed/labor force (labor force = employed + unemployed) · frictional, structural, cyclical · NAIRU
- **Okun's law:** 1 % unemployment above the natural rate costs about 2 % of GDP · **Phillips curve:** short-run trade-off between inflation and unemployment, vertical in the long run

### 4.6 Macro: models
- **Keynesian multiplier:** ΔY = 1/(1 − c)·ΔG · tax multiplier: −c/(1 − c) · **balanced budget: 1** · open economy: 1/(1 − c + m)
  Example: c = 0.8 → multiplier 5, tax multiplier −4
- **IS-LM:** expansionary fiscal policy: IS shifts right, Y↑ and i↑ (**crowding out**) · expansionary monetary policy: LM shifts right, Y↑ and i↓ · liquidity trap: monetary policy ineffective
- **AS-AD:** demand shock: P and Y move in the same direction · supply shock (e.g. energy prices): **stagflation** (P↑, Y↓)
- **Mundell-Fleming** (perfect capital mobility): fixed exchange rates: **fiscal policy** works, monetary policy doesn't · flexible exchange rates: **monetary policy** works, fiscal policy doesn't
- **Impossible trinity:** fixed exchange rate + free capital flows + independent monetary policy, at most 2 of 3
- **Solow:** steady state s·f(k) = (n + δ)·k. A higher savings rate raises the **level**, not the long-run growth rate. That comes only from technological progress. **Golden rule:** MPK = n + δ.
- Growth rate of a product ≈ sum of the growth rates (e.g. nominal GDP ≈ real + inflation)

### 4.7 International trade (already a free-text topic!)
- **Comparative advantage:** lower **opportunity costs** decide, not absolute productivity
- **Tariff (small country):** domestic price↑, imports↓, consumer surplus↓, producer surplus↑, tariff revenue, **deadweight loss = 2 triangles** (production and consumption distortion). Large country: possible terms-of-trade gain, risk of retaliatory tariffs.
- Exchange rate: **appreciation of the €** → exports more expensive, imports cheaper · purchasing power parity: e = P/P* (long run)
- Balance of payments: current account + capital/financial account (+ errors and omissions) = 0

---

## 5. Free text (25 % ≈ 10 points)

### 5.1 Structure (memorize, works for any topic)
1. **Thesis** in one sentence: a clear position, no "on the one hand, on the other"
2. **Argument 1:** economic **mechanism** + **concrete evidence** (figure, company, country, event)
3. **Argument 2:** as above, ideally from a different perspective (firms vs. government vs. consumers, short vs. long run)
4. **Counterargument:** present it fairly, then rebut or weigh it
5. **Conclusion + recommendation:** what should policymakers or firms actually do?

Use technical terms visibly (opportunity cost, externality, economies of scale, network effects, incentives, deadweight loss, terms of trade, path dependence). That shows understanding of both economics **and** technology. One key point per paragraph. Keep the last 2 minutes for proofreading.

**Useful phrases:** *I argue that…* · *The key mechanism is…* · *For instance, …* · *Admittedly, … However, …* · *On balance, …* · *Policymakers should therefore…*

### 5.2 Likely topic areas (tariffs came up before, so probably something else)
| Area | Mechanism / key terms |
|---|---|
| **AI and work/productivity** | automation vs. augmentation, productivity paradox, skill-biased technological change, reskilling, market concentration in foundation models (economies of scale, compute costs) |
| **AI regulation (EU AI Act)** | risk-based approach, innovation vs. safety, compliance costs as a barrier to entry, "Brussels effect" |
| **Energy transition / carbon pricing** | externality → Pigou/emissions trading (EU ETS), carbon leakage → carbon border adjustment (CBAM), electricity prices as a location factor, grid expansion |
| **Semiconductors / technological sovereignty** | supply chain risks, subsidies (Chips Act) vs. comparative advantage, concentration risk Taiwan, industrial policy |
| **Car industry and e-mobility / China** | path dependence, battery costs and learning curves, subsidy race, tariffs on EVs |
| **Platforms / Digital Markets Act** | network effects, winner-takes-all, gatekeepers, data monopolies, interoperability |
| **Demographics / skills shortage** | labor force potential, immigration, automation as a response, pension system |
| **Defense / dual use** | public good, crowding out vs. innovation spillovers, public debt, Germany's debt brake |

Best to have your own concrete piece of evidence ready for **2–3 areas** rather than memorizing an essay.

---

## 6. Common traps
- det(cA) = **c⁴**·det A for 4×4 · no Sarrus for 4×4 · det(A + B) ≠ det A + det B · AB ≠ BA
- f″(x₀) = 0 does not automatically mean an inflection point
- Var(X − Y) = Var X + Var Y (independent), **not** minus · Var(aX) = **a²**·Var X
- Sample variance with **n − 1**
- Disjoint ≠ independent · uncorrelated ≠ independent · P(A | B) ≠ P(B | A)
- Expenditure ≠ cash outflow ≠ expense ≠ cost (Ausgabe ≠ Auszahlung ≠ Aufwand ≠ Kosten)
- With a bottleneck, rank by **relative** CM · ignore sunk costs
- IRR and NPV disagree → **NPV** wins
- Monopoly MR has **twice** the slope · profit max is always MR = MC
- In the Solow model, a higher savings rate does **not** raise the long-run growth rate
- The **less elastic** side bears the tax burden
- +x % then −x % does not give 0

---

## 7. Self-check (no calculator, solutions below)

1. A is an upper triangular 4×4 matrix with diagonal 1, 2, 3, −1. Compute det A, det(2A), det(A⁻¹). Is A invertible?
2. f(x) = x³ − 3x: extrema and inflection point?
3. Is f(x) = ln x convex or concave on (0, ∞)? And f(x) = e^(−x)?
4. Disease 1 %, sensitivity 99 %, false positives 1 %. P(sick | positive)?
5. X ~ Bin(100; 0.2): E X, Var X, σ?
6. C_f = €40,000, p = €50, c_v = €30. Break-even quantity?
7. r_TC = 10 %, interest on debt 6 %, D/E = 3. Return on equity?
8. I₀ = 100, CF₁ = CF₂ = 60, r = 10 %. Is the investment worthwhile?
9. Monopoly with P = 100 − 2Q, MC = 20: Q, P, deadweight loss?
10. Q = 100 − 2P at P = 20: price elasticity? What happens to revenue if the price rises?
11. c = 0.75: government spending multiplier, tax multiplier; effect of ΔG = ΔT = 10?
12. U = x^0.25·y^0.75, m = 100, p_x = 5: x*?
13. Cournot: P = 100 − Q, MC = 10 for both firms. qᵢ, Q, P?
14. Which Big Five profile fits a sales representative best?

<details>
<summary><b>Solutions</b></summary>

1. det A = 1·2·3·(−1) = **−6** · det(2A) = 2⁴·(−6) = **−96** · det(A⁻¹) = **−1/6** · invertible, since det ≠ 0
2. f′ = 3x² − 3 = 0 → x = ±1; f″ = 6x → **max at (−1, 2)**, **min at (1, −2)**; **inflection point at (0, 0)** (f″ changes sign)
3. ln x: f″ = −1/x² < 0, **concave** · e^(−x): f″ = e^(−x) > 0, **convex** (and strictly decreasing)
4. 0.0099/(0.0099 + 0.0099) = **50 %**
5. E = 20, Var = 100·0.2·0.8 = 16, σ = **4**
6. 40,000/(50 − 30) = **2,000 units**
7. 10 % + (10 % − 6 %)·3 = **22 %**
8. 60/1.1 + 60/1.21 ≈ 54.5 + 49.6 = 104.1 → NPV ≈ **+4.1 > 0, yes**
9. MR = 100 − 4Q = 20 → **Q = 20, P = 60**. Competition: P = MC = 20 → Q = 40. DWL = ½·(60 − 20)·(40 − 20) = **400**
10. Q = 60, ε = −2·20/60 = **−2/3**, inelastic → a price increase **raises** revenue
11. 1/(1 − 0.75) = **4** · −0.75/0.25 = **−3** · balanced budget: +40 − 30 = **+10**
12. x* = 0.25·100/5 = **5**
13. qᵢ = (100 − 10)/3 = **30**, Q = 60, **P = 40**
14. High **conscientiousness** + high **extraversion** + low **neuroticism**
</details>

---

## 8. Checklist for 07 Oct
- Re-read the invitation email: time, link, ID, permitted aids (paper/pen?), technical requirements (camera, browser)
- Charge your laptop, use LAN or stable Wi-Fi, notifications off, quiet room
- Clarify at the start: are wrong answers penalized? Can you go back? Time per section?
- Reserve fixed time for the free-text field, don't rush it at the end
- For multiple choice without negative marking: never leave anything blank
