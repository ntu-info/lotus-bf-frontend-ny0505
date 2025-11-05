# LoTUS-BF Frontend

## Setup Instructions

1. Install dependencies:
   ```sh
   npm install
   ```
2. Start the development server:
   ```sh
   npm run dev
   ```
3. Build for production:
   ```sh
   npm run build
   ```

## App URLs
- `/` — Home (full layout)
- `/terms` — Terms page
- `/query` — QueryBuilder page
- `/studies` — Studies page
- `/viewer` — NiiViewer page

## Features
- Search for brain function terms
- Build queries and view related studies
- Interactive NiiViewer for brain images
- Responsive layout with resizable panes

## Favicon
A `favicon.ico` is included in the `public` folder. You can replace it with your own icon if desired.

## Troubleshooting
- If you see a blank page, check your browser console for errors.
- Make sure all dependencies are installed and the dev server is running.

## Notes
- For server deployment, upload the `dist` folder after running `npm run build`.

---

nvm install --lts # for solving 
rm -rf node_modules package-lock.json # delete all incompatible packages
npm install # reinstall every packages according to pacakge.json
npm run dev # for local development
npm run build # for server deployment; upload the ./dist folder to a server
