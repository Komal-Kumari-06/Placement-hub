# Setu · IGDTUW Careers

A React and Vite placement portal concept connecting IGDTUW students with employers. It includes a responsive dashboard, searchable mock opportunities, saved and applied role states, application tracking, and distinct student/company sign-up forms.

## Run locally

```sh
npm install
npm run dev
```

Use the registration screen to preview the student and company dashboards. The mock experience accepts any valid email and an eight-character password; it does not create or verify real accounts. Registration selections and dashboard actions are demo state held in the browser session.

## Before production

Replace the demo sign-in handler with a server-side identity provider, verified IGDTUW student enrollment, verified company domains/recruiters, secure httpOnly session cookies, server-side authorization for every role and action, rate limits, CSRF protection, password reset and account recovery, privacy/consent controls, and secure document storage. Never store real passwords or sensitive application data in browser storage.
