# ThatDataGuySA-data-engineering-challenge-playbook
A real-world Data Engineering Challenge with datasets, starter kit, and a complete Top 3 solution breakdown series.

## Data Engineering Challenge – Top 3 Solution Journey

## Overview

This repository contains the challenge pack from a large-scale Data Engineering Challenge where I placed **3rd out of more than 500 entrants**.

The purpose of sharing this repository is not to provide a completed solution, but to give aspiring Data Engineers an opportunity to work through the same challenge and compare their thinking against a real competition scenario.

If you are looking to strengthen your skills in:

* Data Engineering
* Data Modelling
* Data Quality
* Data Architecture
* ETL / ELT Design
* Pipeline Optimisation
* Dockerised Data Workloads
* Batch and Streaming Processing

then this challenge is an excellent exercise.

---

## Living Repository

This repository is a living resource and will continue to evolve as the walkthrough series is released.

Over the coming weeks I will be progressively add:

* Requirement analysis
* Architecture diagrams
* Design decisions
* Data modelling discussions
* Pipeline implementation walkthroughs
* Performance optimisation techniques
* Lessons learned during the challenge

The goal is not only to show the final solution, but to document the thinking process behind each decision.

As new insights emerge or better approaches are identified, the repository may be updated to reflect the most accurate and maintainable solution.

This means some implementations shown in earlier videos may later be refined or improved as part of the learning journey.

## Alternative Implementations

The challenge constraints and tooling used during the competition may not match the environments available to all learners or maybe beyond the scope of your current capacity.

While the original solution was built within the competition constraints, the same design principles can be applied using modern data platforms such as:

* Azure Databricks
* Microsoft Fabric
* Apache Spark
* Azure Data Factory
* Delta Lake
* Lakehouse Architectures

If your goal is learning rather than strict competition compliance, focus on building a correct, scalable and maintainable design first. The platform is secondary to the engineering principles.

## Roadmap

- [x] Challenge Pack Released
- [x] Repository Published
- [ ] Episode 1 – Requirement Analysis
- [ ] Episode 2 – Architecture Design
- [ ] Episode 3 – Data Modelling
- [ ] Episode 4 – Batch Pipeline
- [ ] Episode 5 – Data Quality Framework
- [ ] Episode 6 – Performance Optimisation
- [ ] Episode 7 – Scaling Considerations
- [ ] Episode 8 – Final Solution Release

## Challenge Structure

The challenge is split into three stages.

### Stage 1 – Batch Processing

Build a data pipeline capable of:

* Ingesting customer, account and transaction data
* Transforming raw data into analytical outputs
* Applying data quality validation
* Producing required output datasets
* Passing automated validation checks

### Stage 2 – Scale and Data Quality

The challenge complexity increases by introducing:

* Larger data volumes
* Additional data quality issues
* Schema evolution requirements
* Performance constraints

### Stage 3 – Streaming Extension

Extend the solution to support:

* Streaming ingestion
* Incremental processing
* Near real-time handling of incoming data

---

## Repository Contents

```text
docs/
├── challenge_brief.md
├── data_dictionary.md
├── output_schema_spec.md
├── validation_queries.sql
├── challenge_rules.md
├── resource_constraints.md
└── ...

starter_kit/
├── pipeline/
├── config/
├── adr/
├── stream/
├── README.md
├── requirements.txt
└── Dockerfile

data/
├── customers.csv
├── accounts.csv
└── transactions.jsonl
```

---

## Recommended Approach

Before writing any code:

### 1. Read the Challenge Brief

Understand:

* Business requirements
* Technical requirements
* Success criteria
* Constraints

### 2. Study the Data

Review:

* Data Dictionary
* Output Specifications
* Validation Rules

### 3. Design First

Create:

* Architecture Diagram
* Data Flow Diagram
* Entity Relationships
* Data Quality Strategy

### 4. Build Incrementally

Recommended order:

1. Ingestion
2. Validation
3. Transformation
4. Aggregation
5. Output Generation
6. Optimisation

---

## My Solution Walkthrough Series

Over the coming weeks I will be publishing a complete breakdown of how I approached this challenge.

Topics include:

### Episode 1

Understanding Requirements Before Writing Code

### Episode 2

Designing The Architecture

### Episode 3

Building The Pipeline

### Episode 4

Data Quality Framework Design

### Episode 5

Performance Optimisation

### Episode 6

Scaling For Larger Volumes

### Episode 7

Lessons Learned From A Top 3 Submission

---

## Challenge Yourself First

I strongly recommend attempting the challenge before watching the solution walkthroughs.

Treat it like a real client project.

Document your assumptions.

Design your architecture.

Build your pipeline.

Then compare your thinking against the walkthrough series.

---

## Evaluation Rubric

If I were reviewing your submission, I would look at:

| Area          | Focus                                    |
| ------------- | ---------------------------------------- |
| Correctness   | Does the output satisfy requirements?    |
| Data Quality  | Are issues detected and handled?         |
| Architecture  | Is the design scalable and maintainable? |
| Performance   | Can it handle increased volume?          |
| Code Quality  | Is the solution modular and testable?    |
| Documentation | Can another engineer understand it?      |

---

## Acknowledgements

This challenge was originally created and hosted by Nedbank as part of the N*ovation Data and Analytics Masters Challenge Data Engineering competition.

The challenge materials, datasets, and specifications belong to their respective owners.

This repository is intended for educational purposes only and serves as a companion resource to my public walkthrough series documenting my approach, architecture decisions, and lessons learned while participating in the challenge.

I am not affiliated with or endorsed by Nedbank.

## Follow The Journey

If you found this repository useful:

* Follow me on TikTok (@ThatDataGuySA)
* Subscribe on YouTube (@ThatDataGuySA)
* Connect on LinkedIn (linkedin.com/tinashe-chinyati)

I will be sharing the complete thought process, architecture decisions, optimisation techniques and lessons learned from achieving a Top 3 finish.

Good luck and happy building.

