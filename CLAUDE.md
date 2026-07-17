\# CLAUDE.md



Guidance for Claude Code (or any AI assistant) working in this repo.



\## Project



Portfolio site for Aalok Niroula — proves fast, solo, end-to-end web

application delivery. Built as the FlyRank AI Fluency capstone.



\## Stack



\- \*\*Framework\*\*: Next.js (App Router)

\- \*\*Styling\*\*: Tailwind CSS

\- \*\*Database/Auth\*\*: Supabase

\- \*\*ORM\*\*: Prisma

\- \*\*Media\*\*: Cloudinary

\- \*\*Deploy\*\*: Vercel



\## Conventions



\- Commits follow Conventional Commits (feat:, fix:, docs:, chore:, etc.)

\- Components live in /components, one component per file, PascalCase filenames.

\- Server logic and DB clients live in /lib — never instantiate Supabase/Prisma

&#x20; clients inline in components.

\- Prefer server components by default; only use "use client" when interactivity

&#x20; is required.

\- Keep case-study content data-driven (e.g. a /lib/projects.ts array) rather than

&#x20; hardcoded into JSX, so pages stay easy to update.



\## What to prioritize when assisting



1\. Working, deployable code over premature abstraction.

2\. Clear commit messages over large uncommented diffs.

3\. Accessibility basics (semantic HTML, alt text, contrast) on every page.

