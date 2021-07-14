# :owl: Poldi

Personal bucket for lovely [Scoop](https://scoop.sh/).

## Usage

```powershell
scoop bucket add poldi https://github.com/aliesbelik/poldi
# Recommended, but you can omit the bucket name most of the time
scoop install poldi/<app>
```

## Manifests

> Only apps NOT available in `scoop bucket known` buckets.

### Dev tools

- [websocat](https://github.com/vi/websocat) - A CLI client for WebSockets, like `netcat` (or `curl`) for ws:// with advanced `socat`-like functions.

### Load-testing tools

- [ali](https://github.com/nakabonne/ali) - A HTTP load testing tool capable of performing real-time analysis, inspired by `vegeta` and `jplot`.
- [bombardier](https://github.com/codesenberg/bombardier) - Fast cross-platform HTTP benchmarking tool written in Go.
- [cassowary](https://github.com/rogerwelin/cassowary) - Modern cross-platform HTTP load-testing tool written in Go, inspired by `k6`, `ab` & `httpstat`.
- [hey](https://github.com/rakyll/hey) - HTTP load generator, ApacheBench (`ab`) replacement.
- [oha](https://github.com/hatoo/oha) - HTTP load generator, inspired by `hey` with `tui` animation.
- [plow](https://github.com/six-ddc/plow) - A high-performance HTTP benchmarking tool written in Go, with real-time web UI and terminal displaying.
- [vegeta](https://github.com/tsenart/vegeta) - HTTP load testing tool and library written in Go.

### Network tools

- [cdntest](https://github.com/Redundancy/cdntest) - A CLI tool for gathering info in order to debug CDN connection issues without requiring end users to install and use complicated tools.
- [curlie](https://github.com/rs/curlie) - A frontend to `curl` that adds the ease of use of `httpie`, without compromising on features and performance.
- [dnslookup](https://github.com/ameshkov/dnslookup) - Simple CLI utility to make DNS lookups.
- [dnsping](https://github.com/fortio/dnsping) - DNS ping utility to check packet loss and latency issues with DNS servers.
- [dnsproxy](https://github.com/AdguardTeam/dnsproxy) - A simple DNS proxy server with support all existing DNS protocols including DNS-over-TLS, DNS-over-HTTPS, DNS-over-QUIC and DNSCrypt.
- [dnstrace](https://github.com/rs/dnstrace) - A DNS resolution tracing tool, performs a DNS resolution by tracing the delegation path from the root name servers, and by following the CNAME chain.
- [mturoute](http://www.elifulkerson.com/projects/mturoute.php) - Eli Fulkerson's CLI tool analogous to `ping` and `traceroute`, which finds the maximum MTU between you and another host by passing ICMP requests with differing payload size.
- [tcping](https://elifulkerson.com/projects/tcping.php) - Eli Fulkerson's TCP ping tool, simulates `ping` over TCP by establishing a connection to network hosts.
