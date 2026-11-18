# AGENTS.md

Strict rules for all agents working on the HUST Hotel Booking Web System in this workspace:

1. **Single-File Constraint:** The entire application MUST live in a single `index.html` file. Do NOT create `package.json`, `node_modules`, React/Vue components, or separate `.css`/`.js` files.
2. **Minimal Stack:** Use only Tailwind CSS Play CDN (`https://cdn.tailwindcss.com`) and clean Vanilla JavaScript with `localStorage`.
3. **Scope Guardrails (from Week 3 Report):**
   - **Include:**
     - Guest room search & 5-step booking flow
     - Step 2 overbooking availability formula (`T + min(D, p% * Total)`)
     - Guaranteed vs. Non-guaranteed (`18:00` auto-release)
     - Modify/Cancel with history log & waitlist priority
     - Reception daily arrival/departure list
     - Monthly room density view
     - Manager policy settings
     - Blacklist warning
     - VI/EN language toggle
   - **Exclude:**
     - Online payment gateways
     - CRS/GDS APIs
     - Check-in/check-out room assignment
     - SMS/push notifications
