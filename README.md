# Rez Moss

I build infrastructure and security tools that tell you what changed in your stack and whether you can trust it.

Leading VM scanning at [@AikidoSec](https://github.com/AikidoSec) · Founder of [CloudAid](https://github.com/cloudaidnet) · Author of [Go at Scale](https://www.amazon.com/Go-Scale-Patterns-Professional-Development/dp/1069363006)

[Website](https://rezmoss.com) · [Writing](https://rezmoss.com/blog) · [Book](https://www.amazon.com/Go-Scale-Patterns-Professional-Development/dp/1069363006) · [X](https://twitter.com/rez_moss) · [LinkedIn](https://www.linkedin.com/in/rezmoss/)

---

## What I'm building

### CLOUD-IP

CLOUD-IP assembles daily cloud and network intelligence from 60+ cloud providers, CDNs, SaaS platforms, crawlers, and VPN networks.

**Updated daily · firewall-ready formats · service and region data**

[Live dashboard](https://cloudipdb.io) · [Dataset](https://github.com/rezmoss/cloud-provider-ip-addresses) · [Go SDK](https://github.com/rezmoss/go-cloudip) · [JavaScript SDK](https://github.com/rezmoss/js-cloudip) · [Python SDK](https://github.com/rezmoss/py-cloudip) · [Auto-sync](https://github.com/rezmoss/ip-watch)

- Download ready-to-use CIDRs and configurations for web servers and firewalls
- Look up providers and track network changes without maintaining dozens of upstream integrations

### sbomlyze

**`git diff` for your SBOM.**

[sbomlyze](https://github.com/rezmoss/sbomlyze) compares CycloneDX, SPDX, and Syft documents to expose dependency, metadata, and integrity drift.

It catches a package hash changing without a version bump, a supply-chain signal that manifest diffs and vulnerability scanners miss.

[Repository](https://github.com/rezmoss/sbomlyze) · [GitHub Action](https://github.com/marketplace/actions/sbomlyze-diff) · [Live tampering demo](https://github.com/rezmoss/sbomlyze-go-spdx-demo/pull/2)

---

## More projects

### Security and infrastructure

- [Awesome Security Pipeline](https://github.com/rezmoss/awesome-security-pipeline): tested open-source security controls organized by CI/CD stage
- [ip-watch](https://github.com/rezmoss/ip-watch): synchronize cloud-provider IP ranges with web servers and firewalls without breaking live traffic
- [go-is-disposable-email](https://github.com/rezmoss/go-is-disposable-email): fast disposable-email detection for Go applications

### Go systems

- [axios4go](https://github.com/rezmoss/axios4go): Axios-inspired Go HTTP client with interceptors, retries, caching, and progress tracking
- [simple-load-balancer](https://github.com/rezmoss/simple-load-balancer): an educational HTTP load balancer built with the Go standard library

---

## Field notes

I write implementation-focused articles about Go internals, cloud infrastructure, and software supply-chain security.

- [Build a Live Goroutine Visualizer in Go](https://rezmoss.com/blog/build-live-goroutine-visualizer-leak-detector-go/)
- [Compare Container SBOMs and Detect Drift Between Image Versions](https://rezmoss.com/blog/compare-container-sbom-detect-drift-image-versions/)
- [Beyond Vulnerability Scanning: How SBOM Diff Exposes Shadow Dependencies](https://dev.to/rezmoss/beyond-vulnerability-scanning-how-sbom-diff-exposes-shadow-dependencies-in-your-supply-chain-1m6k)
- [Inside Go's strconv: a seven-part deep dive](https://rezmoss.com/blog/basic-conversions-atoi-and-itoa-p1-7/)

[Read all field notes →](https://rezmoss.com/blog)

---

## Go at Scale

I wrote [**Go at Scale: Patterns for Professional Development**](https://www.amazon.com/Go-Scale-Patterns-Professional-Development/dp/1069363006), covering concurrency, microservices, event-driven systems, observability, testing, and production engineering.

[Book](https://www.amazon.com/Go-Scale-Patterns-Professional-Development/dp/1069363006) · [Companion code](https://github.com/rezmoss/go-at-scale)
