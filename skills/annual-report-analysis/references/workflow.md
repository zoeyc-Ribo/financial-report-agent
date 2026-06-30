# Detailed Workflow for Annual Report Analysis

This document provides detailed step-by-step instructions for each phase of the annual report analysis process.

## CRITICAL WARNING: ALWAYS USE THE LATEST ANNUAL MATERIALS

**STOP AND READ THIS FIRST:**

Training data may be outdated. Actively search for and retrieve the MOST RECENT annual materials. Using outdated filings or prior-year annual materials is the #1 mistake in annual report analysis.

## CRITICAL: DATA SOURCE RESTRICTIONS

DO NOT use the Fetch tool on any sec.gov or edgar URLs — they block automated requests and will return 403 errors, wasting time and tokens.

**Data source priority**:
1. Company investor relations website (e.g., investor.google.com) — fetch directly from IR pages
2. SEC filings — use web search to find and read 10-K/20-F content, but NEVER fetch sec.gov URLs directly
3. Financial data aggregators (Yahoo Finance, Macrotrends, etc.) — use as supplementary or fallback sources

**FORMAT PRIORITY: HTML FIRST, PDF SECOND**
- ALWAYS prefer fetching the HTML version of earnings releases, annual results, and filings over PDF.
- Most company IR pages and financial aggregators offer HTML versions that are faster and more reliably parsed.
- Only fetch a PDF if no HTML version is available.
- If a PDF must be used: extract the text content first, verify the extracted text is substantial (at least 500 words of readable financial data), and output a 5-bullet summary of what was extracted BEFORE proceeding to analysis. If extraction fails or returns minimal text, discard the PDF and fall back to HTML or aggregator sources.

**BEFORE STARTING:**
1. **CHECK TODAY'S DATE** - Write down the current date
2. **SEARCH FOR LATEST ANNUAL MATERIALS** - Use web search to find the most recent annual results and annual filing
3. **VERIFY THE FISCAL YEAR** - Confirm the annual release and filing correspond to the requested or latest fiscal year
4. **IF THE MATERIALS ARE FOR THE WRONG YEAR** - Stop and search again

## Phase 1: Annual Data Collection and Verification

### Step 1: Identify the Latest Annual Reporting Period

**CRITICAL**: ALWAYS SEARCH FOR THE LATEST ANNUAL MATERIALS - DO NOT RELY ON KNOWLEDGE CUTOFF.  
**CRITICAL**: NEVER USE OUTDATED ANNUAL MATERIALS FROM MEMORY OR TRAINING.

### Step 1a: Search for Latest Annual Results

**MANDATORY STEP 1: CHECK TODAY'S DATE**
- Write down today's date explicitly: [Month] [Day], [Year]
- Use this to verify the annual materials are current
- Example: "Today is March 27, 2026"

**MANDATORY STEP 2: SEARCH FOR THE LATEST ANNUAL MATERIALS**
- Use web search with queries like:
  - `[Company name] latest annual report`
  - `[Company name] latest annual results`
  - `[Ticker symbol] 10-K`
  - `[Ticker symbol] 20-F`
  - `[Company name] FY2024 annual results`
- Or search the company investor relations site:
  - Go to `investor.[company].com` or `[company].com/investors`
  - Navigate to "Press Releases", "News", "Financial Results", or "SEC Filings"
  - Sort by date to find the MOST RECENT annual materials
  - Look for keywords: "annual results", "full-year results", "10-K", "20-F", "annual report"

**MANDATORY STEP 3: VERIFY THE REPORTING PERIOD**
- Read the title or heading of the document
- Confirm the fiscal year explicitly (for example: FY2024, 2024 annual report)
- Confirm the annual release and filing refer to the same fiscal year
- If the filing and the release do not match, stop and search again

**COMMON MISTAKES TO AVOID:**
- Using prior-year annual materials because they appear first in search
- Assuming the latest filing is annual without checking whether it is a 10-Q
- Confusing calendar year with fiscal year
- Using management commentary from a different reporting period
- Proceeding without confirming the exact fiscal year

**CORRECT APPROACH:**
- Check today's date first
- Search explicitly for "latest annual report" or "latest annual results"
- Read the actual title and date of the release and filing
- Confirm both documents refer to the same fiscal year
- If unsure, search again with different terms

### Step 1b: Understand the Company's Fiscal Calendar

After identifying the latest annual materials, understand the company's fiscal year structure to interpret the results correctly.

**Common fiscal year patterns:**
- **Calendar year**: fiscal year ends in December
- **Nike fiscal**: fiscal year ends in May
- **Apple fiscal**: fiscal year ends in September
- **Walmart fiscal**: fiscal year ends in January

