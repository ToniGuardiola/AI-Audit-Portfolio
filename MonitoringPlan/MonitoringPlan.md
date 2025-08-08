# AI Monitoring Plan for EduScan Homework Grading Tool

## 1. System Overview

**System Name:** EduScan  
**Function:** AI-powered homework grading and feedback assistant used in secondary school classrooms.  
**Deployment Context:** Teachers upload student essays or short-answer responses. EduScan provides draft scores, highlights key strengths/weaknesses, and suggests comments aligned to rubrics.



## 2. Monitoring Objectives

- Ensure the AI system remains accurate, fair, and aligned with curriculum standards.
- Detect any signs of model degradation, bias, or system misuse.
- Maintain compliance with the EU AI Act (Article 17) and GDPR (ongoing accountability).
- Protect student rights and support transparent, ethical use of AI in classrooms.



## 3. Key Metrics to Track

| **Category**                    | **Metric**                                                                 |
|----------------------------------|---------------------------------------------------------------------------|
| **Performance & Accuracy**       | - Monthly average deviation from teacher-assigned grades (target: <10%)  |
|                                 | - Error rate trend (month over month)                                     |
| **Bias/Fairness**               | - Accuracy by demographic group (e.g. native vs non-native speakers)     |
|                                 | - Incidents of flagged bias/inconsistency                                 |
| **User Feedback**              | - Teacher satisfaction rating (survey per term)                           |
|                                 | - Number of teacher overrides (manual edits to AI feedback)               |
| **Transparency/Explainability** | - % of outputs with confidence scores or rationale provided               |
|                                 | - Number of teacher/student questions about unclear feedback              |
| **Compliance & Privacy**        | - Last DPIA review date and status                                        |
|                                 | - Number of data access/deletion requests processed                       |
| **Reliability/Uptime**          | - Weekly system availability (target: 99%+)                               |
|                                 | - Number of system crashes or critical bugs                               |



## 4. Monitoring Frequency & Tools

| **Metric Category**     | **Review Frequency** | **Tools/Methods**                           |
|-------------------------|----------------------|---------------------------------------------|
| Performance             | Monthly              | Export logs; compare to teacher gradebook   |
| Bias/Fairness           | Quarterly            | Segmented analysis; LLM assistance          |
| User Feedback           | Per term             | Surveys (Google Forms); override logs       |
| Transparency            | Monthly              | Qualitative feedback + issue tracker        |
| Compliance              | Biannually           | GDPR logbook; DPIA tracking sheet           |
| Reliability             | Ongoing (daily)      | IT system logs; alerts for downtime         |



## 5. Roles and Responsibilities

| **Role**                      | **Responsibility**                                      |
|------------------------------|----------------------------------------------------------|
| AI Governance Officer        | Oversees all monitoring activities; documents results    |
| IT Support Lead              | Maintains uptime logs and alerts                         |
| Teaching & Learning Lead     | Coordinates teacher feedback collection                  |
| Data Protection Officer      | Reviews compliance indicators (e.g., DPIA, consent)      |
| Vendor (EduScan Provider)    | Provides system update notes and technical logs          |



## 6. Monitoring Outcomes & Escalation

- Metrics that breach predefined thresholds (e.g., accuracy drop >10%, teacher override >20%) will trigger:
  - Root cause analysis
  - Immediate reporting to school leadership
  - Notification to vendor for resolution
  - Internal review and possible update to risk register



## 7. Documentation and Storage

- Monitoring logs and summary reports will be stored in the school’s secure governance drive (compliant with GDPR).
- Termly reports will be reviewed during AI governance committee meetings.
- Summarised results will be shared with school leadership and included in annual improvement planning.



## 8. Review Schedule

| **Review Type**        | **Frequency**         |
|------------------------|-----------------------|
| Monitoring Plan Review | Annually (June)       |
| Audit Comparison Check | Each semester         |
| Metric Thresholds      | Reviewed quarterly    |



**Last Updated:** August 2025  
**Next Scheduled Review:** June 2026  
**Maintained by:** Maria-Antònia Guardiola, AI Governance Officer  

