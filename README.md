## PCF Event Alerts

This repo contains the documentation for PCF Event Alerts.

**Note**: Please use PRs to contribute new content or make fixes to this PCF Event Alerts documentation.

The contents of this repo are currently published at [docs-pcf-staging.cfapps.io/event-alerts/](https://docs-pcf-staging.cfapps.io/event-alerts/).

The book file that publishes this content is at [https://github.com/pivotal-cf/docs-book-event-alerts](https://github.com/pivotal-cf/docs-book-event-alerts).

## About product name

The name of this product is **PCF Event Alerts**. The plugin is the **PCF Event Alerts plugin**, which users can install from Pivnet.

When you are referring generically to an alert as a concept (rather than referring to the actual product), use the term "alerts" consistently.

## About branches 

Make changes or PRs to the correct branch:

| Branch name | Use for… |
|-------------| ------|
| master      | v1.3.x pre-release|
| 1.2         | v1.2.x GA release |
| 1.1         | v1.1.x (this was a closed beta)|

**Note**: Provide instructions in your PRs to indicate which branches you want Docs to apply your commits to. 


Other branches will be created for future versions.
For example, when work began on v1.2.x, we did the following:

1. Create a v1.1 branch from master.
2. Update the config.yml in the master branch of https://github.com/pivotal-cf/docs-book-event-alerts
to publish the v1.1 branch. 
3. Develop content for v1.2.x on the master branch.
4. Create an edge branch in https://github.com/pivotal-cf/docs-book-event-alerts to publish staging.

The above info about branches is true as of July 18, 2018.

## First draft info 

Some questions tech writers had for PMs during the first documentation phase are summarized in [this google doc](https://docs.google.com/document/d/1aNMSYMR6rs1_gunXoBlC3qq_Uq97mMXWBiJUydGCDHw/edit?usp=sharing).

## Developing docs locally

This will make the book available at localhost:4567 and automatically update when you write changes to disk:

```
cd docs-book-event-alerts
bundle install
bundle exec bookbinder watch

```
