---
title: "Debezium"
link: "https://debezium.io/"
github: "debezium/debezium"
description: "An open source distributed platform for change data capture that streams row-level changes out of MySQL's binary log — and MariaDB, Vitess, and TiDB — into Kafka and other event streams."
subcategories:
  - Connectors & Drivers
compatibility:
  - MySQL
  - MariaDB
  - Vitess
  - TiDB
deployment:
  - Self-Hosted
  - Docker
pricing:
  - Open Source
images:
  - logo.png
---

Debezium's MySQL connector takes an initial consistent snapshot of the tables it's watching and then keeps reading the binary log, turning every insert, update, and delete into a structured change event on a Kafka topic. It ships as a set of Kafka Connect connectors — with dedicated connectors for MariaDB and an incubating one for Vitess and TiDB — and is commonly used to feed search indexes, caches, data warehouses, and microservices without querying the source database directly.

It's released under the Apache 2.0 license (the bundled Antlr grammars are MIT-licensed) and is a CNCF-adjacent project backed by Red Hat.
