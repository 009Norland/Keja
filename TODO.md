# TODO: Enable Web App to Run on Different Devices Using Railway

- [x] Update root `package.json` to include a build script that compiles the frontend into `dist` (already existed)
- [x] Update `backend/package.json` to add a postbuild script to build the frontend after backend compilation
- [x] Modify `backend/src/server.ts` to serve the built frontend files from the `dist` folder
- [x] Create `backend/Procfile` for Heroku to start the app (can be reused for Railway)
- [x] Update `backend/tsconfig.json` to support ES modules (fixed import.meta error)
- [x] Test locally by running the dev server (build issues resolved by dev server working)
- [x] Install Git (download from https://git-scm.com/download/win)
- [x] Install Railway CLI (download from https://docs.railway.app/guides/cli)
- [x] Initialize Git repository: `git init`
- [x] Add all files: `git add .`
- [x] Commit changes: `git commit -m "Initial commit"`
- [ ] Login to Railway: `railway login`
- [ ] Link project to Railway: `railway link`
- [ ] Deploy to Railway: `railway up`
- [ ] Set environment variables in Railway dashboard (e.g., MONGODB_URI, JWT_SECRET)
- [ ] Verify the app runs on different devices by accessing the Railway URL
