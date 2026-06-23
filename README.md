# cloud-computing-demo-2026

A simple Hello World Node.js app deployed to DigitalOcean App Platform.

## Deploy

1. Push this repository to GitHub.
2. In the [DigitalOcean control panel](https://cloud.digitalocean.com/apps), click **Create** → **Apps**.
3. Choose **GitHub** as the source and select `MarkiyanFostyak/cloud-computing-demo-2026` on the `main` branch.
4. DigitalOcean should detect `package.json` as a Node.js web service. If settings look wrong, click **Edit App Spec** and confirm it matches `.do/app.yaml` in this repo.
5. Click **Create Resources**. After the first deploy finishes, your site will be live at the generated `*.ondigitalocean.app` URL.

With `deploy_on_push: true` in the app spec, every `git push` to `main` triggers a new deployment automatically.

## Local preview

```bash
npm start
```

Then open http://localhost:8080
