# IMDb & Wikimedia Data Engineering Project

This project explores fundamental Data Engineering concepts through two approaches: large-scale data analysis (Batch) and real-time stream processing (Streaming).

## Table of Contents
1. Project Overview
2. Prerequisites and Installation
3. Part 1: Batch Analysis (IMDb)
4. Part 2: Streaming (Wikimedia)
5. File Structure

---

## Project Overview

The objective is to demonstrate the ability to manipulate complex relational datasets and implement reactive data pipelines.

* **Technologies used:** Python 3.10+, Polars (for in-memory performance), Requests/SSEClient (for streaming), Matplotlib/Seaborn (visualization).
* **Technical Choice:** The project uses **Polars** instead of PySpark to optimize local performance and avoid heavy Java/Hadoop dependencies on the Windows environment.

## Prerequisites and Installation

```bash
# Install dependencies
pip install polars sseclient-py requests matplotlib seaborn