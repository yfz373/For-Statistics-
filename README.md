---

# 📘 Statistics Exercises – Step-by-Step Solutions

Here are detailed solutions for all the exercises from the provided PDFs, explained in a simple, step-by-step manner suitable for exam preparation.

---

## 📄 Exercise 08 2025.pdf

### 1. Box Plot for Quiz Scores  
**Dataset:** 45, 50, 52, 55, 60, 62, 65, 68, 70, 72, 75, 80  

#### a. Five-Number Summary  
1. **Sort the data:** Already sorted.  
2. **Minimum:** 45  
3. **Q1 (25th percentile):**  
   - Lower half (first 6 numbers): 45, 50, 52, 55, 60, 62  
   - Q1 = average of 3rd and 4th: (52 + 55) / 2 = **53.5**  
4. **Median (Q2, 50th percentile):**  
   - Average of 6th and 7th: (62 + 65) / 2 = **63.5**  
5. **Q3 (75th percentile):**  
   - Upper half (last 6 numbers): 65, 68, 70, 72, 75, 80  
   - Q3 = average of 3rd and 4th: (70 + 72) / 2 = **71**  
6. **Maximum:** 80  

**Five-number summary:** Min = 45, Q1 = 53.5, Median = 63.5, Q3 = 71, Max = 80  

#### b. Box Plot with Whiskers  
1. **IQR = Q3 – Q1 =** 71 – 53.5 = 17.5  
2. **Step = 1.5 × IQR =** 1.5 × 17.5 = 26.25  
3. **Lower fence = Q1 – Step =** 53.5 – 26.25 = 27.25  
4. **Upper fence = Q3 + Step =** 71 + 26.25 = 97.25  
5. **Whiskers:**  
   - Lower whisker: smallest value ≥ lower fence → 45  
   - Upper whisker: largest value ≤ upper fence → 80  
6. **Outliers:** None (all data within fences).  

---

### 2. Arranging Students for Presentation  
**Choose and arrange 4 out of 10 students in order.**  

- Use **permutations** because order matters.  
- Formula: \( P(10,4) = \frac{10!}{(10-4)!} \)  
- \( 10! / 6! = 10 × 9 × 8 × 7 = 5040 \)  

**Answer:** 5040 possible ordered lines.  

---

### 3. Two-Way ANOVA  
**Factors:** Training Program (A1, A2) × Practice Duration (B1–B4)  
**n = 3 per combination**, α = 0.05  

#### Steps:  
1. **Hypotheses:**  
   - H0 (Training): No difference between Standard and Intensive.  
   - H0 (Practice): No difference between practice durations.  
   - H0 (Interaction): No interaction between training and practice.  
2. **Calculate means for each combination.**  
3. **Compute:**  
   - SS Total (total variation)  
   - SS Training (between training types)  
   - SS Practice (between practice durations)  
   - SS Interaction (combined effect)  
   - SS Within (error)  
4. **Degrees of Freedom:**  
   - df Training = 1  
   - df Practice = 3  
   - df Interaction = 3  
   - df Within = 16  
5. **Mean Squares = SS / df**  
6. **F = MS Factor / MS Within**  
7. **Compare F to F-critical or p-value to α.**  
8. **Conclusion:**  
   - If p < 0.05 → significant effect.  

---

### 4. 99% Confidence Interval for Delivery Time  
**Given:**  
- Sample mean = 48  
- Population SD = 6  
- Sample size = 36  
- Confidence level = 99%  

#### Steps:  
1. **Find z* for 99% CI:** z* ≈ 2.576  
2. **Margin of Error (ME):**  
   ME = z* × (σ / √n)  
   = 2.576 × (6 / √36)  
   = 2.576 × 1 = 2.576  
3. **CI:**  
   48 ± 2.576  
   = (45.424, 50.576)  

**Answer:** (45.42, 50.58) minutes.  

---

### 5. Chi-Square Test for Independence  
**Data:**  

| Gender | Online | Face-to-Face | Total |  
|--------|--------|--------------|-------|  
| Male   | 35     | 25           | 60    |  
| Female | 20     | 40           | 60    |  
| Total  | 55     | 65           | 120   |  

**Test at α = 0.05**  

#### Steps:  
1. **Hypotheses:**  
   - H0: Gender and preference are independent.  
   - H1: They are associated.  
2. **Expected frequencies:**  
   E = (RowTotal × ColTotal) / GrandTotal  
   Example: Male Online = (60 × 55) / 120 = 27.5  
3. **Chi-square statistic:**  
   χ² = Σ[(O-E)² / E]  
4. **df = (rows-1)(cols-1) = 1**  
5. **Critical value at α=0.05, df=1:** 3.841  
6. **Compare:**  
   If χ² > 3.841 → reject H0.  
7. **Conclusion:**  
   There is/is not significant association.  

---

## 📄 Exercise 02 - Answers (1).pdf  

### 1. Trimean Calculation  
**Dataset:** 10, 12, 15, 18, 21, 24, 27, 30, 33, 36, 39, 42, 45, 48, 50  

