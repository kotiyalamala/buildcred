# BlocBIM MVP Interface

A self-contained, clickable front-end prototype for the BlocBIM construction finance platform.

## Run it
1. Extract the ZIP file.
2. Open the `BlocBIM_MVP_Interface` folder.
3. Double-click `index.html` to open it in Chrome or Edge.

No installation, server, API key, or payment account is required for this first UI prototype.

## Included screens
- Overview dashboard
- Projects (create and search demo projects)
- BIM Models (IFC file selection placeholder)
- BOQ Management (add BOQ items)
- Milestones (add payment milestones)
- Progress Verification (demo approval flow)
- Smart Contracts (simulation status)
- Payments
- Transactions

## Important prototype limitations
- All data is local in browser memory and resets when the page is refreshed.
- Demo figures and transaction references are illustrative.
- The IFC upload control only selects a file; it does not parse or render the model yet.
- Smart-contract and payment screens are simulations. No blockchain transaction or real-money transfer occurs.
- Authentication, persistent database, production security, IFC parsing, actual 3D model viewing and audited smart contracts are future development stages.

## Next development stage
Move this prototype into the planned Next.js + Python/FastAPI + PostgreSQL + IFC + Solidity architecture, then implement persistence, authentication and real IFC model processing.
