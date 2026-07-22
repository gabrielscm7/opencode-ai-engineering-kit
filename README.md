# OpenCode AI Engineering Kit

> A modular AI Engineering Framework for OpenCode projects.

The **OpenCode AI Engineering Kit** is a framework designed to transform AI-assisted software development into a structured engineering process.

Instead of relying on a single generic AI assistant, this project organizes specialized Agents, Skills, workflows, documentation and architectural artifacts into a repeatable development methodology.

The framework is designed for projects that use modern AI tooling such as:

- OpenCode
- DeepSeek
- Claude
- GPT models
- MCP (Model Context Protocol)
- RAG (Retrieval-Augmented Generation)
- n8n
- Vector Databases
- Draw.io MCP

---

# Vision

Software projects evolve.

Architecture evolves.

Documentation evolves.

AI context changes.

The purpose of this framework is to ensure that **architecture, documentation, code and AI knowledge evolve together**.

Rather than acting as a code generator, AI becomes an engineering team composed of specialized roles coordinated by an architectural orchestrator.

---

# Core Principles

- Documentation First
- Architecture First
- Small Iterative Improvements
- Continuous Review
- Living Documentation
- Reproducible Engineering
- Separation of Responsibilities
- Human-in-the-loop
- Incremental Refactoring
- AI-assisted Decision Making

---

# High-Level Architecture

```
                 User
                   │
                   ▼
         Chief Architect Agent
                   │
      ┌────────────┴────────────┐
      │                         │
      ▼                         ▼
 Architecture Skill        Improve Skill
      │                         │
      ▼                         ▼
 Documentation Skill      Review Skill
      │                         │
      └────────────┬────────────┘
                   ▼
              Draw.io MCP
                   │
                   ▼
       Living Architecture Docs
```

---

# Planned Components

## Agents

- Chief Architect

---

## Skills

- Architecture
- Documentation
- Improve
- Review
- Performance
- Security
- Testing
- RAG Auditor
- Knowledge Manager

---

## Supported Artifacts

- Architecture Documentation
- Draw.io Diagrams
- ADRs
- Technical Debt
- Roadmaps
- Project State
- Architecture Reports

---

# Repository Structure

```text
.opencode/

agents/

skills/

prompts/

state/

templates/

docs/

examples/
```

---

# Development Roadmap

## v0.1

Framework foundation

- Repository
- Folder structure
- Standards
- Documentation

## v0.2

Chief Architect

## v0.3

Architecture Skill

## v0.4

Documentation Skill

## v0.5

Improve Skill

## v0.6

Review Skill

## v0.7

Draw.io Integration

## v0.8

RAG Auditor

## v0.9

Performance & Security

## v1.0

Stable AI Engineering Framework

---

# Design Goals

This framework aims to:

- Reduce AI hallucinations.
- Improve architectural consistency.
- Keep documentation synchronized with the source code.
- Produce reproducible engineering workflows.
- Enable long-term AI-assisted software evolution.
- Support complex systems with multiple agents and MCP servers.

---

# License

Apache License 2.0
