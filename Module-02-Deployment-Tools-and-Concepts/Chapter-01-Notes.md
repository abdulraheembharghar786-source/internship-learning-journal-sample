# Week 2 - Session 1 Notes (TDS Sep 2025)

## 📌 Topic: Containerization with Podman

---

## 1. Introduction to Containerization
- Containers provide lightweight, portable environments for applications.
- Difference from Virtual Machines:
  - **VMs:** Full OS virtualization, heavy resource usage.
  - **Containers:** Share host OS kernel, faster and more efficient.
- Benefits in Data Science:
  - Reproducibility
  - Dependency isolation
  - Easy deployment across systems

---

## 2. Podman Overview
- Podman: Daemonless container engine (alternative to Docker).
- Features:
  - Rootless operation → better security.
  - Docker‑compatible CLI.
  - Supports **pods** (groups of containers sharing resources).
- Installation:
  - Linux: `sudo apt install podman`
  - macOS: `brew install podman`

---

## 3. Running Jupyter Lab in Containers
- Pull Jupyter Lab image:
  ```bash
  podman pull jupyter/base-notebook

Run container:

podman run -it -p 8888:8888 jupyter/base-notebook

Access via browser: http://localhost:8888

Benefits:

Isolated Python environment

Avoids dependency conflicts
---
4. Running Local LLM (Olama) in Containers

Purpose: Experiment with Large Language Models locally.

Steps:

Pull image:

podman pull olama/llm

Run container:

podman run -it -p 5000:5000 olama/llm

Access via API/CLI.

Applications:

Offline experimentation

Prompt testing

Controlled workflows
---
5. Networking in Containers

Expose ports: -p host_port:container_port

Link multiple containers:

Use Podman pods for shared networking.

Example: Run Jupyter + Olama in same pod for integrated workflows.
---
6. Practical Demonstration

Install Podman

Pull images

Run Jupyter Lab

Run Olama LLM

Connect via browser/API

Show reproducibility in Data Science projects
---
7. Applications in Data Science

Reproducible research environments

Share containerized notebooks

Run LLMs locally for:

Preprocessing

Automated analysis

AI experimentation

Combine Jupyter + LLM for end‑to‑end workflows
---
8. Best Practices

Use versioned images for reproducibility.

Keep containers lightweight.

Monitor with:

podman ps
podman logs <container_id>

Clean up unused containers/images:

podman rm <container_id>
podman rmi <image_id>

--
