TRACE · GitHub source + Railway CLI deployment

This folder is a minimal Node static server plus the TRACE website in public/. No application database or NHAA integration is included. All intake cases are fictional/browser-session demo data.

To run locally (Node 20+):
  npm start
Then visit http://localhost:3000/

To deploy with Railway CLI:
  1. Install Railway CLI from its official documentation: https://docs.railway.com/cli
  2. From this folder, run `railway login` and complete Railway's browser sign-in yourself.
  3. Run `railway init` and choose or create a Railway project.
  4. Run `railway up` to upload and deploy this folder.
  5. Run `railway domain` to create a public HTTPS domain. A deployment does not become public until a domain is added.

GitHub source:
  Create a GitHub repository for this folder and push its files. Railway CLI deployment uploads this local folder; it is separate from GitHub's repository integration. To auto-deploy every GitHub push instead, connect the repository to Railway in Railway's project settings.

Voice note: microphone features need HTTPS or localhost. The pitch/activity estimates are local acoustic observations, not emotion or stress recognition. Browser speech-to-text may use the browser's recognition provider. Do not submit real victim data; this is a public-facing prototype with fictional examples and no authentication.
