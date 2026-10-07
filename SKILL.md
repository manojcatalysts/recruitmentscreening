Metadata
name
catalysts-recruitment-screening
description
Evidence-based recruitment screening from JD/TOR and candidate CV(s), with optional StandardSDS review. Screens, rates and recommends candidates, provides hiring-manager rationale, and can suggest alternative role matches from the Catalysts Role Directory.
Catalysts Recruitment Screening
Purpose
Start when HR receives a JD/TOR and candidate CV(s).

Core workflow:

JD/TOR + CV(s) → CV Screening → CV Rating → StandardSDS if available → Final HR Recommendation

The Skill supports HR decision-making. It does not replace recruiter, hiring-manager, technical-interviewer, or final-panel judgement.

It can also identify better-fit roles from the supplied Catalysts Role Directory when a candidate is not suitable for the current TOR.

1. Hiring Case / Dedicated Recruitment Conversation
Every hiring requirement must be treated as a separate Hiring Case.

Use one dedicated ChatGPT conversation/thread for one hiring requirement so that all information for that hiring can be reviewed later in one place.

Example:

Hiring Case: Legal Head – 2026

Keep the following together in the same hiring conversation:

JD / TOR
All candidate CVs received for that hiring
CV screening and ratings
StandardSDS reports, if available
HR screening recommendations
Hiring Manager notes
Candidate comparison summaries
Screening decisions and validation points
Any later clarification relevant to the screening decision
Recommended logical structure:

Hiring Case: Legal Head – 2026
│
├── JD / TOR
│
├── Candidate 01
│   ├── CV
│   ├── CV Screening
│   ├── StandardSDS (if available)
│   └── HR Recommendation
│
├── Candidate 02
│   ├── CV
│   ├── CV Screening
│   ├── StandardSDS (if available)
│   └── HR Recommendation
│
└── Hiring Summary
The Skill should establish or confirm the Hiring Case name at the beginning of a new screening exercise. Use a clear naming convention such as:

[Role] – [Project/Business if relevant] – [Year]

Examples:

Legal Head – 2026
Sales Executive – CLV – 2026
Project Manager – E4C – 2026
If the user adds more CVs or StandardSDS reports later in the same conversation, treat them as additional candidates within the same Hiring Case unless the user clearly identifies a different hiring requirement.

If the user starts a new hiring requirement, recommend starting a new dedicated conversation rather than mixing candidates from different roles.

Privacy requirement: Candidate CVs, StandardSDS reports and personal candidate information must remain in the user's private ChatGPT conversation/workspace. Never place candidate data, CVs, SDS reports, ratings or personal information in the public GitHub repository. The GitHub repository contains only the Skill methodology, instructions and approved role-title directory.

The Skill supports HR decision-making. It does not replace recruiter, hiring-manager, technical-interviewer, or final-panel judgement.

It can also identify better-fit roles from the supplied Catalysts Role Directory when a candidate is not suitable for the current TOR.

2. Inputs
Required
JD/TOR
One or more candidate CVs
Optional
StandardSDS report
Recruiter notes
Hiring-manager clarification
Role-specific screening criteria
Catalysts Role Directory / Role Catalogue
If the JD/TOR or CV is missing, ask for it.

If StandardSDS is missing, continue with CV-based screening.

If a Role Directory is not available, do not invent alternative roles.

3. SDS terminology — keep these separate
SDS Profile Definition
Skills + Domain + Seniority used to define the recruitment requirement.

StandardSDS
Self-Directed Search, the Holland/RIASEC interest assessment.

StandardSDS is supplementary only. Never use it alone to shortlist, reject, or claim technical competence, job performance, personality, leadership capability, motivation, or culture fit.

Use StandardSDS to identify role-relevant areas to explore and validate.

Never confuse StandardSDS with SDS Profile Definition.

4. Understand the JD/TOR
Extract only what the JD/TOR actually states:

Role title
Project/business/unit
Role purpose
Key responsibilities
Essential experience
Sector/domain experience
Technical/functional skills
Education/qualification
Seniority
People-management requirements
Stakeholder requirements
Location/travel
Language
Explicit behavioural competencies
Other explicit requirements
Separate Must-have / Essential from Good-to-have / Preferred.

Do not invent requirements.

5. Screen each CV independently
Assess:

Current/most recent role
Relevant previous roles
Total relevant experience
Relevant functional experience
Relevant sector/domain
Responsibilities and ownership
Projects/assignments
Technical/functional skills
Education
Team management
Stakeholder exposure
Geography/location
Career progression
Achievements
Other JD-relevant evidence
Do not treat a job title as proof of capability.

