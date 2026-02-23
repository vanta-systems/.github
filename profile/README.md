<div align='center'>

# Vanta Systems

**Enterprise-grade Discord systems, internal control plane, and operational telemetry.**  
Part of the Vanta ecosystem.

<br/>

<img alt='CI' src='https://img.shields.io/badge/CI-passing-2ea44f?style=flat-square' />
<img alt='Release cadence' src='https://img.shields.io/badge/releases-every%2010%20patches-5865F2?style=flat-square' />
<img alt='Status' src='https://img.shields.io/badge/status-online-2ea44f?style=flat-square' />
<img alt='Artifacts' src='https://img.shields.io/badge/artifacts-GHCR-0f172a?style=flat-square' />

<br/>

<img alt='Node' src='https://img.shields.io/badge/node-20.x-2ea44f?style=flat-square' />
<img alt='TypeScript' src='https://img.shields.io/badge/typescript-5.x-3178c6?style=flat-square' />
<img alt='MongoDB' src='https://img.shields.io/badge/mongodb-atlas-10aa50?style=flat-square' />
<img alt='Discord.js' src='https://img.shields.io/badge/discord.js-v14-5865F2?style=flat-square' />
<img alt='Deploy' src='https://img.shields.io/badge/deploy-railway-7b3fe4?style=flat-square' />

</div>

---

## Quick links

- **Internal API (Swagger):** https://vanta-internal-api-production.up.railway.app/docs
- **Internal API (Health):** https://vanta-internal-api-production.up.railway.app/health
- **Public status:** https://vanta-public-site-production.up.railway.app/public/status

---

## Ecosystem

<table>
  <tr>
    <td width='33%' valign='top'>
      <h3>Vanta Bot</h3>
      <p>Enterprise Discord systems bot: intel, evidence registry, watchlist, audit trails.</p>
      <ul>
        <li><b>Runtime</b>: Docker on Railway</li>
        <li><b>Artifacts</b>: GHCR container images</li>
        <li><b>Releases</b>: every 10 patch tags</li>
      </ul>
      <a href='https://github.com/vanta-systems/vanta-bot'>Repo</a>
    </td>
    <td width='33%' valign='top'>
      <h3>Internal API</h3>
      <p>Authenticated control plane powering bots and dashboards.</p>
      <ul>
        <li><b>Docs</b>: Swagger UI</li>
        <li><b>Auth</b>: service key</li>
        <li><b>Telemetry</b>: heartbeat + metrics</li>
      </ul>
      <a href='https://github.com/vanta-systems/vanta-internal-api'>Repo</a> ·
      <a href='https://vanta-internal-api-production.up.railway.app/docs'>Swagger</a>
    </td>
    <td width='33%' valign='top'>
      <h3>Public Site</h3>
      <p>Status endpoints and public-facing utilities.</p>
      <ul>
        <li><b>Status</b>: uptime + service health</li>
        <li><b>Public</b>: no internal access required</li>
      </ul>
      <a href='https://github.com/vanta-systems/vanta-public-site'>Repo</a>
    </td>
  </tr>
</table>

---

## Engineering

**Release + artifacts**
- Tags are created automatically on successful CI runs to `main`
- A GitHub Release is created every **10 patch versions**
- Releases publish container images to **GitHub Container Registry (GHCR)**

**Principles**
- Internal-first design with public surfaces where appropriate
- Auditability by default (logs, evidence, traceability)
- Automate operational hygiene (CI, releases, deployments)

---

## Security

Do not open public issues for vulnerabilities.  
Report security concerns privately.
