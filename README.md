<!-- ============================================================
     TiaKohir / README.md  —  profile README, "clinical chart" edition
     Everything below the header is plain GitHub-flavored Markdown + the
     small HTML subset GitHub allows (tables, picture, details, align).
     Dynamic cards come from github-readme-stats, streak-stats and
     readme-typing-svg. Each one has a light + dark variant via <picture>.
     ============================================================ -->

<p align="center">
  <img src="assets/chart-header.svg" alt="Tia Kohir — clinical chart header: MRN TiaKohir, DOB 2014 (first Epic go-live), service: clinical data and AI value measurement" width="100%" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3800&pause=1200&color=2DD4BF&center=true&vCenter=true&repeat=true&width=760&height=46&lines=Healthcare+AI+starts+with+the+clinician%2C+not+the+model.;Accuracy+is+a+model+metric.+Value+is+a+deployment+metric.;Ship+fewer+tools.+Measure+every+one+you+ship.;Epic+%E2%86%92+OMOP+%E2%86%92+evidence.+The+order+matters." />
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3800&pause=1200&color=0F766E&center=true&vCenter=true&repeat=true&width=760&height=46&lines=Healthcare+AI+starts+with+the+clinician%2C+not+the+model.;Accuracy+is+a+model+metric.+Value+is+a+deployment+metric.;Ship+fewer+tools.+Measure+every+one+you+ship.;Epic+%E2%86%92+OMOP+%E2%86%92+evidence.+The+order+matters." alt="Healthcare AI starts with the clinician, not the model." />
  </picture>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/teijahebshibah-tia"><img src="https://img.shields.io/badge/LinkedIn-Tia%20Kohir-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://tiakohir.github.io/"><img src="https://img.shields.io/badge/Portfolio-tiakohir.github.io-0f766e?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
  &nbsp;
  <a href="https://github.com/TiaKohir?tab=repositories"><img src="https://img.shields.io/badge/AI%20Lab-public%20research-134e4a?style=for-the-badge&logo=github&logoColor=white" alt="AI Lab repos" /></a>
</p>

<br/>

## 🩺 Chief Complaint

> **"We deployed the AI. Is it working?"**

Every health-system exec asks it after go-live. Almost nobody answers it with a number they'd defend in front of a CFO. Vendors bring accuracy. Leadership wants value. Those are different quantities, and the gap between them is where I work.

<br/>

## 📜 History of Present Illness

Nine-plus years on the provider side of healthcare data. In order:

**Epic build side first.** Five years at CommonSpirit Health (via Deloitte) implementing ASAP, SmartForms, Cogito — then down into the data layer: Clarity, Caboodle, the data models everything downstream pretends are clean. They aren't. That's the job.

**Then BI at Sutter Health.** SQL, ETL, KPI reporting. The unglamorous middle of the stack, where one wrong join turns into one wrong board slide.

**Then NYU Langone**, as Senior BI & Clinical Product Analyst. Hadoop/Impala data marts, Tableau for oncology, XML-feed schema design, Collibra governance, incremental loads. I led the team that *audited* the ETL pipelines — standards, code review, sign-off — rather than writing them myself. Reviewing other people's pipelines teaches you more about failure modes than writing your own ever will.

**Then Stanford Health Care**, Technology & Digital Solutions. Two back-to-back roles: data science in Finance & Business Ops, then AI healthcare product management. Four AI automations were already live, and leadership wanted to know what they were worth. That question became a benefit-attribution framework for clinical AI — a way to take a deployed automation and say, with a defensible number, what it actually changed. Along the way: a Strategic Priority Index for scoring the AI backlog, a Product Hub / PRD framework, a predictive model on 14K+ EHR records (five algorithms benchmarked, Python + scikit-learn on Databricks/Azure), and a financial-validation step that went from eight hours to two minutes.

**Now:** the AI Lab. Public, homegrown research on the part of clinical AI nobody budgets for — what happens *after* deployment. Repos are under *Imaging* below.

