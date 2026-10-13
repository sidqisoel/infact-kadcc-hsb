# InFacT MVP prototype

Functional browser-based prototype for KADCC and Hospital Sultanah Bahiyah (HSB).

## Run locally

1. Open `dist/index.html` directly in a modern browser, or serve the `dist` folder with any static web server.
2. Use the role switcher in the header to move between Requester, KADCC Operator, Emergency Physician, Manager, Pilot and Live Board.
3. Create a transfer from the Requester view. Choose a destination state outside Kedah to test the mandatory medical-approval gate.
4. Continue the case in the Emergency Physician, Operator and Pilot views.
5. Use Manager → Reports & exports to download the exact 65-column iSPRINT-compatible CSV or the enhanced InFacT CSV.

All records are synthetic. State is stored in the browser's local storage for demonstration only. Use “Reset demo” in the profile menu to restore the seed data.

## Production boundary

This prototype does not provide production authentication, a server database, encryption key management, clinical-system integration, backup, disaster recovery, immutable audit storage, or KKM-approved hosting. Do not enter real patient information. A production deployment requires KKM security, privacy, clinical safety and governance approval, plus formal role-based access, secure identity, encryption, monitoring, retention controls, penetration testing and an approved Malaysian data-hosting architecture.
