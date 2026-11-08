### Hi, I'm Tham

Junior DevOps / Cloud engineer. I like scripts, pipelines and things that run by themselves.
Open to Junior DevOps / Cloud roles in Bangkok.

[skez.codes](https://skez.codes) · [LinkedIn](https://www.linkedin.com/in/tham-kaeoket/) · [tham.kaeoket@gmail.com](mailto:tham.kaeoket@gmail.com)

---

#### Try my work in the browser (no login, fake data)

| Project | What it is | Live demo | Code |
|---|---|---|---|
| **Daily Monitoring Automation** | n8n workflows + dashboard that collect daily health-check reports for many servers. Cut a 1–2 hour manual routine to about 5 minutes. | [skez.codes/demo/monitoring](https://skez.codes/demo/monitoring) | [dashboard](https://github.com/5kez/automate-daily-monitoring) · [n8n backend](https://github.com/5kez/n8n-server-monitoring) |
| **Smart Bed** | Hospital bed monitoring: sensors over MQTT → NestJS API → live dashboard with alerts. | [skez.codes/demo/smartbed](https://skez.codes/demo/smartbed) | [backend](https://github.com/5kez/backend_bedproject) · [frontend](https://github.com/5kez/frontend_bedproject) |

#### Run the full Smart Bed stack yourself, one command

```bash
git clone https://github.com/5kez/backend_bedproject && cd backend_bedproject
docker compose -f compose.demo.yml up --build --wait   # then open http://localhost:8080
```

MySQL, Mosquitto, the API, a sensor simulator and the web app start in order, with healthchecks.
Or open the repo in GitHub Codespaces. CI boots this same stack and smoke-tests it on every push.

---

#### Tools I use

**Ops:** Linux · Bash · Docker · Docker Compose · GitHub Actions · nginx · n8n
**Code:** Python · TypeScript / Node.js (NestJS) · SQL (MySQL)
**Messaging:** MQTT (Mosquitto) · Socket.IO