#### Steps:  
1. **Sorted:** Yes.  
2. **Median (Q2):** 8th value = 30  
3. **Q1:** Median of lower half (first 7) = 4th value = 18  
4. **Q3:** Median of upper half (last 7) = 4th value = 42  
5. **Trimean =** (Q1 + 2×Median + Q3) / 4  
   = (18 + 60 + 42) / 4 = 120 / 4 = 30  

**Answer:** 30  

---

### 2. Geometric Mean of Growth Rates  
**Rates:** +5%, +10%, –3%, +6%  

#### Steps:  
1. **Convert to growth factors:**  
   1.05, 1.10, 0.97, 1.06  
2. **Product:** 1.05 × 1.10 × 0.97 × 1.06 ≈ 1.181841  
3. **Geometric mean =** ⁴√1.181841 ≈ 1.0426  
4. **Convert back to %:** (1.0426 – 1) × 100 = 4.26%  

**Answer:** Average growth rate = 4.26% per year.  

---

### 3. 10% Trimmed Mean  
**Scores:** 65, 70, 72, 75, 80, 85, 90, 92, 95, 100  

#### Steps:  
1. **Sorted:** Yes.  
2. **Trim 10% from each end:** Remove 1 smallest (65) and 1 largest (100).  
3. **Remaining:** 70, 72, 75, 80, 85, 90, 92, 95  
4. **Mean =** Sum / 8 = 659 / 8 = 82.375  

**Answer:** 82.375  

---

## 📄 Exercise 01 - Answers (1).pdf  

### 1. Stem-and-Leaf Display  
**Data:** 62, 65, 68, 70, 73, 75, 75, 78, 81, 83, 84, 85, 87, 89, 92, 95, 96, 98, 100  

- Stem = tens digit, leaf = units digit  
- Example:  
  6 | 2 5 8  
  7 | 0 3 5 5 8  
  8 | 1 3 4 5 7 9  
  9 | 2 5 6 8  
  10 | 0  

---

### 2. Box Plot for Test Scores  
**Data:** 55, 60, 62, 63, 65, 66, 68, 70, 72, 75, 77, 78, 80, 85, 88  

#### a. Five-Number Summary:  
- Min = 55  
- Q1 = 63 (between 4th and 5th)  
- Median = 70 (8th value)  
- Q3 = 78 (between 11th and 12th)  
- Max = 88  

#### b. Box Plot:  
- IQR = 78 – 63 = 15  
- Step = 1.5 × 15 = 22.5  
- Lower fence = 63 – 22.5 = 40.5  
- Upper fence = 78 + 22.5 = 100.5  
- Whiskers: 55 to 88  
- No outliers.  

---

## 📄 Exercise 7 - Answers.pdf  

### 1. One-Way ANOVA for Fertilizers  
**Data:** Fertilizer A, B, C heights  

#### Steps:  
1. **H0:** μA = μB = μC  
   **H1:** At least one different.  
2. **Group means:** A=15.4, B=20.4, C=26.0  
3. **Grand mean:** 20.6  
4. **SS Between, SS Within, SS Total**  
5. **df Between = 2, df Within = 12**  
6. **MS = SS / df**  
7. **F = MS Between / MS Within**  
8. **Compare to F-critical (3.89) or p-value**  
9. **Conclusion:** Reject H0 if F > 3.89 or p < 0.05.  

---

### 2. Chi-Square Test of Independence  
**Data:** Plant type vs Fertilizer preference  

#### Steps:  
1. **H0:** Independent, **H1:** Associated.  
2. **Expected frequencies** for each cell.  
3. **Chi-square =** Σ[(O-E)² / E]  
4. **df = (rows-1)(cols-1) = 4**  
5. **Critical χ² at α=0.05, df=4 = 9.488**  
6. **Compare:** If χ² > 9.488 → reject H0.  

---

### 3. Two-Way ANOVA for Programming & Study Method  
**Data:** Python, Java, C++ × Self-Study, Instructor-Led  

#### Steps:  
1. **H0 for Language, Study Method, Interaction.**  
2. **Compute means for each group.**  
3. **SS Total, SS Language, SS Study, SS Interaction, SS Within.**  
4. **df Language=2, df Study=1, df Interaction=2, df Within=12.**  
5. **F = MS Factor / MS Within**  
6. **Compare p-values to α=0.05.**  
7. **Conclusion:** Language and Study Method are significant, Interaction is not.  

---

## 📄 Exercise 6 - Answers.pdf  

### 1. Regression: Hours vs Exam Score  
**Data:** Hours(X) and Score(Y)  

#### Steps:  
1. **Compute:** ΣX, ΣY, ΣXY, ΣX², n=10  
2. **Slope b =** (nΣXY – ΣXΣY) / (nΣX² – (ΣX)²)  
3. **Intercept a =** (ΣY – bΣX) / n  
4. **Equation:** Y' = bX + a  
5. **Predict for X=7 and X=11.**  

---

### 2. Regression: Height vs Weight  
**Data:** Height(X) and Weight(Y) for 5 people  

