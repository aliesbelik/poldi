# :owl: Poldi

Personal bucket for lovely [Scoop](https://scoop.sh/).

## Usage

```powershell
scoop bucket add poldi https://github.com/aliesbelik/poldi
# Recommended, but you can omit the bucket name most of the time
scoop install poldi/<app>
```

## Apps

> Only apps NOT available in `scoop bucket known` buckets.

<details>
  <summary><strong>Benchmarking</strong></summary>

- [ali](https://github.com/nakabonne/ali) - A HTTP load testing tool capable of performing real-time analysis, inspired by `vegeta` and `jplot`.
- [beast](https://github.com/jjmrocha/beast) - Stress testing tool for RESTful APIs.
- [blast](https://github.com/dave/blast) - A simple, protocol agnostic tool for API load testing and batch jobs, written in Go.
- [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in Go.
- [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load testing tool written in Go, inspired by `k6`, `ab` & `httpstat`.
- [fortio](https://github.com/fortio/fortio) - A HTTP/gRPC load testing library, CLI tool, advanced echo server and web UI written in Go.
- [ghz](https://github.com/bojand/ghz) - Simple gRPC benchmarking and load testing tool written in Go.
- [goku](https://github.com/k-nasa/goku) - A HTTP load testing application written in Rust.
- [hey](https://github.com/rakyll/hey) - HTTP load generator, ApacheBench (`ab`) replacement.
- [oha](https://github.com/hatoo/oha) - HTTP load generator, inspired by `hey` with `tui` animation.
- [pewpew](https://github.com/bengadbois/pewpew) - A flexible HTTP CLI stress testing tool for websites and web services, written in Go.
- [plow](https://github.com/six-ddc/plow) - A high-performance HTTP benchmarking tool written in Go, with real-time web UI and terminal displaying.
- [reqstress](https://github.com/utkusen/reqstress) - A benchmarking & stressing tool that can send raw HTTP requests, written in Go.
- [rewrk](https://github.com/ChillFish8/rewrk) - A modern HTTP framework benchmarking tool written in Rust, supporting HTTP/1 and HTTP/2 benchmarks.
- [terjang](https://github.com/andylibrian/terjang) - Scalable HTTP load testing tool built on `vegeta`.
- [vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library written in Go.

</details>

<details>
  <summary><strong>Misc</strong></summary>

- [certinfo](https://github.com/pete911/certinfo) - Print X.509 certificate info.
- [changie](https://github.com/miniscruff/changie) - Automated changelog tool for preparing releases with lots of customization options.
- [dijo](https://github.com/NerdyPepper/dijo) - Scriptable, curses-based, digital habit tracker.
- [dsq](https://github.com/multiprocessio/dsq) - CLI tool for running SQL queries against JSON, CSV, Excel, Parquet, and more.
- [gotop](https://github.com/xxxserxxx/gotop) - A terminal based graphical activity monitor inspired by `gtop` and `vtop`, written in Go.
- [jc](https://github.com/kellyjonbrazil/jc) - CLI converter from the output of popular command-line tools and file-types to JSON, YAML, or Dictionaries.
- [mani](https://github.com/alajmo/mani) - CLI tool to help you manage repositories.
- [octosql](https://github.com/cube2222/octosql) - A query tool to join, analyse and transform data from multiple databases and file formats using SQL.

</details>

<details>
  <summary><strong>Network</strong></summary>

- [cdntest](https://github.com/Redundancy/cdntest) - A CLI tool for gathering info in order to debug CDN connection issues without requiring end users to install and use complicated tools.
- [dnsping](https://github.com/fortio/dnsping) - DNS ping utility to check packet loss and latency issues with DNS servers.
- [dnsproxy](https://github.com/AdguardTeam/dnsproxy) - A simple DNS proxy server with support all existing DNS protocols including DNS-over-TLS, DNS-over-HTTPS, DNS-over-QUIC and DNSCrypt.
- [dnstrace](https://github.com/rs/dnstrace) - A DNS resolution tracing tool, performs a DNS resolution by tracing the delegation path from the root name servers, and by following the CNAME chain.
- [dnsx](https://github.com/projectdiscovery/dnsx) - A fast and multi-purpose DNS toolkit allow to run multiple DNS queries using `retryabledns` library.
- [dt](https://github.com/42wim/dt) - DNS tool to display information about your domain.
- [httpie-go](https://github.com/nojima/httpie-go) - `httpie`-like HTTP client written in Go.
- [httpx](https://github.com/projectdiscovery/httpx) - A fast and multi-purpose HTTP toolkit allows to run multiple probers using `retryablehttp` library.
- [mturoute](https://elifulkerson.com/projects/mturoute.php) - Eli Fulkerson's CLI tool analogous to `ping` and `traceroute`, which finds the maximum MTU between you and another host by passing ICMP requests with differing payload size.
- [pingu](https://github.com/sheepla/pingu) - Ping command implementation but with Pingu ASCII art, written in Go.
- [proxify](https://github.com/projectdiscovery/proxify) - Swiss Army knife proxy tool for HTTP/HTTPS traffic capture, manipulation and replay written in Go.
- [tcping-go](https://github.com/cloverstd/tcping) - Ping over a TCP connection, like `tcping`, written in Go.

</details>

<details>
  <summary><strong>Testing</strong></summary>

- [hetty](https://github.com/dstotijn/hetty) - An HTTP toolkit for security research.
- [httplab](https://github.com/qustavo/httplab) - An interactive web server written in Go.
- [mqtt-cli](https://github.com/hivemq/mqtt-cli) - MQTT 5.0 and 3.1.1 compatible and feature-rich MQTT CLI tool.
- [muffet](https://github.com/raviqqe/muffet) - Fast website link checker in Go.
- [plumber](https://github.com/batchcorp/plumber) - A swiss army knife CLI tool for interacting with Kafka, RabbitMQ and other messaging systems.
- [trubka](https://github.com/xitonix/trubka) - A CLI tool for Kafka.
- [websocat](https://github.com/vi/websocat) - A CLI client for WebSockets, like `netcat` (or `curl`) for ws:// with advanced `socat`-like functions.
- [wombat](https://github.com/rogchap/wombat) - Cross platform gRPC client.

</details>

<details>
  <summary><strong>Migrated</strong></summary>

- [curlie](https://github.com/rs/curlie) - Migrated, use `main/curlie`.
- [ddosify](https://github.com/ddosify/ddosify) - Migrated, use `main/ddosify`.
- [dnslookup](https://github.com/ameshkov/dnslookup) - Migrated, use `main/dnslookup`.
- [eget](https://github.com/zyedidia/eget) - Migrated, use `extras/eget`.
- [hopp-cli](https://github.com/hoppscotch/hopp-cli) - Migrated, use `main/hopp-cli`.
- [jo](https://github.com/jpmens/jo) - Migrated, use `main/jo`.
- [tcping](https://elifulkerson.com/projects/tcping.php) - Migrated, use `main/tcping`.
- [termscp](https://github.com/veeso/termscp) - Migrated, use `main/termscp`.

</details>
