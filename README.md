# demo-devops-actions-0

A simple Go demo application for DevOps workflows.

This repository shows how to build and publish a simple docker image using GitHub Actions.
It also includes a Dependabot configuration to keep dependencies up to date.

## Prerequisites

- Go 1.24+

## Run locally

```bash
go run hello-devops.go
```

## Build binary

```bash
go build -o hello-devops hello-devops.go
```

## Docker build

```bash
docker build -t hello-devops .
```
