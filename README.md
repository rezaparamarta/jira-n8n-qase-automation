# Jira → n8n → Qase Automation (QA Test Case Generation)

## Overview
This repository demonstrates a QA automation workflow that generates
test cases in Qase automatically from Jira user stories using n8n and LLMs.

The goal is to focus on test design quality and requirement-driven automation,
not test execution.

## Architecture
Jira → n8n → LLM → Qase

## What this project shows
- QA-driven Acceptance Criteria design
- Automated test case generation
- Understanding of API limitations (Qase)
- Practical use of AI in QA workflow

## Important Notes
- Qase API does NOT support the "Data" column
- Test data is embedded directly in step actions
- Jira is treated as the single source of truth

## How to use
1. Import the n8n workflow JSON
2. Configure Jira and Qase credentials
3. Run the workflow manually for learning or POC

## Status
This repository represents **Path 1: Jira → Qase (test case generation only)**.
Test execution and CI/CD are intentionally out of scope.
