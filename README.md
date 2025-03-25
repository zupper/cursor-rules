# Cursor Rules

This directory contains Cursor rules that define code conventions and architectural guidelines for projects using TypeScript and a clean architecture/hexagonal style layer separation. The rules are organized into logical categories based on their purpose.

## Directory Structure

- **architecture/** - Rules defining architectural boundaries and layer responsibilities
- **workflow/** - Rules for development processes like testing and documentation
- **patterns/** - Rules for coding patterns and naming conventions
- **project/** - Rules for project configuration and execution
- **meta/** - Rules about rules (formatting, organization, location)

## Rule Summaries

### Architecture Rules

- **api_controller** - Enforces proper controller structure and separation from business logic
- **application_layer** - Ensures application layer is free from technical implementation details
- **composition_root** - Enforces dependency injection for application layer components
- **clean_architecture** - Enforces layer separation and proper dependencies between layers
- **view_layer_responsibility** - Defines view layer responsibilities and prevents business logic in views

### Workflow Rules

- **backend_feature_implementation** - Guides implementation of backend features using TDD and clean architecture
- **feature_documentation** - Standards for writing user-facing feature documentation
- **tdd** - Enforces test-driven development practices for API components
- **technical_documentation** - Standards for writing technical documentation

### Pattern Rules

- **command_query** - Enforces the Command and Query separation pattern
- **domain_event_naming** - Ensures consistent naming of domain events
- **file_naming** - Enforces consistent file naming based on primary implementation
- **implementation_naming** - Requires implementation classes to include technology in name

### Project Rules

- **dual_protocol_api** - Ensures API controllers support both WebSocket and HTTP
- **execution** - Enforces running the project from the top-level directory
- **ports** - Ensures correct ports and hosts for services

### Meta Rules

- **cursor_format** - Defines the proper structure and format for Cursor rules
- **cursor_location** - Standards for placing and organizing rule files
- **rule_classification** - Enforces that rules are properly classified in directories

## Usage

When placed under `.cursor/rules` and when using the Cursor IDE, these rules are automatically enforced by Cursor.

For more detailed information about a specific rule, refer to the rule file itself, which contains comprehensive examples and explanations. 
