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

### Network tools

- [cdntest](https://github.com/Redundancy/cdntest) - A CLI tool for gathering info in order to debug CDN connection issues without requiring end users to install and use complicated tools.
- [curlie](https://github.com/rs/curlie) - A frontend to `curl` that adds the ease of use of `httpie`, without compromising on features and performance.
- [dnstrace](https://github.com/rs/dnstrace) - A DNS resolution tracing tool, performs a DNS resolution by tracing the delegation path from the root name servers, and by following the CNAME chain.
- [tcping](https://elifulkerson.com/projects/tcping.php) - Eli Fulkerson's TCP ping tool, simulates `ping` over TCP by establishing a connection to network hosts.

### Load generators

- [hey](https://github.com/rakyll/hey) - HTTP load generator, ApacheBench (`ab`) replacement.
- [oha](https://github.com/hatoo/oha) - HTTP load generator, inspired by `hey` with `tui` animation.
