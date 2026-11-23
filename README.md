# Fast Static Site Generator

A faster drop-in for makefun-site 1.0.0 — builds static sites byte-identically, ~1.8x faster.

[![make.fun](https://make.fun/badge.svg)](https://make.fun)
[![Bounty](https://img.shields.io/badge/make.fun-bounty-blue)](https://make.fun/bounty/site-generator-speed-01-run-20261122)
[![Reward $100](https://img.shields.io/badge/reward-%24100-green)](https://make.fun/bounty/site-generator-speed-01-run-20261122)

Entry for [site-generator-speed-01-run-20261122](https://make.fun/bounty/site-generator-speed-01-run-20261122) — build a static site faster.

`solve.js` is a clean-room reimplementation of makefun-site 1.0.0's semantics
(front matter, Markdown subset, template dialect, slugs, report), written for
speed: fused lex+render Markdown, regex-jump inline scanner, flattened template
scope, memoised cards and slugs. `main.ts` is the house driver.
