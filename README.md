<div align="center">

<!-- HERO TERMINAL BADGE -->
<p>
  <a href="https://github.com/HaoHV2k5">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=16&pause=1000&color=38BDF8&center=true&vcenter=true&width=580&lines=%3E_++HAOHV+%C2%B7+JAVA+BACKEND+ENGINEER;SCALABLE+DISTRIBUTED+SYSTEMS+%C2%B7+SPRING+BOOT;HIGH+CONCURRENCY+%C2%B7+REDIS+%C2%B7+FULL+OBSERVABILITY" alt="Typing SVG" />
  </a>
</p>

# <b>Huỳnh Văn Hào</b>

<p>
  <strong>☕ Java Backend Developer</strong> • <em>FPT University Senior (GPA 3.3/4.0)</em> • <em>FPT Software Academy Grade A</em>
</p>

<p>
  <a href="mailto:magicmath2k5@gmail.com"><img src="https://img.shields.io/badge/Email-magicmath2k5%40gmail.com-0a0e17?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email" /></a>
  <a href="https://linkedin.com/in/huỳnh-văn-hào-1002ba28b"><img src="https://img.shields.io/badge/LinkedIn-Huỳnh_Văn_Hào-0a0e17?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn" /></a>
  <a href="https://github.com/HaoHV2k5"><img src="https://img.shields.io/badge/GitHub-HaoHV2k5-0a0e17?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <img src="https://img.shields.io/badge/Location-Ho_Chi_Minh_City,_VN-0a0e17?style=for-the-badge&logo=googlemaps&logoColor=34D399" alt="Location" />
</p>

</div>

---

### <code>01. about</code>

> *"You may delay, but time will not"* — Engineering robust, high-throughput, and clean distributed architectures.

- 🎓 **Academic Background**: Final-year Software Engineering student at **FPT University** (GPA: **3.3 / 4.0**).
- 🏆 **Enterprise Delivery**: Team Leader & Core Backend Developer at **FPT Software Academy** (Enterprise OJT Trainee — **Grade A**, Top Evaluation).
- 🌏 **Global Experience**: Completed an intensive academic exchange at **HELP University (Kuala Lumpur, Malaysia)** in an English-first engineering cohort.
- 🎯 **Engineering Focus**: Designing resilient RESTful microservices, preventing race conditions under high concurrency, implementing defense-in-depth Spring Security, containerizing CI/CD with Docker & Harbor, and telemetry via Grafana.

---

### <code>02. stack</code>

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>☕ Backend & Core</h4>
      <p>
        <img src="https://skillicons.dev/icons?i=java,spring,hibernate,maven,python,nodejs" height="38" alt="Backend Stack" />
      </p>
      <p>
        <kbd>Java 17 / 21</kbd> <kbd>Spring Boot 3</kbd> <kbd>Spring Security</kbd> <kbd>Hibernate / JPA</kbd> <kbd>RESTful API</kbd> <kbd>Maven</kbd> <kbd>MapStruct</kbd> <kbd>Python</kbd> <kbd>Node.js</kbd>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>🗄️ Data & In-Memory</h4>
      <p>
        <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,supabase,firebase" height="38" alt="Data & Messaging Stack" />
      </p>
      <p>
        <kbd>PostgreSQL</kbd> <kbd>MySQL</kbd> <kbd>SQL Server</kbd> <kbd>Redis (Cache & Locks)</kbd> <kbd>Supabase</kbd> <kbd>Firebase Realtime</kbd>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🚀 DevOps & Infrastructure</h4>
      <p>
        <img src="https://skillicons.dev/icons?i=docker,linux,githubactions,nginx,cloudflare,aws" height="38" alt="DevOps Stack" />
      </p>
      <p>
        <kbd>Docker</kbd> <kbd>Linux VPS</kbd> <kbd>GitHub Actions (CI/CD)</kbd> <kbd>Harbor Registry</kbd> <kbd>Cloudflare Tunnel (Zero Trust)</kbd> <kbd>Nginx</kbd>
      </p>
    </td>
    <td width="50%" valign="top">
      <h4>📊 Observability & Quality</h4>
      <p>
        <img src="https://skillicons.dev/icons?i=grafana,prometheus,postman,git" height="38" alt="Observability Stack" />
      </p>
      <p>
        <kbd>Grafana (Alloy / Loki / Mimir / Tempo)</kbd> <kbd>Prometheus</kbd> <kbd>Telegram Alert Bot</kbd> <kbd>JUnit 5 & Mockito</kbd> <kbd>Postman</kbd>
      </p>
    </td>
  </tr>
