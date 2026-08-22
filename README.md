## Hi there 👋

# Hey, I'm Nikhil 👋

I make software tell you what's wrong with your software.

Backend engineer at **[SigNoz](https://github.com/SigNoz/signoz)** (open-source observability, 31K+ ⭐) — writing Go that runs on 2,000+ Kubernetes clusters I will never see, which is exactly as terrifying as it sounds. Everything I build ships to both our cloud and to self-hosted installs run by strangers on the internet. Distributed systems keep you humble.

## 🔭 What I actually do all day

- **Infrastructure Monitoring at SigNoz** — built the Hosts + Kubernetes monitoring end to end: from the Helm charts that collect metrics on customer clusters, through ClickHouse query APIs, all the way to the frontend. Containers ↔ pods ↔ nodes, all correlated, all fast(ish — ClickHouse cardinality is a lifestyle, not a problem)
- **Alert channel integrations** — Google Chat, Jira, JSM Ops, incident.io. When your pod dies at 3 AM, one of my integrations is probably the reason your phone buzzed. You're welcome. Sorry.
- **[signoz-otel-collector](https://github.com/SigNoz/signoz-otel-collector)** — the ingestion pipeline. Span metrics, delta temporality, schema migrations. The unglamorous plumbing that everything else depends on.

## 🌍 Open Source — OpenTelemetry

My favorite kind of PR is one that ships in five languages:

- Implemented `is_remote` span flags in the OTLP exporters of **Go, JavaScript, Rust, Ruby, and Erlang** — so tracing backends can spot service boundaries and draw service graphs straight from trace data. No more maintaining topology state by hand 🎉
- W3C trace-flags work in [opentelemetry-go](https://github.com/open-telemetry/opentelemetry-go), plus a Prometheus metric-shape fix in the [Operator](https://github.com/open-telemetry/opentelemetry-operator) that I drove from feature gate → beta
- Apparently 20+ contributions/year gets you a vote in the OTel Governance Committee election, so I have opinions *and* a ballot now

## 🧪 Side quests

- **[Cold_Emailer](https://github.com/nikhilmantri0902/Cold_Emailer)** — a Go pipeline that finds companies via Apollo, writes personalized outreach with OpenAI, and sends it through Gmail. Built it to automate the most soul-crushing part of job hunting. The irony of an observability engineer building an email pipeline with *comprehensive logging* is not lost on me.
- Previously: co-founded an NFT analytics platform (5,000+ wallets in 2 months, RIP), built no-code KYC orchestration on Temporal.io at FinBox, and once trained a GAN at Citibank to catch fraudsters

## 🛠️ The stack I reach for

`Go` `ClickHouse` `Kubernetes` `OpenTelemetry` `Temporal.io` `PostgreSQL` `Docker` `Helm` — and `C++` when competitive programming brain activates

## ⚽ Off the keyboard

Chasing a football or watching Liverpool make things unnecessarily dramatic. YNWA.

---

📫 Reach me: [LinkedIn](https://www.linkedin.com/in/nikhil-mantri-2bb46914a) · mantri.dpn09@gmail.com
