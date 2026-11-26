# nodejs-ci-example

A simple Node.js application for CI with GitHub Actions lab (Lab 6 – Continuous Integration).

- `calculator.js` – add / subtract / multiply / divide
- `calculator.test.js` – Jest unit tests
- `index.js` – simple HTTP server (port 3000)
- `Dockerfile` – container image
- `.github/workflows/nodejs.yml` – CI: build & test on push/PR to `main`, then build & push Docker image on push to `main`

```bash
npm install
npm test
```
