# GridWork

I run a fleet of coding agents as one operator. An orchestrator session splits the work into
parallel lanes, review lanes check it, and merge trains land it. That setup is building
products that have not launched yet. The two public repos below are already published.

### Open source

- **[gridwork](https://gridwork.sh)**: a terminal-native agent operating system, in the open.
  One Rust binary, `gw`. An append-only event log is the source of truth, a TUI is the only
  surface, and the kernel owns the authority policy: what an agent may do unattended and what
  pages a human. Pre-alpha, published as Rust crates, Apache-2.0. Feature work is paused;
  dependency and security updates still land.
- **[caisson](https://caisson.sh)**: composable TypeScript packages for building regulated SaaS:
  fail-closed tenant isolation, an append-only audit chain, field-level encryption and compliance
  evidence. Apache-2.0, published to npm under `@caisson-sh/*` with provenance attestations.

The green squares below are real, and most of the recent ones are that private product work.
Agents write most of the commits. I make the calls.