Many companies state their fiscal year in the annual release or annual filing header. Search `[company] fiscal year end` if needed.

### Step 1c: Mandatory Verification - Verify the Correct Annual Materials Were Obtained

**DO NOT PROCEED until verifying ALL of these:**

- [ ] Today's date written down
- [ ] Actively searched using "latest annual report" or "latest annual results"
- [ ] Annual earnings release date found
- [ ] Annual filing date found
- [ ] Verified both documents refer to the same fiscal year
- [ ] Did not assume the year based on expectations alone
- [ ] Opened and read the actual release or filing confirming the fiscal year
- [ ] Confirmed this is the requested or latest annual reporting period

**RED FLAGS - If ANY of these are true, the wrong materials may have been obtained:**
- Release and filing refer to different fiscal years
- Working from memory or prior knowledge instead of current documents
- Cannot state the exact release date and filing date
- Have not opened the actual annual release or filing
- Using a quarterly filing as the main annual document
- Annual materials are clearly from the prior year when a newer annual cycle exists

**IF ANY RED FLAGS ARE PRESENT**: stop and search again.

### Step 1d: Handle Naming Variations

Companies use different terminology - recognize these patterns:

**Annual reporting terminology:**
- "FY2024", "Fiscal 2024", "Full Year 2024", "2024 Annual Report"
- "Form 10-K", "Form 20-F", "Annual Report", "Annual Results Announcement"

**Annual release titles:**
- "[Company] Reports Fiscal 2024 Results"
- "[Company] Announces Full-Year 2024 Financial Results"
- "[Company] Files Annual Report"

**SEC filing searches:**
- Company legal name may differ from common name
- Search by ticker symbol to find filings reliably
- Look for 10-K, 20-F, or annual report instead of 10-Q

### Step 2: Gather Annual Materials

After confirming the correct annual reporting period, collect the following:

**Primary Materials (REQUIRED):**
- **Annual earnings release / annual results announcement**
  - Usually on the company investor relations site under "Press Releases", "News", or "Financial Results"
  - Search patterns:
    - "[Company] FY2024 annual results"
    - "[Company] latest annual earnings release"
    - "[Company] full-year results"
  - Verify the date and fiscal year on the document itself
  - Read the actual document to confirm key reported figures

- **10-K / 20-F / annual report**
  - Search for the filing via web search or the company IR site
  - Search by ticker symbol if needed
  - Note the filing date
  - Confirm it matches the annual release year

- **Earnings call transcript / webcast / prepared remarks**
  - Search for:
    - "[Company] FY2024 earnings call transcript"
    - "[Company] annual results webcast"
  - Verify the date matches the annual results event
  - If transcript is unavailable, use webcast replay or prepared remarks

**Supplemental Materials (if available):**
- **Investor presentation / annual results slides**
- **Supplemental data file**
- **Management presentation or strategy deck**

**Reference Materials (for comparison):**
- **Prior-year annual report** - for YoY comparison
- **Multi-year historical results** - for 3-year or 5-year trend analysis
- **Prior guidance / management targets** - if referenced in the current year
- **Consensus estimates or market expectations** - only if accessible and time-appropriate
  - Use estimates that existed before the annual release when comparing expectation vs. reported result
  - If premium sources are unavailable, do not fabricate consensus

**MANDATORY VERIFICATION before proceeding to Step 3:**

**DATES AND PERIODS - Verify ALL of these:**
- [ ] Today's date written down
- [ ] Annual earnings release date recorded
- [ ] Annual filing date recorded
- [ ] Transcript / webcast / presentation date recorded when used
- [ ] All materials refer to the SAME fiscal year

**SEARCH AND ACCESS - Verify active search completed:**
- [ ] Searched for latest annual materials
- [ ] Accessed and read the actual annual release
- [ ] Accessed and read the actual annual filing
- [ ] Confirmed this is the requested or latest fiscal year
- [ ] Have core reported figures from the actual source materials
- [ ] If using expectations, have a dated and supportable source

**RED FLAGS - STOP if ANY of these are true:**
- Did not actually search for or access the annual materials
- Working from memory instead of current documents
- Filing and release refer to different fiscal years
- Cannot state the exact release date or filing date
- Using a quarterly filing as the main annual source
- Using unsupported consensus assumptions

### Step 3: Extract Key Metrics

Create a structured summary:

ANNUAL REPORTED RESULTS
─────────────────────────────────────────────────
                         FY[YEAR]      FY[YEAR-1]      YoY Change