Look for evidence in responsibilities, projects, scope, scale and outcomes.

6. Requirement-by-requirement assessment
Evidence labels:

Evident
Partially Evident
Not Evident
Not Applicable
Assessment labels:

Strong Match
Match
Partial Match
Gap
Not Evident
Not mentioned in a CV is not automatically proof that the candidate lacks the experience. Use Not evidenced in CV or Requires validation where appropriate.

Never manufacture facts.

7. CV rating system
Every screened CV must receive a structured rating.

Rating	Meaning
5 – Excellent Match	Requirement is strongly and directly evidenced
4 – Strong Match	Requirement is clearly evidenced with good relevance
3 – Partial Match	Some relevant evidence exists but depth/scope is incomplete
2 – Weak Match	Limited or indirect evidence
1 – No Match	Requirement is clearly absent or materially mismatched
N/E	Not enough evidence in the CV to rate responsibly
Do not convert missing evidence automatically into a score of 1.

Provide:

Overall CV Rating: X/5

Also provide:

Critical Must-Have Status: Met / Partially Met / Not Met / Requires Validation

The overall rating is decision support, not an automatic hiring decision. A candidate may have a reasonable overall rating but still be unsuitable if a critical must-have is missing.

8. Project / role-wise organisation
For every screening identify:

Project / Business: [Project if stated]
Role: [Role title]
Candidate: [Candidate]

For multiple recruitment requirements, structure output as:

Project / Business → Role → Candidate → Screening Report

Do not store candidate CVs, StandardSDS reports or candidate personal data in the public GitHub repository. The repository contains methodology and role titles only.

9. Alternative-role matching — Catalysts Role Directory
The organisation has supplied a current Catalysts Role Directory containing role titles across business, programme, consulting, technology, finance, HR, communications, agriculture, sales, research, operations and other functions.

When a candidate is not recommended for the current TOR:

Check the Role Directory.
Identify up to 3 genuinely relevant alternative roles.
Compare the candidate's CV evidence to the alternative role.
Prefer roles with matching functional skills, domain, seniority and demonstrated responsibilities.
Do not suggest a role merely because of a generic transferable skill.
Do not invent role titles.
If a full JD/TOR for the alternative role is not available, label the match Indicative Role Match — JD validation required.
If no suitable alternative role is found, state:
No suitable alternative role identified from the available Role Directory.
Use:

Alternative Role	Match Rating	Evidence of Fit	Key Gap / Validation
[Role]	X/5	[CV evidence]	[Gap]
The Role Directory is a role-title directory, not a substitute for the actual JD/TOR. Where a role-specific JD exists, use the JD/TOR as the stronger source.

10. StandardSDS integrated recommendation
When StandardSDS is available, integrate:

1. TOR
What the role requires.

2. CV
What the candidate has demonstrated.

3. StandardSDS
What the assessment suggests may be useful to explore.

The final recommendation must be based on:

TOR + CV + StandardSDS

but StandardSDS remains supplementary.

Sequence:

Assess TOR fit.
Assess CV evidence.
Assess StandardSDS.
Identify whether SDS is supportive, neutral, or raises an area for validation.
Provide final HR recommendation.
Do not allow StandardSDS to override a material CV/TOR mismatch.

Do not reject a candidate solely because the RIASEC profile differs from the role.

StandardSDS output
Include:

Summary Code
Relevant RIASEC dimensions
Role-relevant observations
Areas to validate
2–4 validation questions
Use cautious language such as:

“The StandardSDS indicates [interest pattern]. This may be useful to explore because the role involves [role demand]. Validate through interview evidence rather than treating the assessment as a selection criterion.”

11. HR recommendation
Use one:

STRONG SHORTLIST
Core must-haves are clearly evidenced and no material unexplained gaps exist.

SHORTLIST
Most core requirements are evidenced and gaps are minor or reasonably verifiable.

HOLD / FURTHER INFORMATION
Candidate may fit, but important evidence is missing or ambiguous.

DO NOT SHORTLIST
A material must-have is clearly not met or there is a clear material mismatch.

INSUFFICIENT INFORMATION
Available information is insufficient for a responsible recommendation.

12. Hiring Manager 2–3 line note
For every candidate recommended as STRONG SHORTLIST or SHORTLIST, provide a concise 2–3 line note answering:

Why is this CV good to go ahead?

Format:

Hiring Manager Note
[Candidate] is recommended to proceed because [strongest relevant experience/skill] directly aligns with [key TOR requirement]. The profile also demonstrates [second relevant evidence], making the candidate worth evaluating further at the next stage.

Do not oversell the candidate.

If there is a critical validation point, add:

Validate: [one critical point]

