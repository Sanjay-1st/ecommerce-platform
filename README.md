# E-Commerce Platform

A monorepo combining an admin panel and a customer-facing storefront, both built with React and sharing the same Firebase Realtime Database.

## Structure
- `myadmin/` — Admin panel: manage products and customers (add/list)
- `ecommerce/` — Storefront: browse products, login page

## Tech stack
- React 18, React Router, Bootstrap / React-Bootstrap
- Firebase Realtime Database (shared between both apps) and Firebase Authentication
- Create React App (`react-scripts`)

## How to run
Each app runs independently:
```
cd myadmin
npm install
npm start
```
```
cd ecommerce
npm install
npm start
```

## Known limitations
- Sign-up forms are not fully wired up to create real accounts in either app.
- No shared component library yet — the two apps don't share code, only the backend database.
- A Firebase Web API key is present in the admin panel's source (`myadmin/src/pages/SignIn.jsx`). This is expected for Firebase web apps, but real protection comes from Firebase's database security rules, not from hiding the key.

## Status
Combining two previously separate practice projects (admin panel, built first; storefront, built shortly after) into one repo for easier management.

## Versioning
This project follows [Semantic Versioning](https://semver.org/). See `CHANGELOG.md` for release history.
`v0.1.0` is the preserved baseline captured before any further improvements.
