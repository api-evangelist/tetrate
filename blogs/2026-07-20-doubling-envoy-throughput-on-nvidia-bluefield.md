---
title: "Doubling Envoy Throughput on NVIDIA BlueField"
url: "https://tetrate.io/blog/doubling-envoy-throughput-on-nvidia-bluefield-3/"
date: "2026-07-20"
feed_url: "https://tetrate.io/rss.xml"
---
We modified Envoy to offload TLS cryptography to NVIDIA BlueField-3 hardware accelerators. On a single core with AES-256 and a 5 MB payload, throughput went from 6.6 Gbps to 13.6 Gbps — 2x, without touching L7 policy.