Revenue                  $X,XXX        $X,XXX          +X.X%
Gross Margin             XX.X%         XX.X%           +XXbps
Operating Income         $XXX          $XXX            +X.X%
Operating Margin         XX.X%         XX.X%           +XXbps
Net Income               $XXX          $XXX            +X.X%
EPS                      $X.XX         $X.XX           +X.X%
Operating Cash Flow      $XXX          $XXX            +X.X%
Free Cash Flow           $XXX          $XXX            +X.X%

KEY BUSINESS METRICS
─────────────────────────────────────────────────
[Metric 1]               XXX           XXX             +X.X% YoY
[Metric 2]               XXX           XXX             +X.X% YoY
[Metric 3]               XXX           XXX             +X.X% YoY

If expectations or guidance are available, create a separate comparison section instead of mixing unsupported numbers into the main reported table.

### Step 4: Identify Key Themes from Management Commentary

Read or listen to the annual results call and note:
- Management's tone (confident, cautious, defensive, constructive)
- Key themes emphasized (demand, pricing, product mix, geographic trends, cost actions, investment priorities)
- Questions from analysts (what are investors focused on?)
- Guidance or qualitative outlook for the next year
- Any surprises or unexpected commentary
- Capital allocation priorities (buybacks, dividends, capex, acquisitions)

### Step 4a: Mandatory Intermediate Output (DO NOT SKIP)

**STOP. Before proceeding to Phase 2, output the following to the user:**

1. Today's date
2. The exact document(s) found, with URLs
3. Document type for each (earnings release, 10-K, annual report, transcript, etc.)
4. Fiscal year covered by each document
5. A 5-bullet summary of key financial figures successfully extracted from each document

**If any document's text was not successfully extracted, state this explicitly.**
**If the extracted content is insufficient for a full analysis, state what is missing and search for alternative sources before continuing.**

Do NOT proceed to Phase 2 until this intermediate output is complete.

## Phase 2: Analysis

### Step 5: Annual Performance Analysis

For EACH major reported area, explain:

**If performance was stronger than expected or stronger than prior trends:**
- What drove the outperformance?
- Was it one-time or sustainable?
- Does it change the long-term thesis?
- Does management expect it to continue?

**If performance was weaker than expected or weaker than prior trends:**
- What drove the shortfall?
- Was it company-specific or industry-wide?
- Is management taking corrective action?
- Does it weaken the long-term thesis?

**Example Format:**

■ **Revenue Growth Accelerated on Strong [segment / geography / product] Performance**

FY[YEAR] revenue of $13.5B grew 12% YoY, driven primarily by [specific driver].  
[Segment] revenue grew X% YoY, while [segment] declined X%, reflecting [reason].  
Management cited [specific products / initiatives / markets] as key drivers.  
This supports / challenges the thesis that [thesis point].

### Step 6: Segment / Geographic / Product Analysis

Analyze performance by:
- Business segment
- Geography
- Product category
- Channel or customer group, if relevant

Identify:
- What outperformed prior-year or prior-trend expectations?
- What underperformed?
- Which areas drove the annual outcome?
- What changed vs. prior years?
- What did management say about outlook for each area?

### Step 7: Profitability Analysis

Analyze profitability:
- Gross margin: up or down? why?
- Operating margin: up or down? why?
- Net margin: up or down? why?
- Cost structure and operating leverage
- Whether earnings quality improved or weakened

### Step 8: Cash Flow, Balance Sheet, and Capital Allocation Analysis

Analyze financial quality:
- Operating cash flow
- Free cash flow
- Cash and liquidity
- Debt and leverage
- Working capital if relevant
- Buybacks, dividends, capex, M&A
- Overall financial flexibility

### Step 9: Outlook and Guidance Analysis

If the company provided guidance or outlook:
- Compare new guidance to prior guidance if available
- Compare to internal assumptions and market expectations if reliable
- Assess credibility
- Identify key assumptions behind guidance

If the company did NOT provide formal guidance:
- Note this explicitly
- Provide a scenario-based outlook based on reported results and management commentary

### Step 10: Update Assumptions / Estimates

Update assumptions for:
- Next fiscal year
- Longer-term margins or cash flow if relevant
- Segment mix, growth, or capital allocation assumptions

**Show clearly:**

UPDATED ASSUMPTIONS / ESTIMATES
─────────────────────────────────────────────────
                              Prior View     Updated View     Change      Reason
FY[YEAR+1] Revenue            $XX.XB         $XX.XB           +X.X%       [Reason]
FY[YEAR+1] Operating Margin   XX.X%          XX.X%            +XXbps      [Reason]
FY[YEAR+1] EPS                $X.XX          $X.XX            +X.X%       [Reason]
FY[YEAR+1] FCF                $X.XB          $X.XB            +X.X%       [Reason]

### Step 11: Update Valuation View

