# DevOps Batch 14
## Server Monitoring, Logging & CI Pipeline

## Project Overview

This project implements a basic DevOps monitoring,
logging and CI environment using:

- Ubuntu
- Prometheus
- Node Exporter
- Grafana
- Loki
- Grafana Alloy
- GitHub Actions
- GitHub Self-Hosted Runner

## Architecture

Internet
   |
   v
Ubuntu Server
   |
   +-- Node Exporter :9100
   |
   +-- Prometheus :9090
   |
   +-- Loki :3100
   |
   +-- Grafana :3000
   |
   +-- GitHub Self-Hosted Runner

## 1. Node Exporter

Installation steps...

## 2. Prometheus

Installation steps...

## 3. Grafana

Installation steps...

## 4. Loki

Installation steps...

## 5. GitHub Actions

Installation steps...

## 6. Self Hosted Runner

Runner name:

ostad-runner

## 7. Dashboard

The dashboard contains:

- CPU Usage
- Memory Usage
- Disk Usage
- Network Usage

## 8. Logging

Loki is configured as the Grafana logging datasource.

## 9. CI Pipeline

The pipeline performs:

1. Build
2. Test
3. Artifact generation
4. Artifact upload

## 10. Screenshots
