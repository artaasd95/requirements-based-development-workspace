# Requirements-Based Development Workspace

A comprehensive example project demonstrating requirements-driven development methodology. This workspace provides a complete template structure for translating high-level requirements and user stories into robust, maintainable system architecture and working code.

## Overview

This project serves as a reference implementation for requirements-based development, following a systematic approach from requirements analysis to deployment. It includes all necessary folders, documentation templates, and placeholder files to guide development teams through the entire software development lifecycle.

## Project Structure

```
/
├── docs/                           # System documentation
│   ├── system_overview.md          # High-level architecture description
│   ├── architecture.drawio         # Component diagrams and data flow
│   ├── api_spec.md                 # REST/GraphQL API contracts
│   ├── data_model.drawio           # ER diagrams and data schemas
│   ├── tech_decisions.md           # Technology stack rationale
│   └── deployment_guide.md         # CI/CD and deployment instructions
├── requirements/                   # All project requirements
│   ├── functional_requirements/    # Feature specifications and workflows
│   ├── non_functional_requirements/ # Performance, security, scalability
│   └── user_stories/               # User stories and acceptance criteria
├── src/                            # Main application source code
├── tests/                          # Test suites
│   ├── unit/                       # Unit tests (target: ≥80% coverage)
│   └── integration/                # Integration and workflow tests
├── agent-prompt.txt                # AI agent instructions for development
├── LICENSE                         # Project license
└── README.md                       # This file
```

## Development Process

This workspace follows a structured 5-phase development approach:

### 1. Requirements Analysis
- Review functional requirements for features and workflows
- Analyze non-functional requirements (performance, security, scalability)
- Study user stories for edge cases and acceptance criteria

### 2. Design & Documentation
- Create system overview and architecture documentation
- Design component diagrams and data flow
- Define API contracts and data models
- Document technology decisions and rationale

### 3. Implementation
- Scaffold project structure following best practices
- Implement core services and modules
- Follow coding standards and SOLID principles
- Maintain clear separation of concerns

### 4. Testing
- Write comprehensive unit tests (≥80% coverage)
- Implement integration tests for service interactions
- Create end-to-end tests for complete workflows
- Generate coverage reports

### 5. Documentation & Deployment
- Maintain up-to-date README and API documentation
- Create deployment guides and CI/CD pipelines
- Document environment setup and configuration

## Getting Started

### Prerequisites

Before starting development, define:
- **Programming language(s)** and framework(s)
- **Data storage** solution (SQL, NoSQL, file-based)
- **Deployment environment** (cloud provider, containerization)
- **Architectural style** (layered, hexagonal, microservices, event-driven)

### Initial Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/artaasd95/requirements-based-development-workspace
   cd requirements-based-development-workspace
   ```

2. **Review requirements**
   - Start with `requirements/functional_requirements/`
   - Analyze `requirements/non_functional_requirements/`
   - Study `requirements/user_stories/`

3. **Plan architecture**
   - Update `docs/system_overview.md`
   - Create diagrams in `docs/architecture.drawio`
   - Define APIs in `docs/api_spec.md`

4. **Begin implementation**
   - Set up development environment
   - Implement core modules in `src/`
   - Write tests in `tests/`

## Usage with AI Agents

This workspace includes `agent-prompt.txt` with detailed instructions for AI-powered development. The prompt guides AI agents through:

- Requirements analysis and clarification
- Architecture design and documentation
- Code implementation following best practices
- Comprehensive testing strategies
- Documentation and deployment preparation

### Using with Trae IDE (trae.ai)

For optimal results when using this workspace with Trae IDE:

1. **Load the agent prompt**: Use the file `/agent-prompt.txt` as your main agent prompt in Trae IDE
2. **Set as system prompt**: Copy the contents of `agent-prompt.txt` and set it as your system prompt for the AI agent
3. **Follow the structured process**: The agent will guide you through the 5-phase development approach automatically
4. **Leverage AI assistance**: The prompt is specifically designed to work with AI agents for requirements-driven development

The agent prompt contains comprehensive instructions that enable AI assistants to:
- Analyze requirements systematically
- Make informed technology decisions
- Generate proper documentation
- Implement clean, maintainable code
- Create comprehensive test suites

## Best Practices

- **Requirements First**: Always start with clear, documented requirements
- **Architecture Documentation**: Maintain up-to-date system documentation
- **Test-Driven Development**: Write tests alongside implementation
- **Code Quality**: Follow linting, formatting, and naming conventions
- **Continuous Integration**: Implement automated testing and deployment
- **Security**: Follow security best practices throughout development

## Contributing

When contributing to this workspace:

1. Update requirements documentation first
2. Modify architecture documents as needed
3. Implement changes following established patterns
4. Add comprehensive tests
5. Update relevant documentation

## License

This project is licensed under the terms specified in the LICENSE file.

---

**Note**: This is a template workspace. Replace placeholder content with actual project requirements, specifications, and implementation details as development progresses.