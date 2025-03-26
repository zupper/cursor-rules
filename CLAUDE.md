# CLAUDE.md - Guidelines for Agents Working in This Repository

## Repository Organization
- TypeScript Clean rules in `/typescript-clean/` - conventions for TS with clean architecture
- Rust rules in `/rust/` - conventions for Rust projects

## Development Guidelines

### TypeScript Rules
- **Naming**: Files match primary class/interface name (Product.ts for Product class)
- **Clean Architecture**: Strict layer separation (application, infrastructure, API/view)
- **Services**: Prefer domain-specific services over "util" classes
- **APIs**: Design dual-protocol support (HTTP and WebSocket)
- **Testing**: Follow TDD (test-driven development) practices

### Rust Rules
- **Naming**: Use idiomatic snake_case for variables/functions, CamelCase for types
- **Error Handling**: Use Result<T, E> for operations that can fail, create domain-specific error types
- **Memory Safety**: Prefer ownership over borrowing when reasonable
- **Testing**: Test behavior not implementation, write small focused tests
- **Documentation**: Document public APIs with examples

## Development Workflow
- Make small, incremental changes with TDD approach
- Run tests after every code change
- Document feature implementations and technical decisions