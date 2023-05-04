<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Copyright Contributors to the ODPi Egeria project. -->

[![License](https://img.shields.io/github/license/odpi/egeria-connector-xtdb)](LICENSE)
[![Build](https://github.com/odpi/egeria-connector-xtdb/workflows/Build/badge.svg)](https://github.com/odpi/egeria-connector-xtdb/actions/workflows/merge.yml?query=workflow%3ABuild)
[![CodeQL](https://github.com/odpi/egeria-connector-xtdb/workflows/CodeQL/badge.svg)](https://github.com/odpi/egeria-connector-xtdb/actions/workflows/codeql-analysis.yml)
[![Release](https://img.shields.io/maven-central/v/org.odpi.egeria/egeria-connector-xtdb?label=release)](http://repository.sonatype.org/service/local/artifact/maven/redirect?r=central-proxy&g=org.odpi.egeria&a=egeria-connector-xtdb&v=RELEASE&c=jar-with-dependencies)
[![Development](https://img.shields.io/nexus/s/org.odpi.egeria/egeria-connector-xtdb?label=development&server=https%3A%2F%2Foss.sonatype.org)](https://oss.sonatype.org/content/repositories/snapshots/org/odpi/egeria/egeria-connector-xtdb/)

# XTDB Plugin Repository Connector

This repository houses the code for a plugin repository connector using [XTDB](https://xtdb.com) (formerly known as "Crux") as its back-end. [XTDB](https://xtdb.com) provides an unbundled database that supports temporal graph queries, and is itself built on a pluggable architecture supporting a variety of underlying storage back-ends.

Of particular interest for Egeria is that it has native support for storing historical information and temporal queries -- making it one of the first repositories to support the use of the `asOfTime` parameter across all metadata.

## [Documentation](https://egeria-project.org/connectors/repository/xtdb/)

[https://egeria-project.org/connectors/repository/xtdb/](https://egeria-project.org/connectors/repository/xtdb/)

----
License: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/),
Copyright Contributors to the ODPi Egeria project.
