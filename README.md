# TRACE demo

TRACE is a static prototype for an officer triage workspace and a separate victim intake demonstration. This folder contains the site in `public/` and a small Node.js server for Railway.

## Run locally

Requires Node.js 20 or newer.

```sh
npm start
```

Then open <http://localhost:3000/>.

## Deploy with Railway CLI

From this folder, sign in and deploy:

```sh
railway up
```

Follow the prompts to create or select a Railway project. After deployment, add a public HTTPS domain with:

```sh
railway domain
```

## Prototype limitations

This is a demo only. It has no backend, authentication, database, or connection to NHAA or live case systems. Intake examples and handoff data are fictional and browser-local. Do not enter real names or identifiable case details. Voice pitch/activity observations do not determine emotion, stress, trauma, or risk; browser speech recognition may use the browser's recognition service.
