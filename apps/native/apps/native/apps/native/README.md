# Native shell (Capacitor)

Use Capacitor to package `apps/web/dist` for iOS/Android.

## Setup
1. `npm i`
2. `npm run build`
3. `npx cap init kegel.clinical.app KegelClinical`
4. `npx cap add ios && npx cap add android`
5. `npx cap sync`

## Required plugins
- `@capacitor/haptics`
- `@capacitor/local-notifications`
- `@capacitor/preferences`

## Monetization
RevenueCat placeholders are in `apps/web/src/lib/iap.ts`.
