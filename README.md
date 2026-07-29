<img src="./assets/banner.svg" alt="Mahesh Sangawar" width="100%">

# Mahesh Sangawar

**Cloud architect and platform engineer. Sydney, Australia.**

I build platforms end to end: the infrastructure underneath, the services on top of it, and the developer experience that makes both worth using. Most of my work sits where cloud architecture, Kubernetes and product engineering meet.

Currently building [**Tesserix**](https://tesserix.app), where I work on multi-tenant commerce, agentic tooling, and the platform that runs it all.

---

## What I am building

### [Mark8ly](https://mark8ly.com)

A multi-tenant commerce platform. A merchant signs up with an emailed link and gets a branded storefront and an admin dashboard on their own subdomain, with payments, shipping and tax handled per region. Roughly ten Go services and a set of Next.js apps, running on GKE with per-tenant isolation enforced in the data layer rather than left to convention.

### The platform underneath

A single GKE Autopilot foundation running every Tesserix product: Knative for scale to zero, Istio for the mesh, Argo CD and Kargo for GitOps promotion, OpenFGA for relationship-based authorization, and Terraform for everything below that. Built deliberately cheap to run, because a platform you cannot afford to keep running is not a platform.

---

## Open source

| Project | What it does |
|---|---|
| [**cloudnav**](https://github.com/tesserix/cloudnav) | Fast, keyboard-driven multi-cloud TUI for Azure, GCP and AWS. Drill through resources without leaving the terminal. |
| [**reposhift**](https://github.com/tesserix/reposhift) | Azure DevOps to GitHub migration platform. Moves repos, work items and pipelines. |
| [**sandboxctl**](https://github.com/tesserix/sandboxctl) | One-command local Kubernetes sandbox for macOS. kind, Argo CD, Kargo and Istio, ready to use. |
| [**agentic-registry**](https://github.com/tesserix/agentic-registry) | Gateway-neutral registry for agentic artifacts: skills, tools, MCP servers and prompts. |
| [**base-docker-images**](https://github.com/tesserix/base-docker-images) | Lean, non-root base images, rebuilt weekly against current CVEs. |
| [**design-system**](https://github.com/tesserix/design-system) | Design system for web and React Native. TypeScript, Tailwind and shadcn/ui principles. [Docs](https://docs.tesserix.app) |
| [**homebrew-tap**](https://github.com/tesserix/homebrew-tap) | Homebrew formulae for Tesserix command line tools. |

---

## Working with

**Languages** Go, TypeScript, Python, Java

**Platform** Kubernetes (GKE Autopilot), Knative, Istio, Argo CD, Kargo, Crossplane, Terraform, Helm

**Cloud** GCP, AWS, Azure

**Backend** Gin, gRPC, PostgreSQL with CloudNativePG, Redis, Pub/Sub, OpenFGA, OpenTelemetry

**Frontend** Next.js, React, React Native with Expo, Tailwind CSS

---

## Elsewhere

[tesserix.app](https://tesserix.app) &nbsp;·&nbsp; [Engineering blog](https://blog.tesserix.app) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/mahesh-sangawar) &nbsp;·&nbsp; AWS Certified Solutions Architect
