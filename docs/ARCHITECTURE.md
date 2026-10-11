# Architecture

The worker and admin pages load same-origin browser modules from `public/`. `demo-data.mjs` creates three fictional workers in the current Cambodia week. `time-logic.mjs` calculates intervals and overrides; `state-logic.mjs` validates and projects saved data. `display.mjs` formats visible text. `app.js` coordinates view selection, corrections, approvals, language and reset.

Changes are stored only in a separate fictional local-storage namespace. The app never reads the original operational key. The view selector is navigation; it does not represent authentication. Names are escaped or rendered as text. HTML Content Security Policy denies script-initiated connections, workers and form submission.

`server.mjs` binds loopback and serves only `public/`. The Pages workflow runs the Node test suite, then uploads only that same directory. Tests, documentation, and historical source are excluded from the hosted artifact. There is no backend, model API, credential, usage bill, or production database connection in the demo.
