---
title: "gh-ost"
link: "https://github.com/github/gh-ost"
github: "github/gh-ost"
description: "A triggerless online schema migration tool for MySQL, built by GitHub, that produces a lightweight replication-based workload instead of relying on triggers."
subcategories:
  - Schema Management & Migration
compatibility:
  - MySQL
deployment:
  - Self-Hosted
pricing:
  - Open Source
images:
  - logo.png
---

gh-ost runs schema migrations by tailing the binary log rather than installing triggers on the table being altered, so the extra load it places on the primary stays light and decoupled from the table's existing write traffic. Migrations can be tested in dry-run mode, throttled or paused mid-flight, and controlled interactively over a Unix socket or plain text file — without ever touching the table's structure until the final atomic cutover.

It was built and open-sourced by GitHub, is released under the MIT license, and is used in production to run large-scale schema changes with minimal impact on live traffic.
