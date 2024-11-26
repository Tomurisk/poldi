# :owl: Poldi

Personal bucket for lovely [Scoop](https://scoop.sh/).\
Made for personal use, free for everyone.

## Usage

```powershell
scoop bucket add poldi https://github.com/aliesbelik/poldi
# Recommended, but you can omit the bucket name most of the time
scoop install poldi/<app>
```

## Apps

> Only apps NOT available in `scoop bucket known` buckets.

<details>
  <summary><strong>AI</strong></summary>

- [tgpt](https://github.com/aandrew-me/tgpt) - AI Chatbots in terminal without needing API keys.
- [yai](https://github.com/ekkinox/yai) - AI powered terminal assistant.

</details>

<details>
  <summary><strong>Benchmarking</strong></summary>

- [ali](https://github.com/nakabonne/ali) - A HTTP load testing tool capable of performing real-time analysis, inspired by `vegeta` and `jplot`.
- [beast](https://github.com/jjmrocha/beast) - Stress testing tool for RESTful APIs.
- [blast](https://github.com/dave/blast) - A simple, protocol agnostic tool for API load testing and batch jobs, written in Go.
- [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load testing tool written in Go, inspired by `k6`, `ab` & `httpstat`.
- [clobbr-cli](https://github.com/parsecph/clobbr) - A CLI tool to test API endpoint speed.
- [fortio](https://github.com/fortio/fortio) - A HTTP/gRPC load testing library, CLI tool, advanced echo server and web UI written in Go.
- [ghz](https://github.com/bojand/ghz) - Simple gRPC benchmarking and load testing tool written in Go.
- [gobench](https://github.com/EricNeid/go-bench) - HTTP/HTTPS load testing and benchmarking tool written in Go.
- [gocannon](https://github.com/kffl/gocannon) - Performance-focused HTTP load testing tool written in Go.
- [goku](https://github.com/k-nasa/goku) - A HTTP load testing application written in Rust.
- [goku-bench](https://github.com/jcaromiq/goku) - Another HTTP load testing application written in Rust, inspired by `drill` and `vegeta`.
- [gopayloader](https://github.com/domsolutions/gopayloader) - HTTP/S benchmark/load testing cross-platform tool with optional JWT generation, inspired by `bombardier`.
- [hey](https://github.com/rakyll/hey) - HTTP load generator, ApacheBench (`ab`) replacement.
- [ntttcp](https://github.com/microsoft/ntttcp) - A Windows network throughput benchmarking tool.
- [pewpew](https://github.com/bengadbois/pewpew) - A flexible HTTP CLI stress testing tool for websites and web services, written in Go.
- [plow](https://github.com/six-ddc/plow) - A high-performance HTTP benchmarking tool written in Go, with real-time web UI and terminal displaying.
- [reqstress](https://github.com/utkusen/reqstress) - A benchmarking & stressing tool that can send raw HTTP requests, written in Go.
- [rewrk](https://github.com/lnx-search/rewrk) - A modern HTTP framework benchmarking tool written in Rust, supporting HTTP/1 and HTTP/2 benchmarks.
- [rip](https://github.com/bjarneo/rip) - An HTTP load testing and UDP flood attack tool written in Go.
- [terjang](https://github.com/andylibrian/terjang) - Scalable HTTP load testing tool built on `vegeta`.
- [vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library written in Go.

</details>

<details>
  <summary><strong>Database</strong></summary>

- [atlas](https://github.com/ariga/atlas) - A language-agnostic tool for managing and migrating database schemas as code.
- [dblab](https://github.com/danvergara/dblab) - A fast and lightweight interactive terminal based UI application for PostgreSQL, MySQL and SQLite3, written in Go.
- [pgweb](https://github.com/sosedoff/pgweb) - Simple web-based and cross platform PostgreSQL database explorer written in Go.
- [rainfrog](https://github.com/achristmascarl/rainfrog) - A database management TUI for PostgreSQL.

</details>

<details>
  <summary><strong>Development</strong></summary>

- [cpa](https://github.com/ysawa0/create-python-app) - A CLI tool for ultra fast setup of Rust & Python projects.

</details>

<details>
  <summary><strong>DevOps</strong></summary>

- [ctlptl](https://github.com/tilt-dev/ctlptl) - A CLI for declaratively setting up local Kubernetes clusters.
- [dry](https://github.com/moncho/dry) - A terminal application to manage and monitor Docker containers.
- [gocker](https://github.com/pommee/gocker) - A TUI tool for Docker management.
- [helmify](https://github.com/arttor/helmify) - A CLI tool to create Helm charts from Kubernetes YAMLs.
- [helmsman](https://github.com/Praqma/helmsman) - A Helm charts as code tool to automate the deployment/management of Helm charts from version controlled code.
- [kafkactl](https://github.com/deviceinsight/kafkactl) - A CLI tool for managing Apache Kafka.
- [kafta](https://github.com/electric-saw/kafta) - A modern non-JVM command-line for managing Kafka clusters written in Go.
- [kail](https://github.com/boz/kail) - Kubernetes log viewer.
- [kcli](https://github.com/cswank/kcli) - A Kafka read-only command-line browser.
- [kubedump](https://github.com/msfidelis/kubedump) - Simple tool to dump and restore Kubernetes resources.
- [kubestr](https://github.com/kastenhq/kubestr) - A collection of tools to discover, validate and evaluate Kubernetes storage options.
- [kubewall](https://github.com/kubewall/kubewall) - A single binary Kubernetes dashboard to manage multiple clusters.
- [netfetch](https://github.com/deggja/netfetch) - Kubernetes tool for scanning clusters for network policies and identifying unprotected workloads.
- [oxker](https://github.com/mrjackwills/oxker) - A simple TUI to view & control Docker containers.
- [prom2json](https://github.com/prometheus/prom2json) - A tool to scrape a Prometheus client and dump the result as JSON.
- [tanka](https://github.com/grafana/tanka) - A robust configuration utility for Kubernetes cluster, powered by the Jsonnet language.
- [terrap](https://github.com/sirrend/terrap-cli) - A CLI tool to scan your infrastructure and identify any required changes.
- [tpm](https://github.com/Madh93/tpm) - A package manager for Terraform providers.
- [updo](https://github.com/Owloops/updo) - Uptime monitoring CLI tool with alerting and advanced settings.
- [werf](https://github.com/werf/werf) - A CNCF Sandbox CLI tool to implement full-cycle CI/CD to Kubernetes easily.
- [yc](https://cloud.yandex.ru/docs/cli/) - CLI for Yandex Cloud.

</details>

<details>
  <summary><strong>Git</strong></summary>

- [ghdl](https://github.com/beetcb/ghdl) - A convenient way to download GitHub release binaries from the command line.
- [ghs](https://github.com/sonatard/ghs) - A CLI utility for searching Github repository.
- [gickup](https://github.com/cooperspencer/gickup) - A tool to clone/mirror cloud Git repositories.
- [git-extras](https://github.com/tj/git-extras) - Git utilities: repo summary, repl, changelog population, author commit percentages and more.
- [git-sync](https://github.com/AkashRajpurohit/git-sync) - A CLI tool to backup and sync your git repositories.

</details>

<details>
  <summary><strong>Misc</strong></summary>

- [anew](https://github.com/tomnomnom/anew) - A tool for adding new lines to files, skipping duplicates.
- [assh](https://github.com/moul/assh) - A transparent wrapper that adds support for regex, aliases, gateways, dynamic hostnames, graphviz, json output, yaml configuration, and more to SSH.
- [binjr](https://github.com/binjr/binjr) - A standalone time series data browser.
- [certinfo](https://github.com/pete911/certinfo) - Print X.509 certificate info.
- [changie](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
- [csvq](https://github.com/mithrandie/csvq) - A CLI tool to operate CSV with SQL-like query.
- [diffnav](https://github.com/dlvhdr/diffnav) - A git diff pager based on `delta` but with a file tree, à la GitHub.
- [dirx](https://github.com/chrisant996/dirx) - The `dir` command, extended.
- [diskus](https://github.com/sharkdp/diskus) - A minimal, fast alternative to `du -sh`.
- [diskusage](https://github.com/chenquan/diskusage) - A CLI tool for showing disk usage.
- [dsq](https://github.com/multiprocessio/dsq) - CLI tool for running SQL queries against JSON, CSV, Excel, Parquet, and more.
- [dyff](https://github.com/homeport/dyff) - Diff tool for YAML files, and sometimes JSON.
- [ego](https://github.com/koki-develop/ego) - An `echo` alternative written in Go.
- [ente-cli](https://github.com/ente-io/ente) - A CLI utility for exporting data from Ente Photos.
- [epoch](https://github.com/sj14/epoch) - Easily convert epoch timestamps to human-readable formats and vice versa.
- [filebrowser](https://github.com/filebrowser/filebrowser) - Web file browser.
- [flog](https://github.com/mingrammer/flog) - A fake log generator for common log formats.
- [gat](https://github.com/koki-develop/gat) - A `cat` alternative written in Go.
- [goawk](https://github.com/benhoyt/goawk) - A POSIX-compliant AWK interpreter written in Go, with CSV support.
- [godu](https://github.com/viktomas/godu) - Simple CLI utility helping to discover large files/folders.
- [gojq](https://github.com/itchyny/gojq) - Pure Go implementation of `jq`.
- [gokey](https://github.com/cloudflare/gokey) - A simple vaultless password manager in Go.
- [gomi](https://github.com/babarot/gomi) - A simple CLI trash tool, written in Go.
- [hgrep](https://github.com/rhysd/hgrep) - Grep with human-friendly search results.
- [hl](https://github.com/pamburus/hl) - A fast and powerful log viewer and processor that translates JSON or logfmt logs into a pretty human-readable format.
- [hq](https://github.com/orf/html-query) - Like `jq`, but for HTML.
- [humanlog](https://github.com/humanlogio/humanlog) - Read logs from stdin and prints them back to stdout, but prettier.
- [hwatch](https://github.com/blacknon/hwatch) - A modern alternative to the watch command, records the differences in execution results and can check this differences at after.
- [jlv](https://github.com/hedhyw/json-log-viewer) - Interactive viewer for JSON logs.
- [jnv](https://github.com/ynqa/jnv) - Interactive JSON filter using `jq`.
- [jql](https://github.com/yamafaktory/jql) - A JSON Query Language CLI tool.
- [jvms](https://github.com/ystyle/jvms) - JDK Version Manager (JVMS) for Windows.
- [pdu](https://github.com/KSXGitHub/parallel-disk-usage) - Highly parallelized, blazing fast directory tree analyzer.
- [phraze](https://github.com/sts10/phraze) - Generate random passphrases.
- [qrtool](https://github.com/sorairolake/qrtool) - A command-line utility for encoding or decoding QR code.
- [query-json](https://github.com/davesnx/query-json) - Faster, simpler and more portable implementation of `jq` in Reason.
- [qv](https://github.com/timvw/qv) - A simple CLI to quickly view your data.
- [rq](https://github.com/dflemstr/rq) - Record Query, a tool for doing record analysis and transformation.
- [schemacheck](https://github.com/adrielp/schemacheck) - A CLI utility to validate YAML and JSON files against a schema written in Go.
- [sq](https://github.com/neilotoole/sq) - A command-line tool that provides `jq`-style access to structured data sources: SQL databases, or document formats like CSV or Excel.
- [stew](https://github.com/marwanhawari/stew) - An independent package manager for compiled binaries.
- [sttr](https://github.com/abhimanyu003/sttr) - Command-line application to perform various operations on strings.
- [superfile](https://github.com/yorukot/superfile) - Pretty fancy and modern terminal file manager.
- [tdu](https://github.com/josephpaul0/tdu) - Top Disk Usage, a command-line tool to estimate the disk space occupied by all files in a given path.
- [tlrc](https://github.com/tldr-pages/tlrc) - A `tldr` client written in Rust.
- [trdsql](https://github.com/noborus/trdsql) - CLI tool to execute SQL queries on CSV, LTSV, JSON and TBLN, with output to various formats.
- [unfurl](https://github.com/tomnomnom/unfurl) - Pull out bits of URLs provided on stdin.
- [xq](https://github.com/MiSawa/xq) - Pure Rust implementation of `jq`.
- [xurls](https://github.com/mvdan/xurls) - Extract URLs from text.
- [yamlfmt](https://github.com/google/yamlfmt) - An extensible command-line tool or library to format YAML files.
- [yj](https://github.com/sclevine/yj) - Convert between YAML, TOML, JSON, and HCL.

</details>

<details>
  <summary><strong>Network</strong></summary>

- [bandwhich](https://github.com/imsnif/bandwhich) - Terminal bandwidth utilization tool.
- [cdntest](https://github.com/Redundancy/cdntest) - A CLI tool for gathering info in order to debug CDN connection issues without requiring end users to install and use complicated tools.
- [cidr](https://github.com/bschaatsbergen/cidr) - A CLI tool to perform various actions on CIDR ranges.
- [dnsping](https://github.com/fortio/dnsping) - DNS ping utility to check packet loss and latency issues with DNS servers.
- [dnstrace](https://github.com/rs/dnstrace) - A DNS resolution tracing tool, performs a DNS resolution by tracing the delegation path from the root name servers, and by following the CNAME chain.
- [dnsx](https://github.com/projectdiscovery/dnsx) - A fast and multi-purpose DNS toolkit allow to run multiple DNS queries using `retryabledns` library.
- [dt](https://github.com/42wim/dt) - DNS tool to display information about your domain.
- [fast](https://github.com/ddo/fast) - Minimal zero-dependency utility for testing your internet download speed from terminal.
- [goreplay](https://github.com/buger/goreplay) - A network monitoring tool which can record live traffic, and use it for shadowing, load testing, monitoring and detailed analysis.
- [gossl](https://github.com/vvrnv/gossl) - Simple CLI app for checking SSL certificates written in Go.
- [httpie-go](https://github.com/nojima/httpie-go) - `httpie`-like HTTP client written in Go.
- [httprobe](https://github.com/tomnomnom/httprobe) - Take a list of domains and probe for working HTTP and HTTPS servers.
- [httpx](https://github.com/projectdiscovery/httpx) - A fast and multi-purpose HTTP toolkit allows to run multiple probers using `retryablehttp` library.
- [mturoute](https://elifulkerson.com/projects/mturoute.php) - Eli Fulkerson's CLI tool analogous to `ping` and `traceroute`, which finds the maximum MTU between you and another host by passing ICMP requests with differing payload size.
- [naabu](https://github.com/projectdiscovery/naabu) - A fast port scanner written in Go with a focus on reliability and simplicity.
- [pingu](https://github.com/sheepla/pingu) - Ping command implementation but with Pingu ASCII art, written in Go.
- [proxify](https://github.com/projectdiscovery/proxify) - Swiss Army knife proxy tool for HTTP/HTTPS traffic capture, manipulation and replay written in Go.
- [speedbump](https://github.com/kffl/speedbump) - TCP proxy for simulating variable, yet predictable network latency.
- [tcping-go](https://github.com/cloverstd/tcping) - Ping over a TCP connection, like `tcping`, written in Go.
- [tlsx](https://github.com/projectdiscovery/tlsx) - Fast and configurable TLS grabber focused on TLS based data collection.
- [whris](https://github.com/harakeishi/whris) - A CLI tool to display management information for IPs associated with the domain.

</details>

<details>
  <summary><strong>Productivity</strong></summary>

- [bartib](https://github.com/nikolassv/bartib) - A simple timetracker for the command line.
- [chrono](https://github.com/gochrono/chrono) - A fast time tracking tool, written in Go.
- [ck-cli](https://github.com/clippingkk/cli) - A CLI tool to parse Amazon's My Clippings.txt to JSON format.
- [dijo](https://github.com/oppiliappan/dijo) - Scriptable, curses-based, digital habit tracker.
- [hmm](https://github.com/samwho/hmm) - A small command-line note taking app written in Rust.
- [mani](https://github.com/alajmo/mani) - CLI tool to help you manage repositories.
- [openpomodoro-cli](https://github.com/open-pomodoro/openpomodoro-cli) - A command-line Pomodoro tracker which uses the Open Pomodoro Format.
- [todoist-cli](https://github.com/sachaos/todoist) - Todoist CLI client, written in Golang.
- [tuifeed](https://github.com/veeso/tuifeed) - A terminal feed reader with a fancy UI.

</details>

<details>
  <summary><strong>Testing</strong></summary>

- [ain](https://github.com/jonaslu/ain) - A terminal API client, alternative to `postman`, `paw` or `insomnia`.
- [atac](https://github.com/Julien-cpsn/ATAC) - A simple `postman` like API client for terminal.
- [claws](https://github.com/thehowl/claws) - An interactive command-line client for testing WebSockets servers.
- [grpc-client-cli](https://github.com/vadimi/grpc-client-cli) - Generic gRPC command-line client.
- [grpcui](https://github.com/fullstorydev/grpcui) - An interactive web UI for gRPC, along the lines of `postman`.
- [hetty](https://github.com/dstotijn/hetty) - An HTTP toolkit for security research.
- [httplab](https://github.com/qustavo/httplab) - An interactive web server written in Go.
- [mqttui](https://github.com/EdJoPaTo/mqttui) - Subscribe to a MQTT Topic or publish something quickly from the terminal.
- [muffet](https://github.com/raviqqe/muffet) - Fast website link checker in Go.
- [nap](https://github.com/davesheldon/nap) - A command-line tool that utilizes YAML files to test APIs.
- [pict](https://github.com/microsoft/pict) - Pairwise Independent Combinatorial Tool.
- [plumber](https://github.com/streamdal/plumber) - A swiss army knife CLI tool for interacting with Kafka, RabbitMQ and other messaging systems.
- [trubka](https://github.com/xitonix/trubka) - A CLI tool for Kafka.
- [websocat](https://github.com/vi/websocat) - A CLI client for WebSockets, like `netcat` (or `curl`) for ws:// with advanced `socat`-like functions.
- [wombat](https://github.com/rogchap/wombat) - Cross platform gRPC client.

</details>

<details>
  <summary><strong>Migrated</strong></summary>

- [bombardier](https://github.com/codesenberg/bombardier) - Migrated, use `main/bombardier`.
- [curlie](https://github.com/rs/curlie) - Migrated, use `main/curlie`.
- [ddosify](https://github.com/ddosify/ddosify) - Migrated, use `main/ddosify`.
- [dnslookup](https://github.com/ameshkov/dnslookup) - Migrated, use `main/dnslookup`.
- [dnsproxy](https://github.com/AdguardTeam/dnsproxy) - Migrated, use `main/dnsproxy`.
- [doggo](https://github.com/mr-karan/doggo) - Migrated, use `main/doggo`.
- [eget](https://github.com/zyedidia/eget) - Migrated, use `extras/eget`.
- [focus](https://github.com/ayoisaiah/focus) -  Migrated, use `extras/focus`.
- [gotop](https://github.com/xxxserxxx/gotop) - Migrated, use `main/gotop`.
- [gut](https://github.com/julien040/gut) - Migrated, use `main/gut`.
- [hopp-cli](https://github.com/hoppscotch/hopp-cli) - Migrated, use `main/hopp-cli`.
- [jaq](https://github.com/01mf02/jaq) - Migrated, use `main/jaq`.
- [jc](https://github.com/kellyjonbrazil/jc) - Migrated, use `main/jc`.
- [jo](https://github.com/jpmens/jo) - Migrated, use `main/jo`.
- [mqtt-cli](https://github.com/hivemq/mqtt-cli) - Migrated, use `extras/mqtt-cli`.
- [octosql](https://github.com/cube2222/octosql) - Migrated, use `main/octosql`.
- [oha](https://github.com/hatoo/oha) - Migrated, use `main/oha`.
- [ov](https://github.com/noborus/ov) - Migrated, use `main/ov`.
- [restfox](https://github.com/flawiddsouza/Restfox) - Migrated, use `extras/restfox`.
- [riff](https://github.com/walles/riff) - Migrated, use `extras/riff`.
- [sshs](https://github.com/quantumsheep/sshs) - Migrated, use `extras/sshs`.
- [tailspin](https://github.com/bensadeh/tailspin) - Migrated, use `main/tailspin`.
- [taplo](https://github.com/tamasfe/taplo) - Migrated, use `main/taplo`.
- [tcping](https://elifulkerson.com/projects/tcping.php) - Migrated, use `main/tcping`.
- [termscp](https://github.com/veeso/termscp) - Migrated, use `main/termscp`.
- [tf-summarize](https://github.com/dineshba/tf-summarize) - Migrated, use `main/tf-summarize`.
- [ttdl](https://github.com/VladimirMarkelov/ttdl) - Migrated, use `extras/ttdl`.
- [wait4x](https://github.com/atkrad/wait4x) - Migrated, use `extras/wait4x`.
- [walk](https://github.com/antonmedv/walk) -  Migrated, use `main/walk`.

</details>
