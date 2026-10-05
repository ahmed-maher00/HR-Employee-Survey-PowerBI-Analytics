# HR Employee Survey Analytics (Power BI)

A 2-page Power BI report analyzing 14,725 employee survey answers
(about 1,470 respondents, 10 questions, 21 departments).

## Key Findings
- **Sheriff's Department** averages 2.46/4 vs 3.15 for the rest of the
  organization, with low scores across all roles (mainly recognition,
  growth and overall satisfaction).
- **Lowest question overall:** Q6, "I have a best friend at work" (about 2.6/4).
- **Staff score 2.97** vs 3.41 for Directors and 3.27 for Managers.
- 71.8% of answers have no role recorded. Recommendation: make "Role"
  a required field.

## What I Did
- Cleaned duplicate question labels (e.g. trailing spaces, "&" vs "and")
- Excluded "Not Applicable" and skipped answers from averages (they were coded as 0)
- Built DAX measures: Avg Score, Completion Rate, Total Answers
- Designed a 2-page dashboard with department and question filters,
  a heatmap, a role-by-question trend and written recommendations

## Tools
Power BI, DAX, Power Query

## Files
- `HR_Employee_Survey.pbix`: Power BI report


## Contact
Ahmed Maher | [LinkedIn](https://www.linkedin.com/in/ahmed-mohamed-maher-728b15113)