<br/>

## 🗂️ Past History

| Period | Where | Service | Findings |
|---|---|---|---|
| 2025 – 2026 | **Stanford Health Care** — Technology & Digital Solutions | Data science (Finance & Business Ops) → AI Healthcare Product Management | Value assessment of four deployed clinical AI automations · benefit-attribution framework · AI backlog prioritization index · PRD framework · 14K-record predictive model on Databricks/Azure · Reporting Workbench → Fabric pipelines |
| 2021 – 2023 | **NYU Langone Health** (via Clairvoyant) | Senior BI & Clinical Product Analyst | Hadoop/Impala data marts · oncology dashboards · XML-feed schema design · led ETL audit (standards, code review, sign-off) · Collibra governance · incremental loads |
| 2019 – 2021 | **Sutter Health** (via Deloitte) | BI Developer | SQL/ETL development · KPI reporting · clinical and operational dashboards |
| 2014 – 2019 | **CommonSpirit Health** (via Deloitte) | Epic Consultant, Associate Lead | Five years of Epic implementation — ASAP, SmartForms, Cogito, Clarity, Caboodle |

<br/>

## 💊 Medications — active stack

| Medication | Dose | Indication |
|---|---|---|
| **SQL / PL-SQL** | daily · 10+ yrs · no plans to taper | Everything. Still the drug of choice. |
| **Epic Clarity · Caboodle · Cogito · Reporting Workbench** | long-term maintenance | Getting clinical data out of the EHR without lying about it |
| **Python** (pandas · scikit-learn) | daily | Predictive models, eval harnesses, synthetic data generators |
| **Databricks · PySpark · Delta Lake · Unity Catalog** | daily | Lakehouse builds, OMOP CDM, data-quality gates, time travel for reproducible cohorts |
| **Microsoft Fabric · OneLake · dbt · Azure Data Factory** | titrating up | Medallion pipelines, warehouse modeling, neurosymbolic validation |
| **OMOP CDM v5.4 · FHIR · SNOMED / LOINC / RxNorm / ICD-10-CM** | as needed, which is often | Making three hospitals' data agree with each other |
| **Hadoop · Impala · BigQuery** | historical · tolerated well | Large clinical data marts |
| **Tableau · Power BI** | PRN | When the number has to be seen to be believed |
| **Claude · GPT · Gemini APIs** · LLM-as-judge | investigational | Clinical summarization eval: factuality, omissions, relevance |
| **Difference-in-differences · decision-curve analysis** | low dose · high effect | Attributing change to the tool, not to the season or the staffing |

<p align="left">
  <img src="https://img.shields.io/badge/SQL%20%2F%20PL%2FSQL-0f766e?style=flat-square" alt="SQL" />
  <img src="https://img.shields.io/badge/Python-0f766e?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/scikit--learn-0f766e?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Databricks-0f766e?style=flat-square&logo=databricks&logoColor=white" alt="Databricks" />
  <img src="https://img.shields.io/badge/PySpark-0f766e?style=flat-square&logo=apachespark&logoColor=white" alt="PySpark" />
  <img src="https://img.shields.io/badge/Delta%20Lake-0f766e?style=flat-square" alt="Delta Lake" />
  <img src="https://img.shields.io/badge/Microsoft%20Fabric-0f766e?style=flat-square" alt="Microsoft Fabric" />
  <img src="https://img.shields.io/badge/Azure-0f766e?style=flat-square" alt="Azure" />
  <img src="https://img.shields.io/badge/dbt-0f766e?style=flat-square&logo=dbt&logoColor=white" alt="dbt" />
  <img src="https://img.shields.io/badge/Epic%20Clarity%20%2F%20Caboodle-0f766e?style=flat-square" alt="Epic" />
  <img src="https://img.shields.io/badge/OMOP%20CDM-0f766e?style=flat-square" alt="OMOP CDM" />
  <img src="https://img.shields.io/badge/FHIR-0f766e?style=flat-square" alt="FHIR" />
  <img src="https://img.shields.io/badge/Hadoop%20%2F%20Impala-0f766e?style=flat-square&logo=apachehadoop&logoColor=white" alt="Hadoop" />
  <img src="https://img.shields.io/badge/BigQuery-0f766e?style=flat-square&logo=googlebigquery&logoColor=white" alt="BigQuery" />
  <img src="https://img.shields.io/badge/Tableau-0f766e?style=flat-square" alt="Tableau" />
  <img src="https://img.shields.io/badge/Power%20BI-0f766e?style=flat-square" alt="Power BI" />
  <img src="https://img.shields.io/badge/Claude-0f766e?style=flat-square&logo=anthropic&logoColor=white" alt="Claude" />
  <img src="https://img.shields.io/badge/GPT-0f766e?style=flat-square&logo=openai&logoColor=white" alt="GPT" />
  <img src="https://img.shields.io/badge/Gemini-0f766e?style=flat-square&logo=googlegemini&logoColor=white" alt="Gemini" />
