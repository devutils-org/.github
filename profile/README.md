<p align="center">
  <a href="https://devutils-org.github.io"><img src="https://devutils-org.github.io/mark.svg" width="72" alt="devutils" /></a>
</p>

<h3 align="center">Small tools. Honest answers.</h3>

<p align="center">
  Developer tools for your Linux workflow — written in Rust, read-only by default, with the evidence beside every answer.
  <br />
  <a href="https://devutils-org.github.io"><b>devutils-org.github.io</b></a>
</p>

---

Each tool owns one kind of question about a Linux machine, installs on its own and says plainly how mature it is.

| | Tool | What it answers | Status |
|---|---|---|---|
| ◎ | **Omniscient** | *Observe* — Linux observability straight from the kernel (perf_event_open, eBPF, procfs, sysfs, netlink). Every number says what it lost and how far it can be trusted. | In development · repo not public yet |
| ? | **[ATFQ](https://github.com/devutils-org/atfq)** | *Explain* — a terminal companion: short answers first, your machine's real state second. Never runs commands, never touches the network. | v0.1 |
| ⧉ | **[distroproof](https://github.com/devutils-org/distroproof)** | *Verify* — runs your program across a matrix of distro VMs, each on its real kernel, and ties failures to the environment difference behind them. | POC |
| ▥ | **[pkgx](https://github.com/devutils-org/pkgx)** | *Reconcile* — native package inventory and provenance, converged to a TOML profile through a plan you read before it runs. | POC |
| ◰ | **[VMAnyware](https://github.com/devutils-org/VMAnyware)** | *Provision* — reproducible environments on your own Proxmox homelab, from a native client and a self-hosted control plane. | In development |

### The standard

- **Show the work** — where a number comes from, next to the number.
- **Say what was lost** — dropped samples, missing permissions, unsupported kernels.
- **Refuse rather than guess** — no answer is better than a wrong one.

<sub>Statuses follow each repository's README. Most tools are dual-licensed MIT / Apache-2.0.</sub>
