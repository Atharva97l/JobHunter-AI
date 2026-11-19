# JobHunter AI 🚀
### An Autonomous Multi-Agent Job Hunting & Career Intelligence System

JobHunter AI is an AI-powered personal job-hunting assistant designed to automate and optimize the job application process.

Built using **LangChain, LangGraph and Python**, the system uses multiple specialized AI agents to discover job opportunities, evaluate candidate-job compatibility, improve resumes, prepare applications and track career progress.

Rather than simply searching for jobs, JobHunter AI continuously learns about the candidate's preferences, monitors the job market and provides personalized recommendations to improve their chances of securing interviews.

---

## 🎯 Project Objectives

- Automate daily job discovery across multiple platforms.
- Understand individual career goals and job preferences.
- Evaluate job descriptions against candidate skills and experience.
- Identify resume weaknesses and missing qualifications.
- Generate tailored resumes and application materials.
- Automate applications through supported integrations.
- Track applications, deadlines and responses.
- Generate weekly career intelligence and resume improvement reports.

## 🤖 Multi-Agent Architecture

The system is designed around specialized AI agents coordinated through LangGraph.

| Agent | Responsibility |
|---|---|
| Career Profile Agent | Understands career goals, skills and preferences. |
| Job Discovery Agent | Finds relevant opportunities across supported sources. |
| Job Matching Agent | Evaluates job relevance and candidate compatibility. |
| Resume Analyst Agent | Identifies resume weaknesses and skill gaps. |
| Application Agent | Prepares customized application materials and submits through permitted integrations. |
| Verification Agent | Checks application accuracy and detects duplicates. |
| Career Intelligence Agent | Generates weekly reports and career recommendations. |

### Workflow

```text
           User Profile & Career Goals
                       |
                       v
              LangGraph Orchestrator
                       |
          +------------+------------+
          |            |            |
          v            v            v
       Discovery    Profile      Resume
        Agent       Agent       Analyst
          |            |            |
          +------------+------------+
                       |
                       v
                Job Matching
                       |
                       v
               Application Agent
                       |
                       v
              Verification Agent
                       |
                       v
              Application Tracker
                       |
                       v
             Career Intelligence
```

## ✨ Planned Features

### 1. Intelligent Job Discovery
- Daily job discovery from configured job sources.
- Support for job APIs, career pages and permitted integrations.
- Job description extraction and normalization
