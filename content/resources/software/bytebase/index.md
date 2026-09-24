---
title: "Bytebase"
link: "https://www.bytebase.com/"
github: "bytebase/bytebase"
description: "An open-source database governance platform that gives teams a single control plane for schema changes, SQL review, and access control across MySQL and other databases."
subcategories:
  - Schema Management & Migration
  - Database Management & GUI
compatibility:
  - MySQL
  - MariaDB
  - TiDB
pricing:
  - Open Source & Open Core
deployment:
  - Self-Hosted
  - Docker
  - Kubernetes
images:
  - logo.png
---

Bytebase sits between engineers and a MySQL fleet as a change-management layer: migrations go through a review-and-approval workflow (GitOps or its built-in UI), a web-based SQL editor gives ad-hoc query access under role-based permissions, and dynamic data masking and audit logging cover compliance needs. It integrates with Terraform, Kubernetes, ArgoCD, and common ORMs, and ships an MCP server for AI-agent access to databases under the same governance controls.

The core is open source under the MIT license and distributed as a Docker image or Helm chart; features under `enterprise/` require a paid subscription for production use, making it an open-core project.
