<!--
author:   ICoBC - International Council on Badges and Credentials
email:    info@icobc.net
version:  1.0.0
language: en
narrator: UK English Female
comment:  A practice course in which HR, academy and executive teams turn credential and skills data into a skills supply and demand view, a build, buy or borrow gap decision, a job architecture link and a governed data approach.

@style
:root { --icobc-navy:#02375B; --icobc-orange:#F78222; --icobc-cyan:#5DCAE7; --icobc-lime:#B1CF37; --icobc-mist:#F1F5F8; --icobc-line:#D8E2E9; --icobc-muted:#4F6576; }
body { font-family: "Open Sans", Arial, sans-serif; }
h1, h2, h3, h4 { color: var(--icobc-navy); }
a { color: var(--icobc-navy); }
table th { background: var(--icobc-mist); color: var(--icobc-navy); }
blockquote { border-left: 4px solid var(--icobc-orange); background: var(--icobc-mist); padding: 8px 16px; }
@end
-->

# Workforce Planning with Skills and Credential Data

**From credential data to workforce decisions.**

## About this course

This course is part of the ICoBC Credentialing Skills Framework (ICSF). It develops the skill "Skills-based talent practice" (VRITE pillar: Impact) at level L4 "Assure", stage A "Ability". At this level you lead skills-based practice across an organisation and connect credentials with job architecture and workforce planning. At the Ability stage you practise on realistic tasks in a controlled setting. You work with cases and sample data, not with live employee records.

**Who it is for**

- HR, talent acquisition and mobility teams (C2)
- Executive sponsors such as the CHRO, CLO and CDO (C4)
- L&D and corporate academy leads (C1)

**Prerequisite:** ICB-P16 Skills-Based Hiring and Internal Mobility with Credentials. You should already know how credentials act as an evidence layer for hiring and mobility decisions.

**Learning outcomes**

After this course you can:

1. Build a view of skills supply and demand using credential data.
2. Identify gaps and choose between building, buying and borrowing skills.
3. Connect credentials with job architecture.
4. Govern skills data quality and privacy.

**Workload.** The course is a blended cohort programme with 10 hours of notional learning. This file covers the self-paced part. Live and workshop elements appear as facilitator notes.

**How it is assessed.** You produce a skills gap analysis for one job family. A person assesses it with the rubric in the section "Assessment and badge". You also answer a final knowledge check. Nothing in this file grades your task.

**Badge.** On successful completion you earn the badge "Workforce Planning with Skills and Credential Data (Ability, L4)", alignment code ICSF-TALN-L4-A. The badge evidence is your gap analysis.

| Outcome | Module | How it is assessed |
|---|---|---|
| 1. Build a view of skills supply and demand using credential data | Skills data | Supply and demand section of the gap analysis; knowledge check |
| 2. Identify gaps and choose between building, buying and borrowing skills | Gap analysis | Gap and build, buy, borrow section of the gap analysis; knowledge check |
| 3. Connect credentials with job architecture | Job architecture | Job architecture link section of the gap analysis; knowledge check |
| 4. Govern skills data quality and privacy | Governance | Data quality and privacy section of the gap analysis; knowledge check |

**Status of topics in this course**

- Skills-based hiring and internal mobility: established. It is widely discussed and practice varies. Credentials provide the evidence layer.
- AI skills inference: emerging. It is common in HR software. It may fall under high-risk use when used for employment decisions.

Status as of November 2026; check before publishing.

**Case used throughout.** You work as a workforce planning lead at the corporate academy of a fictional mid-sized logistics and manufacturing group called Nordhafen Group. All names and numbers are illustrative.

<details>
<summary>Facilitator notes</summary>

Run a 45-minute kick-off session before learners start the self-paced part. Introduce the Nordhafen case, the four modules and the assessment task. Ask each learner to choose one job family for their own gap analysis. Suggest job families with at least 20 roles in the sample data. If learners bring real organisational data, remind them to remove personal data before sharing it with the cohort.

</details>

## Skills data

### From credentials to a skills inventory

Workforce planning asks a simple question: which skills do we have, and which do we need? Credential data helps answer the first half. A credential, such as a digital badge, a certificate or a degree record, is evidence that a person was assessed against a standard. Each credential can carry skills information: a skill name, a level, an issuer and a date.

A skills inventory collects this information across the workforce. Credential data is only one source. Other sources include self-assessments, manager ratings, project records, learning records and, in some organisations, skills inferred by software. Each source has a different strength of evidence.

A useful way to think about evidence is a ladder:

- **Assessed and verifiable:** a credential from a known issuer, with a defined standard and a verification link.
- **Observed:** a manager or peer confirms the skill in real work.
- **Claimed:** the employee states the skill in a profile.
- **Inferred:** software suggests the skill from text or activity.

Your inventory should record the evidence type next to every skill record. Without it, a planning view mixes strong and weak data and gives a false sense of certainty.

### Building the supply view

Supply is the number of people who hold a skill at a defined level, now and in the near future. To build it, follow these steps.

1. Choose a skills taxonomy or framework. Use one common vocabulary. If your organisation has several, map them to one reference.
2. Collect skills records from each source and tag them with the evidence type.
3. Remove duplicates and match skill names to the common vocabulary.
4. Count people per skill and level. Count only records that meet your evidence rule, for example "assessed or observed".
5. Adjust for time. Credentials expire or become outdated. Include expected leavers, retirements and planned moves.

Supply is a range, not a single figure. State your assumptions next to the number.

### Building the demand view

Demand is the number of people with a skill at a level that the business needs. It comes from strategy, not from the inventory. Sources include the business plan, project pipelines, product roadmaps, regulatory changes and job requisitions. Translate each plan item into skills and headcount. For example, a new automated warehouse needs people who can maintain robotic systems.

Demand is always uncertain. Use scenarios, such as a base case and a growth case, rather than one forecast.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Skills supply and demand chart for four skills</title>
  <desc>A grouped bar chart comparing illustrative supply and demand for four skills at Nordhafen Group. Data analysis: supply 40, demand 55. Robotics maintenance: supply 12, demand 30. Safety management: supply 60, demand 55. Customer service: supply 45, demand 40. Supply bars are navy and demand bars are orange. Robotics maintenance shows the largest shortfall.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <text x="400" y="34" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="18" fill="#02375B" font-weight="bold">Skills supply and demand (illustrative headcount)</text>
  <line x1="80" y1="360" x2="760" y2="360" stroke="#D8E2E9" stroke-width="2"/>
  <line x1="80" y1="80" x2="80" y2="360" stroke="#D8E2E9" stroke-width="2"/>
  <text x="70" y="364" text-anchor="end" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">0</text>
  <text x="70" y="224" text-anchor="end" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">30</text>
  <text x="70" y="84" text-anchor="end" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">60</text>
  <line x1="80" y1="220" x2="760" y2="220" stroke="#D8E2E9" stroke-width="1"/>
  <line x1="80" y1="80" x2="760" y2="80" stroke="#D8E2E9" stroke-width="1"/>
  <!-- Data analysis: supply 40 -> 187, demand 55 -> 257 (scale 4.67 px per unit) -->
  <rect x="120" y="173" width="50" height="187" rx="6" fill="#02375B"/>
  <rect x="176" y="103" width="50" height="257" rx="6" fill="#F78222"/>
  <text x="145" y="164" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">40</text>
  <text x="201" y="94" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">55</text>
  <text x="173" y="384" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Data analysis</text>
  <!-- Robotics: supply 12 -> 56, demand 30 -> 140 -->
  <rect x="290" y="304" width="50" height="56" rx="6" fill="#02375B"/>
  <rect x="346" y="220" width="50" height="140" rx="6" fill="#F78222"/>
  <text x="315" y="295" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">12</text>
  <text x="371" y="211" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">30</text>
  <text x="343" y="384" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Robotics maintenance</text>
  <!-- Safety: supply 60 -> 280, demand 55 -> 257 -->
  <rect x="460" y="80" width="50" height="280" rx="6" fill="#02375B"/>
  <rect x="516" y="103" width="50" height="257" rx="6" fill="#F78222"/>
  <text x="485" y="71" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">60</text>
  <text x="541" y="94" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">55</text>
  <text x="513" y="384" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Safety management</text>
  <!-- Customer service: supply 45 -> 210, demand 40 -> 187 -->
  <rect x="630" y="150" width="50" height="210" rx="6" fill="#02375B"/>
  <rect x="686" y="173" width="50" height="187" rx="6" fill="#F78222"/>
  <text x="655" y="141" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">45</text>
  <text x="711" y="164" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">40</text>
  <text x="683" y="384" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Customer service</text>
  <rect x="520" y="400" width="18" height="18" rx="3" fill="#02375B"/>
  <text x="546" y="414" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Supply (people)</text>
  <rect x="660" y="400" width="18" height="18" rx="3" fill="#F78222"/>
  <text x="686" y="414" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Demand</text>
</svg>

*Figure: an illustrative supply and demand view. The numbers are invented for teaching.*

### Worked example and practice

**Worked example: Nordhafen's first supply view**

Amira Okafor leads workforce planning at the Nordhafen corporate academy. The board plans to automate one warehouse within 18 months. She needs a supply view for "robotics maintenance".

1. She picks the group's skills taxonomy and maps the academy's badge skills to it.
2. She pulls three sources: academy badge records, manager-confirmed skills from performance reviews, and self-declared skills in the HR profile.
3. She tags each record: badge records as "assessed", manager records as "observed", self-declared as "claimed".
4. Her evidence rule is "assessed or observed". Under this rule she counts 12 people at working level. If she counted claimed skills too, the figure would be 31.
5. She reports supply as "12 confirmed, up to 31 if claims are verified" and adds a note that two of the 12 retire within the planning period.
6. Demand from the automation project is 30 people at working level. The shortfall is between 18 and 19 on the confirmed figure.

Amira shows the range, because the choice of evidence rule changes the answer. All numbers are illustrative.

**Practice activity: Build a supply and demand view**

You receive a small sample table (provided by your facilitator or created from the model below) for one job family with 20 to 30 people. Each row lists a person ID, a skill, a level, a source (badge, manager, self-declared, inferred) and a date.

1. Define your evidence rule in one sentence.
2. Count supply for three skills under your rule and under a looser rule.
3. Write demand for the same three skills from a short business scenario.
4. Present supply and demand in a table, with a range for supply and a note on assumptions.

Keep this table. It becomes part of your assessed gap analysis.

<details>
<summary>Facilitator notes</summary>

Provide a synthetic dataset of 25 records with no real names. Include some duplicates, two expired credentials and three inferred skills so that learners must make evidence decisions. In the live workshop (60 minutes), pairs compare their evidence rules and discuss how the rule changes the supply figure. Point out that no rule is correct in every case. The rule must fit the risk of the decision.

</details>

### Check your understanding: Skills data

**Question 1.** A planner counts every skill that employees entered in their own profiles as confirmed supply. What is the main risk?

[( )] The count will be too low because employees under-report.
[(X)] The supply view mixes claimed skills with assessed skills and may overstate capacity.
[( )] The view will break the common taxonomy.
[( )] The credentials in the data will lose their validity.
****
Self-declared skills are at the bottom of the evidence ladder. Counting them as confirmed supply hides uncertainty. Record the evidence type and apply an evidence rule.
****

**Question 2.** Where does the demand side of a skills view mainly come from?

[( )] The skills inventory of current employees.
[( )] The credentials that employees already hold.
[(X)] Business strategy, project pipelines and regulatory needs, translated into skills and headcount.
[( )] Skills inferred by software from employee emails.
****
Demand describes what the business needs, so it starts from strategy and plans, not from today's inventory.
****

**Question 3.** Why should supply be reported as a range?

[( )] Because credentials never contain level information.
[( )] Because ranges are required in every taxonomy.
[(X)] Because the result depends on the evidence rule and on assumptions such as leavers and expiry.
[( )] Because a single number is not allowed in workforce planning.
****
Different evidence rules and time assumptions produce different counts. A range with stated assumptions is more honest and more useful for decisions.
****

**Question 4.** A credential in your data expired two years ago. How should you treat it in the supply view?

[( )] Count it fully, because the person earned it.
[( )] Delete the person's record.
[(X)] Flag it, apply your rule on validity, and count it only if your rule allows lapsed credentials with other evidence.
[( )] Replace it with an inferred skill.
****
Credentials have validity rules. Your evidence rule should say how lapsed credentials are handled so that results are consistent.
****

## Gap analysis

### Defining and sizing the gap

A skills gap is the difference between the demand for a skill and the supply of that skill at a defined level and time. A gap analysis puts supply and demand side by side and decides what to do about the difference.

Good gap analysis answers five questions for each skill:

1. How large is the gap, and in which period?
2. How critical is the skill for the business?
3. How quickly can the gap close by different routes?
4. What does each route cost, and what risk does it carry?
5. Who owns the decision?

Not every gap deserves action. Rank gaps by two factors: business criticality and size. A small gap in a critical safety skill may matter more than a large gap in a skill that is easy to source.

Also look for surpluses. A skill with more supply than demand is a source of internal mobility. Surpluses can fill gaps elsewhere through reskilling, which links back to your work in ICB-P16.

### Build, buy or borrow

Three routes close a gap.

- **Build:** develop current employees through learning, credentials, projects and mentoring. This route is often slower to start, builds loyalty and uses the corporate academy.
- **Buy:** hire people from the external market. This route can be fast for common skills, but costs more and carries onboarding risk.
- **Borrow:** use contractors, partners, consultants or temporary assignments. This route gives flexibility and speed. Knowledge may leave when the contract ends.

Use clear decision criteria. Typical criteria are time to fill, cost, availability in the market, strategic importance, how long the need will last and the risk of losing knowledge. A skill needed for two years only may suit borrowing. A skill that is core to your future products usually suits building, with some buying to start.

Most gaps use a mix. For example, buy two senior specialists to lead, build ten technicians through a credential programme and borrow a vendor-neutral integration partner for the first six months.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Decision flow for build, buy or borrow</title>
  <desc>A flow chart. Start with a skills gap. First question: is the need long term and strategic? If yes, lean towards build, with buying to start. If no, second question: is the skill available in the market quickly? If yes, buy for permanent needs or borrow for short needs. If no, borrow through partners or build slowly. Three outcome boxes are labelled Build, Buy and Borrow.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#F1F5F8"/>
  <rect x="300" y="20" width="200" height="50" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="51" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#FFFFFF">Skills gap identified</text>
  <line x1="400" y1="70" x2="400" y2="110" stroke="#02375B" stroke-width="2"/>
  <rect x="270" y="110" width="260" height="60" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="136" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Is the need long term</text>
  <text x="400" y="156" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">and strategic?</text>
  <line x1="270" y1="140" x2="150" y2="140" stroke="#02375B" stroke-width="2"/>
  <line x1="150" y1="140" x2="150" y2="300" stroke="#02375B" stroke-width="2"/>
  <text x="210" y="132" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Yes</text>
  <rect x="50" y="300" width="200" height="90" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="150" y="332" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="18" fill="#02375B" font-weight="bold">Build</text>
  <text x="150" y="356" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Develop staff, buy a few</text>
  <text x="150" y="376" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">leaders to start</text>
  <line x1="530" y1="140" x2="650" y2="140" stroke="#02375B" stroke-width="2"/>
  <text x="590" y="132" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">No</text>
  <rect x="540" y="160" width="220" height="60" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <line x1="650" y1="140" x2="650" y2="160" stroke="#02375B" stroke-width="2"/>
  <text x="650" y="186" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Is the skill quickly</text>
  <text x="650" y="206" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">available in the market?</text>
  <line x1="590" y1="220" x2="590" y2="300" stroke="#02375B" stroke-width="2"/>
  <text x="570" y="262" text-anchor="end" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Yes</text>
  <rect x="470" y="300" width="200" height="90" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="570" y="332" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="18" fill="#02375B" font-weight="bold">Buy</text>
  <text x="570" y="356" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Hire for permanent need</text>
  <text x="570" y="376" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">(borrow if short term)</text>
  <line x1="710" y1="220" x2="710" y2="300" stroke="#02375B" stroke-width="2"/>
  <text x="730" y="262" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">No</text>
  <rect x="640" y="300" width="150" height="90" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="715" y="332" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="18" fill="#02375B" font-weight="bold">Borrow</text>
  <text x="715" y="356" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Partners or</text>
  <text x="715" y="376" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">contractors</text>
  <text x="400" y="430" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">A starting guide only. Real decisions combine routes.</text>
</svg>

*Figure: a simple decision flow for the build, buy or borrow choice.*

### AI skills inference in gap analysis

Some HR software infers skills from text such as CVs, job descriptions and project records. This practice is common in HR software and is an emerging topic. Inference can fill gaps in an inventory quickly. It also carries risks. Inferred skills sit at the bottom of the evidence ladder. They may be wrong, they may carry bias from training data, and employees may not know that the inference happens.

Treat inferred skills as hints for review, not as facts. When you use inferred data in gap analysis, label it, keep it separate from assessed data and test a sample against human judgement. When inference supports decisions about hiring, promotion, task allocation or dismissal, it may fall under high-risk use. In that case legal and regulatory duties can apply, such as human oversight, transparency and documentation. Ask your legal and data protection colleagues which rules apply to you. <!-- VERIFY: check the current status and application dates of the EU AI Act provisions on employment-related high-risk systems before publishing. -->

Status as of November 2026; check before publishing.

### Worked example and practice

**Worked example: Closing the robotics maintenance gap**

Amira's analysis shows a shortfall of about 18 people in robotics maintenance within 18 months. She works through the five questions.

1. **Size and period:** 18 people, needed by month 18. A first group of 6 is needed by month 9 for commissioning.
2. **Criticality:** high. The warehouse cannot run safely without them.
3. **Speed:** buying from the market is possible for 4 experienced technicians, but the market is tight. Building takes about 12 months for technicians with an electrical background.
4. **Cost and risk:** buying is expensive and slow to onboard. Building is cheaper per person but misses the month 9 target. Borrowing from an integrator gives immediate capacity but leaves knowledge outside the company.
5. **Owner:** the head of operations owns the decision, with the academy and HR as advisers.

Her recommendation, with illustrative numbers: buy 4 experienced technicians to lead, borrow 6 contractors for months 1 to 12, and build 14 technicians from the surplus pool of 25 warehouse operators through an assessed credential programme. She also notes a surplus in manual picking skills as a source for the build route.

**Practice activity: Choose a route for three gaps**

Use your supply and demand view from the first module.

1. Pick three gaps from your table. Include one critical gap and one surplus.
2. For each gap, answer the five gap analysis questions in one or two lines.
3. Choose build, buy, borrow or a mix, and give two criteria for your choice.
4. Write one sentence on how you would treat inferred skills data if it were in your sources.

<details>
<summary>Facilitator notes</summary>

In the live workshop (90 minutes), run a role play. Learners take roles of CHRO, head of operations, academy lead and finance partner, and negotiate the route for one gap. Give each role a different priority: speed, cost, knowledge retention and fairness. Afterwards, discuss which criteria changed the outcome. Remind learners that the recommended mix is a judgement and must be documented with its assumptions.

</details>

### Check your understanding: Gap analysis

**Question 1.** A skill is needed for only nine months, and the market can supply it quickly. Which route fits best?

[( )] Build, because training always gives the best long-term value.
[( )] Buy, with permanent contracts.
[(X)] Borrow, for example through contractors or partners.
[( )] Do nothing and wait for inferred skills data.
****
For a short, time-limited need that the market can meet, borrowing gives speed and flexibility without a permanent commitment.
****

**Question 2.** Which factor should rank a small gap above a large gap?

[( )] The small gap has more inferred skills data.
[(X)] The small gap concerns a skill that is critical to safety or core operations.
[( )] The small gap was found first.
[( )] The small gap is cheaper to report.
****
Rank gaps by business criticality as well as by size. A small gap in a critical skill can carry more risk than a large gap in a skill that is easy to source.
****

**Question 3.** What is the most appropriate use of AI-inferred skills in a gap analysis?

[( )] Treat them as confirmed supply, because software is consistent.
[( )] Use them as the only source for promotion decisions.
[(X)] Label them as inferred, keep them apart from assessed data and review a sample with human judgement.
[( )] Hide them from employees to avoid questions.
****
Inferred skills are hints. They may be wrong or biased. Label them, review them and be transparent. Use in employment decisions may be high-risk and needs legal advice.
****

**Question 4.** Why does a surplus of one skill matter in gap analysis?

[( )] It proves that the training budget is too high.
[( )] It means the taxonomy is wrong.
[(X)] It can be a source of internal mobility and reskilling for gaps elsewhere.
[( )] It must be removed from the inventory.
****
Surpluses show where people could move or reskill. This supports the build route and links to internal mobility practice.
****

## Job architecture

### What job architecture is

Job architecture is the structure that organises jobs in an organisation. It usually defines job families, job functions, career levels and job profiles. A job family groups related roles, for example "Warehouse operations". A level shows the scope and complexity of work. A job profile describes the purpose, tasks and requirements of a role.

Traditional job architecture describes jobs by titles, tasks and qualifications. A skills-based approach adds skills to the profile: which skills the job needs, at which level, and which are essential or desirable. This gives workforce planning a common language. Demand from business plans can be written as jobs and skills. Supply from credentials and other evidence can be matched to the same skills.

### Attaching skills and credentials to jobs

To connect credentials with job architecture, work in four steps.

1. **Define skills per job profile.** For each profile, list the core skills and the level needed. Keep the list short. Five to ten core skills per profile is usually enough.
2. **Distinguish requirement types.** Mark each skill as essential at entry, essential within a set period, or desirable. This avoids rejecting people for skills they can learn on the job.
3. **Link credentials as evidence.** For each skill, list which credentials count as evidence. Use ones with a clear standard and a known issuer. Accept equivalents. Where no credential exists, name other evidence such as a work sample or manager observation.
4. **Link profiles into pathways.** Show how skills carry between profiles. A path from "Warehouse operator" to "Robotics maintenance technician" shares some skills and needs a few new ones. These pathways support mobility and make the build route visible.

Credentials are evidence of a skill. They do not replace judgement. Completing a course or earning a badge does not prove that a person can do a whole job. Treat credentials as one input to selection and development decisions.

Avoid two common mistakes. The first is to list too many skills per job, which makes profiles unusable. The second is to turn a credential into a hard barrier when other valid evidence exists.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Job architecture with skills and credentials attached</title>
  <desc>A hierarchy diagram. At the top is the job family Warehouse operations. Below are three job profiles: Warehouse operator, Robotics maintenance technician and Warehouse team lead. Under the technician profile are three skills: Mechatronics basics, Robot fault diagnosis and Safety management. Each skill links to a credential evidence box labelled Credential evidence: assessed badge, Work sample and Manager observation. Colours show roles: navy for the core job structure, cyan for education provider credentials and orange for the employer observation.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#FFFFFF"/>
  <rect x="280" y="20" width="240" height="50" rx="6" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="51" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#FFFFFF">Job family: Warehouse operations</text>
  <line x1="400" y1="70" x2="400" y2="95" stroke="#02375B" stroke-width="2"/>
  <line x1="130" y1="95" x2="670" y2="95" stroke="#02375B" stroke-width="2"/>
  <line x1="130" y1="95" x2="130" y2="120" stroke="#02375B" stroke-width="2"/>
  <line x1="400" y1="95" x2="400" y2="120" stroke="#02375B" stroke-width="2"/>
  <line x1="670" y1="95" x2="670" y2="120" stroke="#02375B" stroke-width="2"/>
  <rect x="30" y="120" width="200" height="50" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="130" y="143" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Job profile:</text>
  <text x="130" y="161" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Warehouse operator</text>
  <rect x="290" y="120" width="220" height="50" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="143" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Job profile: Robotics</text>
  <text x="400" y="161" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">maintenance technician</text>
  <rect x="570" y="120" width="200" height="50" rx="6" fill="#F1F5F8" stroke="#02375B" stroke-width="2"/>
  <text x="670" y="143" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Job profile:</text>
  <text x="670" y="161" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Warehouse team lead</text>
  <line x1="400" y1="170" x2="400" y2="195" stroke="#02375B" stroke-width="2"/>
  <line x1="170" y1="195" x2="630" y2="195" stroke="#02375B" stroke-width="2"/>
  <line x1="170" y1="195" x2="170" y2="215" stroke="#02375B" stroke-width="2"/>
  <line x1="400" y1="195" x2="400" y2="215" stroke="#02375B" stroke-width="2"/>
  <line x1="630" y1="195" x2="630" y2="215" stroke="#02375B" stroke-width="2"/>
  <rect x="70" y="215" width="200" height="50" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="170" y="237" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Skill: Mechatronics</text>
  <text x="170" y="255" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">basics</text>
  <rect x="300" y="215" width="200" height="50" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="237" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Skill: Robot fault</text>
  <text x="400" y="255" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">diagnosis</text>
  <rect x="530" y="215" width="200" height="50" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="630" y="237" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Skill: Safety</text>
  <text x="630" y="255" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">management</text>
  <line x1="170" y1="265" x2="170" y2="305" stroke="#02375B" stroke-width="2"/>
  <line x1="400" y1="265" x2="400" y2="305" stroke="#02375B" stroke-width="2"/>
  <line x1="630" y1="265" x2="630" y2="305" stroke="#02375B" stroke-width="2"/>
  <rect x="50" y="305" width="240" height="70" rx="6" fill="#5DCAE7" stroke="#02375B" stroke-width="2"/>
  <text x="170" y="333" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Evidence: assessed badge</text>
  <text x="170" y="353" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">from an education provider</text>
  <rect x="280" y="305" width="240" height="70" rx="6" fill="#F78222" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="333" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Evidence: work sample or</text>
  <text x="400" y="353" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">manager observation</text>
  <rect x="510" y="305" width="240" height="70" rx="6" fill="#B1CF37" stroke="#02375B" stroke-width="2"/>
  <text x="630" y="333" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">Evidence: certificate from a</text>
  <text x="630" y="353" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">professional association</text>
  <text x="400" y="420" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#4F6576">Skills attach to profiles. Credentials and other evidence support each skill.</text>
</svg>

*Figure: job architecture with skills and evidence attached to one profile.*

### Worked example and practice

**Worked example: Writing the robotics technician profile**

Tomasz Nowak, an HR business partner at Nordhafen, works with Amira to add skills to the new profile "Robotics maintenance technician".

1. He lists six core skills: mechatronics basics, robot fault diagnosis, preventive maintenance, safety management, technical documentation and teamwork on shift.
2. He sets requirement types. Mechatronics basics and safety management are essential at entry. Robot fault diagnosis is essential within 12 months. Technical documentation is desirable.
3. For each skill he lists evidence. Safety management accepts an assessed academy badge, an equivalent certificate from a professional association or a manager-observed work sample. He writes "accept equivalents" in the profile.
4. He draws a pathway from "Warehouse operator". The operator already holds safety management and teamwork. The gaps are mechatronics basics and fault diagnosis. These become the learning outcomes for the academy's build programme.
5. He records that the badge is evidence for one skill and not a statement that the holder can perform the whole job. Hiring and promotion decisions also use interviews and work samples.

**Practice activity: Attach skills and credentials to one profile**

Choose one job profile from your job family.

1. List five to eight core skills with levels.
2. Mark each as essential at entry, essential within a period or desirable.
3. For each essential skill, name acceptable evidence, including at least one non-credential option.
4. Draw or describe one pathway from a neighbouring profile and list the skills gap along that pathway.

<details>
<summary>Facilitator notes</summary>

In the live workshop (60 minutes), learners swap profiles in pairs and review each other's work. Reviewers check for three faults: too many skills, credentials treated as hard barriers and missing equivalents. Encourage learners to compare their pathway skills gaps with the gaps from the second module. Mismatches show where the analysis needs to be revised.

</details>

### Check your understanding: Job architecture

**Question 1.** What is the main benefit of attaching skills to job profiles for workforce planning?

[( )] It removes the need for job families.
[(X)] Demand and supply can be written in one common language of skills.
[( )] It guarantees that every employee is perfectly matched to a job.
[( )] It replaces interviews and work samples.
****
Skills in job profiles give planners a shared vocabulary. Demand from business plans and supply from evidence can be compared on the same skills.
****

**Question 2.** A profile lists "essential within 12 months" for a skill. What is the purpose of this requirement type?

[( )] To hide the skill from candidates.
[( )] To make the skill optional forever.
[(X)] To avoid rejecting candidates for skills that can be learned on the job within a defined period.
[( )] To replace the credential with an inferred skill.
****
Requirement types separate what is needed at entry from what is needed later. This widens the talent pool and supports the build route.
****

**Question 3.** Which statement about credentials in job architecture is correct?

[( )] A badge proves that a person can do the entire job.
[( )] Only one credential may serve as evidence for each skill.
[(X)] A credential is evidence for a specific skill and sits alongside other evidence such as work samples.
[( )] Credentials should be hard barriers for every skill.
****
A credential supports a claim about a skill, based on an assessment against a standard. It does not prove job competency by itself.
****

**Question 4.** What makes a pathway between two job profiles useful for workforce planning?

[( )] It shows which employees should be dismissed.
[(X)] It shows shared skills and the skills gaps to close, which feeds the build route.
[( )] It replaces the supply and demand view.
[( )] It removes the need for job levels.
****
A pathway highlights what transfers and what must be learned. This helps size the build programme and supports internal mobility.
****

## Governance

### Data quality

Skills data supports decisions that affect people. Poor data leads to poor decisions. Governance sets the rules to keep the data fit for use. Start with data quality.

Check the data against five dimensions:

- **Accuracy:** does the record show what is true?
- **Completeness:** are required fields filled, such as skill, level, date and source?
- **Timeliness:** is the record current? Skills and credentials change.
- **Consistency:** do sources use the same vocabulary and levels?
- **Provenance:** do you know where the record came from and who can confirm it?

For credential data, provenance includes the issuer, the standard, the assessment method and whether the credential can be verified. Where possible, use open, standards-based credential formats so that data moves between systems without manual retyping. Examples of such standards appear in the sources section.

Assign ownership. Every skills data set needs a named owner, a refresh cycle and a way for employees to correct errors. Measure quality with simple indicators, such as the share of records with an evidence type, the share older than 24 months and the number of correction requests.

### Privacy, fairness and AI

Skills data about identifiable people is personal data. In many places, including the European Union, data protection law applies. Core principles include a clear purpose, a lawful basis, data minimisation, transparency, accuracy, limited storage and security. Employees should know what is collected, why, who sees it and how to challenge it. Ask your data protection officer and legal team to confirm which rules apply to your organisation and country.

Plan with the least data needed. Aggregate where you can. A workforce plan usually needs counts by skill and job family, not named individuals. Use individual records only where the purpose needs them, such as a mobility match, and limit access.

AI skills inference needs extra care. It is an emerging practice that is common in HR software. If inferred skills influence decisions about hiring, promotion, task allocation or termination, the use may fall under high-risk rules. Typical duties in such cases include risk management, data governance, documentation, transparency to affected people and human oversight. Check the rules that apply to you. <!-- VERIFY: confirm current legal requirements for high-risk AI systems in employment contexts and their application dates before publishing. -->

Status as of November 2026; check before publishing.

Practical safeguards for inference:

- Tell employees that inference is used and for what purpose.
- Keep inferred skills labelled and separate from assessed skills.
- Do not use inferred skills as the sole basis for a decision about a person.
- Test for different results across groups, and fix problems you find.
- Let people see and correct their data.
- Keep a log of model changes and decisions.

<svg viewBox="0 0 800 450" width="100%" role="img" xmlns="http://www.w3.org/2000/svg">
  <title>Governance cycle for skills data</title>
  <desc>A circular process with four steps in a loop around a navy circle labelled Trusted skills data. Step 1 Define purpose and owner. Step 2 Check quality and provenance. Step 3 Protect privacy and review AI inference. Step 4 Monitor, correct and report. Arrows connect the steps clockwise. Three open arcs in lime, orange and cyan surround the circle to represent recognition and trust.</desc>
  <rect x="0" y="0" width="800" height="450" fill="#F1F5F8"/>
  <path d="M 330 150 A 110 110 0 0 1 470 150" fill="none" stroke="#B1CF37" stroke-width="6"/>
  <path d="M 500 190 A 110 110 0 0 1 500 260" fill="none" stroke="#F78222" stroke-width="6"/>
  <path d="M 340 290 A 110 110 0 0 1 300 220" fill="none" stroke="#5DCAE7" stroke-width="6"/>
  <circle cx="400" cy="225" r="75" fill="#02375B" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="220" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#FFFFFF">Trusted</text>
  <text x="400" y="242" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="16" fill="#FFFFFF">skills data</text>
  <rect x="270" y="20" width="260" height="56" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="45" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">1. Define purpose</text>
  <text x="400" y="64" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">and owner</text>
  <rect x="560" y="197" width="220" height="56" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="670" y="222" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">2. Check quality</text>
  <text x="670" y="241" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">and provenance</text>
  <rect x="270" y="370" width="260" height="56" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="400" y="395" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">3. Protect privacy and</text>
  <text x="400" y="414" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">review AI inference</text>
  <rect x="20" y="197" width="220" height="56" rx="6" fill="#FFFFFF" stroke="#02375B" stroke-width="2"/>
  <text x="130" y="222" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">4. Monitor, correct</text>
  <text x="130" y="241" text-anchor="middle" font-family="Open Sans, Arial, sans-serif" font-size="14" fill="#02375B">and report</text>
  <line x1="530" y1="60" x2="620" y2="60" stroke="#02375B" stroke-width="2"/>
  <line x1="620" y1="60" x2="670" y2="197" stroke="#02375B" stroke-width="2"/>
  <line x1="670" y1="253" x2="620" y2="395" stroke="#02375B" stroke-width="2"/>
  <line x1="620" y1="395" x2="530" y2="398" stroke="#02375B" stroke-width="2"/>
  <line x1="270" y1="398" x2="180" y2="395" stroke="#02375B" stroke-width="2"/>
  <line x1="180" y1="395" x2="130" y2="253" stroke="#02375B" stroke-width="2"/>
  <line x1="130" y1="197" x2="180" y2="60" stroke="#02375B" stroke-width="2"/>
  <line x1="180" y1="60" x2="270" y2="60" stroke="#02375B" stroke-width="2"/>
</svg>

*Figure: a four-step governance cycle for skills data.*

### Worked example and practice

**Worked example: A data review at the academy**

Nordhafen's data protection officer, Elena Marchetti, joins Amira for a quarterly review of the skills data set used in workforce planning.

1. **Purpose and owner:** the purpose is "workforce planning and internal mobility matching". The owner is the head of workforce planning. The data is not used for performance ratings or pay.
2. **Quality check:** a sample of 100 records shows that 88 have an evidence type, 9 are older than 24 months and 3 have inconsistent skill names. Elena and Amira set a target of 95 per cent with evidence type by next quarter. These numbers are illustrative.
3. **Privacy:** the planning report uses counts by skill and job family only. Named lists are limited to three mobility advisers. Employees can view and correct their own records in the HR portal.
4. **AI inference:** a tool suggests skills from project descriptions. The team labels these as "inferred", excludes them from the confirmed supply count and writes a note that the tool may not be used as the sole basis for any decision about a person. Elena flags that any change to use inference for selection would need a fresh legal review.
5. **Monitoring:** they agree a simple log of corrections and a yearly review of group differences in inferred results.

**Practice activity: Draft a governance one-pager**

For your chosen job family, write a one-page governance note.

1. State the purpose of the skills data and name an owner.
2. List three quality indicators and a target for each.
3. List the personal data you will use and how you will minimise it.
4. State your rule for inferred skills in one sentence and name two safeguards.
5. Say who you would consult about legal requirements.

<details>
<summary>Facilitator notes</summary>

In the live workshop (60 minutes), invite a data protection or legal colleague for a short question session if possible. Ask learners to present one risk and one safeguard from their one-pager. Stress that this course does not give legal advice. Learners should name the right internal experts and document what they decide.

</details>

### Check your understanding: Governance

**Question 1.** Which item belongs to data provenance for a credential record?

[( )] The employee's favourite learning format.
[(X)] The issuer, the standard, the assessment method and whether the credential can be verified.
[( )] The number of colleagues with the same name.
[( )] The colour of the badge image.
****
Provenance tells you where a record came from and how far you can trust it. For credentials it covers issuer, standard, assessment and verifiability.
****

**Question 2.** A workforce plan only needs headcount by skill and job family. What is the best privacy practice?

[( )] Share the full named list with all managers.
[(X)] Use aggregated counts and limit named data to those who need it for a stated purpose.
[( )] Keep all names but remove the skill levels.
[( )] Store the data without an owner to reduce responsibility.
****
Data minimisation means using the least personal data needed for the purpose. Aggregation protects people and still supports planning.
****

**Question 3.** Software infers skills from project descriptions, and managers want to use the results to select people for promotion. What is the most appropriate response?

[( )] Allow it, because software is objective.
[( )] Allow it if the results are hidden from employees.
[(X)] Treat it as potentially high-risk, involve legal and data protection experts, keep human oversight and do not use inference as the sole basis.
[( )] Use it only for men, to test the tool.
****
Use of AI inference in employment decisions may fall under high-risk rules. Seek expert advice, ensure transparency and human oversight, and never rely on inference alone.
****

**Question 4.** Which indicator is a sensible data quality measure for a skills inventory?

[( )] The number of skills in the taxonomy per employee.
[(X)] The share of records that carry an evidence type and a date, and the share older than 24 months.
[( )] The total number of badge images stored.
[( )] The number of managers who log in each week.
****
Completeness, provenance and timeliness can be measured with simple indicators such as the share of records with evidence type and the share of outdated records.
****

## Assessment and badge

### The assessed task: skills gap analysis for one job family

You produce a skills gap analysis for one job family. Use the Nordhafen case or, with permission, a case from your own organisation using synthetic or fully anonymised data. A person assesses your work using the rubric below. This file does not grade your submission.

**Task brief**

Write a report of up to six pages, plus tables, with these sections.

1. **Context and scope:** the job family, the planning horizon and the business drivers.
2. **Supply and demand view:** a table or chart of supply and demand for at least five skills, your evidence rule, assumptions and a supply range.
3. **Gaps and routes:** a ranked list of gaps with criticality, and a build, buy or borrow recommendation for at least three gaps with reasons and risks.
4. **Job architecture link:** one job profile with core skills, requirement types, accepted evidence including non-credential evidence, and one pathway from a neighbouring profile.
5. **Data quality and privacy:** a one-page governance note with purpose, owner, quality indicators, minimisation approach and your rule for AI-inferred skills.
6. **Limits and next steps:** the main weaknesses of your data and what you would do in the next quarter.

Do not claim that any credential proves job competency.

**Rubric**

| Criterion | Developing (1) | Competent (2) | Strong (3) |
|---|---|---|---|
| Supply and demand view (outcome 1) | Supply and demand are listed without an evidence rule or sources | Evidence rule stated, supply and demand compared for at least five skills with assumptions | Evidence types separated, supply shown as a range, demand based on scenarios, assumptions explicit |
| Gap analysis and route choice (outcome 2) | Gaps listed without ranking or reasons | Gaps ranked by criticality and size, route chosen with stated criteria for at least three gaps | Routes combined sensibly, costs, timing and risks compared, surpluses used, owner named |
| Job architecture link (outcome 3) | Skills listed for a job without levels or evidence | Core skills with levels and requirement types, credentials linked as evidence, one pathway | Equivalents and non-credential evidence accepted, pathway gaps feed the build plan, no overclaim about credentials |
| Data quality and privacy (outcome 4) | Governance mentioned in general terms | Purpose, owner, quality indicators and minimisation described, inferred skills labelled | Clear safeguards for inference, human oversight, correction route, legal consultation named, risks acknowledged |
| Clarity and professional judgement | Hard to follow, claims unsupported | Clear structure, conclusions follow from the data | Concise, honest about limits, ready for an executive sponsor to act on |

**Pass rule**

- Score at least 2 on each of the four outcome criteria and at least 10 points overall out of 15.
- Pass the final knowledge check with at least 8 correct answers out of 10.
- Both conditions are needed to earn the badge.

**Badge and evidence**

On passing, you earn the badge "Workforce Planning with Skills and Credential Data (Ability, L4)", alignment code ICSF-TALN-L4-A. You submit your gap analysis as the badge evidence. The badge states what you did in a controlled setting. It does not state that you can perform any particular job.

<details>
<summary>Facilitator notes</summary>

Allow about 3 hours for the task, spread over the programme. Plan a 60-minute assessment clinic where learners ask questions about the brief. Assessors should use two reviewers for borderline cases and give written feedback against each criterion. Remind learners that the task may use only synthetic or anonymised data. Check that no personal data appears in the submitted evidence.

</details>

### Final knowledge check

**Question 1.** You build a supply view from three sources: badge records, manager confirmation and self-declared skills. What should you do first?

[( )] Add all records together to get the largest supply number.
[(X)] Tag each record with its evidence type and define an evidence rule for what counts as supply.
[( )] Delete the self-declared skills.
[( )] Ask software to infer the missing skills.
****
Evidence types and an explicit rule make the supply view transparent. Different rules give different counts, so the rule must be stated.
****

**Question 2.** Why is demand in a workforce plan usually shown as scenarios?

[( )] Because demand cannot be translated into skills.
[( )] Because scenarios replace the supply view.
[(X)] Because future business needs are uncertain, and scenarios show how gaps change under different assumptions.
[( )] Because scenarios are required by every credential standard.
****
Demand depends on strategy, projects and the market. Scenarios such as a base case and a growth case express this uncertainty.
****

**Question 3.** A skill is critical, long term and part of your future products, and the market has few qualified people. Which route fits best as the main approach?

[( )] Borrow only, indefinitely.
[(X)] Build through assessed development, supported by a small number of external hires to lead.
[( )] Buy only, in large numbers.
[( )] Ignore the gap until the market improves.
****
For long-term, strategic skills, building gives lasting capability. A few hires can lead and speed up the start.
****

**Question 4.** A gap analysis shows a surplus of one skill. What is the best use of this finding?

[( )] Reduce the skill in the taxonomy.
[( )] Remove the skill from job profiles.
[(X)] Consider reskilling or moving people with that skill to areas with gaps, linked to internal mobility.
[( )] Report the surplus as a data error.
****
A surplus is a resource. Reskilling and mobility use it to close gaps elsewhere.
****

**Question 5.** What does AI skills inference add to a skills inventory, and how should you treat it?

[( )] It adds assessed evidence equal to a credential.
[( )] It adds legal approval for use in selection.
[(X)] It adds suggested skills at the weakest evidence level, so label them, review samples and do not rely on them alone.
[( )] It adds verified identity data.
****
Inferred skills are hints for review. They may be wrong or biased. Label and review them, and apply human judgement.
****

**Question 6.** A colleague says: "Our badge holders can all do the full job of robotics technician." What is the best reply?

[( )] Agree, because badges prove job competency.
[( )] Agree, if the badge is digital.
[(X)] A badge is evidence for specific skills assessed against a standard, so combine it with other evidence such as work samples before making job decisions.
[( )] Disagree, because badges are never useful.
****
Credentials provide evidence of specific skills. They do not by themselves prove competency in a whole job.
****

**Question 7.** Which design of a job profile follows good practice for connecting credentials with job architecture?

[( )] Twenty-five essential skills, each with one named credential and no equivalents.
[( )] No skill levels, only job titles.
[(X)] Five to ten core skills with levels and requirement types, accepted evidence including equivalents and non-credential options.
[( )] Skills listed only when a credential exists.
****
Short, clear skills lists with levels and flexible evidence keep profiles usable and fair, and stop credentials from becoming hard barriers.
****

**Question 8.** Which pathway feature helps workforce planning most?

[( )] A list of all employees by name who might leave.
[( )] A pathway with no skills listed.
[(X)] A pathway that shows shared skills and the skills to be learned between two profiles.
[( )] A pathway that ends in a dismissal decision.
****
Seeing what transfers and what must be learned lets planners size build programmes and support mobility.
****

**Question 9.** Which set of dimensions describes data quality for a skills inventory?

[( )] Colour, size, speed, weight and cost.
[(X)] Accuracy, completeness, timeliness, consistency and provenance.
[( )] Popularity, novelty, length, format and fame.
[( )] Price, brand, language, region and age.
****
These five dimensions help you check whether data is fit for use. Provenance matters especially for credential data.
****

**Question 10.** A workforce plan needs counts by skill and job family. Which handling of personal data is best?

[( )] Publish a named list to the whole company for transparency.
[( )] Keep names and share them with any manager who asks.
[(X)] Use aggregated counts, limit named access to a defined purpose, tell employees what is collected and offer a way to correct records.
[( )] Delete all skills data and plan without evidence.
****
Data minimisation, transparency, purpose limitation and correction rights are core principles. Aggregation meets the planning need with less risk.
****

## Sources and further reading

Status as of November 2026; check before publishing.

The sources below are official texts, standards bodies or framework owners. Check current versions and links before publishing.

- ICoBC, Credentialing Skills Framework (ICSF) and the VRITE quality model. Published by the International Council on Badges and Credentials. See the ICoBC website, icobc.net, for the current versions.
- 1EdTech Consortium, Open Badges standard. Specification for verifiable digital badges. See the 1EdTech website, 1edtech.org.
- 1EdTech Consortium, Comprehensive Learner Record (CLR) standard. See the 1EdTech website, 1edtech.org.
- World Wide Web Consortium (W3C), Verifiable Credentials Data Model. See the W3C website, w3.org.
- European Commission, Europass and the European Skills, Competences, Qualifications and Occupations classification (ESCO). See the European Commission ESCO portal.
- European Parliament and Council of the European Union, Regulation (EU) 2016/679, the General Data Protection Regulation (GDPR). Official text in EUR-Lex.
- European Parliament and Council of the European Union, the Artificial Intelligence Act (Regulation (EU) 2024/1689), in particular its provisions on high-risk systems in employment. Official text in EUR-Lex. <!-- VERIFY: confirm regulation number, publication details and application dates against EUR-Lex before publishing. -->
- International Organization for Standardization, ISO 30414, Human resource management: Guidelines for internal and external human capital reporting. See the ISO website, iso.org.
- ICB-P16, Skills-Based Hiring and Internal Mobility with Credentials, ICoBC Kursbibliothek (prerequisite course).
