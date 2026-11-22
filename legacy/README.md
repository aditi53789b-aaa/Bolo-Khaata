# Legacy prototype (not used by the running app)

`prototype_backend/` holds the earlier flat-file Vyapaar AI prototype: phone-number login, an
eligibility engine, a government-scheme sync/RAG assistant and a voice parser. The active API is
`backend/app/main.py`. These files are kept for reference only; their import paths
(`app.core...`, `app.services...`) no longer exist, so they do not run as they are.

If you want the richer scheme features (eligibility scoring, readiness checklist, assistant) back,
port them into `backend/app/` deliberately. The active app currently does a profile-completeness
check only, on purpose (see `docs/ONBOARDING_AND_INTEGRATION.md`).
