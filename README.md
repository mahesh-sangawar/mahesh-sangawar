<img src="./assets/banner.svg" alt="Mahesh Sangawar" width="100%">

# Mahesh Sangawar

**Cloud architect and platform engineer. Sydney, Australia.**

I build platforms end to end: the infrastructure underneath, the services on top of it, and the developer experience that makes both worth using. Most of my work sits where cloud architecture, Kubernetes and product engineering meet.

Currently building [**Tesserix**](https://tesserix.app), where three products share one platform.

---

## Products

### [Mark8ly](https://mark8ly.com) &nbsp;·&nbsp; commerce

A multi-tenant commerce platform. A merchant signs up with an emailed link and gets a branded storefront and an admin dashboard on their own subdomain, with payments, shipping and tax handled per region. Roughly ten Go services and a set of Next.js apps, with per-tenant isolation enforced in the data layer rather than left to convention.

### [HomeChef](https://fe3dr.com) &nbsp;·&nbsp; food delivery

A three-sided marketplace: home chefs cook, drivers deliver, customers order. A Go and Gin backend, a Next.js marketing site, React operations consoles for vendors and delivery, and Expo mobile apps for each side of the market.

### [Kora](https://github.com/tesserix/kora) &nbsp;·&nbsp; AI nutrition tracking

Nutrition tracking for iOS and Android that does not feel like data entry. Log a meal by photographing it, describing it out loud, or just saying what you ate. The interesting problem is confidence: knowing when the model is sure enough to log silently and when it has to ask.

---

## The foundation

### [Tesserix Design System](https://github.com/tesserix/design-system)

`@tesserix/web`, the component library every Tesserix product is built from. TypeScript, Tailwind and shadcn/ui principles, shipped for web and React Native so a product and its mobile counterpart stay recognisably the same thing. Versioned with Changesets and published for reuse across every app.

[Documentation](https://docs.tesserix.app) &nbsp;·&nbsp; [Storybook](https://ui.tesserix.app)

### The platform underneath

A single GKE Autopilot foundation running every product above: Knative for scale to zero, Istio for the mesh, Argo CD and Kargo for GitOps promotion, OpenFGA for relationship-based authorization, and Terraform for everything below that. Built deliberately cheap to run, because a platform you cannot afford to keep running is not a platform.

---

## Open source

| Project | What it does |
|---|---|
| [**cloudnav**](https://github.com/tesserix/cloudnav) | Fast, keyboard-driven multi-cloud TUI for Azure, GCP and AWS. Drill through resources without leaving the terminal. |
| [**reposhift**](https://github.com/tesserix/reposhift) | Azure DevOps to GitHub migration platform. Moves repos, work items and pipelines. |
| [**sandboxctl**](https://github.com/tesserix/sandboxctl) | One-command local Kubernetes sandbox for macOS. kind, Argo CD, Kargo and Istio, ready to use. |
| [**agentic-registry**](https://github.com/tesserix/agentic-registry) | Gateway-neutral registry for agentic artifacts: skills, tools, MCP servers and prompts. |
| [**base-docker-images**](https://github.com/tesserix/base-docker-images) | Lean, non-root base images, rebuilt weekly against current CVEs. |
| [**homebrew-tap**](https://github.com/tesserix/homebrew-tap) | Homebrew formulae for Tesserix command line tools. |

---

## Working with

**Languages** Go, TypeScript, Python, Java

**Platform** Kubernetes (GKE Autopilot), Knative, Istio, Argo CD, Kargo, Crossplane, Terraform, Helm

**Cloud** GCP, AWS, Azure

**Backend** Gin, gRPC, PostgreSQL with CloudNativePG, Redis, Pub/Sub, NATS, OpenFGA, OpenTelemetry

**Frontend** Next.js, React, React Native with Expo, Tailwind CSS

---

## Elsewhere

[tesserix.app](https://tesserix.app) &nbsp;·&nbsp; [Engineering blog](https://blog.tesserix.app) &nbsp;·&nbsp; [LinkedIn](https://www.linkedin.com/in/mahesh-sangawar-985a3214) &nbsp;·&nbsp; AWS Certified Solutions Architect
