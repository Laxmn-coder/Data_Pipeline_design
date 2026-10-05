# Data Pipeline Design Assignment

## Overview

This repository contains my Data Pipeline Design assignment.

The assignment focuses on understanding how data moves through a pipeline:

**Source → Ingestion → Processing → Storage → Consumer**

Two real-world data pipeline architectures have been designed.

---

## Pipeline 1 — College Management System

### Architecture

MySQL → Python → Amazon S3 → Python/Pandas → PostgreSQL → Metabase

The pipeline extracts college management data, stores the raw data, transforms it, and makes the processed data available for reporting and analysis.

[View Pipeline 1](Pipeline-1-College-Management.md)

---

## Pipeline 2 — Weather API

### Architecture

Open-Meteo API → Python → Amazon S3 → Python/Pandas → PostgreSQL → Grafana

The pipeline collects weather data periodically, stores the raw API responses, transforms the data, and makes it available for analysis and visualization.

[View Pipeline 2](Pipeline-2-Weather-API.md)

---

## Key Design Principles

- Start with the logical architecture before selecting technologies.
- Keep the architecture simple and understandable.
- Preserve raw data before transformation.
- Separate operational workloads from analytical workloads.
- Use batch processing when real-time processing is not required.
- Select technologies based on the requirements of the use case.


