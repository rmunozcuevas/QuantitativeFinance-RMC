# Workstreams and deliverables

The five students work as one team. Workstreams describe what must get done, not separate departments. Raymundo coordinates all work and gives final approval. See [team responsibilities](TEAM.md) for the five contributor slots.

| Area | Deliverable | Ready for review when |
| --- | --- | --- |
| Data | Dataset metadata, cleaning procedure, exploratory figures | Source, permitted use, fields, transformations, and time coverage are clear |
| Finance | BA II Plus exercise and sensitivity table | Another student can reproduce results with stated cash flows, units, timing, and rates |
| Modeling | Baseline and one model comparison | Same held-out time window, defined metric, no future-data leakage, and limitations |
| Hardware | Setup protocol and Jetson runtime demonstration | Versions, inputs, device conditions, repeat measurements, and shutdown steps are recorded |
| Teaching | Three session packets and a final decision brief/demo | Learning objectives, timing, exercise, expected output, and facilitator notes are tested |
| Coordination and reporting | Task board, equipment bookings, reviewed artifact index | Raymundo maintains the record; Summer can summarize it without inventing claims |

## Integration sequence

Agree on question and dataset → reproduce financial calculation and baseline → compare model → run on Jetson → change an assumption → explain the decision and its limits.

Review occurs at useful milestones. Use a short notebook entry for routine work and the full template for experiments. A peer checks the artifact before Raymundo accepts it. Work is complete only when its evidence is linked; a planning document alone does not count as a completed experiment or workshop.
