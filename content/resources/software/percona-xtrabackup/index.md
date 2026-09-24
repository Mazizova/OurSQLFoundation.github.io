---
title: "Percona XtraBackup"
link: "https://github.com/percona/percona-xtrabackup"
github: "percona/percona-xtrabackup"
description: "An open-source hot backup utility for MySQL-based servers that performs non-blocking, non-locking backups for InnoDB, XtraDB, and MyRocks tables."
subcategories:
  - Backup & Recovery
compatibility:
  - MySQL
  - Percona Server
pricing:
  - Open Source
deployment:
  - Self-Hosted
images:
  - logo.png
---

Percona XtraBackup takes physical, hot backups of MySQL-based servers without locking the database or interrupting production traffic, unlike `mysqldump` or `FLUSH TABLES WITH READ LOCK`-based approaches. It supports full, incremental, and compressed backups, streaming to remote hosts, and point-in-time recovery when combined with binary logs.

It's developed and maintained by Percona, released under the GPLv2 license, and works with MySQL, Percona Server for MySQL, and Percona XtraDB Cluster, across the InnoDB, XtraDB, and MyRocks storage engines.
