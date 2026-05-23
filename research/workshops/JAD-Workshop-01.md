# JAD Workshop Minutes: FlowRoute Internal Requirements

**Date:** May 22, 2026  
**Location:** Internal Discord/Teams Call  
**Attendees:** Pabodha, Sanira, Hansi, Chathura  
**Facilitator:** Pabodha

## Meeting Agenda

1. Finalize the core algorithmic routing logic for video intake.
2. Determine fail-safes for maximum pod capacity.
3. Brainstorm UI layout for the Product Owner (PO) Dashboard.

## 5 Key System Decisions (Acceptance Criteria 2)

1. **Routing Tie-Breaker Logic:** If two Editing Pods have the exact same lowest active task count, the system will route the video to the pod with the fastest rolling 7-day average completion time.
2. **Maximum Capacity Threshold:** A pod will be considered "at maximum capacity" if their active task count equals their total number of assigned editors multiplied by 2.
3. **Queueing System:** If all pods are at maximum capacity, incoming videos will not be rejected. They will be placed in a "Master Pending Queue" until a pod frees up.
4. **PO Dashboard Layout:** The PO dashboard will feature a real-time bar chart showing the active task load of all 8 pods side-by-side to easily visualize standard deviation imbalances.
5. **Manual Override Privileges:** Only the Product Owner (PO) role will have the system permission to manually yank a video from one pod's queue and assign it to another to handle emergency VIP clients.

## Action Items

- Add the 7-day average tie-breaker logic to the UC-02 documentation.
- Begin drafting wireframes for the PO Dashboard based on Decision 4.