</p>

<br/>

## ⚠️ Allergies

Documented reactions. Severity noted.

- **Vendor ROI decks with no baseline** — severe. Cannot be in the same room.
- **Pre/post comparisons with no control group** — severe. See the telemetry repo for the antidote.
- **ROUGE scores presented as clinical evidence** — moderate, worsening.
- **A 90% alert-override rate described as "adoption"** — moderate.
- **Dashboards nobody opens** — chronic exposure, 2014 to present.
- **"The data is clean."** — anaphylaxis.

<br/>

## 🔬 Review of Systems

Organized the way the open-source healthcare world organizes itself. All systems examined.

| System | Findings |
|---|---|
| **EHR** | Epic — six module certifications (ASAP, SmartForms, Cogito, Clarity Data Model, Clinical Data Model, Caboodle Data Model). Hands-on with Orders, ClinDoc, Ambulatory, ADT/Grand Central, Radar dashboards, Reporting Workbench. Willow exposure. |
| **Data models & specifications** | OMOP CDM v5.4 · FHIR · Epic Clarity / Caboodle · SNOMED CT, LOINC, RxNorm, ICD-10-CM, CPT, NDC, UCUM. Domain routing by mapped concept, not by source table. Unit harmonization before any threshold logic. |
| **Integration** | ETL design and audit · Azure Data Factory · Databricks Auto Loader · XML feeds · incremental and idempotent loads · provenance columns on every bronze row |
| **Data platforms** | Databricks (PySpark, Delta Lake, Unity Catalog) · Microsoft Fabric / OneLake · Hadoop / Impala · BigQuery |
| **Data quality & governance** | Kahn-framework checks · quarantine tables · drift monitors · release gates that block publication · Collibra · HIPAA · healthcare AI governance |
| **Machine learning & LLMs** | Classification and regression with scikit-learn · point-in-time, anti-leakage feature design · LLM evaluation (factuality, significant omissions, clinical relevance) · LLM-as-judge · neurosymbolic validation of LLM output against structured EHR data |
| **Research data** | MIMIC-IV · Synthea · Coherent Data Set · NHANES · BRFSS — synthetic or public only, no PHI, ever |
| **Clinical domains** | Oncology and pathology · ADT and patient flow · clinical trials · ICD/CPT coding · value-based care |
| **Product** | CSPO · PRD frameworks · backlog scoring · requirements derived from clinician behavior data (audit logs, clickstream) |
| **Methods** | Pre/post with controls · difference-in-differences · pre-trend checks · adoption-ramp modeling · decision-curve analysis and net benefit |

<br/>

## 📈 Vitals

Taken at the door. Self-reported, verifiable.

