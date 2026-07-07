# System Overview Diagram — ai-platform-engineering-portfolio

```mermaid
flowchart TD
    User[User] --> Frontend[Next.js Frontend]
    Frontend --> API[API Routes]
    API --> Auth[Authentication / Access Logic]
    API --> DB[(Supabase PostgreSQL)]
    API --> Admin[Admin Dashboard]
    Admin --> Reports[Search / Pagination / Export]
```

## Disclaimer

> This schema is a sanitized learning version based on independent development work. It does not contain production data, private credentials, proprietary logic, or real customer records.
