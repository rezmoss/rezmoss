# Hi, I'm Rez 👋

I build security and infrastructure tools, take Go systems apart to see how they work, and publish the useful pieces.

Right now I lead VM scanning at [Aikido Security](https://github.com/AikidoSec), build products at [CloudAid](https://www.cloudaid.net), and contribute package-detection work to [Anchore Syft](https://github.com/anchore/syft/pulls?q=is%3Apr+author%3Arezmoss+is%3Amerged).

I also wrote [**Go at Scale**](https://www.amazon.com/Go-Scale-Patterns-Professional-Development/dp/1069363006), 528 pages on building production Go systems.

[Website](https://rezmoss.com) · [Latest writing](https://dev.to/rezmoss) · [Book](https://rezmoss.com/go-at-scale/) · [LinkedIn](https://www.linkedin.com/in/rezmoss/) · [X](https://twitter.com/rez_moss)

## Start here

- ☁️ [**CLOUD-IP**](https://cloudipdb.io): a daily-refreshed map of 63 cloud, CDN, SaaS, VPN, and crawler networks; 460K+ CIDRs with ready-to-use firewall formats.
- 🔎 [**sbomlyze**](https://github.com/rezmoss/sbomlyze): `git diff` for SBOMs; catch dependency, metadata, and package-integrity drift in CycloneDX, SPDX, and Syft documents.
- 🤖 [**Brainmox**](https://brainmox.com): a local-first AI professional with persistent memory, desktop tools, multiple channels, and an inspectable audit trail. In private beta.
- 📘 [**Go at Scale**](https://rezmoss.com/go-at-scale/): production patterns for concurrency, microservices, event-driven systems, observability, and testing, with [companion code](https://github.com/rezmoss/go-at-scale).
- 🧪 [**The workshop below**](#open-source-workshop): small CLIs, learning builds, browser tools, macOS experiments, and libraries. Pick a rabbit hole.

## Open-source workshop

### Security & software supply chain
- 🛡️ **Security research**: sometimes I dig through open-source Go projects for security flaws and responsibly report what I find [Published advisories](https://github.com/advisories?query=credit%3Arezmoss)
- 🧾 [**sbomlyze**](https://github.com/rezmoss/sbomlyze): compare SBOMs, detect same-version/different-hash tampering, and gate CI with human, JSON, or SARIF output.
- 🧰 [**Awesome Security Pipeline**](https://github.com/rezmoss/awesome-security-pipeline): CI-tested open-source controls organized into a practical GitHub Actions security pipeline.
- 🕸️ [**Network Vulnerability Scanner**](https://github.com/rezmoss/network-vulnerability-scanner): an educational Go build covering port scanning, service detection, and vulnerability identification.
- 🔗 [**Go Dependency Scanner**](https://github.com/rezmoss/go-dependency-scanner): build a dependency scanner from scratch and understand what the real tools are doing.
- 🔬 [**HTTPS Traffic Inspector**](https://github.com/rezmoss/https-traffic-inspector): a Go intercepting proxy for seeing the HTTP calls hidden inside SDK operations.
- ✉️ [**go-is-disposable-email**](https://github.com/rezmoss/go-is-disposable-email): fast, embeddable disposable-email detection for Go services.

### Cloud, networking & operations

- 🌍 [**cloud-provider-ip-addresses**](https://github.com/rezmoss/cloud-provider-ip-addresses): the source dataset behind CLOUD-IP; I rebuild it every day in 13+ machine- and firewall-friendly formats.
- 👀 [**ip-watch**](https://github.com/rezmoss/ip-watch): sync changing provider ranges into Nginx, Caddy, HAProxy, nftables, iptables, or UFW without breaking a running config.
- ⚡ **Cloud IP SDKs**: offline provider lookup for [Go](https://github.com/rezmoss/go-cloudip), [JavaScript/TypeScript](https://github.com/rezmoss/js-cloudip), and [Python](https://github.com/rezmoss/py-cloudip), backed by a compact [MessagePack database](https://github.com/rezmoss/cloudip-db).
- ⚖️ [**simple-load-balancer**](https://github.com/rezmoss/simple-load-balancer): round robin, weighted routing, and health checks using only Go's standard library.
- 💸 [**CostSweep**](https://github.com/rezmoss/costsweep): find and price AWS waste, print the annual total, and fail CI above a budget threshold; read the [three-part build log](https://dev.to/aws-builders/i-built-a-go-tool-that-found-4200yr-of-wasted-aws-spend-cost-explorer-api-part-1-326a).
- 🔭 [**real-time-system-monitor**](https://github.com/rezmoss/real-time-system-monitor): a terminal dashboard for CPU, memory, network activity, and hungry processes.
- 📡 [**Zero-configuration service discovery**](https://github.com/rezmoss/zero-configuration-service-discovery-system): a small Go implementation for learning how services find one another without a central registry.

### Go libraries, diagnostics & learning builds

- 🚀 [**axios4go**](https://github.com/rezmoss/axios4go): an Axios-inspired Go HTTP client with interceptors, retries, caching, progress tracking, and configurable instances.
- 🔭 [**goroscope**](https://github.com/rezmoss/goroscope): `htop` for goroutines; collapse pprof dumps into live stack groups and spot the one that keeps growing.
- 💽 [**partition-analyzer**](https://github.com/rezmoss/partition-analyzer): parse MBR and GPT partition tables in Go, then [try the WebAssembly version](https://rezmoss.com/tools/disk-analyzer/) without uploading a disk image.
- 🍎 [**macOS hardware detection**](https://github.com/rezmoss/macos-hardware-detection-go): inspect Mac hardware from Go without reaching for a heavyweight framework.
- ⏱️ [**TimeTrackCLI**](https://github.com/rezmoss/timetrackcli): private, local-only automatic time tracking with a terminal dashboard, goals, and reports.

### Browser tools, apps & weekend experiments

- 🧠 [**VocabAmp**](https://vocabamp.com): AI-assisted flashcards with FSRS spaced repetition; [source](https://github.com/rezmoss/vocabamp).
- 🕰️ [**CityChime**](https://github.com/rezmoss/citychime): a small macOS city-hall clock app I built to learn Go.
- 💡 [**virtual-light**](https://github.com/rezmoss/virtual-light): control a virtual Go light from Apple's Home app through HomeKit.
- 🏊 [**Pool Water Planner**](https://rezmoss.com/tools/pool-water-planner/): a browser-based pool chemistry calculator, built for my own pool rather than a product roadmap.
- 🧹 [**diskfree**](https://github.com/rezmoss/diskfree): an APFS-aware Go disk scanner that finds what is really consuming space—including sparse files, rebuildable caches, and Time Machine snapshots—and lets you clean it up interactively
- 📐 [**MyMeasure**](https://github.com/rezmoss/mymeasure): iOS experiment that earned a permanent place on my phone—and a few friends' phones—for LiDAR measurements, photo annotations, and 2D/3D room scans
- 🗺️ [**MyExplore**](https://github.com/rezmoss/myexplore): iPhone experiment that turns everyday movement into a private fog-of-war game—walk or drive to reveal the map while every breadcrumb stays offline on your phone
- 🏠 [**MyHouse**](https://github.com/rezmoss/myhouse): the iPhone app I built to remember how my own house works—what needs maintenance, where the shutoffs are, which contractor fixed what, and when appliances may need replacing

[Browse all repositories, newest activity first →](https://github.com/rezmoss?tab=repositories&q=&type=source&language=&sort=updated)

## Reading trails

I write implementation-focused series: **50+ articles on DEV**, plus field notes and interactive tools on my own site.

- 🔐 [**Go's crypto package**](https://dev.to/rezmoss/unlocking-the-power-of-gos-crypto-package-go-crypto-1-4m0p): 14 parts, from primitives and encryption through TLS, password hashing, constant-time code, and real applications.
- 🗂️ [**Go's `fs` package**](https://dev.to/rezmoss/gos-fs-package-modern-file-system-abstraction-19-5aad): 9 parts on interfaces, traversal, custom filesystems, `embed.FS`, and testing.
- 🕐 [**Go's `time` package**](https://dev.to/rezmoss/understanding-time-in-go-110-1j85): 10 parts on clocks, durations, time zones, timers, calendars, and production pitfalls.
- 🌐 [**Go's `net/netip` package**](https://dev.to/rezmoss/understanding-gos-netnetip-addr-type-a-deep-dive-17-j7b): 7 parts on addresses, prefixes, CIDR set operations, and `AddrPort`.
- 🔤 [**Inside `strconv`**](https://rezmoss.com/blog/basic-conversions-atoi-and-itoa-p1-7/): 7 parts from parsing integers and floats to allocation-aware append APIs, quoting, and Unicode utilities.
- 💸 [**Finding AWS waste in Go**](https://dev.to/aws-builders/i-built-a-go-tool-that-found-4200yr-of-wasted-aws-spend-cost-explorer-api-part-1-326a): a 3-part build from Cost Explorer calls to a $4,204 demo report and CI gate.
- ☸️ [**Enhancing Kubernetes Event Management with Custom Aggregation**](https://kubernetes.io/blog/2025/06/10/enhancing-kubernetes-event-management-custom-aggregation/): my Kubernetes Blog guide to building event watchers, correlation, storage, and pattern detection in Go.
- 🛡️ [**SBOM integrity drift**](https://dev.to/rezmoss/same-version-different-hash-the-sbom-drift-your-manifest-diff-cannot-see-304i): why matching versions can still hide changed package contents.
- 🧵 [**Build a live goroutine visualizer**](https://rezmoss.com/blog/build-live-goroutine-visualizer-leak-detector-go/): turn pprof noise into groups you can inspect while a process runs.

[All field notes](https://rezmoss.com/blog/) · [All DEV articles](https://dev.to/rezmoss) · [HackerNoon stories](https://hackernoon.com/u/rezmoss) · [AWS Community Builders posts](https://dev.to/aws-builders/how-to-schedule-ec2-instances-to-stopstart-automatically-1bl5)

## Products beyond the repositories

- ☁️ [**CloudAid**](https://www.cloudaid.net): the cloud and DevOps company I founded in 2020.
- 🤖 [**Brainmox**](https://brainmox.com): local-first AI professionals with persistent identity, memory, tools, and privacy controls.
- 📞 [**PBXDom**](https://www.pbxdom.com): the call-analytics platform I launched in 2015; it has analyzed 14B+ calls for 500+ companies.
- 🧰 [**HTTPfy**](https://httpfy.io): 40+ small browser tools for networking, DNS, security, data conversion, and everyday DevOps work.
- 📈 [**StatusAid**](https://statusaid.com): website health monitoring across DNS, TLS, servers, email, performance, and content integrity.
- 📱 [**CloudAid Studio / Motively**](https://www.cloudaidstudio.com): a mobile motivation app with 100,000+ hand-picked quotes.

## Elsewhere

- ✍️ [DEV](https://dev.to/rezmoss): 50+ posts, including work with AWS Community Builders.
- 📰 [HackerNoon](https://hackernoon.com/u/rezmoss): stories about hashing, load balancers, dependency scanners, and SBOM diffing.
- 💬 [Stack Overflow](https://stackoverflow.com/users/6619626/rez-moss): an archive of practical answers from years of debugging AWS, S3, Node.js, and cloud infrastructure problems.
- 📚 [Go at Scale](https://www.amazon.com/Go-Scale-Patterns-Professional-Development/dp/1069363006): the book and its [open companion repository](https://github.com/rezmoss/go-at-scale).
