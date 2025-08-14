# VV Latam Registration Form A/B Test

**Date of Analysis:** 14 Aug 2025  
**Analyst:** Ashkan Pirasteh Far  
**Dataset:** 702 total sessions, 347 unique users before filtering

---

## 1. Test Overview

This A/B test compared two versions of the VidaVegas Chile/Latam registration page:

- **Variant A:** With header and footer  
- **Variant B:** Without header and footer  

**Goal:** Determine whether removing the header/footer improves registration or deposit conversion rates.

---

## 2. Data Preparation

- **Primary metric view:** User-level (first session per user) to avoid inflating conversion rates from repeat sessions.
- **Cross-contamination:** No users appeared in both variants.
- **Device breakdown:** ~95% of traffic from smartphones.
- **High-frequency user filtering:** Removed 15 users with more than 5 sessions to avoid skew.

**Remaining sample size:** 332 users.

---

## 3. Key Metrics (User-Level)

| Metric                    | Variant A | Variant B | Difference (B–A) | p-value | 95% CI (diff)         | Significant? |
|---------------------------|-----------|-----------|------------------|---------|-----------------------|--------------|
| Registration Submitted    | 29.59%    | 30.68%    | +1.09%           | 0.829   | -11.0% → +8.78%       | ❌ No         |
| Registration Completed    | 31.95%    | 36.81%    | +4.86%           | 0.351   | -15.07% → +5.35%      | ❌ No         |
| Registration Failed       | 6.51%     | 6.75%     | +0.24%           | 0.930   | -5.59% → +5.11%       | ❌ No         |
| First Deposit Completed   | 2.96%     | 1.84%     | -1.12%           | 0.507   | -2.17% → +4.40%       | ❌ No         |

---

## 4. Sessions & Users After Filtering

| Variant | Sessions | Users |
|---------|----------|-------|
| A       | 176      | 176   |
| B       | 171      | 171   |

---

## 5. Interpretation

- No statistically significant differences in any primary conversion metric.
- Confidence intervals are wide enough to include both positive and negative effects, meaning the dataset does not rule out the possibility of either variant being better — but no strong signal exists.
- Removing header and footer did not materially improve conversions. Observed differences are small and inconsistent.
- This test targeted a low-leverage change — removing visual chrome — which rarely impacts core conversions unless the header/footer is causing major UX issues.

---

## 6. Conclusion

From a statistical and practical standpoint, **this A/B test did not produce evidence that removing the header/footer improves user registrations or deposits**.

Given the high similarity between variants and the negligible effect sizes, **future testing resources should focus on high-impact hypotheses** such as:

- Copy changes  
- Field reduction  
- Mobile-first optimizations  

---
