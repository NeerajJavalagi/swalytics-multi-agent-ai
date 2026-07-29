# swalytics-multi-agent-ai

# Swalytics: Multi-Agent AI Analytics Platform

Swalytics is a multi-agent AI-powered analytics platform that automates data analysis through an **Analyze → Code → Execute** workflow. Users can upload datasets and ask questions in natural language, while the platform generates Python code, executes analytical workflows, validates results, and produces interactive insights and visualizations.

The project was developed to simplify exploratory data analysis by combining Large Language Models (LLMs), intelligent agent orchestration, and backend automation into a seamless analytical experience.

## Features

- Multi-agent AI architecture
- Natural language data analysis
- Analyze → Code → Execute workflow
- Automated Python code generation
- Intelligent query planning
- FastAPI backend services
- Interactive Next.js frontend
- REST API-based communication
- Data preprocessing and analysis
- Automated visualization generation
- Error detection and recovery
- AST-based code validation
- Iterative reasoning for analytical tasks

## Motivation

Traditional data analysis requires programming knowledge and familiarity with multiple libraries and visualization tools.

Swalytics bridges this gap by enabling users to simply upload a dataset and describe what they want to analyze in natural language. The system automatically determines the analytical steps, generates executable Python code, executes the analysis, and returns meaningful insights.

## Workflow

### Step 1 – Analyze

The system understands the user's analytical request and inspects the uploaded dataset.

### Step 2 – Plan

The planning agent determines the required analytical workflow.

### Step 3 – Generate Code

The code generation agent produces Python code for the requested analysis.

### Step 4 – Validate

The generated code is validated before execution to reduce execution failures.

### Step 5 – Execute

Validated code is executed and results are collected.

### Step 6 – Recover

If execution fails, the system identifies errors, revises the generated code, and retries the analysis.

### Step 7 – Present Results

The final output includes:

- Statistical summaries
- Visualizations
- Insights
- Generated Python code
