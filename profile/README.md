<p align="center">
  <a href="https://devutils-org.com"><img src="https://raw.githubusercontent.com/devutils-org/.github/main/profile/assets/github-social-preview-with-phrase.png" width="1280" alt="devutils — See beyond the surface." /></a>
</p>

<h2 align="center">Understand your Linux system.</h2>

<p align="center">
  Independent Rust tools to debug with context, check portability,<br />
  and manage packages and local environments.
</p>

<p align="center">
  <a href="https://devutils-org.com"><b>Explore the tools →</b></a>
</p>

---

Each tool owns one kind of question about a Linux machine and installs on its own.

| Tool | What it answers | Status |
|---|---|---|
| **[Omniscient](https://github.com/devutils-org/omniscient)** | *Observe* — Linux observability straight from the kernel (perf_event_open, eBPF, procfs, sysfs, netlink). Every number says what it lost and how far it can be trusted. | In development · no release yet |
| **[ATFQ](https://github.com/devutils-org/atfq)** | *Explain* — a terminal companion: short answers first, your machine's real state second. Never runs commands, never touches the network. | [v0.1](https://github.com/devutils-org/atfq/releases) |
| **[distroproof](https://github.com/devutils-org/distroproof)** | *Verify* — runs your program across a matrix of distro VMs, each on its real kernel, and ties failures to the environment difference behind them. | [v0.1](https://github.com/devutils-org/distroproof/releases) · signed static binaries |
| **[xpac](https://github.com/devutils-org/xpac)** | *Reconcile* — native package inventory and provenance across seven package managers, converged to a TOML profile through a plan you read before it runs. | [v0.1](https://github.com/devutils-org/xpac/releases) · signed binaries |
| **[VMAnyware](https://github.com/devutils-org/VMAnyware)** | *Provision* — reproducible environments on your own Proxmox homelab, from a native client and a self-hosted control plane. | In development |

The tools never depend on each other's code: they meet through files. A shared
[cross-tool check](https://devutils-org.com/together/) runs all of them
together in disposable VMs of nine distributions.

### The standard

- **Show the work** — where a number comes from, next to the number.
- **Say what was lost** — dropped samples, missing permissions, unsupported kernels.
- **Refuse rather than guess** — no answer is better than a wrong one.

<sub>MIT or Apache-2.0, at your option. See each repository for file-specific terms.</sub>
