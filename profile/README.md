<p align="center">
  <h1 align="center">Eclipser Labs</h1>
  <p align="center"><strong>Engineering tools, infrastructure, and applied research.</strong></p>
  <p align="center">Execution layers for automated systems that do consequential work — governed runs, fallback paths, and verifiable records.</p>
</p>

<p align="center">
  <a href="https://github.com/eclipserlabs"><img src="https://img.shields.io/github/followers/eclipserlabs?style=flat-square&logo=github&label=Followers" alt="followers"/></a>
  <a href="https://www.igrisinertial.com"><img src="https://img.shields.io/badge/Website-igrisinertial.com-blue?style=flat-square&logo=googlechrome" alt="website"/></a>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" alt="Rust"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

---

### What we build

> `Action -> Run -> Proof`

Systems that let agents and automation safely execute consequential operations through a durable boundary — with policy checks, controlled runs, and signed records of what happened.

- **Governed execution** — controlled runs, fallback paths, signed records
- **Policy & guardrails** — policy-checked tool use, safe execution boundaries
- **Adaptive decision-making** — bandits for changing provider/model sets, behavior trees with LLM reasoning

### Projects

| Project | What it is | CI | License | Stars |
|---|---|---|---|---|
| [**igris**](https://github.com/eclipserlabs/igris) `Go` | Governed execution layer for controlled runs, fallback paths, and signed records | [![runtime-ci](https://github.com/eclipserlabs/igris/actions/workflows/runtime-ci.yml/badge.svg)](https://github.com/eclipserlabs/igris/actions/workflows/runtime-ci.yml) | ![License](https://img.shields.io/github/license/eclipserlabs/igris) | ![Stars](https://img.shields.io/github/stars/eclipserlabs/igris?style=flat-square) |
| [**overture**](https://github.com/eclipserlabs/overture) `Go` | Safe execution boundary for consequential operations. Keep your agent, route consequential work through `Action -> Run -> Proof` | [![CI](https://github.com/eclipserlabs/overture/actions/workflows/ci.yml/badge.svg)](https://github.com/eclipserlabs/overture/actions/workflows/ci.yml) | ![License](https://img.shields.io/github/license/eclipserlabs/overture) | ![Stars](https://img.shields.io/github/stars/eclipserlabs/overture?style=flat-square) |
| [**marshal**](https://github.com/eclipserlabs/marshal) `Rust` | Policy-checked tool execution for agents | [![CI](https://github.com/eclipserlabs/marshal/actions/workflows/ci.yml/badge.svg)](https://github.com/eclipserlabs/marshal/actions/workflows/ci.yml) | ![License](https://img.shields.io/github/license/eclipserlabs/marshal) | ![Stars](https://img.shields.io/github/stars/eclipserlabs/marshal?style=flat-square) |
| [**interceptor**](https://github.com/eclipserlabs/interceptor) `Python` | Let agents safely execute consequential actions | [![CI](https://github.com/eclipserlabs/interceptor/actions/workflows/ci.yml/badge.svg)](https://github.com/eclipserlabs/interceptor/actions/workflows/ci.yml) | ![License](https://img.shields.io/github/license/eclipserlabs/interceptor) | ![Stars](https://img.shields.io/github/stars/eclipserlabs/interceptor?style=flat-square) |
| [**thompson**](https://github.com/eclipserlabs/thompson) `Rust` | Beta-Bernoulli multi-armed bandit for dynamic provider/model selection with multi-objective rewards | [![CI](https://github.com/eclipserlabs/thompson/actions/workflows/ci.yml/badge.svg)](https://github.com/eclipserlabs/thompson/actions/workflows/ci.yml) | ![License](https://img.shields.io/github/license/eclipserlabs/thompson) | ![Stars](https://img.shields.io/github/stars/eclipserlabs/thompson?style=flat-square) |
| [**btree**](https://github.com/eclipserlabs/btree) `Rust` | Behavior tree engine with LLM reasoning nodes | [![CI](https://github.com/eclipserlabs/btree/actions/workflows/ci.yml/badge.svg)](https://github.com/eclipserlabs/btree/actions/workflows/ci.yml) | ![License](https://img.shields.io/github/license/eclipserlabs/btree) | ![Stars](https://img.shields.io/github/stars/eclipserlabs/btree?style=flat-square) |
| [**rapture**](https://github.com/eclipserlabs/rapture) `TypeScript` | Systems-engineering repository | [![CI](https://github.com/eclipserlabs/rapture/actions/workflows/ci.yml/badge.svg)](https://github.com/eclipserlabs/rapture/actions/workflows/ci.yml) | ![License](https://img.shields.io/github/license/eclipserlabs/rapture) | ![Stars](https://img.shields.io/github/stars/eclipserlabs/rapture?style=flat-square) |

### Quickstart

```bash
# governed execution
git clone https://github.com/eclipserlabs/igris.git

# safe boundary (same pattern for marshal / interceptor / overture)
git clone https://github.com/eclipserlabs/overture.git
```

Each repo has its own README with setup and usage. Start with `igris` for the full runtime, `overture` / `marshal` / `interceptor` for the execution boundary.

### Stack

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)

### Contributing

Issues and PRs welcome. For significant changes, please open an issue first to discuss.