<table align="center">
<tr>
<td align="center"><b>9+</b><br/><sub>years, provider-side<br/>healthcare data</sub></td>
<td align="center"><b>4</b><br/><sub>health systems<br/>CommonSpirit · Sutter · NYU Langone · Stanford</sub></td>
<td align="center"><b>6</b><br/><sub>Epic module<br/>certifications</sub></td>
<td align="center"><b>4</b><br/><sub>deployed clinical AI automations<br/>value-assessed at Stanford</sub></td>
<td align="center"><b>5</b><br/><sub>public AI Lab<br/>research repos</sub></td>
<td align="center"><b>0</b><br/><sub>rows of PHI<br/>in any of them</sub></td>
</tr>
</table>

<!-- ------------------------------------------------------------------
     LIVE GITHUB CARDS — parked for now.
     These work (verified), but with a young public account they show
     small numbers. Un-comment when the activity graph is denser.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api?username=TiaKohir&show_icons=true&hide_border=true&hide_rank=true&include_all_commits=true&custom_title=Vitals&bg_color=00000000&title_color=2dd4bf&icon_color=2dd4bf&text_color=e5e7eb" />
    <img height="170" src="https://github-readme-stats.vercel.app/api?username=TiaKohir&show_icons=true&hide_border=true&hide_rank=true&include_all_commits=true&custom_title=Vitals&bg_color=00000000&title_color=0f766e&icon_color=0f766e&text_color=1f2937" alt="GitHub stats" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://streak-stats.demolab.com?user=TiaKohir&hide_border=true&background=00000000&ring=2dd4bf&fire=2dd4bf&currStreakLabel=2dd4bf&sideLabels=e5e7eb&currStreakNum=e5e7eb&sideNums=e5e7eb&dates=9ca3af&stroke=2dd4bf" />
    <img height="170" src="https://streak-stats.demolab.com?user=TiaKohir&hide_border=true&background=00000000&ring=0f766e&fire=0f766e&currStreakLabel=0f766e&sideLabels=1f2937&currStreakNum=1f2937&sideNums=1f2937&dates=6b7280&stroke=0f766e" alt="Contribution streak" />
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs/?username=TiaKohir&layout=compact&hide_border=true&hide=html&langs_count=8&custom_title=Languages%20on%20file&bg_color=00000000&title_color=2dd4bf&text_color=e5e7eb" />
    <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TiaKohir&layout=compact&hide_border=true&hide=html&langs_count=8&custom_title=Languages%20on%20file&bg_color=00000000&title_color=0f766e&text_color=1f2937" alt="Top languages" />
  </picture>
</p>
------------------------------------------------------------------ -->

<br/>

## 🩻 Imaging — the AI Lab

Homegrown research on healthcare AI deployment, adoption, and impact measurement. Every repo runs on synthetic data. No PHI, anywhere, at any point. Each one is a living project: the thinking changes as I iterate, and issues are welcome.

<table>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/TiaKohir/-clinical-lakehouse-omop">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=-clinical-lakehouse-omop&show_owner=false&hide_border=true&bg_color=00000000&title_color=2dd4bf&icon_color=2dd4bf&text_color=e5e7eb" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=-clinical-lakehouse-omop&show_owner=false&hide_border=true&bg_color=00000000&title_color=0f766e&icon_color=0f766e&text_color=1f2937" alt="clinical-lakehouse-omop" />
</picture>
</a>

**Epic EHR → OMOP CDM v5.4 on Databricks.** Three hospital sites that disagree about everything, eleven deliberately injected real-world defects, a Kahn-framework data-quality gate that refuses to publish, and a cohort question a pharma customer would actually ask. The last defect passes every row-level check. That's the point.

</td>
<td width="50%" valign="top">

<a href="https://github.com/TiaKohir/clinical-summary-eval">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=clinical-summary-eval&show_owner=false&hide_border=true&bg_color=00000000&title_color=2dd4bf&icon_color=2dd4bf&text_color=e5e7eb" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=clinical-summary-eval&show_owner=false&hide_border=true&bg_color=00000000&title_color=0f766e&icon_color=0f766e&text_color=1f2937" alt="clinical-summary-eval" />
</picture>
</a>

