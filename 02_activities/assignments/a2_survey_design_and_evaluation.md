# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `1`

Describe the purpose of your survey:
```
This survey is designed to identify the main drivers of turnover and intent-to-leave among entry- and lower-level employees (e.g., compensation, manager support/relationship, workload, career growth, team culture). Results will be used to prioritize actionable HR and manager interventions and to assess employee satisfaction across departments and locations.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population:

All entry- and lower-level employees at the company currently employed , plus employees who voluntarily left those levels in the past 6 months.

Sampling frame:

The Human Resources Information System (HRIS) roster for current employees at those job levels, plus the HRIS termination records for voluntary leavers in the past 6 months (email contact available). Coverage issues are possible if contact information is outdated for leavers or if some employees have limited access to company email. Survey mode and frame quality can affect coverage.

Sampling units:

Individual employees (current employees and recent voluntary leavers) as listed in the HRIS frame.

Observational units:

Individual survey responses (one response per sampled employee).

Sampling strategy:

Stratified probability sample to ensure representation across departments and locations:

    Primary strata: department (e.g., Eng, Sales, Support, Ops, etc.) × location/region.

    Secondary quotas/monitoring: tenure bands (0–6 months, 6–18 months, 18–36 months) to ensure new hires are adequately represented.

    If resources allow: attempt a census of recent voluntary leavers (highly informative).

    Oversample small/high-turnover departments to ensure stable subgroup estimates, then weight back to the true composition during analysis (poststratification/weighting class logic).

Mode: primarily online (anonymous link), with reminders/follow-ups to reduce nonresponse. 
```

Your 5-10 question survey:
```
1. Employment status (single choice)
☐ Currently employed at the company
☐ Voluntarily left the company in the past 6 months
2. Overall satisfaction (single choice)
Overall, how satisfied were you with your job in your current/most recent role?
☐ Very dissatisfied ☐ Dissatisfied ☐ Neutral ☐ Satisfied ☐ Very satisfied
3. Intent to leave / reason for leaving:
If currently employed: How likely are you to look for a new job in the next 6 months?
☐ Very unlikely ☐ Unlikely ☐ Unsure ☐ Likely ☐ Very likely
If left: What was the primary reason you decided to leave? (single choice)
☐ Compensation/benefits ☐ Career growth ☐ Manager relationship ☐ Workload/burnout
☐ Team/culture ☐ Work-life balance ☐ Role fit ☐ Location/commute ☐ Other: ________
4. Pay/benefits perception (single choice)
How fair do you feel your compensation is relative to your responsibilities and market rates?
☐ Very unfair ☐ Unfair ☐ Neutral ☐ Fair ☐ Very fair
5. Manager support (single choice)
My direct manager supported my success (clear expectations, feedback, and help removing blockers).
☐ Strongly disagree ☐ Disagree ☐ Neutral ☐ Agree ☐ Strongly agree
6. Workload sustainability (single choice)
My workload was sustainable over the past 2 months of my employment.
☐ Strongly disagree ☐ Disagree ☐ Neutral ☐ Agree ☐ Strongly agree
7. Growth and development (single choice)
I had clear opportunities to grow (learning, mentorship, promotions, or meaningful skill-building).
☐ Strongly disagree ☐ Disagree ☐ Neutral ☐ Agree ☐ Strongly agree

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
Survey: Canadian General Social Survey (Cycle 33): Giving, Volunteering and Participating, 2018 (GSS GVP)

1) Sample type
- Probability sample, cross-sectional survey. 
- Stratified design with probability sampling, stratified at province/CMA level. 
- Two-stage design: (1) groups of telephone numbers as sampling units, then (2) one randomly selected eligible person (15+) per household. 
- Includes “rejective sampling” (sub-sampling) because volunteers are relatively rare: volunteers receive a long interview; non-volunteers are randomized into long vs short interview groups. 

2) Sample size
- Field sample: approximately 50,000 units. 
- About 40,000 invitation letters to the electronic questionnaire were sent; completion expectation was ~24,000 questionnaires (planned). 
- Overall response rate was 41.9% (so realized completes are materially lower than the field sample). 

3) Target population
- All persons aged 15+ living in the ten provinces; excludes full-time residents of institutions (6+ months). 

4) Sampling frame
- Frame combines landline and cellular telephone numbers from the Census and administrative sources with Statistics Canada’s dwelling frame. Records are groups of one or more telephone numbers linked to an address (or a single number if address linkage isn’t available). 

5) Survey mode(s)
- Mixed-mode: self-completed electronic questionnaire and CATI (computer-assisted telephone interviewing). 

6) Timeline
- Reference period: past 12 months preceding interview date. 
- Data collection for 2018 cycle: 2018-09-04 to 2018-12-28. 
- Program-level description also notes 2018 GSS collection from September to December 2018. 

7) Response rate
- Overall response rate: 41.9%. 

8) Weights
- Person-level analysis weight: WGHT_PER (basic person weight for estimating counts for non-institutionalized persons aged 15+). 
- Bootstrap weights were created for design-based variance estimation; bootstrap used for sampling variability estimation. 
- Weighting adjustments include:
  - adjustment for rejective sampling (non-volunteer “not rejected” respondents get a multiplicative factor), 
  - calibration/adjustment so weighted estimates are representative by certain characteristics (age-sex groups by province, monthly independent estimates), 
  - an additional nonresponse adjustment in 2018 using administrative characteristics (e.g., income, household composition) to model and adjust nonresponse. 
  - income-distribution alignment: weights adjusted so weighted income distribution matches 2017 CIS distribution by province. 

9) Data processing
- Processing used SSPE generalized processing steps/utilities; edits performed automatically and manually at macro and micro levels (family/consistency/flow edits). 
- CATI program contained range checks and built-in edits enforcing questionnaire flow; interviewer comments reviewed; head office editing applied. 
- Validation included change-over-time analysis, cross-tab checks, and comparison (“confrontation”) with other similar sources. 
- Disclosure control applied to prevent identification; suppression as needed. 

10) Cleaning, imputation, etc.
- Donor imputation was the primary method: donor records selected via a score function; ties resolved by random selection; mean imputation used where donor imputation not possible. 
- Imputation executed in multiple steps (income first, then volunteering/donation-related variables). 
- Income collection change in 2018: personal income questions not asked; income obtained via linkage to tax data (2017 T1FF) for 81.9% of respondents, with missing values imputed; family income obtained for 81.7% of households with remaining imputed. 

11) Sources of error
- Sampling error exists because results come from a sample; variance estimated via bootstrap weights. 
- Non-sampling error sources explicitly noted: imperfect coverage and nonresponse; plus response and processing errors.

12) Limitations, known biases, etc.
- Coverage limitations: households without telephones (and those not covered by the current telephone frame) are excluded from the surveyed population, which can bias results if excluded households differ systematically. 
- Nonresponse: two-stage nonresponse can occur (household and individual levels); weights adjusted to reduce nonresponse bias but cannot eliminate it.
- Mode-related considerations: the GSS program introduced multimode internet+telephone collection after the redesign; mode can create differential coverage/response patterns (e.g., who completes online vs phone). 
- Institutional population excluded by design, so results do not generalize to full-time institutional residents. 

13) Link to documentation and any additional sources used
- Main survey metadata (IMDB): 
  https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
- Program overview (GSS overview, redesign, modes): 
  https://www150.statcan.gc.ca/n1/pub/89f0115x/89f0115x2019001-eng.htm
- PUMF documentation landing page (catalogue 45-25-0011):
  https://www150.statcan.gc.ca/n1/en/catalogue/452500112021001

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
