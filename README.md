<h1 align="center">Hi, I'm Matee 👋</h1>

<p align="center">
  <strong>Robotics & Reinforcement Learning · Applied AI · Developer Tools · Engineering Education</strong>
</p>

<p align="center">
  <a href="https://github.com/VMatee?tab=repositories">Repositories</a> ·
  <a href="https://github.com/VMatee/linux-git-github-labs">Open course</a> ·
  <a href="#selected-conference-publication">Publication</a>
</p>

I'm an engineering lecturer interested in **robotics, reinforcement learning, and applied artificial intelligence**. I develop learning-based control experiments, approachable implementations of machine-learning algorithms, and software tools that bridge research with practical engineering.

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

### Featured: AI from first principles

Small, readable implementations of important ideas—not claims of training production-scale foundation models.

| Repository | Explore | Build status |
| :--- | :--- | :---: |
| [**LLM from Scratch**](https://github.com/VMatee/llm-from-scratch) | A character-level causal Transformer: attention, training, and text generation | [![CI](https://github.com/VMatee/llm-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/llm-from-scratch/actions/workflows/tests.yml) |
| [**Reasoning from Scratch**](https://github.com/VMatee/reasoning-from-scratch) | Exact arithmetic search with independently checked solution steps | [![CI](https://github.com/VMatee/reasoning-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/reasoning-from-scratch/actions/workflows/tests.yml) |
| [**LoRA from Scratch**](https://github.com/VMatee/lora-from-scratch) | Trainable low-rank adapters on frozen PyTorch layers | [![CI](https://github.com/VMatee/lora-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/lora-from-scratch/actions/workflows/tests.yml) |
| [**RAG from Scratch**](https://github.com/VMatee/rag-from-scratch) | BM25 retrieval, source-aware evidence, and optional local generation | [![CI](https://github.com/VMatee/rag-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/rag-from-scratch/actions/workflows/tests.yml) |
| [**KAG from Scratch**](https://github.com/VMatee/kag-from-scratch) | Knowledge graph traversal, multi-hop paths, and provenance | [![CI](https://github.com/VMatee/kag-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/kag-from-scratch/actions/workflows/tests.yml) |

**Learning path:** [LLM](https://github.com/VMatee/llm-from-scratch) → [LoRA](https://github.com/VMatee/lora-from-scratch) → [RAG](https://github.com/VMatee/rag-from-scratch) → [KAG](https://github.com/VMatee/kag-from-scratch) → [Reasoning](https://github.com/VMatee/reasoning-from-scratch). Each repository includes tests, a guided notebook, and known limitations.

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
