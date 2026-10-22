# MEMORA architecture

MEMORA is a role-aware web companion with a React frontend and a FastAPI backend.

- **Person** sees a large, simple home with six primary choices.
- **Caregiver** sees overview, routines, reminders, alerts, and reports.
- **Admin** sees workspace-level counts and monitoring.

The frontend never receives API keys. The backend loads secrets from environment variables and returns only authorized records for the signed-in user.
