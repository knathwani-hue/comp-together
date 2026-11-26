# COMP Together

Individual study schedules with private notes and shared accountability.

## Website

GitHub Pages is configured to publish `main` from the repository root.

## Connect the database

1. Sign in at https://supabase.com/dashboard and create a free project.
2. Run `setup.sql` once in the SQL Editor of the new project.
3. Set Authentication > URL Configuration > Site URL to the deployed GitHub Pages URL. Keep email confirmation enabled.
4. Copy the project URL and public publishable key (or legacy anon key) into the website. Never use a secret or service-role key.
5. Each student creates their own account and confirms their email.
6. Load the original plan or build an individual schedule, then Save & sync.
7. Create an invite and send its single-use code privately to your partner. They select Join partner.

Schedules and notes are private to their account. Only paired accounts can read one another's aggregate progress. Save & sync publishes the latest totals; Refresh accountability retrieves them. Stop sharing removes the pairing.

Use separate test accounts to verify permissions before adding private notes. Avoid editing the same account in multiple tabs: the last save wins. Backend setup and cross-account behavior are pending live verification.
