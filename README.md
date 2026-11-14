# Surendira Balaji Natarajan

MS Computer Science student at USC. I build full-stack applications in Java and Spring with Angular or React front ends, and I build and evaluate LLM systems. Before USC I was a Software Analyst at Citi and a research intern at IIT Madras.

**Available for a co-op from January 2027 and full-time from May 2027**, in software engineering, applied AI / forward-deployed engineering, and ML roles.

[Portfolio](https://surendirabalaji.dev?ref=git) · [LinkedIn](https://linkedin.com/in/surendira-balaji-n/) · [surendirabalaji.n@gmail.com](mailto:surendirabalaji.n@gmail.com)

## Selected work

**Applied AI**

- [paper-analyst](https://github.com/surendirabalaji/paper-analyst): a multi-agent system that answers questions about a corpus of arXiv papers. A LangGraph supervisor delegates to research, summary and data agents, with RAG over Chroma, live web search through Tavily MCP, and cost/capability routing between two LLM providers with fallback. Deployed on Cloud Run and evaluated with RAGAS on a frozen 44-question test set.
- [GameBoyWorlds](https://github.com/DhananjayAshok/GameBoyWorlds): co-author of an embodied-AI benchmark that evaluates vision-language agents on grounding, navigation, planning and self-improvement. Under review at ICLR 2027.

**Full stack**

- [InvestMates](https://github.com/surendirabalaji/InvestMates): a stock portfolio tracker with a React and Vite front end, a Spring Boot 3 / Java 21 REST API, Spring Data JPA and MySQL. Covers holdings, FIFO sell logic with gain/loss, transaction history and watchlists.
- [Simple Mailer](https://github.com/cegaana/simple-mailer): an open-source TypeScript library and CLI for bulk and transactional email, built for CEGAANA. SQLite-backed dispatch with rate pacing, exponential backoff, crash recovery and pluggable transports.
- At Citi (July 2024 to July 2025) I built Java and Spring Boot microservices and an operations console in Angular and React, and upgraded Jenkins CI/CD pipelines.

**Systems**

- [distributed-key-value-store](https://github.com/surendirabalaji/distributed-key-value-store): a Raft-replicated key-value store in C++20 over gRPC, with leader election, log replication, exactly-once client semantics and lease reads. Benchmarked at about 6,000 ops/sec on a three-node local cluster before optimization.

**ML and computer vision**

- [Pose-Estimation-FYP](https://github.com/surendirabalaji/Pose-Estimation-FYP): human pose estimation with UniPose in PyTorch, my undergraduate final-year project and the basis of the yoga assistant patent below.
- [AyurVision](https://github.com/surendirabalaji/AR-Ayur-Vision-Herbal-Classification-Recommendation): herbal plant classification with a CNN exported to ONNX and run inside a Unity AR app, plus a similarity-based recommender.
- Co-inventor on a published patent for a digital-twin-based yoga assistant.

## Stack

| Area | Tools |
|---|---|
| Backend | Java, Spring Boot, Spring Data JPA, Hibernate, REST, gRPC, C++ |
| Frontend | Angular, React, TypeScript, JavaScript, HTML/CSS |
| Data | MySQL, SQL, Chroma |
| AI / ML | Python, PyTorch, TensorFlow, LangGraph, RAG, MCP, RAGAS, NumPy, Pandas |
| Cloud and tooling | Google Cloud Run, Docker, Git, Maven, CMake |
