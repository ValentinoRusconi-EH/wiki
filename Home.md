## Basics

* [Getting Started](Getting-Started)
* [Components](Components)
* [Configuration](Configuration)
* [Setting up Kafka](Setting-up-Kafka)
* [Producing messages](Producing-messages)
* [Consuming messages](Consuming-messages)
* [Web UI](Web-UI-Getting-Started)
* [Testing](Testing)
* [FAQ](FAQ)

## Web UI

* [About](Web-UI-About)
* [Getting Started](Web-UI-Getting-Started)
* [Configuration](Web-UI-Configuration)
* [Transactions](Web-UI-Transactions)
* [Features](Web-UI-Features)
    * [Consumers](Web-UI-Features#consumers)
    * [Jobs](Web-UI-Features#jobs)
    * [Health](Web-UI-Features#health)
    * [Routing](Web-UI-Features#routing)
    * [Explorer](Web-UI-Features#explorer)
    * [Errors](Web-UI-Features#errors)
    * [DLQ / Dead](Web-UI-Features#dlq-dead)
    * [Cluster](Web-UI-Features#cluster)
    * [Status](Web-UI-Features#status)
* [Tagging](Web-UI-Tagging)
* [Multi App Mode](Web-UI-Multi-App)
* [Single Process Setup](Web-UI-Single-Process-Setup)
* [Development vs Production](Web-UI-Development-vs-Production)
* [Components](Web-UI-Components)

## WaterDrop

* [About](WaterDrop-About)
* [Getting Started](WaterDrop-Getting-Started)
* [Configuration](WaterDrop-Configuration)
* [Usage](WaterDrop-Usage)
* [Transactions](WaterDrop-Transactions)
* [Monitoring and Logging](WaterDrop-Monitoring-and-Logging)
* [Testing](WaterDrop-Testing)
* [Middleware](WaterDrop-Middleware)

## Production usage

* [Development vs Production](Development-vs-Production)
* [Signals and states](Signals-and-states)
* [Deployment](Deployment)
    * [systemd (+ Capistrano)](Deployment#systemd-capistrano)
    * [Docker](Deployment#docker)
    * [AWS + MSK (Fully Managed Apache Kafka)](Deployment#aws-msk-fully-managed-apache-kafka)
    * [Heroku](Deployment#heroku)
* [Monitoring and Logging](Monitoring-and-Logging)
* [Error handling and back off policy](Error-handling-and-back-off-policy)

## Advanced

* [Upgrading](Upgrading)
* [Routing](Routing)
* [Active Job](Active-Job)
* [Dead Letter Queue](Dead-Letter-Queue)
* [Auto reload of code changes in development](Auto-reload-of-code-changes-in-development)
* [Topics management and administration](Topics-management-and-administration)
* [CLI](CLI)
* [Integrating with Ruby on Rails and other frameworks](Integrating-with-Ruby-on-Rails-and-other-frameworks)
* [Concurrency and multithreading](Concurrency-and-multithreading)
* [Deserialization](Deserialization)
* [Offset management (checkpointing)](Offset-management)
* [Pausing, Seeking and Rate-Limiting](Pausing-Seeking-and-Rate-Limiting)
* [Consumer mappers](Consumer-mappers)
* [Inline Insights](Inline-Insights)
* [WaterDrop reconfiguration](WaterDrop-reconfiguration)
* [Exit codes](Exit-codes)
* [Embedding](Embedding)
* [Multi-Cluster Setup](Multi-Cluster-Setup)
* [Env Variables](Env-Variables)
* [Librdkafka Configuration](Librdkafka-Configuration)
* [Librdkafka Statistics](Librdkafka-Statistics)
* [Articles and other references](Articles-and-other-references)
* [Versions Lifecycle and EOL](Versions-Lifecycle-and-EOL)
* [Problems, Troubleshooting and Debugging](Problems,-Troubleshooting-and-Debugging)

## Karafka Pro

* [Build vs. Buy](Build-vs-Buy)
* [Purchase Karafka Pro](Purchase-Karafka-Pro)
* [Getting Started](Pro-Getting-Started)
* [Rotating credentials](Pro-Rotating-Credentials)
* [Pro FAQ](Pro-FAQ)
* [Pro Support](Pro-Support)
* [Security](Pro-Security)
* [Enterprise](Pro-Enterprise)
* [Enterprise Workshop Session](Pro-Enterprise-Workshop-Session)

### Features and enhancements

* [Features list](Pro-Features-List)
* [Features Compatibility](Pro-Features-Compatibility)
* [Virtual Partitions](Pro-Virtual-Partitions)
* [Delayed Topics](Pro-Delayed-Topics)
* [Long-Running Jobs](Pro-Long-Running-Jobs)
* [Expiring Messages](Pro-Expiring-Messages)
* [Routing Patterns](Pro-Routing-Patterns)
* [Rate Limiting](Pro-Rate-Limiting)
* [Filtering API](Pro-Filtering-API)
* [Iterator API](Pro-Iterator-API)
* [Granular Backoffs](Pro-Granular-Backoffs)
* [Cleaner API](Pro-Cleaner-API)
* [Messages At Rest Encryption](Pro-Messages-At-Rest-Encryption)
* [Enhanced Dead Letter Queue](Pro-Enhanced-Dead-Letter-Queue)
* [Enhanced Active Job](Pro-Enhanced-Active-Job)
* [Enhanced Reliability](Pro-Enhanced-Reliability)
* [Enhanced Inline Insights](Pro-Enhanced-Inline-Insights)
* [Enhanced Web UI](Pro-Enhanced-Web-UI)
    * [Getting Started](Pro-Enhanced-Web-UI#getting-started)
    * [Consumers](Pro-Enhanced-Web-UI#consumers)
    * [Health](Pro-Enhanced-Web-UI#health)
    * [Explorer](Pro-Enhanced-Web-UI#explorer)
    * [Sanitization](Pro-Enhanced-Web-UI-Sanitization)
    * [Errors](Pro-Enhanced-Web-UI#errors)
    * [DLQ / Dead](Pro-Enhanced-Web-UI#dlq-dead)

## Upgrade notes

It is recommended to do one major upgrade at a time.

* [Upgrading to 2.2](https://karafka.io/docs/Changelog-Karafka/#220-2023-09-01)
* [Upgrading to 2.1](https://karafka.io/docs/Changelog-Karafka/#210-2023-05-22)
* [Upgrading to 2.0](https://karafka.io/docs/Upgrades-2.0/)
* [Upgrading to 1.4](https://mensfeld.pl/2020/09/karafka-framework-1-4-0-release-notes-ruby-kafka/#changes-features-incompatibilities-etc)
* [Upgrading to 1.3](https://mensfeld.pl/2019/09/karafka-framework-1-3-0-release-notes-ruby-kafka/#changes-features-incompatibilities-etc)
* [Upgrading to 1.2](https://mensfeld.pl/2018/03/karafka-framework-1-2-0-release-notes-ruby-kafka/#upgrade-guide)
* [Upgrading to 1.1](https://mensfeld.pl/2017/11/karafka-ruby-kafka-framework-1-1-0-release-notes/#incompatibilities-and-breaking-changes)

## Changelogs

* [Karafka](https://karafka.io/docs/Changelog-Karafka)
* [WaterDrop](https://karafka.io/docs/Changelog-WaterDrop)
* [Karafka-Web](https://karafka.io/docs/Changelog-Karafka-Web-UI)
* [Karafka-Testing](https://karafka.io/docs/Changelog-Karafka-Testing)
* [Karafka-Core](https://karafka.io/docs/Changelog-Karafka-Core)
* [Karafka-Rdkafka](https://karafka.io/docs/Changelog-Karafka-Rdkafka)

## Code Docs

* [Karafka](https://karafka.io/docs/code/karafka)
* [WaterDrop](https://karafka.io/docs/code/waterdrop)
* [Karafka-Web](https://karafka.io/docs/code/karafka-web)
* [Karafka-Testing](https://karafka.io/docs/code/karafka-testing)
* [Karafka-Core](https://karafka.io/docs/code/karafka-core)
