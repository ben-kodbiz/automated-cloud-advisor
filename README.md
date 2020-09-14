<h1 align="center">Automated-Cloud-Advisor</h1>

<div style="text-align:center">
    <img align="center" src="https://github.com/disneystreaming/automated-cloud-advisor/raw/master/website/static/img/logo.png" width="200px" height="200px"  alt="Logo">
</div>


<h3 align="center">
  <a href="https://disneystreaming.github.io/automated-cloud-advisor/">> Documentation <</a>
</h3>

<p align="center">
  <a href="https://github.com/disneystreaming/automated-cloud-advisor/actions?query=workflow%3ABuild">
    <img alt="Build" src="https://github.com/disneystreaming/automated-cloud-advisor/workflows/Build/badge.svg">
  </a>
  <a href="https://github.com/disneystreaming/automated-cloud-advisor/actions?query=workflow%3ADocs">
    <img alt="Docs" src="https://github.com/disneystreaming/automated-cloud-advisor/workflows/Docs/badge.svg">
  </a>
  <a href="https://github.com/disneystreaming/automated-cloud-advisor/actions?query=workflow%3APublish">
    <img alt="Docs" src="https://github.com/disneystreaming/automated-cloud-advisor/workflows/Publish/badge.svg">
  </a>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/automated-cloud-advisor">
    <img alt="npm latest version" src="https://img.shields.io/npm/v/automated-cloud-advisor">
  </a>
  <a href="https://www.npmjs.com/package/automated-cloud-advisor">
    <img alt="dependencies Status" src="https://david-dm.org/disneystreaming/automated-cloud-advisor/status.svg">
  </a>
  <a href="https://www.npmjs.com/package/automated-cloud-advisor">
    <img alt="devDependencies Status" src="https://david-dm.org/disneystreaming/automated-cloud-advisor/dev-status.svg">
  </a>
</p>

<p align="center">
  <a href="https://sonarcloud.io/dashboard?id=disneystreaming_automated-cloud-advisor">
    <img alt="Sonar Quality" src="https://sonarcloud.io/api/project_badges/measure?project=disneystreaming_automated-cloud-advisor&metric=alert_status">
  </a>
  <a href="https://sonarcloud.io/dashboard?id=disneystreaming_automated-cloud-advisor">
    <img alt="Sonar Coverage" src="https://sonarcloud.io/api/project_badges/measure?project=disneystreaming_automated-cloud-advisor&metric=coverage">
  </a>
  <a href="http://standardjs.com">
    <img alt="js-standard-style" src="https://img.shields.io/badge/code%20style-standard-brightgreen.svg">
  </a>
</p>

<p align="center">
  <a href="https://github.com/semantic-release/semantic-release">
    <img alt="semantic-release" src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg">
  </a>
  <a href="https://opensource.org/licenses/Apache-2.0">
    <img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg">
  </a>
  <a href="https://cla-assistant.io/disneystreaming/automated-cloud-advisor">
    <img alt="CLA assistant" src="https://cla-assistant.io/readme/badge/disneystreaming/automated-cloud-advisor">
  </a>
    <a href="https://gitter.im/disneystreaming/automated-cloud-advisor">
    <img alt="Join the chat at https://gitter.im/disneystreaming/automated-cloud-advisor" src="https://badges.gitter.im/Join%20Chat.svg">
  </a>
</p>



# Table of Contents

1. [Motivation](#motivation)
2. [Prerequisites](#prerequisites)
3. [Uninstall](#uninstall)
4. [Contribute](#contribute)
5. [Coding Standards](#coding-standards)
6. [Maintenance Plan](#maintenance-plan)

## Motivation

Automated Cloud Advisor is a extensible tool that aims at facilitating cost optimization in AWS, by collecting data for resources that are under utilized.

It is deployed as a set of cloudformation stacks that comprise the data collection and its display in a Kibana dashboard.

<img src="https://disneystreaming.github.io/automated-cloud-advisor/img/kibana/dashboard/01-dashboard.png" alt="Dashboard">

## Installation

Click [here](https://github.com/disneystreaming/automated-cloud-advisor/docs/setup/) to view prerequisites, dependencies, and requirements.

## Uninstall

You can delete the stacks through the AWS CloudFormation console or CLI by referencing the stack name/id.

## Contribute

- Sign the CLA
- Submit pull request to the master branch

## Coding Standards

- Documentation
- Passing Lint
- Passing Unit Tests
- Code coverage is at 100%

## Maintenance Plan

- Submit PR
- Merge PR to Master
- Let [Semantic Release](https://github.com/semantic-release/semantic-release) publish new version

