---
title: "Percona XtraBackup"
link: "https://www.percona.com/software/mysql-database/percona-xtrabackup"
github: "percona/percona-xtrabackup"
description: "An open-source hot backup utility for MySQL and Percona Server that takes physical backups of InnoDB, XtraDB, and MyISAM tables without locking the database."
subcategories:
  - Backup & Recovery
compatibility:
  - MySQL
  - Percona Server
deployment:
  - Self-Hosted
pricing:
  - Open Source
images:
  - logo.png
---

Percona XtraBackup takes physical, non-blocking backups of InnoDB, XtraDB, and MyISAM tables — copying data files directly instead of querying through SQL — so a full backup doesn't stall writes on the server being backed up. It supports full and incremental backups, streaming backups over the network, and point-in-time recovery when combined with the binary log.

It's released under the GPLv2 license and developed by Percona alongside Percona Server for MySQL and Percona XtraDB Cluster. The current 8.0 series supports MySQL 8.0 and Percona Server for MySQL 8.0; the older 2.4 branch covers MySQL/Percona Server 5.7.
