# Wesley Atwell

Solutions architect and systems builder working across cloud infrastructure, networking, systems software, and automation.

I turn ambiguous requirements into working systems—from architecture and infrastructure as code through implementation, deployment, testing, troubleshooting, and recovery. My day-to-day stack spans AWS, Linux and Windows, Terraform/OpenTofu, Docker, GitLab CI/CD, Python, Go, C, and C++.

## Selected engineering work

### AOM-Chess — C++20 chess engine and validation platform

My favorite project and the deepest systems build in my portfolio. AOM-Chess combines bitboard move generation, alpha-beta and quiescence search, transposition tables, classical and NNUE evaluation, Syzygy tablebases, opening books, and multithreaded time-managed search.

The surrounding engineering includes UCI, native ImGui, and WebAssembly front ends; cross-platform CMake builds with scalar, AVX2, and AVX-512 paths; CUDA-assisted NNUE training and dataset tooling; reproducible CuteChess SPRT A/B matches; and a validation suite covering perft, fuzzing, make/undo invariants, protocol behavior, concurrency, endgames, and performance benchmarks.

The source remains private while actively developed.

### [TrueTunnel VPN](https://github.com/Wes2000ley/TrueTunnel-VPN)

Native multi-client Windows VPN built in C++23 with Wintun, Winsock, encrypted TCP/UDP transports, Windows routing and NAT integration, a Direct3D/ImGui interface, CMake, Conan, and automated integration testing.

### [CloudTapestry](https://cloudtapestry.com)

Full-stack Go/Vue network-design and reachability simulator for modeling AWS-style accounts, VPCs, subnets, route tables, Transit Gateway, VPN attachments, customer networks, and policy boundaries before production changes.

### [ElfGloss / Parf Edhellen](https://github.com/Wes2000ley/Parf-Edhellen)

Public Go migration of a Tolkien-language dictionary into a source-driven, read-only service with reproducible multi-source imports, bbolt storage, search APIs, data audits, and Docker delivery.

### AWS Network Inventory

Private Python platform for read-only, multi-account infrastructure inventory, search, historical change analysis, and reporting. It uses least-privilege collection roles, compressed snapshots, retention management, Docker packaging, CloudFormation, GitLab CI/CD, and automated validation.

### [Linux kernel contributions](https://wesleyatwell.net/kernel/)

Upstream fixes accepted into the mainline Linux kernel across tracing, crypto, TCP/IPv6, and netdevsim, with a focus on race safety, callback context, lifecycle cleanup, and maintainer-reviewed correctness.

### Open-source and research work

- [C++ language support and hardening for jcodemunch-mcp](https://github.com/jgravelle/jcodemunch-mcp/pull/26), including parser behavior, deterministic indexing, incremental storage, documentation, and test coverage.
- [Prime-power cutoff tail bounds](https://github.com/Wes2000ley/prime-power-cutoff-tail-bounds), an exact-integer verifier and reproducible certificate for a mathematical threshold result.

## What I value

- Owning difficult problems from design through production recovery
- Reproducible builds, automated validation, and evidence-backed engineering
- Clear boundaries between public proof and private customer or operational details
- Learning whatever the mission requires and carrying the work to completion

Several substantial codebases are private. I describe their architecture, engineering scope, and validation publicly without exposing source, customer data, or sensitive operational details.

[Resume PDF](https://wesleyatwell.net/assets/Wesley_Atwell_Resume.pdf) · [Engineering portfolio](https://wesleyatwell.net/) · [LinkedIn](https://www.linkedin.com/in/wesleyatwell/)
