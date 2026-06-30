# Ølands Service System v1

Cloned from the Nordic Auto Care system.

Customer site: `/`
Backend routes: `/admin`, `/backend`, `/backend-home`, `/backend-start`
Version check: `/version`

Prototype backend PIN: `2026`

Notes:
- The full customer booking flow and backend order/invoice/service/company modules are preserved.
- Branding has been changed to Ølands Service.
- Default phone number is 26848789.
- Services/packages are still the cloned starter data and can be changed in the backend Services module.
- Deployment metadata is set for Vercel with Node 24.x and npm 10.9.4 downgrade before npm ci.
