<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=2F81F7&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Tanmay+%F0%9F%91%8B;Backend+%26+Full-Stack+Engineer;Distributed+Systems+%7C+AI%2FLLM+Tooling;Building+things+that+scale." alt="Typing SVG" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-tanmay--lotankar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/tanmay-lotankar)
[![Email](https://img.shields.io/badge/Email-tanmay.elotankar%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:tanmay.elotankar@gmail.com)

[![AWS](https://img.shields.io/badge/AWS-Certified_Developer_Associate-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://www.credly.com/badges/23c6d403-452b-4fb7-b52e-b64bf89b44fc/public_url)
[![Azure](https://img.shields.io/badge/Microsoft-Azure_Fundamentals_AZ--900-0089D6?style=flat-square&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/api/credentials/share/en-us/EknathLotankarTanmay-2022/CF97D2F02BAB157C?sharingId=58E47D44F9716E9F)

</div>

---

## `$ whoami`

Backend and full-stack engineer with **3+ years** of production experience at Accenture, where I built the real-time PnL platform for a global investment bank, processing millions of trades daily across Kafka pipelines, Spark jobs, and a Redis caching layer that cut latency by 50%.

I completed my **M.S. in Computer Science (AI/ML focus)** at SUNY Buffalo in Dec 2025, and I am now in NYC focused on the intersection of **distributed backend systems** and **LLM-powered tooling**.

I don't just *use* AI APIs, I build pipelines around them: prompt engineering, RAG context retrieval, structured output, and production deployment on AWS.

---

## `$ cat production_experience.txt`

**Accenture → Global Investment Bank PnL Platform** *(Jun 2021 – Jul 2024)*

```
Trade Events (millions/day)
        │
        ▼
  [Kafka Pipeline] ──► PostgreSQL (bulk insert + upsert)
        │                    │
        │              [Redis Cache-Aside]  ◄── 50% latency reduction
        │                    │
        ▼                    ▼
  [Node.js REST APIs] ──► React Dashboard (real-time portfolio data)
        │
        ▼
  [CloudWatch] — structured logging, latency monitoring, incident triage
```

- Replaced static report exports with a **live React dashboard**: real-time portfolio & trade data via REST APIs
- Built responsive React components consuming Node.js APIs, rendering high-volume financial data with no page reloads
- Eliminated data refresh inconsistencies across **3 downstream reporting services**
- CI/CD-integrated Selenium test suite cut QA cycle from **2 days → 30 min**

---

## `$ cat what_i_ship.txt`

### 🤖 AI-Powered Code Review Pipeline &nbsp;·&nbsp; [View Repo ↗](https://github.com/TanmayEL/ai-code-review-summarizer)
> LangChain + RAG + Claude API + AWS

Agentic pipeline that processes PR diffs end-to-end. Built a RAG retrieval layer for codebase context, engineered prompts for structured review outputs, and deployed the full system on AWS: EC2 (FastAPI), SQS (job queue), Lambda (processor), DynamoDB (storage): provisioned from a single CloudFormation template.

**Stack:** `Python` `FastAPI` `LangChain` `Claude API` `AWS EC2/SQS/Lambda/DynamoDB` `CloudFormation`

---

### 🗂️ Decentralized File Storage Platform &nbsp;·&nbsp; [View Repo ↗](https://github.com/TanmayEL/decentralized-file-sharing-ipfs)
> React + Node.js + IPFS + MongoDB

Full-stack platform connecting a REST API backend to IPFS-based distributed storage via Pinata. JWT auth + RBAC, upload validation + compression pipeline, file metadata in MongoDB.

**Stack:** `React` `Node.js` `Express` `MongoDB` `IPFS / Pinata` `JWT`

---

### 🛰️ Urban Growth Change Detection &nbsp;·&nbsp; [View Repo ↗](https://github.com/TanmayEL/urban_change_detection)
> Python · Computer Vision · Sentinel-2 Satellite Imagery

Pixel-level change detection pipeline comparing two satellite images (T1 vs T2) of the same location. Ingests raw Sentinel-2 GeoTIFF band files, runs image differencing → binary segmentation → morphological denoising → connected component filtering → contour-to-polygon vectorization, and outputs a change mask, overlay, comparison figure, and `stats.json` (changed area %, polygon count).

Designed as a modular baseline — roadmap includes GeoJSON export with real-world coordinates, ECC/feature-matching alignment, a Streamlit demo UI, and ML-based segmentation (U-Net) for robustness to clouds and seasonal drift.

**Stack:** `Python` `OpenCV` `Shapely` `GeoTIFF / Sentinel-2` `NumPy`

---

## `$ ls skills/`

**Languages**

[![Skills](https://skillicons.dev/icons?i=js,ts,python,java,go,scala&theme=light)](https://skillicons.dev)

**Frontend & Backend**

[![Skills](https://skillicons.dev/icons?i=react,nodejs,express,fastapi,graphql&theme=light)](https://skillicons.dev)

**Databases & Streaming**

[![Skills](https://skillicons.dev/icons?i=postgres,redis,mongodb,dynamodb,kafka&theme=light)](https://skillicons.dev)

**Cloud & DevOps**

[![Skills](https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,git&theme=light)](https://skillicons.dev)

**AI / ML**

`PyTorch` `TensorFlow` `LangChain` `Claude API` `OpenAI API` `RAG` `Prompt Engineering`

---

## `$ cat stats.sh | bash`

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=TanmayEL&theme=github-dark-blue&hide_border=true" height="150" />

</div>

---

## `$ cat status.txt`

```yaml
status:         actively_interviewing
location:       New York City
open_to:        SDE | Full-Stack | Backend | AI/LLM Engineering roles
work_auth:      OPT (no sponsorship required, valid 36 months)
availability:   immediate
reach_me_at:    tanmay.elotankar@gmail.com
```

---

<div align="center">
  <sub>If you are hiring for backend systems or AI tooling - let's talk.</sub>
</div>
