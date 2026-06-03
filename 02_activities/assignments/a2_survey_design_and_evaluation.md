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

The number of your chosen topic: `#`

Describe the purpose of your survey:
```
The purpose of this survey is to understand why entry-level and lower-level employees are leaving the company at a high rate. The survey will focus on factors such as compensation, management, workload, and career development. Ideally, results are used by Human Resources to prioritize and implement changes that improve day-to-day working conditions and longer-term job satisfaction for employees in these roles.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: all current entry-level and lower-level employees at the company across all deperatments, as well as employees in these roles who have volunarily left the company withing the past 6 months.

Sampling frame: The HR department's internal employee records (active staff) and exit interview/offboarding records (recently departed employees). These records include contact information, role level, department, and tenure.

Sampling units: Individual employees (both current and recently departed).

Observational units: Same as sampling units where each individual employee is both selected and observed directly.

The sampling strategy will be a stratified random sample, with strata defined by department and employement status (current vs. recently departed). This is to ensure that no single large department dominates the results. Including former employees is important to understand why turnover is occurring.
```

Your 5-10 question survey:
```
1. How long did you work (or have worked) in your current/most recent role at the company?
 - Less than 6 months
 - 7 to 12 months
 - 1 to 2 years
 - 2 to 3 years
 - More than 3 years

2. How satisified are/were you with your compensation (salary + benefits) relative to your responsibilities in this role?
 - Very dissatisfied
 - Dissatisfied
 - Neutral
 - Satisfied
 - Very Satisfied

3. How manageable is your current workload? 
 - Very manageable
 - Somewhat manageable
 - Neutral
 - Somewhat unmanageable
 - Very unmanageable

4. How supported do you feel by your direct manager?
 - Not supported at all
 - Rarely supported
 - Sometimes supported
 - Usually supported
 - Very well supported

5. Were there clear opportunities for advancement or skill development available to you in 
   this role?
 - No, there was no visible path forward
 - Somewhat, options existed but were hard to access
 - Yes, development opportunities were accessible and encouraged

6. Which of the following would most improve your experience at work? Choose up to three.
 - Higher pay
 - Better benefits
 - More flexible scheduling
 - Clearer promotion paths
 - Better training
 - More manageable workload
 - Better communication from managers
 - More recognition for good work
 - Better workplace culture
 - Other: ________

7. How often did you feel that your contributions were recognized or valued by the company?
 - Never
 - Rarely
 - Sometimes
 - Often
 - Almost always

8. If you have considered leaving, what is the main reason?
 - Compensation or benefits
 - Workload or stress
 - Lack of career growth or advancement
 - Poor management
 - Workplace culture
 - Scheduling or flexibility
 - Better opportunity elsewhere
 - Personal reasons
 - Other: ________
 - Not applicable

9. Is there anything specific the company could have done - or could do now - to improve your experience in this role? (Open text)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type
The 2018 GSS GVP uses a probability sample with a cross-sectional design. It uses a random stratified sample with two-stages: telephone number groups (first stage) aand one eligible individual per household is randomly selected (second stage). They also use "rejective sampling" to exclude a portion of non-volunteers from the long interview and routed them to a short interview.

2. Sample size
A field size of 50,000 units were drawn. Around 40,000 invitation letters to the electronic questionnaire were sent out to the selected households. A completed sample of 24,000 questionnaires was targeted.

3. Target population
The survey targets all people 15 years or older living in private households across the 10 Canadian provinces. It excludes full-time residents of institutions (e.g., long-term care facilities, prisons), and residents of the 3 territories.

4. Sampling frame
Landline and cellular telephone numbers that were drawn from the Census of Population and other administrative sources were combined, then this was integrated with Statistics Canada's dwelling frame. This was done in order to replace the older random digit dialing approach and to improve the coverage of cell-phone-only households, and records on the frame represent groups of telephone numbers which are linked to a single address.

5. Survey modes
This was the first survey to offer respondants an online electronic self-completion option. Data was also collected through Computer-Assisted Telephone Interviewing (CATI). Respondants could choose to complete the sruvey in English or French. The average interview length was 44 minutes long.

6. Timeline
Data collection took place between September 4, 2018 to December 28, 2018, and the data was released publicly on January 26, 2021.

7. Response rate
The response rate was 41.9%.

8. Weights
Each respondent was assigned a person-level weight which reflected the number of people in that target population they represent so that weighted totals match independent age-sex-province estimates and was also adjusted for the rejected subsampling which was applied to non-volunters. Weights were also adjusted to align with the weighted income distribution with the 2017 Canadian Income Survey by province. Bootstrap weights were also provided to support variance estimation.

9. Data processing
Data was processed using the Social Survey Processing Environment (SSPE) which is Statistics Canada's standardized framework for survey processing. Edits were applied automatically and manually including edits to flow to ensure that respondents followed the correct skip logic and consistency. Range checks were also built into the CATI system. Quality control/validation included analysis of changes over time, and cross-tabulations.

10. Cleaning, imputation, etc.
Nearest-neighbor donor imputation was used to address missing values where each record with the missing data (recipient) was matched against a pool of complete records (donors) using a scoring function where the best-matching donor's values wre used to fill in the gaps. Mean imputation was used in cases where donor imputation was not possible. Imputation was carried out sequentially covering personal and family income, formal volunteering variables, informal volunteering variables, and donation-related variables. For income, the survery used tax records (2017 T1 Family File) which were linked to 81.9% of respondents, with imputation covering the remainder.

11. Sources of error
Sampling error and non-sampling error are both present. For sampling error, results from a sample will differ from what a full census would produce. For non-sampling error, this could have included non-response error, coverage error, response error, processing error (e.g., mistakes in data entry, coding). 

12. Limitations and known biases
The 2018 cycle was the first to offer an online response option and so results may not be directly comparable to previous interations of the survey. StatCan does caution against comparing the 2018 estimates with earlier cycles. The telephone and dwelling-based frame excludes people without a phone or a stable address, which may underocutn vulnerable/marginalized groups. First Nations people living on reserve and residents of the territories are excluded entirely. Non-response bias (<50% response rate, voluntary) may introduce results that are systematically more different from those who didn't complete the survey.

13. Links to documentation and additional sources
 - Survey methodology and data accuracy (Statistics Canada IMDB record for Cycle 33, 2018):
 https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234

 - Summary of changes across GSS GVP cycles:
 https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getMainChange&Id=143876

 - The Daily release announcement (January 26, 2021):
 https://www150.statcan.gc.ca/n1/daily-quotidien/210126/dq210126h-eng.htm
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