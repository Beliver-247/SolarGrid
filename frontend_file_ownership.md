# Solargrid-Web — File Ownership by Application Feature

**Project:** Smart Solar Microgrid Trading System  
**Layer:** Frontend Web Portal (`solargrid-web`)

---

## 🔐 IT22110084 — Mendis J.D.L.
### Feature: Authentication & Web User Management
*Handles login state, context, protected routes, and staff user management view.*

| File | Purpose |
|:---|:---|
| `src/api/authApi.js` | API integration for login |
| `src/api/usersApi.js` | API integration for user CRUD |
| `src/auth/AuthContext.jsx` | Global authentication state and JWT handling |
| `src/pages/auth/Login.jsx` | Login page UI |
| `src/pages/users/UserList.jsx` | Staff management UI |
| `src/routes/ProtectedRoute.jsx` | Route guard for authenticated users |
| `src/routes/ProtectedRoute.test.jsx` | Tests for route guard |

**Total: 7 files**

---

## 👤 IT22149930 — Rathnayaka D.M.B.H.
### Feature: Prosumer Management & Shared Infrastructure
*Handles prosumer directory, global styles, build configuration, and base API setup.*

| File | Purpose |
|:---|:---|
| `src/api/axios.js` | Axios instance with auth interceptors |
| `src/api/prosumersApi.js` | API integration for prosumers |
| `src/pages/prosumers/ProsumerList.jsx` | Prosumer directory and activation UI |
| `src/App.jsx` | Root React component |
| `src/main.jsx` | React DOM entry point |
| `src/index.css` | Global CSS styles |
| `index.html` | Base HTML template |
| `package.json` | Dependencies and NPM scripts |
| `vite.config.js` | Vite bundler configuration |
| `tailwind.config.js` | Tailwind CSS configuration |
| `postcss.config.js` | PostCSS configuration |
| `.env.development` | Local environment variables |
| `.env.production` | Production environment variables |

**Total: 13 files**

---

## ⚡ IT22189776 — Kodithuwakku I.P.
### Feature: Station Management & Core UI Components
*Handles solar station management interface and reusable generic UI components used across the app.*

| File | Purpose |
|:---|:---|
| `src/api/stationsApi.js` | API integration for stations |
| `src/pages/nodes/StationList.jsx` | Station management UI |
| `src/components/ui/Button.jsx` | Reusable button component |
| `src/components/ui/EmptyState.jsx` | Reusable empty state component |
| `src/components/ui/ErrorBanner.jsx` | Reusable error message component |
| `src/components/ui/Input.jsx` | Reusable form input component |
| `src/components/ui/LoadingSpinner.jsx` | Reusable loading indicator |
| `src/components/ui/Modal.jsx` | Reusable modal dialog component |

**Total: 8 files**

---

## 📅 IT22239198 — Thassara M.P.M.
### Feature: Reservation Management & Layout/Routing
*Handles reservation approvals UI, application navigation, sidebar, and main routing structure.*

| File | Purpose |
|:---|:---|
| `src/api/reservationsApi.js` | API integration for reservations |
| `src/pages/reservations/ReservationList.jsx` | Reservation approvals UI |
| `src/components/layout/Layout.jsx` | Main application shell/layout |
| `src/components/layout/Sidebar.jsx` | Navigation sidebar UI |
| `src/routes/AppRoutes.jsx` | Central routing definition |
| `src/setupTests.js` | Jest/Vitest setup configuration |

**Total: 6 files**

---

## Summary

| Index No. | Name | Feature | Files |
|:---|:---|:---|:---:|
| IT22110084 | Mendis J.D.L. | 🔐 Authentication & Web User Management | 7 |
| IT22149930 | Rathnayaka D.M.B.H. | 👤 Prosumer Management & Shared Infrastructure | 13 |
| IT22189776 | Kodithuwakku I.P. | ⚡ Station Management & Core UI Components | 8 |
| IT22239198 | Thassara M.P.M. | 📅 Reservation Management & Layout/Routing | 6 |
| | | **Total** | **34** |
