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

### Module 1: [Introduction to Data Engineering](./modules/module1/README.md)
- Overview of data engineering
- Setting up the development environment
- Introduction to Docker

### Module 2: [Data Ingestion](./modules/module2/README.md)
- Batch processing
- Stream processing
- ETL vs ELT

### Module 3: [Data Warehousing](./modules/module3/README.md)
- Introduction to data warehouses
- Setting up a data warehouse (e.g., BigQuery, Snowflake)
- Data modeling for analytics

### Module 4: [Analytics Engineering](./modules/module4/README.md)
- Transforming data in the warehouse
- Creating data models with dbt
- Testing and documenting data pipelines

### Module 5: [Batch Processing](./modules/module5/README.md)
- Introduction to Apache Spark
- Distributed computing concepts
- Batch jobs with Spark

### Module 6: [Streaming](./modules/module6/README.md)
- Streaming concepts
- Introduction to Apache Kafka
- Building real-time data pipelines

### Module 7: [Project](./modules/module7/README.md)
- Capstone project combining all learned concepts
- End-to-end data engineering solution

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
├── modules/
│   ├── module1/
│   ├── module2/
│   ├── module3/
│   ├── module4/
│   ├── module5/
│   ├── module6/
│   └── module7/
│
├── data/
├── notebooks/
├── scripts/
├── tests/
├── .gitignore
├── requirements.txt
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
