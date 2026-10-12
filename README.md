<h1 align="center">Matee Vadrukchid</h1>

<p align="center">
  <strong>Robotics · Reinforcement Learning · AI Systems · Software Engineering</strong>
</p>

<p align="center">
  <a href="#robotics-research-reinforcement-learning-control">Robotics research</a> ·
  <a href="#ai-systems-and-implementations">AI implementations</a> ·
  <a href="#selected-conference-publication">Publication</a> ·
  <a href="https://github.com/VMatee?tab=repositories">All repositories</a>
</p>

I'm an engineering lecturer and developer focused on **robotic control, reinforcement learning, and applied AI systems**. This profile showcases research projects, working AI implementations, and software tools—with code, reproducible experiments, automated tests, and technical documentation.

### Robotics Research: Reinforcement Learning Control

**[Deep Reinforcement Learning Control of a Double Inverted Pendulum](https://github.com/VMatee/rl-double-inverted-pendulum)** · *Public Research Repository*

Developed a nonlinear simulation of an underactuated double inverted pendulum and investigated deep reinforcement learning for continuous robotic control. The project compares **A2C, PPO, DDPG, TD3, and SAC**, including friction uncertainty, controller adaptation, and reproducible experimental evaluations.

### Selected conference publication

**Matee Vadrukchid** and **Manukid Parnichkun** (2022).  
[**Development and Control of the Stick Robot Using Three Reaction Wheels**](https://ieeexplore.ieee.org/abstract/document/10003857).  
*22nd International Conference on Control, Automation and Systems (ICCAS 2022)* · **Busan, South Korea** · pp. 319–324.

Developed and experimentally evaluated a **self-balancing stick robot with three reaction wheels**. The work combines mechanical and embedded-system design, a **coupled-axis dynamic model** based on Lagrangian mechanics, and **Linear Quadratic Regulator (LQR)** control to stabilize the real robot in roll and pitch.

**Research areas:** Reaction-wheel robotics · Dynamic modeling · Embedded control · Optimal control · Hardware validation

[**Read the paper on IEEE Xplore**](https://ieeexplore.ieee.org/abstract/document/10003857) · [DOI](https://doi.org/10.23919/ICCAS55662.2022.10003857) · [Watch the robot demonstration](https://youtu.be/T0wGiWzJ40Q)

### AI Systems and Implementations

**Core algorithms implemented explicitly, not thin wrappers around model-service APIs.** The LLM and LoRA projects use PyTorch for tensor computation and automatic differentiation; RAG, KAG, and symbolic reasoning require only Python's standard library. All five include runnable examples, implementation guides and regression tests.

#### [01 · LLM from Scratch — Causal Transformer](https://github.com/VMatee/llm-from-scratch)

Implemented character tokenization, decoder-only multi-head attention with causal masking, Transformer blocks, next-token training and sampling. Includes **tensor-level reference implementations of linear layers, embeddings, LayerNorm, GELU, softmax, cross entropy and AdamW**, alongside a faster optimized execution path.

**Source:** [Transformer architecture](https://github.com/VMatee/llm-from-scratch/blob/main/src/minigpt/model.py) · [Tensor primitives](https://github.com/VMatee/llm-from-scratch/blob/main/src/minigpt/primitives.py) · [AdamW](https://github.com/VMatee/llm-from-scratch/blob/main/src/minigpt/optim.py) · [Training / validation](https://github.com/VMatee/llm-from-scratch/blob/main/src/minigpt/train.py)  
**Output:** Locally trained character-model checkpoint, generated text and held-out cross-entropy diagnostics. [Implementation details](https://github.com/VMatee/llm-from-scratch/blob/main/docs/implementation.md) · [![Tests](https://github.com/VMatee/llm-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/llm-from-scratch/actions/workflows/tests.yml)

#### [02 · LoRA from Scratch — Low-Rank Neural Adaptation](https://github.com/VMatee/lora-from-scratch)

Implemented low-rank matrices **A/B**, frozen base-weight updates, scaling, weight merge/unmerge, and recursive adapter injection into selected neural-network layers. Lightweight adapter checkpoints contain just the learned low-rank parameters.

**Source:** [LoRA layer](https://github.com/VMatee/lora-from-scratch/blob/main/src/lora_lab/layers.py) · [Model injection / checkpoints](https://github.com/VMatee/lora-from-scratch/blob/main/src/lora_lab/inject.py) · [Runnable experiment](https://github.com/VMatee/lora-from-scratch/blob/main/src/lora_lab/inject_demo.py)  
**Output:** Synthetic adaptation-loss comparison, adapter parameter counts and numerical merge-equivalence checks. [Implementation details](https://github.com/VMatee/lora-from-scratch/blob/main/docs/implementation.md) · [![Tests](https://github.com/VMatee/lora-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/lora-from-scratch/actions/workflows/tests.yml)

#### [03 · RAG from Scratch — BM25 Retrieval Engine](https://github.com/VMatee/rag-from-scratch)

Implemented a lexical search engine with tokenization, **term-frequency postings, an inverted index, BM25 scoring, source tracking and per-term score explanations**—without a retrieval framework or vector database. Optional Ollama integration is used only for local text generation.

**Source:** [Index and scoring](https://github.com/VMatee/rag-from-scratch/blob/main/src/rag_lab/bm25.py) · [Evidence assembly](https://github.com/VMatee/rag-from-scratch/blob/main/src/rag_lab/pipeline.py) · [Retrieval evaluation](https://github.com/VMatee/rag-from-scratch/blob/main/src/rag_lab/evaluate.py)  
**Output:** Ranked document hits with source identifiers and independent BM25 score/ranking parity tests. [Implementation details](https://github.com/VMatee/rag-from-scratch/blob/main/docs/implementation.md) · [![Tests](https://github.com/VMatee/rag-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/rag-from-scratch/actions/workflows/tests.yml)

#### [04 · KAG from Scratch — Verified Graph Traversal](https://github.com/VMatee/kag-from-scratch)

Implemented source-aware subject–relation–object indexing, deterministic **bounded breadth-first search**, multi-hop evidence paths and an independent verifier that rejects unsupported or altered graph edges.

**Source:** [Graph algorithms / verifier](https://github.com/VMatee/kag-from-scratch/blob/main/src/kag_lab/graph.py) · [Query checks](https://github.com/VMatee/kag-from-scratch/blob/main/src/kag_lab/evaluate.py)  
**Output:** Explainable graph paths with source IDs, hop budgets and traversal diagnostics. [Implementation details](https://github.com/VMatee/kag-from-scratch/blob/main/docs/implementation.md) · [![Tests](https://github.com/VMatee/kag-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/kag-from-scratch/actions/workflows/tests.yml)

#### [05 · Reasoning from Scratch — Exact Search & Proof Checking](https://github.com/VMatee/reasoning-from-scratch)

Implemented **depth-first arithmetic search with state deduplication**, an independent **bitmask subset-dynamic-programming solver**, and exact rational step verification without a reasoning-model service.

**Source:** [DFS solver](https://github.com/VMatee/reasoning-from-scratch/blob/main/src/verifier_reasoning/solver.py) · [Subset DP](https://github.com/VMatee/reasoning-from-scratch/blob/main/src/verifier_reasoning/dp.py) · [JSON proof certificates](https://github.com/VMatee/reasoning-from-scratch/blob/main/src/verifier_reasoning/certificate.py)  
**Output:** Exact arithmetic solutions with independently verifiable steps and machine-readable certificates. [Implementation details](https://github.com/VMatee/reasoning-from-scratch/blob/main/docs/implementation.md) · [![Tests](https://github.com/VMatee/reasoning-from-scratch/actions/workflows/tests.yml/badge.svg)](https://github.com/VMatee/reasoning-from-scratch/actions/workflows/tests.yml)

*Scope:* compact, tested implementations with reproducible demonstrations—not claims of frontier-model quality or identical GPU throughput to specialized frameworks.

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