Based on updated assumptions:
- Recalculate DCF or other relevant valuation framework if used
- Update comparable company multiples if relevant
- Determine whether fair value / valuation range changes
- Decide whether valuation becomes more attractive, less attractive, or unchanged

**Valuation Decision Framework:**
- If assumptions change materially -> usually update valuation view
- If assumptions change only modestly -> may maintain valuation view
- If thesis strengthens or weakens materially -> valuation framing may change even without large model changes

### Step 12: Assess Thesis Impact

Decide whether the annual results:
- Strengthened the thesis
- Left the thesis intact
- Weakened the thesis

Consider:
- Stock reaction if relevant
- Valuation relative to updated assumptions
- Business quality and competitive position
- Balance sheet strength and downside protection
- Visibility into next year

## Phase 3: Chart Generation

### Step 13: Generate 8-12 Charts

Create charts focusing on ANNUAL TRENDS and WHAT CHANGED THIS YEAR.

**REQUIRED CHARTS (8-12 total):**

1. **Annual Revenue Progression** (Bar chart)
   - Last 4-6 fiscal years
   - Highlight current fiscal year

2. **Annual EPS or Net Income Progression** (Bar chart)
   - Last 4-6 fiscal years
   - Highlight current fiscal year

3. **Annual Margin Trend** (Line chart)
   - Gross margin, operating margin, net margin
   - Last 4-6 fiscal years

4. **Revenue by Segment / Geography** (Stacked bar or table)
   - Current year vs. prior year
   - Growth rates by segment or geography

5. **Key Operating Metrics** (Line or bar chart)
   - Subscribers, ARPU, units, stores, customers, bookings, etc.

6. **Operating Cash Flow and Free Cash Flow Trend**
   - Multi-year cash generation

7. **Balance Sheet / Leverage Chart**
   - Cash, debt, or net debt / EBITDA trend where relevant

8. **Valuation Chart**
   - Historical multiple range or peer comparison

**OPTIONAL CHARTS (if space allows):**
- Multi-year return on capital
- Capital allocation bridge
- Guidance / outlook comparison
- Peer comparison
- Segment margin comparison

**Chart Style Guidelines:**
- Focus on TRENDS and CHANGES
- Highlight current-year performance
- Keep visuals simple and professional
- Use charts that support key arguments rather than decorating the report

## Phase 4: Report Creation

### Step 14: Create DOCX Report

Use DOCX capability to create an 8-12 page report.

See `report-structure.md` for complete page-by-page templates and formatting requirements.

**Key Steps:**
1. Create Page 1 with executive summary and key takeaways
2. Add annual results analysis (Pages 2-3)
3. Include business performance and financial quality (Pages 4-5)
4. Add management commentary, outlook, and thesis update (Pages 6-7)
5. Provide valuation, estimate implications, and conclusion (Pages 8-10)
6. Add appendix if needed (Pages 11-12)
7. Embed all 8-12 charts throughout
8. Add 1-3 summary tables
9. Include complete Sources section with clickable hyperlinks

### Step 15: Optional - Update XLS Model

If a full financial model exists, update it with:
- Actual FY[YEAR] reported results
- Revised assumptions for future years
- Updated valuation view

**Note**: For annual report analysis, a full XLS file is OPTIONAL. The DOCX report is the primary deliverable.

If creating XLS, include:
- Historical annual model tab
- Updated annual projections
- Revised DCF
- Updated comps analysis

## Phase 5: Quality Check and Delivery

### Step 16: Quality Checklist

Before publishing, run through the **Comprehensive Quality Checklist** in `best-practices.md`.
Also complete the **5-Minute Final Review** in `best-practices.md` as a final pass.

Do NOT deliver the report until all checklist items are verified.

### Step 17: Deliver Report

Provide the user with:

1. **DOCX file**: `[Company]_FY[Year]_Annual_Report_Analysis.docx`
2. **Chart files**: all PNG / JPG charts if needed
3. **Optional XLS**: updated financial model if maintained

**Brief summary for user:**

[Company] FY[Year] Annual Report Analysis Complete

Overall View: [POSITIVE / NEUTRAL / NEGATIVE]

Key Financial Highlights:
■ Revenue: $X.XB ([+/-]X.X% YoY)
■ EPS / Net Income: $X.XX or $X.XB ([+/-]X.X% YoY)
■ Operating Margin: X.X% ([+/-]XXbps YoY)
■ Free Cash Flow: $X.XB ([+/-]X.X% YoY)

Key Takeaways:
■ [Takeaway 1]
■ [Takeaway 2]
■ [Takeaway 3]

Outlook / Thesis:
- Management outlook: [summary]
- Thesis impact: [improving / intact / weakening]

Deliverable: 8-12 page annual report analysis with sources, charts, and valuation / outlook discussion.

