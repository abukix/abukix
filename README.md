<!--
  Profile README for github.com/abukix
  Renders on the abukix profile page.
-->

<div align="center">

  <a href="https://abukix.dev">
    <img src="./assets/logo.svg" alt="abukix connected node mark" width="120">
  </a>

# `abukix`

</div>

<br>

I'm **JC Abucay** from the Philippines. I go by **abukix**. I work shift-based ops at a large tech company. By day I respond to alerts; in my off-hours I'm rebuilding a small version of what production-scale data and AI platforms do, in my apartment, on a single Lenovo box running Proxmox.

I do this because, honestly, I want to understand the systems I run alerts on. There's a difference between *operating* a platform someone else built and *understanding* why it was built that way. My career so far has mostly been the first thing. The next years are an experiment in whether the second thing can be self-taught, deliberately, in public.

The technical substrate is **[`basecamp`](https://github.com/abukix/basecamp)**, an open-source unified data, ML, and AI platform. 8 modules on a K8s substrate, running on laptop, homelab, or cloud with the same manifests. The build guide is **[`/root`](https://github.com/abukix/root)**, a self-authored curriculum from Software Engineering Foundations to ML Platform / AI Infrastructure. `vantage` (one of basecamp's modules) is the unified web UI, the daily human surface once the platform is running.

---

## what i'm working on

I designed a 5-arc, 50-phase curriculum I call **`/root`**. Each phase teaches one principle of how computers and platforms actually work, picks one current tool to master, then makes me re-implement the same problem in a second tool to prove the *principle* transferred and the *tool* was incidental.

The thesis is a hunch I keep having: **the half-life of tools is shorter than the half-life of careers.** I've watched engineers spend three years memorizing one cloud's quirks and then stall when they had to move to the next one. I'd rather spend those years learning what every cloud is doing underneath, so the next one is just a different surface over the same patterns.

`/root` looks weird from the outside. Arc 1 isn't "Master Kubernetes." It's *Linux → Python → algorithms → Go → architecture patterns → performance → testing → Git/CI/CD*, in that order, because that's the order things actually compose. Kubernetes only makes sense after you've thought about Linux namespaces. Postgres only makes sense after you've thought about disk vs memory. Skip the foundations and you end up fluent in incantations rather than systems.

The program runs in 5 arcs, in this order:

1. **Software Engineering Foundations**: Linux, Python, Go, DSA, architecture patterns, performance, testing, Git+CI/CD
2. **Backend Engineering**: SQL/Postgres, caching, HTTP/REST/gRPC, auth, Docker, queues, service observability
3. **Infrastructure & Platform Engineering**: OS internals, networking deep, K8s + GitOps, IaC, cloud, mesh, platform engineering, secrets, observability, FinOps, reliability
4. **Data Engineering & ML Foundations**: Lakehouse (Iceberg + Trino), streaming (Kafka + Flink), batch (Spark), ML lifecycle, distributed training, model serving
5. **AI Infrastructure & Capstone**: feature stores, evals, vector stores + RAG, LLM serving, fine-tuning, LLM gateway, agent runtime + MCP, AI security + observability, AIOps. **`basecamp v1.0.0` ships**

12 public artifacts ship across the arcs, each teaching a specific pattern, together forming a homelab-scale data, ML, and AI platform:

- **8 `basecamp` modules**: [`ascent`](https://github.com/abukix/ascent) (dev CLI + Workload operator) · [`crag`](https://github.com/abukix/crag) (data tier) · [`vantage`](https://github.com/abukix/vantage) (unified UI) · [`beacon`](https://github.com/abukix/beacon) (on-call triage) · [`forge`](https://github.com/abukix/forge) (Terraform + Crossplane IaC) · [`prism`](https://github.com/abukix/prism) (LLM gateway) · [`loom`](https://github.com/abukix/loom) (MCP fabric) · [`warden`](https://github.com/abukix/warden) (AIOps operator)
- **2 standalone Arc 1 tools**: [`sift`](https://github.com/abukix/sift) (regex CLI in Python) · [`pulse`](https://github.com/abukix/pulse) (network probe in Go)
- **[`basecamp`](https://github.com/abukix/basecamp) umbrella**: GitOps repo composing the 8 modules
- **[`/root`](https://github.com/abukix/root)**: the curriculum and build guide itself

I write up the things I notice as I go, not tutorials, mostly observations, at [abukix.dev/blog](https://abukix.dev/blog). The full curriculum, phase library, and pattern library live at [root.abukix.dev](https://root.abukix.dev).

---

## activity

<div align="center">

<!--
  KNOWN ISSUE (2026-08-04): the two github-readme-stats.vercel.app cards below render
  as bare links with no image. The shared public demo deployment is returning
  503 DEPLOYMENT_PAUSED (Vercel usage limits on the shared instance - happens
  periodically to this project). streak-stats below is unaffected.
  Revisit: check if the deployment is back, or self-host via a personal Vercel
  fork of https://github.com/anuraghazra/github-readme-stats if it recurs.
-->
<!-- GitHub stats card + top languages side-by-side -->
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=abukix&show_icons=true&hide_border=true&title_color=a855f7&icon_color=ec4899&text_color=e8e8ef&bg_color=0d0d12&include_all_commits=true&count_private=true" alt="abukix's GitHub stats" />
</a>
<a href="https://github.com/anuraghazra/github-readme-stats">
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abukix&layout=compact&hide_border=true&title_color=a855f7&text_color=e8e8ef&bg_color=0d0d12&langs_count=8" alt="Top languages" />
</a>

<br>

<!-- Streak stats -->
<a href="https://git.io/streak-stats">
  <img src="https://streak-stats.demolab.com?user=abukix&hide_border=true&background=0d0d12&stroke=2a2a35&ring=a855f7&fire=f97316&currStreakLabel=e8e8ef&sideLabels=9a9aa8&currStreakNum=e8e8ef&sideNums=e8e8ef&dates=6b6b78" alt="Streak stats" />
</a>

</div>

<br>

<!--
  Wakatime badge, enable once you install Wakatime in your editor and link your GitHub username.
  Setup: https://wakatime.com/dashboard -> Settings -> uncheck "Hide activity from public" ->
         https://github.com/anmol098/waka-readme-stats
  Then uncomment the block below.

<div align="center">
  <a href="https://wakatime.com/@abukix">
    <img src="https://wakatime.com/badge/user/YOUR-UUID.svg" alt="Wakatime coding hours" />
  </a>
</div>
-->

---

## contribution grid

<!--
  The snake eats the contribution grid. Generated by .github/workflows/snake.yml every 12 hours,
  pushed to the "output" branch. GitHub's dark-mode users see the dark palette; others see the default.
-->

<div align="center">
  <picture>
    <source
      media="(prefers-color-scheme: dark)"
      srcset="https://raw.githubusercontent.com/abukix/abukix/output/github-contribution-grid-snake-dark.svg"
    />
    <source
      media="(prefers-color-scheme: light)"
      srcset="https://raw.githubusercontent.com/abukix/abukix/output/github-contribution-grid-snake.svg"
    />
    <img
      alt="A snake eating my GitHub contribution grid"
      src="https://raw.githubusercontent.com/abukix/abukix/output/github-contribution-grid-snake.svg"
    />
  </picture>
</div>

---

## the platform stack

**substrate**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Flux](https://img.shields.io/badge/Flux-5468FF?style=for-the-badge&logo=flux&logoColor=white)
![Cilium](https://img.shields.io/badge/Cilium-F8C517?style=for-the-badge&logo=cilium&logoColor=black)
![Vault](https://img.shields.io/badge/Vault-000000?style=for-the-badge&logo=vault&logoColor=white)

**containers + orchestration**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white)
![kubebuilder](https://img.shields.io/badge/kubebuilder-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

**infrastructure (`forge`)**

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Crossplane](https://img.shields.io/badge/Crossplane-6A5AF9?style=for-the-badge&logo=crossplane&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

**data (`crag`)**

![Iceberg](https://img.shields.io/badge/Iceberg-2C7CDB?style=for-the-badge&logo=apache&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=for-the-badge&logo=trino&logoColor=white)
![Spark](https://img.shields.io/badge/Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Flink](https://img.shields.io/badge/Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)

**ml + ai (`crag` substrate + `prism` + `loom`)**

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![Ray](https://img.shields.io/badge/Ray-028CF0?style=for-the-badge&logo=ray&logoColor=white)
![KServe](https://img.shields.io/badge/KServe-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![vLLM](https://img.shields.io/badge/vLLM-FFD43B?style=for-the-badge&logoColor=black)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white)

**observability**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OTEL-000000?style=for-the-badge&logo=opentelemetry&logoColor=white)
![eBPF](https://img.shields.io/badge/eBPF-FF9F1C?style=for-the-badge&logoColor=black)

**languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---

## sites

[![Website](https://img.shields.io/badge/abukix.dev-000000?style=for-the-badge&logo=safari&logoColor=white)](https://abukix.dev)
[![/root](https://img.shields.io/badge/root.abukix.dev-a855f7?style=for-the-badge&logo=astro&logoColor=white)](https://root.abukix.dev)
[![basecamp](https://img.shields.io/badge/basecamp.abukix.dev-f97316?style=for-the-badge&logo=astro&logoColor=white)](https://basecamp.abukix.dev)
[![Blog](https://img.shields.io/badge/blog-FF6600?style=for-the-badge&logo=rss&logoColor=white)](https://abukix.dev/blog)

---

## socials

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:me@abukix.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abukix)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@abukix)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/abukix)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/abukix)
[![Threads](https://img.shields.io/badge/Threads-000000?style=for-the-badge&logo=threads&logoColor=white)](https://threads.net/@abukix)
[![TikTok](https://img.shields.io/badge/TikTok-000000?style=for-the-badge&logo=tiktok&logoColor=white)](https://tiktok.com/@abukix)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://facebook.com/abukix)

---

<div align="center">

*"stillness between commits."*

</div>