#### Steps:  
1. **Compute:** ΣX=320, ΣY=770, ΣXY=49390, ΣX²=20520, n=5  
2. **b =** (5×49390 – 320×770) / (5×20520 – 320²) = 2.75  
3. **a =** (770 – 2.75×320) / 5 = -22  
4. **Equation:** Y' = 2.75X – 22  
5. **Predict for X=70:** Y' = 170.5 lbs.  

---

## 📄 Exercise 05 - Answers.pdf  

### 1. One-Sample t-Test for Light Bulbs  
**Data:** 10 bulb lifespans, μ₀=1000, α=0.05  

#### Steps:  
1. **H0:** μ = 1000, **H1:** μ ≠ 1000  
2. **Sample mean =** 990.5, SD ≈ 25.87  
3. **t =** (990.5 – 1000) / (25.87 / √10) ≈ -1.16  
4. **df = 9, critical t = ±2.262**  
5. **Since -1.16 is within [-2.262, 2.262] → fail to reject H0.**  

---

### 2. Paired t-Test for Weight Loss  
**Data:** Before and After weights for 8 clients  

#### Steps:  
1. **H0:** μd = 0, **H1:** μd < 0  
2. **Mean difference =** -3.125  
3. **SD of differences ≈ 0.835**  
4. **t =** -3.125 / (0.835 / √8) ≈ -10.59  
5. **df = 7, critical t (one-tailed) = -1.895**  
6. **Since -10.59 < -1.895 → reject H0.**  
7. **Conclusion:** Program significantly reduced weight.  

---

### 3. Independent t-Test for Diet Plans  
**Data:** Group A (New) vs Group B (Standard)  

#### Steps:  
1. **H0:** μA = μB, **H1:** μA > μB  
2. **t =** (8 – 6) / √(4/25 + 6.25/25) ≈ 3.13  
3. **df = 48, critical t (one-tailed) = 1.679**  
4. **Since 3.13 > 1.679 → reject H0.**  
5. **Conclusion:** New diet leads to greater weight loss.  

---

## 📄 Exercise 04 - Answers.pdf  

### 1. Standard Deviation of Quiz Scores  
**Data:** 70, 85, 78, 90, 88  

#### Steps:  
1. **Mean =** (70+85+78+90+88)/5 = 82.2  
2. **Deviations:** -12.2, 2.8, -4.2, 7.8, 5.8  
3. **Squared deviations:** 148.84, 7.84, 17.64, 60.84, 33.64  
4. **Variance =** Sum / 5 = 53.76  
5. **SD = √53.76 ≈ 7.33**  

---

### 2. Normal Approximation to Binomial  
**Problem:** n=100, p=0.3, find P(X<25)  

#### Steps:  
1. **μ = np = 30, σ = √(npq) = √21 ≈ 4.58**  
2. **Continuity correction:** P(X < 25) → P(X ≤ 24.5)  
3. **z =** (24.5 – 30) / 4.58 ≈ -1.20  
4. **P(Z < -1.20) ≈ 0.1151**  
5. **Answer:** 11.51%  

---

### 3. Binomial Probability with Normal Approximation  
**Problem:** n=100, p=0.4, find P(X ≥ 45)  

#### Steps:  
1. **μ = 40, σ = √24 ≈ 4.9**  
2. **Continuity correction:** P(X ≥ 45) → P(X ≥ 44.5)  
3. **z =** (44.5 – 40) / 4.9 ≈ 0.92  
4. **P(Z ≥ 0.92) = 1 – 0.8212 = 0.1788**  
5. **Answer:** 17.88%  

---

## 📄 Exercise 03 - Answers.pdf  

### 1. Permutations for Photo Arrangement  
**n=8, choose r=4 in order**  
- P(8,4) = 8! / 4! = 1680 ways.  

---

### 2. Combinations for Book Selection  
**n=7, choose r=4 (order doesn’t matter)**  
- C(7,4) = 7! / (4!3!) = 35 ways.  

---

### 3. Hypergeometric Probability for Balls  
**N=25, K=10 red, n=5, want x=3 red**  
- P = [C(10,3) × C(15,2)] / C(25,5) ≈ 0.2372  

---

### 4. Independent Events: Card and Coin  
- P(King) = 4/52 = 1/13  
- P(Tail) = 1/2  
- P(King and Tail) = (1/13) × (1/2) = 1/26  

---

### 5. Binomial Probability: Coin Flips  
**n=5, p=0.5, want x=3 heads**  
- P = C(5,3) × 0.5^5 = 10 × 1/32 = 10/32 = 5/16  

---

### 6. Binomial Probability: Basketball Free Throws  
**n=15, p=0.8, want x ≥ 12**  
- Compute P(12), P(13), P(14), P(15) and sum ≈ 0.635  

---

### 7. Poisson Probability: Lions on Safari  
**μ=5, want P(X < 4)**  
- P = P(0) + P(1) + P(2) + P(3) using Poisson formula.  
- Result ≈ 0.2650  

---
