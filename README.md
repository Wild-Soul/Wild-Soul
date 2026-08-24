<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:191724,45:403d52,80:c4a7e7,100:ebbcba&height=220&section=header&text=Rohit%20Kumar&fontSize=70&fontColor=e0def4&animation=fadeIn&fontAlignY=40)

<a href="https://github.com/0x1DKFA"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3500&pause=1000&color=F6C177&center=true&vCenter=true&width=750&height=45&lines=Backend+Engineer+%E2%80%A2+Distributed+Systems;I+build+high-volume+messaging+infrastructure+in+Go;Production+RCA+is+my+favorite+kind+of+puzzle;Teaching+a+VLM+to+spot+viral+gameplay+moments" alt="Typing intro" /></a>

<br/>

<a href="https://dev.to/_cicada"><img src="https://img.shields.io/badge/dev.to-191724?style=for-the-badge&logo=devdotto&logoColor=e0def4" /></a>
<a href="https://stackoverflow.com/users/12846701/cicada"><img src="https://img.shields.io/badge/Stack_Overflow-191724?style=for-the-badge&logo=stackoverflow&logoColor=f6c177" /></a>
<a href="mailto:rohitkk074@gmail.com"><img src="https://img.shields.io/badge/Gmail-191724?style=for-the-badge&logo=gmail&logoColor=eb6f92" /></a>

![Profile views](https://komarev.com/ghpvc/?username=0x1DKFA&label=Profile%20views&color=c4a7e7&style=flat)

</div>

---

### 👨‍💻 About Me

I'm a backend engineer building **high-volume messaging infrastructure in Go** — send pipelines, queue consumers, Temporal workflows, and the **PostgreSQL · Elasticsearch · Redis** layers underneath them.

The part of the job I'd do for free is **production root-cause analysis**: a spiking graph, a hunch, a query plan, and the story of what actually happened.

> *Every incident tells a story — I like reading it in the original telemetry.*

- 🛡️ Security-curious by habit — data-access-layer audits at work, **PortSwigger & TryHackMe** after hours
- 🌱 Currently building [**viral**](https://github.com/0x1DKFA/viral) — a scout + detail VLM pipeline that turns long gameplay recordings into ready-to-post 9:16 highlight clips, running Qwen3-VL locally on a single GPU
- ✍️ I write at [dev.to/_cicada](https://dev.to/_cicada)
- 📫 Reach me at **rohitkk074@gmail.com**

<details>
<summary>🗺️ <b>my week, as a systems diagram</b></summary>
<br/>

```text
┌─ day job ──────────────────────────────────────────────────┐
│                                                            │
│   messages ─▶ [api] ─▶ (queues) ─▶ {consumers} ─▶ storage  │
│   storage = postgres · elasticsearch · redis               │
│   long-running side effects ─▶ temporal workflows          │
│   all of it in Go, at volumes where query plans matter     │
│                                                            │
└────────────────────────────┬───────────────────────────────┘
                             │  pager goes off
                             ▼
┌─ incident mode ────────────────────────────────────────────┐
│   telemetry ─▶ hunch ─▶ query plans ─▶ root cause ─▶ fix   │
│   favorite part of the job — would do it for free          │
└────────────────────────────┬───────────────────────────────┘
                             │  off the clock
                             ▼
┌─ after hours ──────────────────────────────────────────────┐
│   viral ─▶ a VLM watches gameplay, finds the hype,         │
│           and cuts 9:16 shorts (Qwen3-VL, one GPU)         │
│   offsec reps ─▶ PortSwigger labs · TryHackMe              │
└────────────────────────────────────────────────────────────┘
```

</details>

---

### 🚀 Things I've Built

| Project | What it is |
|---|---|
| [viral](https://github.com/0x1DKFA/viral) | A two-stage VLM pipeline (Qwen3-VL, local GPU) that scouts long gameplay recordings for viral moments, scores and re-cuts them at high resolution, and produces 9:16 clips with titles, hashtags, and a stitched highlight reel |
| [go-fts-engine](https://github.com/0x1DKFA/go-fts-engine) | A full-text search engine in Go, built on an inverted index |
| [shell](https://github.com/0x1DKFA/shell) | A Unix shell written from scratch in Go |
| [rss-feed-agg](https://github.com/0x1DKFA/rss-feed-agg) | An RSS feed aggregator in Go |
| [Low-Level-Design](https://github.com/0x1DKFA/Low-Level-Design) | Classic low-level-design problems implemented in Go |

---

### 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=go,ts,js,py,cpp,postgres,elasticsearch,redis,nodejs&theme=dark&perline=9" alt="Languages and data" />
<br/>
<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,rabbitmq,pytorch,grafana,linux,git,bash&theme=dark&perline=9" alt="Cloud and tools" />

<br/><br/>

<img src="https://img.shields.io/badge/Temporal-191724?style=flat-square&logo=temporal&logoColor=c4a7e7" />
<img src="https://img.shields.io/badge/gRPC-191724?style=flat-square&logoColor=9ccfd8" />
<img src="https://img.shields.io/badge/Amazon_SQS-191724?style=flat-square&logo=amazonsqs&logoColor=ebbcba" />
<img src="https://img.shields.io/badge/New_Relic-191724?style=flat-square&logo=newrelic&logoColor=f6c177" />

</div>

---

### 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=0x1DKFA&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=191724&title_color=ebbcba&icon_color=f6c177&text_color=e0def4&ring_color=c4a7e7" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=0x1DKFA&layout=compact&hide_border=true&bg_color=191724&title_color=ebbcba&text_color=e0def4" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=0x1DKFA&hide_border=true&background=191724&ring=ebbcba&fire=f6c177&currStreakNum=e0def4&sideNums=e0def4&currStreakLabel=c4a7e7&sideLabels=c4a7e7&dates=6e6a86" alt="GitHub Streak" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=0x1DKFA&hide_border=true&area=true&bg_color=191724&color=c4a7e7&line=ebbcba&point=f6c177&area_color=403d52&title_color=e0def4" />

</div>

---

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/0x1DKFA/0x1DKFA/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/0x1DKFA/0x1DKFA/output/github-contribution-grid-snake.svg" />
  <img src="https://raw.githubusercontent.com/0x1DKFA/0x1DKFA/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake" />
</picture>

### ☕ *"Build. Break. Learn. Repeat."* 🎧

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:ebbcba,20:c4a7e7,55:403d52,100:191724&height=120&section=footer)

</div>
