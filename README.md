<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=23&pause=1000&color=58A6FF&center=true&vCenter=true&width=780&lines=Hi+there%2C+I'm+Arvin+%F0%9F%91%8B;AI+Infrastructure;Building+reliable%2C+observable%2C+automated+systems;Building+ChatPassport)](https://git.io/typing-svg)

</div>

---

## 🌟 About Me

```javascript
const arvin = {
  name: "Arvin Wang",
  role: "Infrastructure Engineer",
  direction: "AI Infrastructure",
  focus: ["Reliable systems", "Automation", "Observability"],
  building: ["ChatPassport", "nccl-allreduce-bench", "softroce-rdma-nccl-lab"],
};
```

- 👋 Hi, I'm Arvin. I am working toward building reliable, observable, and automated infrastructure for AI systems.
- ⚙️ My engineering interests span network reliability, infrastructure automation, observability, and distributed systems.
- 🧠 I am especially interested in AI infrastructure, model training platforms, and reliability engineering.
- 🛠️ This profile is a public workbench for open-source projects and engineering experiments.

---

## 🎯 Current Focus

- **AI Infrastructure** — training systems, resource efficiency, and scalable execution.
- **Reliable Systems** — high availability, observability, capacity planning, and incident response.
- **Infrastructure Automation** — turning operational workflows into repeatable tools and pipelines.
- **Open-source Building** — creating practical tools around AI workflows and user-controlled data.

---

## 🤝 Open Source Contributions

### [SQLFluff](https://github.com/sqlfluff/sqlfluff)

Added support for PostgreSQL 18 temporal foreign keys using `PERIOD` in both `CREATE TABLE` and `ALTER TABLE` constraints, with parser tests covering the new syntax.

[PR #9150 →](https://github.com/sqlfluff/sqlfluff/pull/9150) · **Merged** on November 14, 2026

---

## 🚀 Featured Projects

### [ChatPassport](https://github.com/sxwangsxwang1/chatpassport)

**Carry the context. Keep control.**

Continue AI conversations across ChatGPT, Claude, Gemini, and DeepSeek while keeping the context local and the user in control.

- Local-first, with no developer-operated server, account, analytics, or tracking.
- Supports structured conversation import, export, and cross-platform continuation.
- Built with TypeScript, React, WXT, Zod, Vitest, and Chrome Manifest V3.

[View the project →](https://github.com/sxwangsxwang1/chatpassport)

### [NCCL Allreduce Bench](https://github.com/sxwangsxwang1/nccl-allreduce-bench)

**Understand the curve, not just the number.**

Controlled NCCL allreduce experiments on two Tesla T4 GPUs show how topology, transport, algorithm, and protocol shape the bandwidth curve.

- Changes one NCCL setting at a time and checks diagnostic logs to confirm it took effect.
- Includes timing logs, analysis scripts, and plots so the results can be reproduced and inspected.
- Examines SHM fallback when P2P is unavailable, plus Ring and Tree performance on the tested virtualized platform.

[View the project →](https://github.com/sxwangsxwang1/nccl-allreduce-bench)

### [Soft-RoCE RDMA & NCCL Lab](https://github.com/sxwangsxwang1/softroce-rdma-nccl-lab)

**Follow the packets, verify the transport.**

Two cloud GPU VMs running software RoCEv2, with evidence from verbs connectivity through NCCL AllReduce.

- Confirms RoCEv2 traffic with a 200-packet capture and NCCL data channels using `NET/IB` over `rxe0`.
- Compares RDMA and TCP Socket AllReduce on two RTX A4000 GPUs, with zero validation errors in both recorded scans.
- Publishes 44 original evidence files, derived tables and plots, reconstructed run scripts, and documented failures and measurement limits.

[View the project →](https://github.com/sxwangsxwang1/softroce-rdma-nccl-lab)

<br/>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,12,20,24&height=110&section=footer&text=Building%20AI%20Infrastructure&fontColor=ffffff&fontSize=20&animation=twinkling" alt="Building AI Infrastructure" />
