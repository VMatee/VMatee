<h1 align="center">Matee Vadrukchid</h1>

<p align="center">
  <strong>Robotics · Reinforcement Learning · AI Systems · Software Engineering</strong>
</p>

<p align="center">
  <a href="#research-spotlight-ai-for-robotic-control">Robotics research</a> ·
  <a href="#open-source-ai-implementations">AI implementations</a> ·
  <a href="#selected-conference-publication">Publication</a> ·
  <a href="https://github.com/VMatee?tab=repositories">All repositories</a>
</p>

I'm an engineering lecturer and developer focused on **robotic control, reinforcement learning, and applied AI systems**. This profile showcases research projects, working AI implementations, and software tools—with code, reproducible experiments, automated tests, and technical documentation.

### Research spotlight: AI for robotic control

**[Learning to Swing Up a Double Inverted Pendulum](https://github.com/VMatee/rl-double-inverted-pendulum)** · *Research code — currently private*

Deep reinforcement learning for an **underactuated double inverted pendulum on a cart**. The project develops a nonlinear simulation with continuous cart-force control, compares **A2C, PPO, DDPG, TD3, and SAC**, and investigates controller behavior under changing friction and additional policy training.

- **Robotics:** nonlinear coupled dynamics, three degrees of freedom, one actuator.
- **Learning-based control:** continuous-action reinforcement learning and swing-up.
- **Robustness & reproducibility:** friction-shift experiments, recovered policy evaluation, and documented limitations.
- **Scope:** simulation research, not a hardware deployment or a claim of real-world robustness.

> The repository is private while redistribution rights for archived material are being reviewed. Its code and files are not available to visitors without access. Research details can be shared appropriately when cleared for release.

### Selected conference publication

**Matee Vadrukchid** and **Manukid Parnichkun** (2022).  
[**Development and Control of the Stick Robot Using Three Reaction Wheels**](https://ieeexplore.ieee.org/abstract/document/10003857).  
*22nd International Conference on Control, Automation and Systems (ICCAS 2022)* · **Busan, South Korea** · pp. 319–324.

Developed and experimentally evaluated a **self-balancing stick robot with three reaction wheels**. The work combines mechanical and embedded-system design, a **coupled-axis dynamic model** based on Lagrangian mechanics, and **Linear Quadratic Regulator (LQR)** control to stabilize the real robot in roll and pitch.

**Research areas:** Reaction-wheel robotics · Dynamic modeling · Embedded control · Optimal control · Hardware validation

[**Read the paper on IEEE Xplore**](https://ieeexplore.ieee.org/abstract/document/10003857) · [DOI](https://doi.org/10.23919/ICCAS55662.2022.10003857) · [Watch the robot demonstration](https://youtu.be/T0wGiWzJ40Q)

### Open-source AI implementations

A collection of **implemented, runnable AI/ML systems** built from first principles. Each repository contains source code, tests, and documented behavior—not just conceptual descriptions.

| Project | Implementation | What you can run / inspect | CI |
| :--- | :--- | :--- | :---: |
| [**LLM from Scratch**](https://github.com/VMatee/llm-from-scratch) | Decoder-only causal Transformer in PyTorch, with character tokenization, masked attention, and a training loop | Train a model checkpoint, generate text, and test causal masking | [![Tests](https://github.com/VMatee/llm-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/llm-from-scratch/actions/workflows/tests.yml) |
| [**LoRA from Scratch**](https://github.com/VMatee/lora-from-scratch) | Low-rank trainable adapters for frozen PyTorch linear layers | Run a synthetic adaptation experiment; verify parameter counts and merge/unmerge equivalence | [![Tests](https://github.com/VMatee/lora-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/lora-from-scratch/actions/workflows/tests.yml) |
| [**RAG from Scratch**](https://github.com/VMatee/rag-from-scratch) | BM25 document indexing, ranked retrieval, and source-aware context assembly | Retrieve evidence with source references; optionally generate answers using local Ollama | [![Tests](https://github.com/VMatee/rag-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/rag-from-scratch/actions/workflows/tests.yml) |
| [**KAG from Scratch**](https://github.com/VMatee/kag-from-scratch) | Source-aware knowledge triples and bounded multi-hop graph traversal | Query relationships and inspect supported paths with evidence identifiers | [![Tests](https://github.com/VMatee/kag-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/kag-from-scratch/actions/workflows/tests.yml) |
| [**Reasoning from Scratch**](https://github.com/VMatee/reasoning-from-scratch) | Exact-rational arithmetic search with an independent step verifier | Solve arithmetic puzzles and inspect verifiable solution traces | [![Tests](https://github.com/VMatee/reasoning-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/reasoning-from-scratch/actions/workflows/tests.yml) |

**Implementation scope:** These are compact, tested reference implementations. Their READMEs document capabilities and limitations; no production-scale training or benchmark superiority is claimed.

### Software I build

| Project | Purpose | Stack |
| :--- | :--- | :--- |
| [**JV CLI**](https://github.com/VMatee/jv-cli) | Terminal-first AI coding assistant with installable releases | CLI tooling |
| [**JV Desktop**](https://github.com/VMatee/jv-desktop) | Desktop workspace for CLI-assisted development | Tauri · React · Rust |
| [**JV LLM API examples**](https://github.com/VMatee/jv-llm-api-example) | Practical examples of an LLM service API | Python · Rust |
| [**JV Web Tools**](https://github.com/VMatee/jv-web-tools) | Browser developer utility documentation and support | Web tooling |

### Teaching in the open

[**Linux, Git & GitHub Labs**](https://github.com/VMatee/linux-git-github-labs) is a beginner-friendly, 15-session learning path for engineering students—from their first terminal commands to collaborative pull requests and a professional project portfolio.

[![Course checks](https://github.com/VMatee/linux-git-github-labs/actions/workflows/autograde.yml/badge.svg)](https://github.com/VMatee/linux-git-github-labs/actions/workflows/autograde.yml)

### How I work

- **Make it reproducible:** document setup, provide runnable examples, and test changes.
- **Make it understandable:** explain the smallest useful implementation before adding complexity.
- **Make it useful:** connect ML concepts to software systems and engineering applications.
- **Make limitations explicit:** examples and teaching demos are not production benchmarks.

**Interests:** Robotic control · Reinforcement learning · Sim-to-real challenges · Nonlinear dynamics · LLM architectures · Efficient fine-tuning · Retrieval & knowledge graphs · Open-source education

---

<sub>All public repositories are works in progress. Contributions and constructive feedback are welcome; please review each project's contribution guide.</sub>
