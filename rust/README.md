# Cursor Rules

This directory contains Cursor rules that define code conventions and architectural guidelines for projects using Rust. The rules are organized into logical categories based on their purpose.

## Directory Structure

- **architecture/** - Rules defining architectural boundaries and dependency management
- **workflow/** - Rules for development processes like testing and documentation
- **patterns/** - Rules for coding patterns and idiomatic Rust practices
- **project/** - Rules for project configuration and structure
- **meta/** - Rules about rules (formatting, organization, location)

## Rule Summaries

### Architecture Rules

- **dependency_inversion** - Enforces proper dependency inversion and trait-based abstractions

### Workflow Rules

- **auto_commit** - Guidelines for automated commit practices
- **containerized_development** - Standards for containerized development environments
- **containerized_testing** - Standards for containerized testing environments
- **small_incremental_steps** - Enforces development in small, testable increments
- **specs_structure** - Defines the structure of specification documents
- **tdd_small_steps** - Enforces test-driven development with small steps

### Pattern Rules

- **api_design** - Guidelines for designing consistent and idiomatic Rust APIs
- **concurrency** - Best practices for safe concurrent code
- **documentation** - Standards for code documentation and comments
- **error_handling** - Enforces consistent error handling patterns
- **functional_approach** - Guidelines for functional programming approaches in Rust
- **idiomatic_rust** - Enforces idiomatic Rust code patterns
- **memory_safety** - Enforces memory safety best practices
- **performance** - Guidelines for performance-conscious code
- **simplicity** - Enforces code simplicity and readability principles
- **testing_best_practices** - Best practices for effective tests

### Project Rules

- **code_test_structure** - Enforces separation of test code from application code

### Meta Rules

- **mdc_rules_location** - Standards for placing and organizing rule files
- **mdc_rules_structure** - Defines the proper structure and format for Cursor rules

## Usage

When placed under `.cursor/rules` and when using the Cursor IDE, these rules are automatically enforced by Cursor.

For more detailed information about a specific rule, refer to the rule file itself, which contains comprehensive examples and explanations.