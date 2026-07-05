# GercepAI Database Standards

## Database

PostgreSQL powered by Supabase.

---

## Core Tables

- users
- companies
- teams
- roles
- permissions
- subscriptions
- customers
- inventory
- products
- finance
- invoices
- expenses
- notifications
- audit_logs

---

## Rules

- UUID Primary Keys
- created_at
- updated_at
- Soft Delete when required
- Foreign Keys
- Index Frequently Queried Columns

---

## Migration Rules

- Version Controlled
- Reversible
- No Direct Production Changes
