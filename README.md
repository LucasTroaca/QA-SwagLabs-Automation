# SwagLabs Test Automation
![Tests](https://github.com/LucasTroaca/QA-SwagLabs-Automation/actions/workflows/tests.yml/badge.svg)

End-to-end UI test automation using Playwright and Pytest with Page Object Model, reusable flows, and CI via GitHub Actions.

## About
This project demonstrates UI test automation using:

- Page Object Model (POM)
- Pytest Fixtures
- Reusable Flows
- Structured test architecture

## How it Works
- Pytest fixtures handle setup and reuse browser state across tests
- Page Object Model (POM) separates UI interactions from test logic
- Flows layer abstracts user actions into reusable business processes
- Configuration is centralized to simplify environment management

## Tech Stack
- Python
- Pytest
- Playwright

## Installation
Clone the repository:
```bash
git clone https://github.com/LucasTroaca/QA-SwagLabs-Automation
```

Install Dependencies:
```bash
pip install -r requirements.txt
```

Install Playwright Browsers:
```bash
playwright install
```

## Running Tests
Run all tests:
```bash
pytest -v
```

Run a specific test:
```bash
pytest tests/test_login.py
```

## Features
- Login Validation
- Add and Remove Products
- Product Filtering
- Checkout Process
- End-to-End Flow

## CI
Tests are executed automatically using GitHub Actions on push or pull requests

## Screenshots
Screenshots are saved in:
screenshots/

## Author
Lucas Gabriel Troaca




