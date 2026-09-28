# MNU Community — static MVP package

Upload the contents of this folder to the document root of a static hosting service. Keep `index.html`, `app.js`, and `styles.css` together, and keep the `assets/` folder beside them. The package has no build step or third-party JavaScript dependencies. Use HTTPS; browser-side password hashing requires a secure context.

## Included product flows

- Student-organization catalog, search, category filters, and interest questionnaire.
- Registration, sign-in, profile settings, sign-out, and account-specific demo state.
- Application contacts, selection stage, and clearly labeled simulated organization approval.
- AI Club sample page with events, announcements, contacts, and downloadable event photos.
- Three-step organization proposal form, notifications, help, and feedback form.

## Demo-account and data limits

This package is a static, browser-local MVP. Accounts, profiles, applications, RSVPs, proposed organizations, and feedback stay in the visitor's current browser and do not sync to a server. The password is stored only as a salted PBKDF2 hash in that browser, but this is not a production authentication system. There is no student identity verification, email confirmation, password reset, server-side authorization, shared database, or actual transmission of applications/feedback. The organization approval control is a demo simulation. Sample organizations, contacts, member counts, events, and photos are illustrative.

Do not use real university passwords or collect real student application data with this static demo. Before production, connect an approved MNU identity flow, server-side sessions and role checks, persistent database, email verification, and managed photo storage. MNU's identity provider, email-domain policy, API availability, and deployment requirements are not verified in this package.