**Is this LLM summary clinically good enough to act on?** Not "is it fluent." Factuality, clinically significant omissions, relevance — scored against hand-labeled must-keep facts, not vibes. Claude, GPT, Gemini, plus an offline mock so the whole pipeline runs with no API keys.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/TiaKohir/clinician-work-telemetry">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=clinician-work-telemetry&show_owner=false&hide_border=true&bg_color=00000000&title_color=2dd4bf&icon_color=2dd4bf&text_color=e5e7eb" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=clinician-work-telemetry&show_owner=false&hide_border=true&bg_color=00000000&title_color=0f766e&icon_color=0f766e&text_color=1f2937" alt="clinician-work-telemetry" />
</picture>
</a>

**What an AI deployment actually changes in clinician work.** EHR audit-log telemetry, pre/post with a control group, difference-in-differences, and the displacement effects that satisfaction surveys will never see — saved documentation time that quietly reappears in the in-basket, or after hours.

</td>
<td width="50%" valign="top">

<a href="https://github.com/TiaKohir/clinician-alert-fatigue-adoption">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=clinician-alert-fatigue-adoption&show_owner=false&hide_border=true&bg_color=00000000&title_color=2dd4bf&icon_color=2dd4bf&text_color=e5e7eb" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=clinician-alert-fatigue-adoption&show_owner=false&hide_border=true&bg_color=00000000&title_color=0f766e&icon_color=0f766e&text_color=1f2937" alt="clinician-alert-fatigue-adoption" />
</picture>
</a>

**Alert fatigue and AI adoption are the same system, seen from two ends.** Both are downstream of one design variable: how the tool spends a clinician's attention. Literature synthesis plus a framework for spending that budget on purpose instead of by accident.

</td>
</tr>
<tr>
<td width="50%" valign="top">

<a href="https://github.com/TiaKohir/Healthcare-Fabric-Analytics">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=Healthcare-Fabric-Analytics&show_owner=false&hide_border=true&bg_color=00000000&title_color=2dd4bf&icon_color=2dd4bf&text_color=e5e7eb" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=Healthcare-Fabric-Analytics&show_owner=false&hide_border=true&bg_color=00000000&title_color=0f766e&icon_color=0f766e&text_color=1f2937" alt="Healthcare-Fabric-Analytics" />
</picture>
</a>

**Neurosymbolic validation of AI clinical summaries on Microsoft Fabric.** Deterministic SQL rules check LLM output against structured EHR data — hallucinated diagnoses, missed allergies, wrong meds, misreported labs. Medallion architecture, dbt, Power BI. Early stage.

</td>
<td width="50%" valign="top">

<a href="https://tiakohir.github.io/">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=tiakohir.github.io&show_owner=false&hide_border=true&bg_color=00000000&title_color=2dd4bf&icon_color=2dd4bf&text_color=e5e7eb" />
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=TiaKohir&repo=tiakohir.github.io&show_owner=false&hide_border=true&bg_color=00000000&title_color=0f766e&icon_color=0f766e&text_color=1f2937" alt="tiakohir.github.io" />
</picture>
</a>

**Portfolio and point of view.** One page. The argument: healthcare AI starts with the clinician, not the model, and the tools that do ship should make the human in the loop stronger, not redundant.

</td>
</tr>
</table>

<details>
<summary><b>Prior films</b> — graduate work, 2023–2024 (click to expand)</summary>
<br/>

- **Alzheimer's & Healthy Aging dashboard** — BRFSS data, Tableau.
- **Breast cancer classification** — Random Forest, Naive Bayes, SVM, k-NN; ~96% accuracy. The point was the comparison, not the number.
- **Housing price trends pre/post COVID** — regression analysis of market resilience.
- **Hospital collaboration study** — strategic process optimization for patient care.

</details>

<br/>

## 🧠 Assessment

