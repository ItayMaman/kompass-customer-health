Project: Kompass Customer Health Platform

Goal:
Build an internal Customer Success web app for customer health monitoring.

Tech stack:
- Frontend: React + TypeScript
- Backend: Python FastAPI
- Database: Snowflake
- Auth later: Microsoft Entra ID

Rules:
- Do not hardcode secrets.
- Use environment variables.
- Frontend must never connect directly to Snowflake.
- Backend reads only from Snowflake views.
- Keep code simple and production-ready.

Main views:
- CORTEX.VW_CUSTOMER_HEALTH_SCORE
- CORTEX.VW_CUSTOMER_HEALTH_TREND
- CORTEX.VW_CUSTOMER_ALERTS
