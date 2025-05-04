# WSJF Prioritization Tool
## A Smarter Way to Prioritize Your Projects

---

## What is WSJF?

**Weighted Shortest Job First (WSJF)** is a prioritization model used to sequence work based on:
- The potential value of the work
- The time-sensitivity of the work
- The risk reduction or opportunity enablement
- The size/effort required to complete the work

WSJF helps teams objectively decide **what to work on first** to maximize value delivery.

---

## The WSJF Formula

**WSJF = (Business Value + Time Criticality + Risk/Opportunity) ÷ Job Size**

Higher WSJF score = Higher priority

**Note**: Job Size is the denominator - larger jobs get lower priority scores!

---

## Why Use WSJF?

- **Objective Prioritization**: Reduces bias in decision-making
- **Value-Driven**: Focuses on business value and time criticality
- **Risk Reduction**: Accounts for risk mitigation
- **Transparency**: Makes prioritization decisions visible and traceable
- **Alignment**: Helps align team members on what matters most

---

## WSJF Parameters Explained

| Parameter | What it measures | Effect on Priority | Scale |
|-----------|------------------|-------------------|-------|
| **Business Value** | How valuable is this to the business? | ↑ Higher = Higher Priority | Fibonacci-like (1-21) |
| **Time Criticality** | How time-sensitive is this work? | ↑ Higher = Higher Priority | Fibonacci-like (1-21) |
| **Risk/Opportunity** | Risk reduction or opportunity enablement | ↑ Higher = Higher Priority | Fibonacci-like (1-21) |
| **Job Size** | Effort required to complete the work | ↓ Higher = Lower Priority | Fibonacci-like (1-21) |

---

## Fibonacci-like Scale

We use a Fibonacci-like scale for all parameters:

| Value | Description |
|-------|-------------|
| 1 | Minimal |
| 2 | Low |
| 3 | Medium |
| 5 | High |
| 8 | Very High |
| 13 | Extreme |
| 21 | Exceptional |

This scale helps differentiate between items and avoids false precision.

---

## Tool Demo - The Interface

Our WSJF tool provides an intuitive interface to:
- Add and evaluate projects
- Calculate WSJF scores automatically
- Visually sort priorities
- Export results for stakeholder review

Key features:
- Modern, clean design
- Color-coded priorities
- Collapsible instructions
- One-click sorting and export

---

## How to Use the Tool
* Open ` wsjf-template-tool.html ` using web browser

1. **Add projects**: Enter project/initiative names
2. **Rate each dimension**:
   - Business Value
   - Time Criticality
   - Risk/Opportunity
   - Job Size
3. **Review calculated WSJF scores**
4. **Sort by WSJF** if desired
5. **Export to CSV** for reporting

---

## Understanding Job Size's Inverse Effect

**How Job Size affects priority:**
```
Small Job + High Value = HIGHEST PRIORITY
Large Job + High Value = MEDIUM PRIORITY
Small Job + Low Value = LOW PRIORITY
Large Job + Low Value = LOWEST PRIORITY
```

**Why Job Size is in the denominator:**
- **Promotes smaller work items**: Smaller jobs with high value get higher priority
- **Faster value delivery**: Completing smaller, high-value items first delivers ROI quicker
- **Economic benefit**: Cost of Delay divided by Duration (CD3) approach
- **Reduced risk**: Smaller items typically have less implementation risk
- **Better flow**: Avoiding large work items improves team flow

---

## Tips for Effective Scoring

- **Be consistent**: Use the same scale interpretation across all projects
- **Score as a team**: Get multiple perspectives on each parameter
- **Business Value**: Consider revenue impact, cost savings, strategic alignment
- **Time Criticality**: Consider deadlines, market windows, and declining value over time
- **Risk/Opportunity**: Consider technical, business, and regulatory risks
- **Job Size**: Focus on relative sizing rather than exact time estimates - remember this LOWERS priority

---

## Benefits of Tool

- **Visual Priority Indicators**: Color-coded scores and rankings
- **Collapsible Instructions**: Focus on the data when needed
- **Intuitive Controls**: Easy sorting and reordering
- **Responsive Design**: Works on desktop and mobile devices
- **One-Click Export**: Share results with stakeholders easily
- **Clean Interface**: Focus on decision-making, not struggling with the tool

---

## Implementation Examples

### Before WSJF:
- Project selection based on who shouted loudest
- Unclear prioritization criteria
- Frequent priority changes
- Low-value work taking precedence over high-value work

### After WSJF:
- Clear, objective prioritization
- Transparent decision-making
- Focus on business value and quick wins
- Reduced debates about what to work on next

---

## Success Stories

Organizations using WSJF have reported:

- 30-40% increase in high-value feature delivery
- Reduced time spent in prioritization meetings
- Better alignment between business and development teams
- More predictable value delivery
- Improved stakeholder satisfaction

---


