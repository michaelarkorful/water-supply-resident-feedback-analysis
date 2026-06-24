# Water Supply & Resident Feedback Analysis

> Analyzed 129 survey responses to quantify a residential water crisis,
> identify root causes, and deliver recommendations to building ownership.
> All three recommendations were implemented.

**Type:** Survey data analysis
**Tools:** Microsoft Excel (COUNTIF, COUNTIFS, AVERAGEIF, wildcard matching, pivot tables, data visualization)
**Dataset:** 129 survey responses, 15 fields (structured ratings, multi-select categories, open text)
**Outcome:** All three recommendations implemented by building ownership

---

## Business Problem

A multi-floor residential facility in Accra, Ghana was experiencing persistent water shortages. As the facility officer, I heard complaints daily — but complaints are anecdotes. I needed data to quantify the problem, identify root causes, and present evidence-based recommendations to the building owner.

## Approach

I followed a structured analytics workflow:

1. **Business Case** — Defined the audience (building owner), the decisions on the table (second borehole vs. Ghana Water connection), and the business risk (semester lease churn if residents leave)
2. **Measurement Plan** — Mapped three business goals to specific KPIs traceable to survey columns: severity metrics, retention risk signals, and infrastructure decision data
3. **Survey Design** — Built a 15-question Google Forms survey covering shortage frequency, outage duration, activities affected, satisfaction ratings (1–5 Likert), reporting experience, and three open-text fields
4. **Data Prep & QA** — Checked for duplicates (zero found), validated rating ranges, standardized multi-select responses, and verified category consistency across all fields
5. **Analysis** — Built frequency distributions for every categorical column, calculated cross-tabulations by floor using AVERAGEIF and COUNTIFS, and manually theme-coded 90+ open-text responses
6. **Visualization** — Created six charts with intentional design: strategic color highlighting, removed clutter (gridlines, legends, borders), added data labels, and used chart type to match data story (column chart for the impact spike, horizontal bars for category comparisons)
7. **Reporting** — Assembled findings into a structured report with an executive summary, data-backed insights, and tiered recommendations

## Key Findings

- **89%** of residents experience water shortages daily
- **80%** endure outages lasting 3 hours or more
- **61%** gave the maximum negative impact score (5/5)
- Communication satisfaction collapsed to **1.6 out of 5**
- **88%** of reported issues were never resolved or went unreported
- Impact is uniformly severe across all 8 floors (avg range: 3.5 – 4.6), ruling out a pressure/distribution problem and confirming a building-wide supply shortage

## Key Insight

The primary frustration is **unpredictability, not volume**. 72% of residents said outages follow no pattern. Among those who suggested specific solutions, a water schedule was the #1 request — more than double any infrastructure option. Residents will tolerate rationing if it is predictable.

## Recommendations & Outcome

| Recommendation | Timeline | Status |
|---|---|---|
| Publish a fixed water schedule via WhatsApp | Immediate (zero cost) | Implemented |
| Drill a second borehole for backup supply | Before next semester | Implemented |
| Install multi-stage filtration system | Before next semester | Contracted |

All three recommendations were implemented after presentation to building ownership and the facility management team. The zero-cost schedule intervention addressed the #1 complaint immediately while infrastructure investments were mobilized.

## Technical Skills Demonstrated

- Survey design and data collection (Google Forms)
- Data profiling and quality assurance
- Excel formulas: COUNTA, COUNTBLANK, COUNTIF, COUNTIFS, AVERAGE, AVERAGEIF, wildcard matching
- Cross-tabulation analysis (floor × impact, floor × satisfaction)
- Qualitative theme coding of open-text responses
- Data visualization with intentional design (chart type selection, strategic color, clutter removal)
- Stakeholder communication and report writing
