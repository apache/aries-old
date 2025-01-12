# Apache Aries

The Aries project consists of a set of pluggable Java components enabling an enterprise OSGi application programming
model.

See [Apache Aries Website](http://aries.apache.org/).

- Application - Missing
- [![Async - CI Build](https://github.com/apache/aries/actions/workflows/async.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/async.yml)
- [![Blueprint - CI Build](https://github.com/apache/aries/actions/workflows/blueprint.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/blueprint.yml)
- [![eba-maven-plugin - CI Build](https://github.com/apache/aries/actions/workflows/eba-maven-plugin.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/eba-maven-plugin.yml)
- EJB - Missing
- [![esa-ant-task - CI Build](https://github.com/apache/aries/actions/workflows/esa-ant-task.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/esa-ant-task.yml)
- [![esa-maven-plugin - CI Build](https://github.com/apache/aries/actions/workflows/esa-maven-plugin.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/esa-maven-plugin.yml)
- [![JMX - CI Build](https://github.com/apache/aries/actions/workflows/jmx.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/jmx.yml)
- [![JNDI - CI Build](https://github.com/apache/aries/actions/workflows/jndi.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/jndi.yml)
- [![Proxy - CI Build](https://github.com/apache/aries/actions/workflows/proxy.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/proxy.yml)
- [![Pushstream - CI Build](https://github.com/apache/aries/actions/workflows/pushstream.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/pushstream.yml)
- [![Quiesce - CI Build](https://github.com/apache/aries/actions/workflows/quiesce.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/quiesce.yml)
- Samples - Missing
- [![SPI Fly - CI Build](https://github.com/apache/aries/actions/workflows/spi-fly.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/spi-fly.yml)
- [![Subsystem - CI Build](https://github.com/apache/aries/actions/workflows/subsystem.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/subsystem.yml)
- [![Transaction - CI Build](https://github.com/apache/aries/actions/workflows/transaction.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/transaction.yml)
- [![Versioning - CI Build](https://github.com/apache/aries/actions/workflows/versioning.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/versioning.yml)
- [![Web - CI Build](https://github.com/apache/aries/actions/workflows/web.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/web.yml)
- [![Util - CI Build](https://github.com/apache/aries/actions/workflows/util.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/util.yml)
- [![Testsupport - CI Build](https://github.com/apache/aries/actions/workflows/testsupport.yml/badge.svg)](https://github.com/apache/aries/actions/workflows/testsupport.yml)

## Source Code

The sources are now directly availble in [aries github](https://github.com/apache/aries).

Some of the subprojects have their own git repos:

| Subproject |
| ---------- |
| [Aries CDI](https://github.com/apache/aries-cdi) |
| [Aries Component DSL](https://github.com/apache/aries-component-dsl) |
| [Aries Containers](https://github.com/apache/aries-containers) |
| [Aries JAX-RS whiteboard](https://github.com/apache/aries-jax-rs-whiteboard) |
| [Aries JPA](https://github.com/apache/aries-jpa) |
| [Aries RSA](https://github.com/apache/aries-rsa) |
| [Aries Transaction Control](https://github.com/apache/aries-tx-control) |

## Build

Most projects can be built using

    mvn clean install

As the Aries svn hosts a lot of different subprojects it makes sense to only
build the specific subproject.
