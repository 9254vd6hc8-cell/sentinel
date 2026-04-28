# Sentinel

Sentinel is a demo test automation framework built with Playwright and TypeScript. The project is designed as a modern, scalable, and maintainable solution focused on quality engineering best practices.

## Overview

This framework demonstrates how to build a robust automation architecture with:
- Decoupled design to reduce dependency on specific tools or implementations.
- Playwright abstraction layers to allow future framework evolution if needed.
- Page Object Model (POM) for maintainable UI automation.
- API + UI testing support in a single solution.
- Environment-based configuration for multiple stages (dev, qa, staging, prod).
- Reusable test data management using JSON-driven structures.
- Database integration ready for validations and setup tasks.
- CI/CD friendly execution with reporting and parallel runs.
- Agent-ready structure prepared for AI-assisted automation workflows.

## Architecture Goals

Eyewitness was created to simulate a real-world enterprise framework where maintainability, readability, scalability, and execution speed are priorities.

The structure is prepared to support:
- Human contributors
- AI coding agents
- Rapid feature growth
- Multi-environment testing
- Low-maintenance test suites

## Tech Stack

- TypeScript
- Node.js
- JSON configuration
- CI/CD pipelines
- Optional DB / API integrations

## Project Purpose

This is a *demo project* intended to showcase engineering practices for modern QA automation teams and future-ready testing platforms.

## Future Vision

- Self-healing locators
- AI-generated test coverage
- Autonomous debugging agents
- Smart flaky test detection
- Quality analytics dashboards

## Test Environment

This project uses https://www.saucedemo.com/ for UI test scenarios such as login, product flows, cart validation, and checkout journeys.

For API-related test cases, it uses https://www.saucedemo.com/ as the target environment for endpoint validation, contract checks, and service-level automation.
