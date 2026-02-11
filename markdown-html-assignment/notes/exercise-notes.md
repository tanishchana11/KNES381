# Exercise Physiology Notes
This hyperlink includes a flowchart 

---

## VO<sub>2</sub> Max Testing Flow

```mermaid
flowchart TD
A[Resting Baseline] --> B[Warm-Up Stage]
B --> C[Incremental Load Increase]
C --> D{Fatigue Reached?}
D -- No --> C
D -- Yes --> E[VO₂ Plateau Achieved]
E --> F[Maximal Oxygen Consumption Recorded]
