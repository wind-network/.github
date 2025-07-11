# Contributing to Wind Network

Thank you for your interest in contributing to Wind Network! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites

- Rust 1.70+ with cargo
- Git
- Basic knowledge of Solana development (helpful but not required)

### Development Setup

1. Fork the repository
2. Clone your fork:
   ```bash
   git clone https://github.com/YOUR_USERNAME/REPOSITORY_NAME.git
   cd REPOSITORY_NAME
   ```

3. Install dependencies:
    
    ```bash
    cargo build
    ```
    
4. Run tests:
    
    ```bash
    cargo test
    ```
    
## 📋 Development Guidelines

### Code Style

- Follow Rust standard formatting: `cargo fmt`
- Pass all lints: `cargo clippy -- -D warnings`
- Use meaningful variable and function names
- Add documentation for public APIs
- Write comprehensive tests

### Commit Messages

Use conventional commit format:

```
type(scope): description

[optional body]

[optional footer]
```

Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`

Examples:

- `feat(sni): add real-time account monitoring`
- `fix(tide): resolve memory leak in SIMD processor`
- `docs(api): update GraphQL schema documentation`

### Branch Naming

- `feature/description` - New features
- `fix/description` - Bug fixes
- `docs/description` - Documentation changes
- `refactor/description` - Code refactoring

## 🔄 Pull Request Process

1. Create a feature branch from `main`
2. Make your changes following the guidelines above
3. Add or update tests as necessary
4. Update documentation if needed
5. Ensure all CI checks pass
6. Submit a pull request with a clear description

### PR Requirements

- [ ] All tests pass
- [ ] Code is properly formatted
- [ ] No clippy warnings
- [ ] Documentation updated
- [ ] Changelog updated (for significant changes)

## 🧪 Testing

### Running Tests

```bash
# Run all tests
cargo test

# Run specific test
cargo test test_name

# Run with output
cargo test -- --nocapture

# Run integration tests
cargo test --test integration
```

### Test Guidelines

- Write tests for all new functionality
- Use descriptive test names
- Test both success and failure cases
- Mock external dependencies
- Use property-based testing where appropriate

## 📚 Documentation

- Update README.md for user-facing changes
- Add inline documentation for public APIs
- Update examples if APIs change
- Keep changelog up to date

## 🐛 Reporting Bugs

Use the bug report template and include:

- Clear description of the issue
- Steps to reproduce
- Expected vs actual behavior
- Environment information
- Relevant logs or error messages

## 💡 Suggesting Features

Use the feature request template and include:

- Clear description of the feature
- Use cases and motivation
- Proposed implementation approach
- Alternatives considered

## 🤝 Code of Conduct

This project follows the Contributor Covenant Code of Conduct. By participating, you agree to uphold this code.

## 📞 Getting Help

- Open an issue for bugs or feature requests
- Join our discussions for questions
- Email: team@windnetwork.ai

## 🏆 Recognition

Contributors will be recognized in:

- CONTRIBUTORS.md file
- Release notes for significant contributions
- Project documentation

Thank you for contributing to Wind Network! 🌊