</table>

---

### <code>03. engineering</code>

Engineering practices and production-ready architectural decisions applied across real-world systems:

- 🛡️ **High Concurrency & Transaction Integrity**:
  - Engineered inventory reservation and event ticket management algorithms leveraging **Redis multi-level caching** and **atomic decrement operations**, eliminating double-booking race conditions during high-demand surges.
  - Implemented transaction-level connection management via **HikariCP** and **PgBouncer** connection pooling to avoid connection starvation under load.
- 🔐 **Defense-in-Depth Security**:
  - Architected stateless security flows in **Spring Security 6** featuring **Refresh Token Rotation (RTR)**, token reuse detection, and client metadata tracking (IP address & User-Agent).
  - Built granular **Role-Based Access Control (RBAC)**, anti-brute-force rate limiting, and OTP email flows with timed expiration.
- 🚢 **Automated CI/CD & Zero-Trust Cloud**:
  - Automated production delivery via **GitHub Actions** with multi-stage Docker buildx, publishing immutable SHA-tagged artifacts to a private **Harbor Registry**.
  - Protected production VPS instances with **Cloudflare Tunnel (Zero Trust)** — completely eliminating open inbound public ports and shielding the host network from external port scanning.
- 📈 **Full-Stack Telemetry (LGTM Stack)**:
  - Deployed **Grafana Alloy** collector agent piping structured JSON logs to **Loki**, JVM/system metrics to **Mimir & Prometheus**, and distributed traces to **Tempo**.
  - Configured proactive threshold alert rules connected directly to a **Telegram Alert Bot** for instantaneous production incident response.

---

### <code>04. projects</code>

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>🎟️ <a href="https://github.com/HaoHV2k5/tikzy">Tikzy Marketplace</a></h3>
      <p><em>Production Event Ticketing Platform</em></p>
      <p>High-concurrency marketplace with ticket inventory reservation, Redis caching, multi-stage Docker/Harbor CI/CD, Cloudflare Zero Trust, and Grafana observability.</p>
      <p>
        <kbd>Java 21</kbd> <kbd>Spring Boot 3</kbd> <kbd>PostgreSQL</kbd> <kbd>Redis</kbd> <kbd>Harbor</kbd> <kbd>Grafana</kbd>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>🚗 <a href="https://github.com/HaoHV2k5/SWP391-SecondhandEV-Battery-Trading-Platform">EV & Battery Trading</a></h3>
      <p><em>E-Commerce & Digital Contract</em></p>
      <p>Specialized commercial platform for buying/selling second-hand EVs & batteries with integrated VNPay payment gateway and Eversign digital contracts.</p>
      <p>
        <kbd>Java 17</kbd> <kbd>Spring Boot</kbd> <kbd>MySQL</kbd> <kbd>Spring Security</kbd> <kbd>VNPay</kbd> <kbd>Eversign</kbd>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>💖 <a href="https://github.com/HaoHV2k5/UniDate">UniDate Platform</a></h3>
      <p><em>AI Campus Dating & Social</em></p>
      <p>Campus matchmaking platform featuring Google Gemini AI for smart icebreaker generation and interest compatibility, with low-latency Firebase chat.</p>
      <p>
        <kbd>Java 17</kbd> <kbd>Spring Boot</kbd> <kbd>SQL Server</kbd> <kbd>Firebase</kbd> <kbd>Gemini AI</kbd> <kbd>Cloudinary</kbd>
      </p>
    </td>
  </tr>
</table>

---

### <code>05. experience</code>

```text
[2026.01 — 2026.04]  FPT Software Academy
                      Role: Trainee | Team Leader & Backend Developer
                      Milestone: Grade A (Top Evaluation) • Cafe Franchise Management System
                      Impact: Led sprint execution, designed microservices & RBAC security, automated CI/CD.

[Academic Exchange]   HELP University — Kuala Lumpur, Malaysia
                      Role: International Study Program Student
                      Milestone: Completed global curriculum in an English-first technical environment.

[Community & DSA]     FPT University & "Wisdom Seeker" Channel
                      Role: Competitive Programmer & Channel Founder
                      Milestone: Ftalent algorithm contestant • ~1,000 developer community followers.
