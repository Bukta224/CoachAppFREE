# CoachApp (Render-ready, single-service)

Deploy via Render Blueprint using `render.yaml`.
Set `COACH_PASSWORD` at deploy time (Render secret).

MVP features:
- Athletes CRUD
- Weekly plan sessions CRUD (simple table)
- Daily check-in
- ZWO export for a session (explicit blocks, no repeats)

SQLite file `coachapp.sqlite` is ephemeral on free services.
