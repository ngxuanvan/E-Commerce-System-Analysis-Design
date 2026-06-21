# E-Commerce System Analysis & Design

## Project Overview

This project presents a Business Analyst case study for an **E-Commerce System Analysis & Design** project. The goal is to analyze manual sales operations, identify business problems, define requirements, and design system workflows for core e-commerce functionalities such as product browsing, shopping cart, checkout, order management, and admin operations.

This repository is created as a BA portfolio project to demonstrate practical analysis deliverables, including business requirements, user stories, use case specifications, workflow diagrams, ERD, UAT test cases, and change request documentation.

## Project Objectives

- Analyze the current manual sales process and identify key business issues.
- Define business scope, stakeholders, assumptions, and constraints.
- Document business and functional requirements.
- Convert requirements into user stories and acceptance criteria.
- Design system workflows using use case, activity, and sequence diagrams.
- Define data structure using an Entity Relationship Diagram.
- Prepare UAT test cases for core business scenarios.
- Document a sample change request to simulate requirement changes.

## Business Context

Many small and medium businesses still manage sales activities manually through phone calls, spreadsheets, chat messages, or paper-based records. This approach may create several problems:

- Orders are difficult to track across different channels.
- Product information may be inconsistent or outdated.
- Sales staff spend extra time confirming order details manually.
- Customers cannot easily monitor order status.
- Business owners have limited visibility into sales and operational performance.
- Manual processes increase the risk of missing, duplicated, or incorrect orders.

The proposed e-commerce system helps standardize product management, checkout, order processing, and customer management through a centralized platform.

## Scope

### In Scope

- Customer registration and login
- Product catalog browsing
- Product search and filtering
- Shopping cart management
- Checkout process
- Order creation
- Order status management
- Admin product management
- Customer management
- Basic sales and order reporting

### Out of Scope

- Online payment gateway integration
- Loyalty program
- Mobile application
- AI recommendation engine
- Advanced warehouse management
- Third-party logistics integration

## Stakeholders

| Stakeholder | Description |
|---|---|
| Customer | Browses products, adds items to cart, places orders, and tracks order status |
| Sales Staff | Supports customers and confirms order information when needed |
| Admin | Manages products, categories, customers, and orders |
| Warehouse Staff | Prepares products and updates fulfillment status |
| Business Owner | Monitors sales performance and operational efficiency |
| Development Team | Builds and tests the system based on documented requirements |

## BA Deliverables

| Deliverable | File |
|---|---|
| Project Overview | [`docs/01-project-overview.md`](docs/01-project-overview.md) |
| Business Requirements | [`docs/02-business-requirements.md`](docs/02-business-requirements.md) |
| User Stories & Acceptance Criteria | [`docs/03-user-stories.md`](docs/03-user-stories.md) |
| Use Case Specifications | [`docs/04-use-case-specifications.md`](docs/04-use-case-specifications.md) |
| UAT Test Cases | [`docs/05-uat-test-cases.md`](docs/05-uat-test-cases.md) |
| Change Request | [`docs/06-change-request.md`](docs/06-change-request.md) |
| Diagram Index | [`diagrams/README.md`](diagrams/README.md) |

## Core Modules

1. Authentication
2. Product Catalog
3. Shopping Cart
4. Checkout
5. Order Management
6. Admin Product Management
7. Customer Management
8. Reporting

## Sample Workflow

```text
Customer browses product catalog
→ Customer adds product to cart
→ Customer proceeds to checkout
→ System validates product availability
→ Customer submits shipping information
→ System creates order
→ Admin confirms order
→ Warehouse prepares shipment
→ Order status is updated
→ Customer receives order status update
```

## Tools Used

- GitHub for documentation and version control
- Markdown for BA documentation
- Draw.io / diagrams.net for diagrams
- Excel or Google Sheets for requirement list and UAT test cases
- Kanboard or Jira-style board for backlog and workflow tracking

## How This Project Can Be Presented in CV

**Business Analyst Portfolio Project – E-Commerce System Analysis & Design**

- Analyzed manual sales operations and documented AS-IS/TO-BE business workflows.
- Created business requirements, user stories, acceptance criteria, and UAT test cases.
- Designed use case, activity, sequence diagrams, and ERD for order management and checkout modules.
- Defined functional requirements for product catalog, cart, checkout, order status, and admin management.
- Prepared change request documentation to simulate requirement changes during the project lifecycle.

## Repository Status

This repository is a portfolio case study and will be updated with diagrams, screenshots, and additional BA artifacts.
