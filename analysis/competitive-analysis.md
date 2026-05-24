# Competitive Analysis: Manual Routing Constraints

- **Date:** 18 May 2026
- **Analysts:** Chathura Hapukotuwa & Sanira Adesha
- **Objective:** To evaluate existing project management tools (Trello, Jira, Notion) against the automated workload balancing requirements of FlowRoute.

## 1. Feature Comparison Matrix

| Feature                         | Trello                  | Jira                           | Notion                 | FlowRoute (Proposed)             |
| :------------------------------ | :---------------------- | :----------------------------- | :--------------------- | :------------------------------- |
| **Kanban Board UI**             | Yes (Excellent)         | Yes (Excellent)                | Yes (Good)             | **Yes**                          |
| **Real-Time Capacity Tracking** | No                      | Partial (Sprint velocity only) | Manual formulas only   | **Yes (Automated)**              |
| **Algorithmic Task Routing**    | No (Manual drag & drop) | No (Manual assignment)         | No (Manual assignment) | **Yes (Least-busy pod routing)** |
| **Role-Based Workload Limits**  | No                      | Yes (WIP Limits)               | No                     | **Yes (Strict Pod Limits)**      |

## 2. Evaluation of Limitations

### Notion Database Limitations

While Notion allows for highly customizable databases and relations, it completely lacks native automation for workload balancing. Calculating real-time pod capacity requires complex, brittle formula columns. Furthermore, Notion cannot autonomously route an incoming client form directly to a specific pod based on those formulas without relying on third-party integration tools like Zapier.

### Trello & Jira Workload Views

Both Trello and Jira excel at visualizing work, but they operate on a "Pull" or "Manual Push" model.

- **Trello:** Relies entirely on a human manager to visually assess which column looks emptiest and drag the card over.
- **Jira:** Offers Work-In-Progress (WIP) limits, but if a pod hits its limit, Jira simply highlights the column in red; it does not automatically reroute the next incoming task to an available pod.

## 3. Conclusion (Gaps Identified)

This analysis confirms a critical gap in the market: existing solutions lack **real-time capacity tracking and algorithmic routing**. They rely on human intervention to balance workloads, which causes the 5.1 standard deviation imbalance observed at Unwir Agency. FlowRoute's algorithmic routing engine provides unique, necessary value over standard drag-and-drop tools.
