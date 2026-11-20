# ReUseRoute — React + Vite prototype

A responsive B2B surplus-material marketplace concept for the DGU Venture Quest assignment.

## Included features
- Browse sample listings for wood, stone, glass, tiles and metal
- Search by keyword and filter by category/location
- Add a surplus material listing
- View material details and prepare a buyer enquiry
- How it works page and simple activity dashboard
- New listings persist in the current browser using localStorage

## Run locally
Install Node.js LTS. In this folder run:
```bash
npm install
npm run dev
```
Open the local URL shown by Vite (usually http://localhost:5173).

## Build
```bash
npm run build
```
The production files are generated in `dist`.

## Deploy with Vercel
1. Upload the contents of this folder to the root of your GitHub repository. The `src` folder must be at the repository root.
2. In Vercel, import the GitHub repository.
3. Framework preset: **Vite**
4. Root directory: `./`
5. Build command: `npm run build`
6. Output directory: `dist`
7. Click Deploy.

## Prototype limitations
This is a frontend demo, not a production marketplace. Sample listings are illustrative. New listings are stored only in the current browser. Enquiry forms show a demo confirmation and do not send messages. There is no real authentication, shared database, payments, verified inventory or logistics integration. Add a secure backend/database and authentication before real business use.