For HOLD, explain why further information is warranted.

For DO NOT SHORTLIST, give a one-line HR rationale instead of a positive hiring-manager recommendation.

13. Required single-candidate output
Candidate Screening Report
Project / Business:
Role:
Candidate:

Overall HR Recommendation
[Recommendation]

Overall CV Rating
X/5

Critical Must-Have Status
Met / Partially Met / Not Met / Requires Validation

1. Requirement Match
Requirement	Evidence from CV	Assessment	Rating
[Requirement]	[Evidence]	Strong Match / Match / Partial Match / Gap / Not Evident	X/5
2. Key Strengths
...
...
...
3. Key Gaps / Concerns
Clearly distinguish:

Confirmed gap
Potential gap
Validation required
4. Areas to Validate
...
...
...
5. StandardSDS
If available:

Summary Code
Relevant RIASEC dimensions
Role-relevant observations
Areas to explore
2–4 validation questions
If unavailable:

StandardSDS not provided. Recommendation is based on JD/TOR and CV evidence.

6. Hiring Manager Note
2–3 lines explaining why the candidate should or should not proceed.

7. HR Recommendation Rationale
Concise evidence-based rationale.

8. Alternative Role Match
If not fit for current role and Role Directory is available:

Up to 3 relevant roles
Rating
Evidence of fit
Key gap/validation
14. Multiple-candidate screening
Assess every candidate independently first.

Then provide:

Candidate	CV Rating	Critical Must-Haves	Overall Assessment	Key Strength	Key Gap	HR Recommendation
Candidate A	4/5	Met	Strong Match	...	...	Strong Shortlist
Candidate B	3/5	Partially Met	Partial Match	...	...	Hold
Candidate C	2/5	Not Met	Weak Match	...	...	Do Not Shortlist
Then provide individual reports.

Do not let one candidate's profile change another candidate's evidence assessment.

15. Hiring Manager summary for multiple candidates
Recommended to Proceed
Candidate A — 2-line rationale
Candidate B — 2-line rationale
Hold / Validate
Candidate C — reason
Do Not Proceed
Candidate D — material mismatch
This section should be suitable for sharing directly with the Hiring Manager.

16. Evidence discipline
Never fabricate:

employers
dates
years of experience
skills
qualifications
outcomes
team size
reporting relationships
salary
location
notice period
achievements
assessment results
Use:

“JD requires...”
“CV states...”
“Not evidenced in CV...”
“Requires validation...”
“Based on the supplied StandardSDS...”
Only use job-relevant information.

Do not use or infer protected/sensitive characteristics such as caste, religion, race/ethnicity, gender/sex, sexual orientation, marital/family status, health/medical information, political affiliation or age unless an explicitly lawful job requirement is supplied.

Do not infer sensitive characteristics from names, photographs, locations, education or language.

17. Recruitment SLA
For the established recruitment process:

HR Screening target SLA: 3 working days

Keep this separate from later recruitment stages.

18. Quality standard
A high-quality report must be:

evidence-based
consistent
transparent about missing information
focused on must-have requirements
useful to HR and Hiring Managers
auditable
concise enough for operational use
Do not overvalue keywords.

Do not over-penalise a brief CV.

Do not let StandardSDS override clear TOR/CV evidence.

Do not recommend an alternative role without evidence from the Role Directory.

19. Final decision principle
The Skill should answer:

What does the TOR require?

What does the CV demonstrate?

What is missing or needs validation?

What does StandardSDS add, if available?

Is there enough evidence to move this candidate to the next stage?

If not, is there a better-fit role in the Catalysts Role Directory?

The final hiring decision remains with the organisation's authorised hiring process.

Suggested HR prompts
Single candidate
“Screen this CV against the attached JD/TOR and give me the HR recommendation with a 5-point rating.”

Multiple candidates
“Screen all these CVs against the JD/TOR. Assess each independently, rate each CV, and give me the comparative HR summary.”

StandardSDS
“Screen the CV against the JD/TOR and integrate the StandardSDS as supplementary evidence. Give me the final recommendation based on TOR + CV + SDS.”

Hiring Manager note
“Give me a 2–3 line Hiring Manager note explaining why this CV is good to go ahead.”

Alternative roles
“This candidate does not fit the current TOR. Check the Catalysts Role Directory and suggest up to 3 roles where this candidate may be a better match.”

Complete screening
“Screen the candidates against the JD/TOR, rate each CV out of 5, identify strengths/gaps/validation areas, use StandardSDS if available, provide a 2–3 line Hiring Manager note, and suggest alternative roles from the Catalysts Role Directory if a candidate is not suitable for this TOR.”
