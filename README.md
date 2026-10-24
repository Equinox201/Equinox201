# Hi, I'm Nicolas 👋

**Software engineering · AI applications · hospitality technology**
📍 Singapore · 🎓 [42 Singapore](https://42.fr/en/) · 🌍 English & French (native), Spanish (business)

I came into software from hotel revenue management: Cluster Revenue Analyst at **Marriott International** (Hong Kong), then Director of Revenue Management & Sales at **Explorar Hotels & Resorts** (Thailand), with an MSc in International Hospitality Business from Glion. I know the operational problems first-hand.
Now I engineer the solutions: from low-level C (memory, processes, file descriptors) up to full-stack TypeScript and AI systems that people can actually trust.

🔨 **Currently:** [42 Singapore](https://42.fr/en/) final team project **Transcendence**, a five-person platform for comparing how inference-scheduling policies affect latency and system performance (Python/FastAPI, C++ simulation engine, JSON Schema contracts, WebSocket). I coordinate scope as PM and own the researcher-facing Console. It is in development.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nicolas_Samarine-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nicolas-samarine-781102143)
[![Email](https://img.shields.io/badge/Email-nick.samarine@yahoo.fr-555?logo=minutemailer&logoColor=white)](mailto:nick.samarine@yahoo.fr)

---

## ⭐ Featured

<table>
<tr>
<td width="220" align="center" valign="top">
  <a href="https://github.com/Equinox201/SustainOps"><img src="https://raw.githubusercontent.com/Equinox201/SustainOps/main/assets/sustainops.png" width="200" alt="SustainOps"/></a>
</td>
<td valign="top">

### [SustainOps](https://github.com/Equinox201/SustainOps): AI-assisted sustainability operations for hotels

Turns an operational issue (say, rising laundry volume) into an action plan that **cites approved company documents**, with **every policy quotation verified server-side** and a **person reviewing and approving** before anything is locked and tracked against KPIs.

![Next.js](https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Postgres](https://img.shields.io/badge/Postgres_+_pgvector-4169E1?logo=postgresql&logoColor=white)
[![CI](https://github.com/Equinox201/SustainOps/actions/workflows/ci.yml/badge.svg)](https://github.com/Equinox201/SustainOps/actions/workflows/ci.yml)
![Evals](https://img.shields.io/badge/Published_LLM_evals-8A2BE2)

[**Live demo**](https://sustainops.vercel.app) · [**Evaluation results**](https://sustainops.vercel.app/evals) · [Source](https://github.com/Equinox201/SustainOps)

</td>
</tr>
<tr>
<td width="220" align="center" valign="top">
  <a href="https://github.com/Equinox201/TimeTracker42"><img src="https://raw.githubusercontent.com/Equinox201/TimeTracker42/main/assets/timetracker.png" width="200" alt="TimeTracker42"/></a>
</td>
<td valign="top">

### [TimeTracker42](https://github.com/Equinox201/TimeTracker42): attendance pace tracker for 42 students

See whether you are ahead or behind your monthly goal and plan the rest of the month. OAuth sign-in, per-user data isolation with Postgres row-level security, end-to-end tested, installable as a PWA.

![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase_RLS-3ECF8E?logo=supabase&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Pages-F38020?logo=cloudflare&logoColor=white)

[**Live demo**](https://timetracker42.pages.dev/demo) · [Source](https://github.com/Equinox201/TimeTracker42)

</td>
</tr>
</table>

### How SustainOps keeps AI accountable

```mermaid
flowchart LR
    A["Describe the case<br/>property · issue · target"] --> B["Structured AI plan<br/>cites approved documents"]
    B --> C["Server verifies<br/>every policy quotation"]
    C --> D["Human review<br/>owner · dates · checklist"]
    D --> E["Second role approves<br/>plan is locked"]
    E --> F["Track actions<br/>and KPIs to close-out"]
```

---

## 🛠️ Systems programming (42 curriculum, C / C++)

Built from scratch under strict constraints: no external libraries, manual memory management, Norm-compliant code.

<table>
<tr>
<td align="center" valign="top" width="33%">
  <a href="https://github.com/Equinox201/HTTP_Server-Webserv"><img src="https://raw.githubusercontent.com/Equinox201/HTTP_Server-Webserv/main/assets/webserv.png" width="170" alt="Webserv"/></a><br/>
  <b><a href="https://github.com/Equinox201/HTTP_Server-Webserv">Webserv</a></b><br/>
  <sub>HTTP/1.1 server in C++: non-blocking I/O event loop, CGI, request parsing. Passed with bonus.</sub>
</td>
<td align="center" valign="top" width="33%">
  <a href="https://github.com/Equinox201/Unix_Command_Shell"><img src="https://raw.githubusercontent.com/Equinox201/Unix_Command_Shell/main/assets/minishell.png" width="170" alt="Minishell"/></a><br/>
  <b><a href="https://github.com/Equinox201/Unix_Command_Shell">Minishell</a></b><br/>
  <sub>Unix shell in C: parsing, pipes, redirections, environment, process control</sub>
</td>
<td align="center" valign="top" width="33%">
  <a href="https://github.com/Equinox201/Raycasting_Engine_Cub3D"><img src="https://raw.githubusercontent.com/Equinox201/Raycasting_Engine_Cub3D/main/assets/cube3d.png" width="170" alt="Cub3D"/></a><br/>
  <b><a href="https://github.com/Equinox201/Raycasting_Engine_Cub3D">Cub3D</a></b><br/>
  <sub>3D raycasting engine in C: textured rendering, real-time camera (MiniLibX)</sub>
</td>
</tr>
<tr>
<td align="center" valign="top">
  <a href="https://github.com/Equinox201/Multi-threading_Dining_Philosophers"><img src="https://raw.githubusercontent.com/Equinox201/Multi-threading_Dining_Philosophers/main/assets/philo.png" width="170" alt="Philosophers"/></a><br/>
  <b><a href="https://github.com/Equinox201/Multi-threading_Dining_Philosophers">Philosophers</a></b><br/>
  <sub>Concurrency in C: threads, mutexes, deadlock prevention, timing constraints</sub>
</td>
<td align="center" valign="top">
  <a href="https://github.com/Equinox201/Containerized_Infrastructure-Inception"><img src="https://raw.githubusercontent.com/Equinox201/Containerized_Infrastructure-Inception/main/assets/inception.png" width="170" alt="Inception"/></a><br/>
  <b><a href="https://github.com/Equinox201/Containerized_Infrastructure-Inception">Inception</a></b><br/>
  <sub>Docker orchestration and system administration</sub>
</td>
<td align="center" valign="top">
  <a href="https://github.com/Equinox201/Tower_of_Hanoi_Sorting_Algorithm"><img src="https://raw.githubusercontent.com/Equinox201/Tower_of_Hanoi_Sorting_Algorithm/main/assets/pushswap.png" width="170" alt="Push_swap"/></a><br/>
  <b><a href="https://github.com/Equinox201/Tower_of_Hanoi_Sorting_Algorithm">Push_swap</a></b><br/>
  <sub>Sorting under strict operation limits: recursive logic and optimisation</sub>
</td>
</tr>
</table>

<sub>Also: [Escape the Dragon Dungeon](https://github.com/Equinox201/Escape_the_Dragon_Dungeon), a Pac-Man-inspired maze game in C · Full write-ups in [42_Projects](https://github.com/Equinox201/42_Projects).</sub>

---

## 🧰 Toolbox

![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000?logo=nextdotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000?logo=vercel&logoColor=white)

## 🧭 How I work

Predictable systems over clever hacks. Clear responsibility boundaries, defensive programming, explicit error handling, and evidence (tests, evaluations) over claims.

## 🍜 Beyond code

I cook, travel and write about it at **[NomadBowl](https://nomadbowls.cc)**, a site of recipes and stories from around the world. Outside the kitchen: triathlon training, piano, hiking and camping.
