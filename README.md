# Grafana Monitoring Stack

This project sets up a complete monitoring stack using Grafana, Prometheus, and other related tools. The goal is to provide real-time monitoring and visualization of system metrics, application performance, and more.

## Overview

This monitoring stack is designed to help you:

- Collect and visualize metrics from various systems and services
- Set up Grafana dashboards for real-time monitoring
- Use Prometheus to scrape and store metrics
- Enable alerting for system anomalies

## Features

- **Prometheus**: Collects and stores time-series data.
- **Grafana**: Provides a powerful dashboard for visualizing metrics from Prometheus.
- **Alerting**: Configured with Prometheus and Grafana to send notifications based on defined thresholds.
- **Scalability**: Easily extendable to include more services or monitoring targets.

## Prerequisites

Before you begin, ensure you have the following installed:

- Docker
- Docker Compose
- Git

## Setup

Follow the steps below to set up the Grafana monitoring stack:

### 1. Clone the Repository

```bash
git clone https://github.com/TriptiGarg04/grafana.git
cd grafana

