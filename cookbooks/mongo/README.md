# MongoDB Cookbook

## What is Chef?

Chef is a configuration management tool which allows for the automation of creating virtual machines (be it locally or on the cloud), by provisioning files for installation.

## Prerequisites

- Chef
- Vagrant (if running machines locally)
- AWS (if running machines on the cloud)

## How to use
1) Clone this repository
2) Run the unit tests
```bash
$ chef exec rspec
```
3.1) Run the integration tests locally
```bash
$ kitchen test
```
3.2) Run the integration tests on the cloud
```bash
$ KITCHEN_YAML=kitchen_cloud.yml kitchen test
```
