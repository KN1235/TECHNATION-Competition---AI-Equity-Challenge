# TECHNATION AI Equity Data Challenge — Team Solo_Data

[📄 View Top 5 Badge Certificate](2025-11-26_ai-equity-data-challenge-top-5-en.pdf)

**Result: Top 5 Finalist** out of 86 teams (200+ post-secondary students) nationwide — TECHNATION AI Equity Data Student Challenge, Nov 2025

This repository contains our team's submission to TECHNATION's national AI Equity Data Challenge, a virtual competition exploring how AI's benefits and risks are distributed across Canada's workforce, ethnicity, gender, etc. and what policy or program response could help close the gaps.

## Team
- Khuong Nguyen
- Ha Nhi Tran
- Huong Thao Nguyen

## The Challenge

Participants were asked to analyze real labour market and demographic data, identify trends and equity impacts from AI adoption, and propose a data-driven tool, policy, or framework to address them.

## What we did

Built and cleaned multi-source datasets using Python (pandas), performed data mapping and transformation to engineer structured data integration pipelines, and conducted statistical analysis on gender and racial representation across 30+ occupations and 20+ industries. Produced data visualizations that contributed to an 80% evaluation score across both Phase 1 and Phase 2 judging rounds. Mentored by a Senior Policy Analyst at the Ontario Ministry of Education.

## What's in this repo

PHASE_1_Technation.ipynb: Data cleaning and analysis, mapping occupations to NOC categories, merging AI exposure (AIOE) scores with gender and racial labour force composition, and exporting summary tables used in the Phase 1 deck.

Phase_1_Submission.pdf: "AI at Work: Promises and Pitfalls," a data analysis of AI exposure by industry, region, gender, and race across Canada, wage premium effects, the entry-level hiring slowdown, and 2030 outlook presented under dashboard format.

Phase_2_Submission.pdf: The AIxHER policy proposal with problem framing, root-cause analysis of why women are underrepresented in AI-exposed/AI-complementary roles, benchmarking against global programs (PwC Tech She Can, Women in AI, etc.), and our proposed policy options with a decision matrix.

## Summary of our proposal: AIxHER

We proposed **AIxHER: National Inclusive AI Program**, a federally-led, provincially co-funded initiative (ISED-led, ~$150–200M over 5 years) to build structured pathways for women into AI-relevant roles through an industry consortium, apprenticeship grants, standardized micro-credentials, and employer incentives — phased from design and partnership formation through a national pilot, full expansion, and an independent evaluation.

## Data sources referenced

Our analysis draws on publicly available labour market data, including:
- U.S. Bureau of Labor Statistics, Employment Projections
- Statistics Canada (industry AI exposure, regional AI adoption, gender distribution by occupation)
- O*NET (Version 27.3) and IPUMS 2022
- OECD, UNESCO, McKinsey, HBS, and PwC reports (cited in the dashboard submissions)

Raw source CSVs are not included in this repo. If you want to rerun the notebook, download the BLS Employment Projections dataset and place it at `notebooks/Employment Projections.csv` (the path the notebook expects), or adjust the path in the first few cells.

## Notes

This was a team submission developed collaboratively under team name "Solo_Data" for TECHNATION's national program. The analysis and policy recommendations reflect our team's interpretation of the data within the competition's scope and timeline, not an official government or TECHNATION position.