Translator between three languages — clinical, technical, business. Native in the data layer; fluent in the clinical workflow and the business case. I've built the data, audited the data, and been the person leadership turns to when the vendor's slide says 40% and nobody can find the 40%.

My bias, stated plainly: fewer tools in production, each one measured. Accuracy is where evaluation *starts*. It's not where value lives. And the most important effects of clinical AI are displacement effects — time and effort don't disappear, they move — which means the only honest measurement is the one that looks for where they went.

<br/>

## 📝 Plan

Active orders, roughly in priority:

1. **Manuscript, sole author** — a benefit-attribution framework for clinical AI deployments. Developed at Stanford Health Care; in preparation for peer review.
2. **Manuscript, co-author** — a multi-author perspective on what health systems should do before and after each release of a clinical generative-AI system. My section: the pre-/post-release governance framework.
3. **DDCT framework** — translating clinician behavioral data (EHR audit logs, clickstream) into structured product-owner requirements. Manuscript in progress; preprint first.
4. **Cost-aware threshold selection** for sepsis prediction on MIMIC-IV — decision-curve analysis, net benefit, packaged in Python with a demo. Scoped.
5. **Peer review** — AMIA Learning Health Systems Year-in-Review working group.
6. **Cochrane Engage** — contributing to a scoping review on clinical decision support systems in emergency settings.
7. **Keep the AI Lab honest** — synthetic data only; every claim either sourced or marked as mine.

<br/>

## 🎓 Credentials on File

**Education**

- MS, Health Data Analytics — University of North Texas, 2024
- MBA, Hospital & Healthcare Management — Apollo, 2014
- B.Tech, Computer Science — Malla Reddy, 2011
- Stanford Online — *Digital Health Product Development* (SOM-XCHE0025), 2026

**Certifications**

- Epic: ASAP · SmartForms · Cogito · Clarity Data Model · Clinical Data Model · Caboodle Data Model
- Certified Scrum Product Owner (CSPO) · Six Sigma Green Belt · ITIL · MySQL · Python

**Recognition**

- Spot Awards and Optimistic Awards for technical leadership

<br/>

## 📚 Publications

- Iwundu CN, **Kohir T**, Heck JE. *Predictors of Cataract Surgery Among US Adults: NHANES 2007–2008.* **Healthcare.** 2025;13(6):641. [doi:10.3390/healthcare13060641](https://doi.org/10.3390/healthcare13060641)
- AMIA poster — informal caregiver burden.

<br/>

## 📷 Social History

- **Hackathons.** *Built with Claude: Life Sciences* (Build track) — turning computational hit lists like Perturb-seq outputs into evidence-backed decision briefs. *MoTrPAC Multi-Omics Hackathon 2026*, Team 2-PAC, "Run or Lift?" — endurance vs. resistance exercise multi-omic networks held up against type 2 diabetes biology.
- **Photography.** Untrained, and fine with that.
- **Keeps an Obsidian vault** of a couple thousand AI conversations converted to markdown. It isn't organized. It's searchable, which is the point.

<br/>

## 🚪 Disposition

Discharged to GitHub in stable condition. Follow up on LinkedIn. Open to conversations about measuring clinical AI value, clinical data engineering, and healthcare product work — especially the hard version of any of those.

<p align="center">
  <a href="https://www.linkedin.com/in/teijahebshibah-tia"><img src="https://img.shields.io/badge/LinkedIn-connect-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  &nbsp;
  <a href="https://tiakohir.github.io/"><img src="https://img.shields.io/badge/Portfolio-tiakohir.github.io-0f766e?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
</p>

<br/>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/TiaKohir/TiaKohir/output/github-contribution-grid-snake-dark.svg" />
    <img src="https://raw.githubusercontent.com/TiaKohir/TiaKohir/output/github-contribution-grid-snake.svg" alt="Contribution graph, eaten by a snake" width="100%" />
  </picture>
</p>

<p align="center">
  <sub>Chart closed. No PHI was used in the making of this README.</sub>
</p>
