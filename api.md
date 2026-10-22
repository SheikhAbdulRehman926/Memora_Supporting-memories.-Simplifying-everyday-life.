# API

Interactive docs: http://localhost:8000/api/docs

Auth: `/api/auth/register`, `/api/auth/login`, `/api/auth/logout`, `/api/auth/me`

Records: `/api/memories`, `/api/people`, `/api/routines`, `/api/reminders`, `/api/activities`, `/api/mood`, `/api/chat`, `/api/chat/history`

Caregiver: `/api/caregiver/overview`, `/api/caregiver/alerts`, `/api/caregiver/reports`

Admin: `/api/admin/dashboard`, `/api/admin/users`, `/api/admin/caregivers`, `/api/admin/monitoring`

All mutating routes validate Pydantic models and return plain-language errors.
