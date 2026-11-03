# SmartHR

Clickable prototype of an HR platform for US companies: sign up, log in, invites, three roles (HR Admin, Manager, Employee), people directory and org chart, onboarding, time off, bi-weekly payroll, benefits enrollment, performance reviews and reports.

This is a single-file front-end prototype. All data is stored in the browser (local storage). Authentication is simulated and is not secure. Do not enter real personal data.

## Run

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

## Demo accounts

Use the demo buttons on the login page (HR Admin, Manager, Employee). The password for every demo account is `Demo#2026`. A pending invite exists for `zoe.carter@northwind.example` (use "Set up your account").

## Deploy to Vercel

This is a static site with no build step.

1. In Vercel, choose Add New, then Project, and import this repository.
2. Set Framework Preset to Other. Leave the build command and output directory empty.
3. Deploy. Every push to `main` redeploys automatically.

Turn on Deployment Protection in the Vercel project settings if the demo should not be public.

This build is a demo. Accounts and data live in each visitor's browser, so it must not be used with real employee data. A production version needs the backend described in the technical design.
