# Data Engineering Zoomcamp 2025

Welcome to the Data Engineering Zoomcamp for the 2025 cohort! This comprehensive course is designed to give you hands-on experience with modern data engineering tools and techniques.

## Table of Contents

1. [Introduction](#introduction)
2. [Course Modules](#course-modules)
3. [Prerequisites](#prerequisites)
4. [Setup](#setup)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)
7. [License](#license)

## Introduction

This data engineering project is part of the 2025 cohort program. It covers various aspects of data engineering, from data ingestion to processing and analysis, using industry-standard tools and best practices.

## Course Modules

### Module 1: [Docker and Terraform](./01-docker-terraform/README.md)
- Introduction to containerization with Docker
- Infrastructure as Code (IaC) with Terraform
- Setting up development environments

### Module 2: [Workflow Orchestration](./02-workflow-orchestration/README.md)
- Introduction to workflow orchestration
- Using tools like Apache Airflow or Prefect
- Designing and implementing data pipelines

### Module 3: [Data Ingestion & Data Warehouse](./03-Data%20Ingestion%20%26%20data-warehouse/README.md)
- Batch and stream processing techniques
- ETL vs ELT approaches
- Setting up and using data warehouses (e.g., BigQuery, Snowflake)
- Data modeling for analytics

### Module 4: [Analytics Engineering](./04-analytics-engineering/README.md)
- Transforming data in the warehouse
- Creating data models with dbt
- Testing and documenting data pipelines

### Module 5: [Batch Processing](./05-batch/README.md)
- Introduction to Apache Spark
- Distributed computing concepts
- Implementing batch jobs with Spark

### Module 6: [Streaming](./06-streaming/README.md)
- Streaming concepts and architectures
- Introduction to streaming technologies (e.g., Apache Kafka, Apache Flink)
- Building and managing real-time data pipelines

## Prerequisites

- Basic understanding of Python programming
- Familiarity with SQL
- Basic knowledge of cloud computing concepts

Certainly! I'll update the README to use Poetry for setting up the project instead of venv. Here's the updated Setup section for your root README:

**File: /Users/amiteshbhattacharya/PycharmProjects/data-engineering-zoomcamp-2025/README.md**

```markdown
[... previous content ...]

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/data-engineering-zoomcamp-2025.git
   ```

2. Navigate to the project directory:
   ```bash
   cd data-engineering-zoomcamp-2025
   ```

3. Install Poetry (if not already installed):
   ```bash
   curl -sSL https://install.python-poetry.org | python3 -
   ```

4. Install project dependencies using Poetry:
   ```bash
   poetry install
   ```

5. Activate the Poetry virtual environment:
   ```bash
   poetry shell
   ```


## Using Poetry

- To add new dependencies:
  ```bash
  poetry add package_name
  ```

- To update dependencies:
  ```bash
  poetry update
  ```

- To run a Python script within the Poetry environment:
  ```bash
  poetry run python your_script.py
  ```

## Project Structure

```
data-engineering-zoomcamp-2025/
│
├── 01-docker-terraform/
├── 02-workflow-orchestration/
├── 03-Data Ingestion & data-warehouse/
├── 04-analytics-engineering/
├── 05-batch/
├── 06-streaming/
│
├── data/
├── notebooks/
├── scripts/
├── tests/
├── .gitignore
├── pyproject.toml
├── poetry.lock
└── README.md
```

## Contributing

We welcome contributions to improve the course material. Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/AmazingFeature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
5. Push to the branch (`git push origin feature/AmazingFeature`)
6. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

For more information, please contact the course instructors or visit our [official website](https://dataengineeringzoomcamp.com).
```

This README provides a comprehensive overview of your Data Engineering Zoomcamp project. It includes:

1. An introduction to the project
2. A table of contents for easy navigation
3. Detailed sections for each module with placeholder links
4. Prerequisites for the course
5. Setup instructions
6. Project structure
7. Contributing guidelines
8. License information
