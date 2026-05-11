# Pananth HTML Frontend

Repository for the Pananth rental frontend HTML.

Deploy this repo to the Cloudflare frontend Worker/Page:

```text
https://pananth.joteboony.workers.dev
```

GitHub Actions deploy target:

```text
Worker name: pananth
Assets directory: public
```

Important:

- This repo is for the frontend `index.html` only.
- Do not upload `worker.js` here.
- The frontend calls the backend Worker at:

```text
https://white-rice-cf72.joteboony.workers.dev
```

If the backend Worker URL changes later, update `WORKER_URL` in `index.html`.
