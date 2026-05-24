# Fact-Finding: Structured Interview with Product Owner

- **Date:** 23 May 2026
- **Interviewer:** Chathura Hapukotuwa
- **Interviewee:** Sankhaja (Product Owner, Unwir Agency)
- **Method:** Google Meet (Recorded with consent)
- **Duration:** 45 minutes

## 1. Interview Guide (10 Structured Questions)

1. **Intake:** Walk me through the exact step-by-step process of what happens when a client submits a new video request today.
2. **Evaluation:** How do you currently evaluate which editing pod has the capacity to take on a new video?
3. **Time Cost:** On average, how many hours per week do you spend manually evaluating workloads and assigning tasks?
4. **Offline Bottlenecks:** What happens to incoming client videos if you are offline, asleep, or in a meeting?
5. **Tracking:** What tools are you currently using to track pod availability, and where do they fail?
6. **Imbalance:** Have you noticed significant workload imbalances between pods? How does that affect delivery times?
7. **Reassignment:** If a pod suddenly becomes unavailable (e.g., illness), how difficult is the manual reassignment process?
8. **Communication:** How do the editors currently notify you that they have finished a video and have freed up capacity?
9. **Metrics:** What are the top 3 metrics you absolutely need to see on a manager dashboard to feel in control of the system?
10. **Automation Vision:** If the system could automatically route tasks perfectly, what higher-level work would you focus your time on?

## 2. Comprehensive Summary (Transcript Highlights)

- **On Intake & Evaluation (Q1, Q2, Q5):** The client emails a brief and a Google Drive link. Sankhaja manually checks a shared Google Sheet and a Trello board to guess which pod looks the least busy. The trackers are often outdated because editors forget to move Trello cards when they finish.
- **On Time Cost & Bottlenecks (Q3, Q4):** Sankhaja spends roughly 10-15 hours a week just doing "traffic control." Because 100% of tasks require his manual assignment, a video submitted on a Friday night sits completely untouched until Monday morning, causing a massive 24hr+ delay.
- **On Imbalance (Q6):** Because assignment is based on "gut feeling" and outdated Trello boards, some pods are working 12-hour days while others are sitting idle waiting for work.
- **On Metrics & Vision (Q9, Q10):** Sankhaja needs to see real-time active task counts per pod and a standard deviation metric. If routing was automated, he could focus on acquiring new clients instead of micromanaging task distribution.

## 3. Key Pain Points Extracted (For SRS)

- **Pain Point 1:** 100% manual assignment creates a single point of failure; tasks stall when the PO is offline.
- **Pain Point 2:** Lack of real-time capacity tracking leads to severe workload imbalances and burnout for specific editing pods.
- **Pain Point 3:** The fragmented use of Email, Google Sheets, and Trello creates a disconnected pipeline prone to human error.
