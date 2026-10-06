# Formelblatt: MMT-Eignungstest (M.Sc. Management & Technology, TUM)

**Stand:** 06.10.2026, Vorbereitung auf den Nachtermin am 07.10.2026

**Grundlage:** offizielle TUM-Angaben (Satzung, „How does the assessment procedure work WS 26/27") und Erfahrungsberichte im WiWi-TReFF-Thread „MMT TUM neuer Eignungstest WS 26/27"

---

## 0. Was über den Test bekannt ist

| Punkt | Info | Quelle |
|---|---|---|
| Umfang | ca. 40–50 Fragen, **max. 40 Punkte** | offiziell |
| Blöcke | **4 × 25 %**: ① Mathe & Statistik ② BWL & **Rechnungswesen** ③ **Mikro & Makro** ④ **Freitext** zu Wirtschaft & Technik | offiziell |
| Formate | Single/Multiple Choice **und andere Antwortformen** (z. B. Zahl eintippen) | Satzung |
| Hilfsmittel | **kein Taschenrechner** | Teilnehmer |
| Mathe | eher theoretisch, nicht allzu schwer: **4×4-Matrix**, **Eigenschaften von Funktionen**, einfache **Wahrscheinlichkeitsrechnung** | Teilnehmer |
| Statistik | Grundwissen, keine schweren Aufgaben | Teilnehmer |
| BWL | z. B. **Big Five**: Welche Persönlichkeit hat ein idealer Vertriebsmitarbeiter? | Teilnehmer |
| Freitext | früher z. B. zu **Trumps Zöllen**; Hinweise auf **englischen** Text, also auf beide Sprachen einstellen | Teilnehmer |

**Was daraus folgt:**
- Der Freitext zählt **25 %, also rund 10 von 40 Punkten**. Er ist der Block, den man am sichersten vorbereiten kann (Abschnitt 5).
- Mikro/Makro und Rechnungswesen zählen je so viel wie Mathe/Statistik, also nicht nur Mathe pauken.
- Kein Taschenrechner bedeutet, dass die Zahlen „glatt" sind. Wer bei krummen Zwischenergebnissen landet, hat sich wahrscheinlich verrechnet.
- Zu den geleakten Fragen: Nichts davon ist überprüfbar, und wer damit erwischt wird, verliert die Bewerbung. Die Finger davon lassen.

---

## 1. Mathematik

### 1.1 Kopfrechnen ohne Taschenrechner
- e ≈ 2,718 · ln 2 ≈ 0,693 · ln 3 ≈ 1,099 · ln 10 ≈ 2,303 · √2 ≈ 1,414 · √3 ≈ 1,732
- 1,1² = 1,21 · 1,1³ = 1,331 · 1,05² = 1,1025 · 1,2² = 1,44 · 1/1,1 ≈ 0,909 · 1/1,21 ≈ 0,826
- **70er-Regel:** Verdopplungszeit ≈ 70 / Wachstumsrate in % (7 % → 10 Jahre)
- Prozent: +20 % und dann −20 % ergibt 0,96, also **−4 %** (nicht 0)

### 1.2 Potenzen und Logarithmen
- aᵐ·aⁿ = aᵐ⁺ⁿ · (aᵐ)ⁿ = aᵐⁿ · a⁻ⁿ = 1/aⁿ · a^(1/n) = ⁿ√a · a⁰ = 1
- ln(xy) = ln x + ln y · ln(x/y) = ln x − ln y · ln(xᵃ) = a·ln x · ln 1 = 0 · ln e = 1 · e^(ln x) = x

### 1.3 Ableitungen
| f(x) | f′(x) |
|---|---|
| xⁿ | n·xⁿ⁻¹ |
| eˣ / e^(g(x)) | eˣ / g′(x)·e^(g(x)) |
| ln x / ln g(x) | 1/x / g′(x)/g(x) |
| aˣ | aˣ·ln a |
| u·v | u′v + uv′ |
| u/v | (u′v − uv′)/v² |
| f(g(x)) | f′(g(x))·g′(x) |

- **Elastizität:** ε = f′(x)·x / f(x). Für f(x) = c·xᵃ ist ε = a (konstant).
- **Integrale:** ∫xⁿ dx = xⁿ⁺¹/(n+1) (n ≠ −1) · ∫1/x dx = ln|x| · ∫eˣ dx = eˣ

### 1.4 Eigenschaften von Funktionen (laut Teilnehmern abgefragt)
- **Monoton steigend:** f′ ≥ 0. **Streng** steigend ⇒ umkehrbar (injektiv).
- **Konvex:** f″ ≥ 0, Sekante liegt über dem Graphen (Kostenfunktionen). **Konkav:** f″ ≤ 0 (Produktion, Nutzen, abnehmende Grenzerträge).
- **Extremum:** notwendig f′ = 0; hinreichend f″ < 0 (Max) bzw. f″ > 0 (Min). Bei f″ = 0 hilft der Vorzeichenwechsel von f′.
- **Wendepunkt:** f″ wechselt das Vorzeichen; **f″ = 0 allein reicht nicht** (x⁴ bei 0 ist ein Minimum).
- **Sattelpunkt:** f′ = 0 und Wendepunkt (x³ bei 0).
- **Definitionsbereich:** ln x für x > 0 · √x für x ≥ 0 · 1/x für x ≠ 0
- eˣ: immer > 0, streng steigend, konvex. ln x: streng steigend, konkav, ln 1 = 0.
- **Differenzierbar ⇒ stetig**, aber nicht umgekehrt (|x| bei 0 hat einen Knick).
- **Wachstum für x → ∞:** ln x ≪ xⁿ ≪ eˣ
- **Gerade:** f(−x) = f(x) (x², cos). **Ungerade:** f(−x) = −f(x) (x³, sin).
- **Homogen vom Grad r:** f(tx, ty) = tʳ·f(x, y). Cobb-Douglas xᵃyᵇ hat r = a + b. r > 1: steigende, r = 1: konstante, r < 1: sinkende Skalenerträge.
- Konkav ⇒ quasikonkav, die Umkehrung gilt nicht.

### 1.5 Mehrere Variablen und Optimierung
- Partielle Ableitungen f_x, f_y. Stationärer Punkt: f_x = f_y = 0.
- **Hesse-Matrix** H = [[f_xx, f_xy], [f_xy, f_yy]]: det H > 0 und f_xx < 0 ergibt ein **Max**, det H > 0 und f_xx > 0 ein **Min**, det H < 0 einen **Sattelpunkt**.
- **Lagrange:** L = f(x, y) − λ·(g(x, y) − c), alle partiellen Ableitungen gleich 0 setzen. **λ = Schattenpreis**, d. h. wie stark sich der Optimalwert ändert, wenn c um 1 steigt.

### 1.6 Lineare Algebra (4×4-Matrix wurde gefragt!)
**Grundregeln**
- (m×n)·(n×p) = m×p. **AB ≠ BA** im Allgemeinen.
- (AB)ᵀ = BᵀAᵀ · (AB)⁻¹ = B⁻¹A⁻¹ · (Aᵀ)⁻¹ = (A⁻¹)ᵀ
- 2×2-Inverse: [[a, b], [c, d]]⁻¹ = 1/(ad − bc) · [[d, −b], [−c, a]]

**Determinante**
- 2×2: ad − bc. 3×3: **Sarrus** (Sarrus funktioniert **nur** bei 3×3, nicht bei 4×4!)
- 4×4: **Laplace-Entwicklung** nach der Zeile oder Spalte mit den meisten Nullen. Vorzeichenmuster (−1)^(i+j):
  ```
  + − + −
  − + − +
  + − + −
  − + − +
  ```
- **Dreiecks- oder Diagonalmatrix:** det = Produkt der Diagonale.
- **Blockdiagonal:** det = det(Block 1) · det(Block 2).
- **det = 0**, wenn eine Nullzeile oder Nullspalte existiert, zwei Zeilen gleich oder proportional sind oder eine Zeile Linearkombination anderer ist.
- Zeilentausch: Vorzeichen dreht sich · Zeile mal k: det mal k · Vielfaches einer Zeile zu einer anderen addieren: **keine Änderung**
- det(Aᵀ) = det A · det(AB) = det A · det B · det(A⁻¹) = 1/det A
- **Falle: det(cA) = cⁿ·det A**, bei 4×4 also **c⁴**·det A
- ⚠ det(A + B) ≠ det A + det B

**Äquivalent für eine n×n-Matrix A** (alles gleichzeitig wahr oder alles falsch):
det A ≠ 0 ⇔ A invertierbar ⇔ Rang A = n ⇔ Zeilen/Spalten linear unabhängig ⇔ Ax = 0 hat nur x = 0 ⇔ Ax = b eindeutig lösbar ⇔ kein Eigenwert ist 0

**Lösbarkeit von Ax = b** (Rang-Kriterium):
- Rang A = Rang(A|b) = n: genau eine Lösung
- Rang A = Rang(A|b) < n: unendlich viele Lösungen (n − Rang freie Parameter)
- Rang A < Rang(A|b): keine Lösung

**Eigenwerte:** det(A − λI) = 0
- **Summe der Eigenwerte = Spur** (Summe der Diagonale) · **Produkt = det A**
- Dreiecksmatrix: Eigenwerte = Diagonaleinträge
- Symmetrische Matrix: alle Eigenwerte reell
- **Definitheit** (symmetrisch): alle EW > 0 positiv definit · alle < 0 negativ definit · gemischte Vorzeichen indefinit
- Orthogonal: AᵀA = I, det = ±1 · Idempotent: A² = A, EW ∈ {0, 1}

**Beispiel 1 (Laplace).** A = [[2,0,1,3], [0,1,0,0], [1,0,1,2], [0,4,0,5]]
Entwicklung nach Zeile 2 (nur ein Eintrag ≠ 0, Position (2,2), Vorzeichen +): det A = 1 · det[[2,1,3], [1,1,2], [0,0,5]]
Diese 3×3 nach Zeile 3 entwickeln: 5 · det[[2,1], [1,1]] = 5 · (2 − 1) = **5**

**Beispiel 2 (Sehen statt Rechnen).** B = [[1,2,3,4], [0,1,1,1], [2,4,6,8], [1,0,0,1]]
Zeile 3 = 2 · Zeile 1, also **det B = 0**, B ist nicht invertierbar, Rang < 4 (hier 3).

**Beispiel 3.** Obere Dreiecksmatrix mit Diagonale 1, 2, 3, −1: det = −6 · det(2A) = 16 · (−6) = −96 · det(A⁻¹) = −1/6 · Eigenwerte 1, 2, 3, −1 → indefinit (wenn symmetrisch)

### 1.7 Folgen und Reihen
- Arithmetisch: Σ = n·(a₁ + aₙ)/2 · Gauß: 1 + 2 + … + n = n(n+1)/2
- Geometrisch: Σ_{k=0}^{n−1} a·qᵏ = a·(1 − qⁿ)/(1 − q) · unendlich (|q| < 1): a/(1 − q)

---

## 2. Statistik und Wahrscheinlichkeit

### 2.1 Deskriptive Statistik
- **Skalen:** nominal (nur Modus) → ordinal (+ Median) → metrisch (+ Mittelwert, Varianz)
- **Median** ist robust gegen Ausreißer, der Mittelwert nicht. Rechtsschief: Mittelwert > Median.
- Varianz Grundgesamtheit: σ² = (1/n)·Σ(xᵢ − x̄)² · Stichprobe: s² = 1/(n−1)·Σ(xᵢ − x̄)²
- **Verschiebungssatz:** Var X = E(X²) − (E X)²
- Variationskoeffizient: σ/μ (einheitenfrei)

### 2.2 Rechenregeln
- E(aX + b) = a·E X + b · **Var(aX + b) = a²·Var X** (b fällt weg!)
- E(X + Y) = E X + E Y (immer)
- Var(X ± Y) = Var X + Var Y **± 2 Cov(X, Y)**. Bei Unabhängigkeit ist Cov = 0, und auch bei X − Y wird die Varianz **addiert**.
- Cov(X, Y) = E(XY) − E X · E Y · ρ = Cov/(σ_X·σ_Y) ∈ [−1, 1]
- **Unabhängig ⇒ unkorreliert**, aber nicht umgekehrt (ρ misst nur linearen Zusammenhang).

### 2.3 Wahrscheinlichkeit
- P(A ∪ B) = P(A) + P(B) − P(A ∩ B) · P(Aᶜ) = 1 − P(A)
- P(A | B) = P(A ∩ B)/P(B) · **unabhängig:** P(A ∩ B) = P(A)·P(B)
- **Disjunkt ≠ unabhängig:** Disjunkte Ereignisse mit P > 0 sind immer **ab**hängig.
- **Totale Wahrscheinlichkeit:** P(B) = Σ P(B | Aᵢ)·P(Aᵢ)
- **Bayes:** P(A | B) = P(B | A)·P(A) / P(B)
- **„Mindestens einmal":** 1 − (1 − p)ⁿ

**Beispiel Bayes:** Krankheit 1 %, Test erkennt 99 % der Kranken, 1 % falsch-positiv.
P(krank | +) = 0,99·0,01 / (0,99·0,01 + 0,01·0,99) = **50 %**. Die Basisrate zählt!

### 2.4 Kombinatorik (k aus n)
| | ohne Wiederholung | mit Wiederholung |
|---|---|---|
| mit Reihenfolge | n!/(n−k)! | nᵏ |
| ohne Reihenfolge | (n über k) = n!/(k!(n−k)!) | (n+k−1 über k) |

(5 über 2) = 10 · (6 über 3) = 20 · (10 über 2) = 45 · 0! = 1

### 2.5 Verteilungen
| Verteilung | E X | Var X |
|---|---|---|
| Bernoulli(p) | p | p(1−p) |
| Binomial(n, p) | np | np(1−p) |
| Poisson(λ) | λ | λ |
| Gleichverteilung stetig [a, b] | (a+b)/2 | (b−a)²/12 |
| Exponential(λ) | 1/λ | 1/λ² |
| Normal(μ, σ²) | μ | σ² |

- Binomial: P(X = k) = (n über k)·pᵏ·(1−p)ⁿ⁻ᵏ
- **Normalverteilung:** μ ± 1σ: 68 % · ± 2σ: 95 % · ± 3σ: 99,7 % · symmetrisch, Φ(0) = 0,5, Φ(−z) = 1 − Φ(z)
- Standardisieren: Z = (X − μ)/σ · z-Werte: 1,645 (90 % zweiseitig / 95 % einseitig) · **1,96 (95 % zweiseitig)** · 2,576 (99 %)
- **Zentraler Grenzwertsatz:** X̄ ≈ N(μ, σ²/n), **Standardfehler σ/√n**. Bei 4-fachem n halbiert sich der Standardfehler.

### 2.6 Schätzen und Testen
- Konfidenzintervall: x̄ ± z·σ/√n. Größeres n → schmaler, höheres Konfidenzniveau → breiter.
- **Fehler 1. Art (α):** H₀ abgelehnt, obwohl wahr. **Fehler 2. Art (β):** H₀ beibehalten, obwohl falsch. **Power** = 1 − β.
- **p-Wert < α → H₀ ablehnen.** Der p-Wert ist **nicht** die Wahrscheinlichkeit, dass H₀ wahr ist.
- Kleineres α → größeres β (bei festem n).

### 2.7 Regression (einfach, OLS)
- β̂₁ = Cov(x, y)/Var(x) · β̂₀ = ȳ − β̂₁·x̄ · Die Gerade geht durch (x̄, ȳ).
- R² ∈ [0, 1] = erklärter Anteil der Varianz. Einfache Regression: R² = r².
- log-log: β = **Elastizität** · log-lin (ln y auf x): β·100 = %-Änderung von y pro Einheit x
- Korrelation ≠ Kausalität (Drittvariablen, umgekehrte Kausalität)

---

## 3. BWL und Rechnungswesen

### 3.1 Bilanz, GuV, Buchführung
- **Aktiva = Passiva**: Vermögen = Eigenkapital + Fremdkapital
- Aktiva: Anlagevermögen, Umlaufvermögen · Passiva: EK, Rückstellungen, Verbindlichkeiten
- Buchungssatz „**Soll an Haben**". Aktivkonto: Zugang im Soll. Passivkonto: Zugang im Haben. Aufwand im Soll, Ertrag im Haben.
- **Vier Begriffspaare:** Auszahlung/Einzahlung (Kasse) · Ausgabe/Einnahme (Geldvermögen inkl. Forderungen/Verbindlichkeiten) · Aufwand/Ertrag (GuV, Jahresabschluss) · Kosten/Leistung (betrieblich, KLR)
- Beispiel: Kauf von Rohstoffen auf Ziel ist eine Ausgabe, aber noch keine Auszahlung. Die Auszahlung folgt erst bei Bezahlung.
- **Abschreibung linear:** (AK − Restwert)/Nutzungsdauer · degressiv: fester %-Satz vom Restbuchwert
- **HGB-Prinzipien:** Vorsichtsprinzip · Realisationsprinzip (Gewinne erst bei Realisierung) · Imparitätsprinzip (drohende Verluste sofort) · Niederstwertprinzip (Umlaufvermögen strikt)
- GuV: **Gesamtkostenverfahren** (nach Aufwandsarten, inkl. Bestandsveränderungen) vs. **Umsatzkostenverfahren** (nach Funktionsbereichen, nur Kosten der verkauften Menge)
- **Cashflow (indirekt)** ≈ Jahresüberschuss + Abschreibungen + Zunahme Rückstellungen − Zunahme Working Capital
- EBIT = Ergebnis vor Zinsen und Steuern · EBITDA = EBIT + Abschreibungen

### 3.2 Kosten- und Leistungsrechnung
- K(x) = K_f + k_v·x · Stückkosten k = K_f/x + k_v · Fixkostendegression: k sinkt mit x
- **Deckungsbeitrag** pro Stück: db = p − k_v · DB gesamt = db·x · Gewinn = DB − K_f
- **Break-even:** x* = K_f/(p − k_v)
- **Preisuntergrenze:** kurzfristig = k_v · langfristig = k (Stückvollkosten)
- **Engpass:** Reihenfolge nach **relativem DB** = db pro Engpasseinheit (nicht nach absolutem db!)
- Make or buy: Fremdbezugspreis vs. **relevante** (variable bzw. abbaubare) Kosten. Sunk Costs ignorieren.
- Kostenarten → Kostenstellen (BAB) → Kostenträger · Einzelkosten direkt, Gemeinkosten per Zuschlag

### 3.3 Kennzahlen
- EK-Quote = EK/GK · Verschuldungsgrad = FK/EK
- EK-Rentabilität = Gewinn/EK · GK-Rentabilität = (Gewinn + FK-Zinsen)/GK · Umsatzrendite = Gewinn/Umsatz
- **ROI (DuPont)** = Umsatzrendite × Kapitalumschlag = (Gewinn/Umsatz)·(Umsatz/GK)
- **Leverage-Effekt:** r_EK = r_GK + (r_GK − i)·FK/EK. Mehr Fremdkapital hebelt die EK-Rendite, solange r_GK > i (dann steigt auch das Risiko).
- Liquidität 1. Grades = liquide Mittel/kurzfr. Verbindlichkeiten · 2. Grades: + Forderungen · 3. Grades: + Vorräte (gesamtes UV)
- **Goldene Bilanzregel:** Anlagevermögen langfristig finanziert (EK + langfr. FK ≥ AV)

### 3.4 Investition und Finanzierung
- **Kapitalwert:** NPV = −I₀ + Σ CFₜ/(1 + r)ᵗ. NPV > 0 → durchführen.
- **Interner Zinsfuß (IRR):** r mit NPV = 0. Bei sich gegenseitig ausschließenden Projekten entscheidet im Konfliktfall der **NPV**.
- **Ewige Rente:** PV = C/r · **wachsend (Gordon):** PV = C₁/(r − g), nur wenn r > g
- **Rentenbarwertfaktor:** (1 − (1+r)⁻ⁿ)/r · Annuität = Barwert / RBF
- Endwert: K·(1 + r)ⁿ · stetig: K·e^(rt)
- **Amortisationsdauer:** I₀/jährl. CF. Ignoriert Zeitwert und Cashflows nach der Amortisation.
- **CAPM:** r_E = r_f + β·(r_M − r_f). β > 1: riskanter als der Markt.
- **WACC** = E/V·r_E + D/V·r_D·(1 − t)
- Diversifikation eliminiert nur **unsystematisches** Risiko. Bepreist wird nur das systematische Risiko (β).
- Finanzierungsarten: Innen- (Gewinnthesaurierung, Abschreibungen, Rückstellungen) vs. Außenfinanzierung (Beteiligung = EK, Kredit = FK)

### 3.5 Strategie, Marketing, Produktion
- **Porter 5 Forces:** Rivalität, neue Anbieter, Substitute, Lieferantenmacht, Kundenmacht
- **Porter generische Strategien:** Kostenführerschaft · Differenzierung · Fokus (Gefahr: „stuck in the middle")
- **BCG-Matrix** (Marktwachstum × relativer Marktanteil): Stars (hoch/hoch) · Cash Cows (niedrig/hoch) · Question Marks (hoch/niedrig) · Poor Dogs (niedrig/niedrig)
- **Ansoff:** Marktdurchdringung · Marktentwicklung · Produktentwicklung · Diversifikation
- SWOT (S/W intern, O/T extern) · PESTEL · Wertkette (Porter) · Produktlebenszyklus: Einführung, Wachstum, Reife, Sättigung, Rückgang
- Marketing-Mix **4P:** Product, Price, Place, Promotion
- **Optimale Bestellmenge (Andler):** q* = √(2·Jahresbedarf·Bestellfixkosten / Lagerkostensatz pro Stück und Jahr)

### 3.6 Organisation und Personal (laut Teilnehmern abgefragt)
- **Big Five (OCEAN):** Openness · Conscientiousness · Extraversion · Agreeableness · Neuroticism
  - **Gewissenhaftigkeit** ist der berufsübergreifend stabilste Prädiktor für Leistung.
  - **Vertrieb:** hohe Gewissenhaftigkeit + hohe Extraversion + niedriger Neurotizismus (emotional stabil). Verträglichkeit und Offenheit sagen Verkaufserfolg kaum voraus.
- **Herzberg:** Hygienefaktoren (Gehalt, Arbeitsbedingungen, Sicherheit) verhindern Unzufriedenheit, schaffen aber keine Zufriedenheit. **Motivatoren** (Anerkennung, Verantwortung, Arbeitsinhalt, Aufstieg) schaffen Zufriedenheit.
- **Maslow** (von unten): physiologisch → Sicherheit → sozial → Wertschätzung → Selbstverwirklichung. Defizit- vs. Wachstumsbedürfnisse.
- **McGregor:** Theorie X (Menschen sind faul, brauchen Kontrolle) vs. Theorie Y (intrinsisch motiviert, wollen Verantwortung)
- **Führungsstile (Lewin):** autoritär, kooperativ/demokratisch, laissez-faire · situativ (Hersey/Blanchard: Stil abhängig vom Reifegrad der Mitarbeitenden)
- **Organisationsformen:** funktional · divisional (Sparten, Profit Center) · **Matrix** (zwei Weisungslinien, Konfliktpotenzial) · Stab-Linie · Einlinien- vs. Mehrliniensystem · Leitungsspanne
- **Prinzipal-Agent:** Hidden Information → **Adverse Selection** (vor Vertrag; Gegenmittel: Signaling, Screening) · Hidden Action → **Moral Hazard** (nach Vertrag; Gegenmittel: Anreizverträge, Monitoring)
- **Rechtsformen:** GmbH 25.000 € Stammkapital · UG ab 1 € · AG 50.000 € Grundkapital (Vorstand, Aufsichtsrat, Hauptversammlung) · OHG: alle haften voll · KG: Komplementär voll, Kommanditist nur mit Einlage
- Shareholder- vs. Stakeholder-Ansatz

---

## 4. Mikro- und Makroökonomie

### 4.1 Mikro: Nachfrage und Elastizitäten
- **Preiselastizität** ε = (dQ/dP)·(P/Q). |ε| > 1 elastisch: eine Preissenkung **erhöht** den Umsatz. |ε| < 1 unelastisch: eine Preiserhöhung erhöht den Umsatz. Umsatzmaximum bei |ε| = 1.
- Lineare Nachfrage: Die Elastizität ist **nicht** konstant (oben elastisch, unten unelastisch).
- **Kreuzpreiselastizität:** > 0 Substitute · < 0 Komplemente
- **Einkommenselastizität:** < 0 inferior · 0–1 normal/notwendig · > 1 Luxusgut
- Giffen-Gut: inferior, Einkommenseffekt größer als Substitutionseffekt, Nachfrage steigt mit dem Preis

### 4.2 Haushalt
- Optimum: **GRS = MU_x/MU_y = p_x/p_y** (Budget m = p_x·x + p_y·y)
- **Cobb-Douglas** U = xᵃyᵇ → x* = a/(a+b)·m/p_x, y* = b/(a+b)·m/p_y (fester Budgetanteil)
- Perfekte Substitute (U = x + y): Randlösung, nur das relativ billigere Gut · Perfekte Komplemente (U = min{x, y}): x = y

### 4.3 Unternehmen und Märkte
- **Gewinnmaximum immer bei MR = MC**
- **Vollkommener Wettbewerb:** p = MC. Kurzfristig produzieren, solange p ≥ min AVC (Betriebsminimum). Langfristig p = min AC (Betriebsoptimum), Gewinn 0.
- MC schneidet AC und AVC jeweils in deren **Minimum**.
- **Monopol:** Bei P = a − bQ ist MR = a − 2bQ (doppelte Steigung). Menge kleiner und Preis höher als im Wettbewerb, es entsteht ein **Wohlfahrtsverlust**.
- **Lerner-Index:** (P − MC)/P = 1/|ε|. Ein Monopolist agiert nie im unelastischen Bereich.
- **Cournot** (2 Firmen, P = a − bQ, MC = c): qᵢ = (a − c)/(3b) · Bertrand (homogen): P = MC · Stackelberg: Leader (a − c)/(2b), Follower (a − c)/(4b)
- Preisdiskriminierung 1. Grades: perfekt, keine Konsumentenrente, kein Wohlfahrtsverlust
- Produktion: MRTS = MP_L/MP_K = w/r im Kostenminimum

### 4.4 Wohlfahrt und Staat
- Konsumentenrente = Fläche zwischen Nachfrage und Preis · Produzentenrente = Fläche zwischen Preis und Angebot
- **Steuerinzidenz:** Die **unelastischere** Marktseite trägt mehr, egal wer formal zahlt.
- Höchstpreis unter Gleichgewicht → Nachfrageüberhang · Mindestpreis über Gleichgewicht → Angebotsüberhang (z. B. Mindestlohn → ggf. Arbeitslosigkeit)
- **Externe Effekte:** negativ → zu viel produziert. **Pigou-Steuer** = Grenzschaden im Optimum. **Coase:** Bei klaren Eigentumsrechten und ohne Transaktionskosten verhandeln die Parteien effizient.
- **Güterarten:**

  | | rival | nicht rival |
  |---|---|---|
  | ausschließbar | privates Gut | Clubgut (Streaming) |
  | nicht ausschließbar | Allmende (Fischbestände) | **öffentliches Gut** (Landesverteidigung) |

- **Spieltheorie:** Nash-Gleichgewicht: Niemand will einseitig abweichen. Dominante Strategie: beste Antwort auf alles. **Gefangenendilemma:** Das Nash-GG ist nicht Pareto-optimal.

### 4.5 Makro: VGR, Geld, Inflation
- **Y = C + I + G + NX** (NX = Ex − Im)
- BIP nominal vs. real · **BIP-Deflator** = nominal/real·100 · BNE = BIP + Primäreinkommen aus dem Ausland − an das Ausland
- **S − I = NX** (+ Budgetsaldo: S_priv + (T − G) − I = NX)
- **Fisher:** i ≈ r + π (Realzins = Nominalzins − Inflation)
- **Quantitätsgleichung:** M·V = P·Y → %ΔM + %ΔV ≈ %ΔP + %ΔY
- **Geldschöpfungsmultiplikator** (einfach): 1/Mindestreservesatz
- EZB: Ziel **2 % Inflation mittelfristig (symmetrisch)**. Instrumente: Leitzinsen (Einlagefazilität, Hauptrefi-Satz, Spitzenrefi), Offenmarktgeschäfte, QE/QT. Den aktuellen Einlagesatz vor dem Test kurz nachschauen.
- Arbeitslosenquote = Arbeitslose/Erwerbspersonen (Erwerbspersonen = Erwerbstätige + Arbeitslose) · friktionell, strukturell, konjunkturell · NAIRU
- **Okun:** 1 % Arbeitslosigkeit über der natürlichen Rate kostet ca. 2 % BIP · **Phillips-Kurve:** kurzfristig Inflation vs. Arbeitslosigkeit, langfristig vertikal

### 4.6 Makro: Modelle
- **Keynes-Multiplikator:** ΔY = 1/(1 − c)·ΔG · Steuermultiplikator: −c/(1 − c) · **Balanced Budget: 1** · offen: 1/(1 − c + m)
  Beispiel: c = 0,8 → Multiplikator 5, Steuermultiplikator −4
- **IS-LM:** expansive Fiskalpolitik: IS nach rechts, Y↑ und i↑ (**Crowding-out**) · expansive Geldpolitik: LM nach rechts, Y↑ und i↓ · Liquiditätsfalle: Geldpolitik wirkungslos
- **AS-AD:** Nachfrageschock: P und Y in gleiche Richtung · Angebotsschock (z. B. Energiepreise): **Stagflation** (P↑, Y↓)
- **Mundell-Fleming** (volle Kapitalmobilität): feste Wechselkurse: **Fiskalpolitik** wirkt, Geldpolitik nicht · flexible Wechselkurse: **Geldpolitik** wirkt, Fiskalpolitik nicht
- **Unmögliches Dreieck:** feste Wechselkurse + freier Kapitalverkehr + autonome Geldpolitik, höchstens 2 von 3
- **Solow:** Steady State s·f(k) = (n + δ)·k. Höhere Sparquote erhöht das **Niveau**, nicht die langfristige Wachstumsrate. Die kommt nur aus technischem Fortschritt. **Goldene Regel:** MPK = n + δ.
- Wachstumsrate eines Produkts ≈ Summe der Wachstumsraten (z. B. nominales BIP ≈ real + Inflation)

### 4.7 Außenhandel (bereits Freitext-Thema!)
- **Komparativer Vorteil:** geringere **Opportunitätskosten** entscheiden, nicht absolute Produktivität
- **Zoll (kleines Land):** Inlandspreis↑, Importe↓, Konsumentenrente↓, Produzentenrente↑, Zolleinnahmen, **Wohlfahrtsverlust = 2 Dreiecke** (Produktions- und Konsumverzerrung). Großes Land: Terms-of-Trade-Gewinn möglich, Risiko von Vergeltungszöllen.
- Wechselkurs: **Aufwertung des €** → Exporte teurer, Importe billiger · Kaufkraftparität: e = P/P* (langfristig)
- Zahlungsbilanz: Leistungsbilanz + Kapitalbilanz (+ Restposten) = 0

---

## 5. Freitext (25 % ≈ 10 Punkte)

### 5.1 Struktur (auswendig, für jedes Thema)
1. **These** in einem Satz: klare Position, kein „sowohl als auch"
2. **Argument 1:** ökonomischer **Mechanismus** + **konkreter Beleg** (Zahl, Firma, Land, Ereignis)
3. **Argument 2:** wie oben, möglichst aus einer anderen Perspektive (Unternehmen vs. Staat vs. Konsumenten, kurz- vs. langfristig)
4. **Gegenargument** fair darstellen und entkräften oder abwägen
5. **Fazit + Empfehlung:** Was sollten Politik oder Unternehmen konkret tun?

Fachbegriffe sichtbar einbauen (Opportunitätskosten, Externalität, Skaleneffekte, Netzwerkeffekte, Anreize, Wohlfahrtsverlust, Terms of Trade, Pfadabhängigkeit). Das zeigt Wirtschafts- **und** Technikverständnis. Pro Absatz eine Kernaussage. Die letzten 2 Minuten für Rechtschreibung freihalten.

**Englische Bausteine:** *I argue that…* · *The key mechanism is…* · *For instance, …* · *Admittedly, … However, …* · *On balance, …* · *Policymakers should therefore…*

### 5.2 Wahrscheinliche Themenfelder (Zölle kam schon, also eher etwas anderes)
| Feld | Mechanismus / Begriffe |
|---|---|
| **KI und Arbeit/Produktivität** | Automatisierung vs. Augmentierung, Produktivitätsparadoxon, Skill-biased technological change, Umschulung, Marktkonzentration bei Foundation Models (Skaleneffekte, Rechenkosten) |
| **KI-Regulierung (EU AI Act)** | risikobasierter Ansatz, Innovation vs. Sicherheit, Compliance-Kosten als Markteintrittsbarriere, „Brussels Effect" |
| **Energiewende / CO₂-Preis** | Externalität → Pigou/Emissionshandel (EU-ETS), Carbon Leakage → CO₂-Grenzausgleich (CBAM), Strompreise als Standortfaktor, Netzausbau |
| **Halbleiter / technologische Souveränität** | Lieferkettenrisiken, Subventionen (Chips Act) vs. komparativer Vorteil, Klumpenrisiko Taiwan, Industriepolitik |
| **Autoindustrie und E-Mobilität / China** | Pfadabhängigkeit, Batteriekosten und Lernkurven, Subventionswettlauf, Zölle auf E-Autos |
| **Plattformen / Digital Markets Act** | Netzwerkeffekte, Winner-takes-all, Gatekeeper, Datenmonopole, Interoperabilität |
| **Demografie / Fachkräftemangel** | Erwerbspersonenpotenzial, Zuwanderung, Automatisierung als Antwort, Rentensystem |
| **Verteidigung / Dual-Use** | öffentliches Gut, Crowding-out vs. Innovations-Spillover, Staatsverschuldung, Schuldenbremse |

Am besten zu **2–3 Feldern** je einen eigenen konkreten Beleg parat haben, statt einen Essay auswendig zu lernen.

---

## 6. Typische Fallen
- det(cA) = **c⁴**·det A bei 4×4 · Sarrus nicht bei 4×4 · det(A + B) ≠ det A + det B · AB ≠ BA
- f″(x₀) = 0 bedeutet nicht automatisch einen Wendepunkt
- Var(X − Y) = Var X + Var Y (unabhängig), **nicht** minus · Var(aX) = **a²**·Var X
- Stichprobenvarianz mit **n − 1**
- Disjunkt ≠ unabhängig · Unkorreliert ≠ unabhängig · P(A | B) ≠ P(B | A)
- Ausgabe ≠ Auszahlung ≠ Aufwand ≠ Kosten
- Bei Engpass nach **relativem** DB sortieren · Sunk Costs ignorieren
- IRR und NPV widersprechen sich → **NPV** gewinnt
- Monopol-MR hat die **doppelte** Steigung · Gewinnmax. ist immer MR = MC
- Höhere Sparquote erhöht im Solow-Modell **nicht** die langfristige Wachstumsrate
- Steuerlast trägt die **unelastischere** Seite
- +x % dann −x % ergibt nicht 0

---

## 7. Selbstcheck (ohne Taschenrechner, Lösungen unten)

1. A ist eine obere 4×4-Dreiecksmatrix mit Diagonale 1, 2, 3, −1. Berechne det A, det(2A), det(A⁻¹). Ist A invertierbar?
2. f(x) = x³ − 3x: Extrema und Wendepunkt?
3. Ist f(x) = ln x auf (0, ∞) konvex oder konkav? Und f(x) = e^(−x)?
4. Krankheit 1 %, Sensitivität 99 %, falsch-positiv 1 %. P(krank | positiv)?
5. X ~ Bin(100; 0,2): E X, Var X, σ?
6. K_f = 40.000 €, p = 50 €, k_v = 30 €. Break-even-Menge?
7. r_GK = 10 %, Fremdkapitalzins 6 %, FK/EK = 3. EK-Rendite?
8. I₀ = 100, CF₁ = CF₂ = 60, r = 10 %. Lohnt sich die Investition?
9. Monopol mit P = 100 − 2Q, MC = 20: Q, P, Wohlfahrtsverlust?
10. Q = 100 − 2P bei P = 20: Preiselastizität? Was passiert mit dem Umsatz bei einer Preiserhöhung?
11. c = 0,75: Staatsausgabenmultiplikator, Steuermultiplikator; Effekt von ΔG = ΔT = 10?
12. U = x^0,25·y^0,75, m = 100, p_x = 5: x*?
13. Cournot: P = 100 − Q, MC = 10 für beide Firmen. qᵢ, Q, P?
14. Welche Big-Five-Ausprägung passt am besten zu einem Vertriebsmitarbeiter?

<details>
<summary><b>Lösungen</b></summary>

1. det A = 1·2·3·(−1) = **−6** · det(2A) = 2⁴·(−6) = **−96** · det(A⁻¹) = **−1/6** · invertierbar, da det ≠ 0
2. f′ = 3x² − 3 = 0 → x = ±1; f″ = 6x → **Max bei (−1, 2)**, **Min bei (1, −2)**; **Wendepunkt bei (0, 0)** (f″ wechselt das Vorzeichen)
3. ln x: f″ = −1/x² < 0, **konkav** · e^(−x): f″ = e^(−x) > 0, **konvex** (und streng fallend)
4. 0,0099/(0,0099 + 0,0099) = **50 %**
5. E = 20, Var = 100·0,2·0,8 = 16, σ = **4**
6. 40.000/(50 − 30) = **2.000 Stück**
7. 10 % + (10 % − 6 %)·3 = **22 %**
8. 60/1,1 + 60/1,21 ≈ 54,5 + 49,6 = 104,1 → NPV ≈ **+4,1 > 0, ja**
9. MR = 100 − 4Q = 20 → **Q = 20, P = 60**. Wettbewerb: P = MC = 20 → Q = 40. DWL = ½·(60 − 20)·(40 − 20) = **400**
10. Q = 60, ε = −2·20/60 = **−2/3**, unelastisch → eine Preiserhöhung **erhöht** den Umsatz
11. 1/(1 − 0,75) = **4** · −0,75/0,25 = **−3** · Balanced Budget: +40 − 30 = **+10**
12. x* = 0,25·100/5 = **5**
13. qᵢ = (100 − 10)/3 = **30**, Q = 60, **P = 40**
14. Hohe **Gewissenhaftigkeit** + hohe **Extraversion** + niedriger **Neurotizismus**
</details>

---

## 8. Checkliste für den 07.10.
- Einladungsmail nochmals lesen: Uhrzeit, Link, Ausweis, erlaubte Hilfsmittel (Papier/Stift?), technische Voraussetzungen (Kamera, Browser)
- Rechner laden, LAN oder stabiles WLAN, Benachrichtigungen aus, ruhiger Raum
- Zu Beginn klären: Abzug für falsche Antworten? Kann man zurückspringen? Zeit pro Block?
- Zeit fürs Freitext-Feld fest einplanen, nicht am Ende hetzen
- Bei MC ohne Minuspunkte: nichts leer lassen
