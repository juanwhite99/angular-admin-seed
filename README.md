# AngularAdminSeed

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.2.

#### Templates source
This project is using modified templates coming from:
https://www.codinglabweb.com


### CLI

```bash
# ============ Auth
npx ng g m modules/auth --route auth -m app
npx ng g c modules/auth/components/auth
npx ng g c modules/auth/components/auth/login
npx ng g c modules/auth/components/auth/register

# ============ Dashboard
npx ng g m modules/dashboard --route dashboard -m app

# ============ Guards and Services
npx ng g g guards/auth
npx ng g s services/auth

```
