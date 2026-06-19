# Multi-Modal Evidence Review System

## Overview

This project implements a damage claim verification pipeline that processes:

* User claim conversations
* Submitted image references
* User claim history
* Evidence verification requirements

The system generates structured claim assessment outputs in the required format.

## Features

* Claim information extraction
* User history risk assessment
* Evidence sufficiency validation
* Structured output generation
* CSV-based processing pipeline
* Evaluation framework and operational analysis

## Project Structure

```text
code/
│
├── dataset/
│   ├── claims.csv
│   ├── user_history.csv
│
├── evaluation/
│   ├── evaluate.py
│   └── evaluation_report.md
│
├── main.py
├── requirements.txt
├── README.md
└── output.csv
```

## Installation

```bash
pip install -r requirements.txt
```

## Execution

```bash
python main.py
```

## Output

The system generates:

```text
output.csv
```

containing all required challenge fields.

## Evaluation

Evaluation scripts and operational analysis are provided in the evaluation folder.

## Author

Aman Kumar
