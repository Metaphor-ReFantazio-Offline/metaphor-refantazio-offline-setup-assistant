# Contributing to Metaphor: ReFantazio Offline Setup Assistant

First off, thank you for considering contributing to our project! 🎮 The gaming community thrives on collaboration, and your contributions help make this tool better for all Metaphor: ReFantazio players.

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Development Process](#development-process)
- [Style Guidelines](#style-guidelines)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Community](#community)

## 📜 Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [community@metaphor-offline.com](mailto:community@metaphor-offline.com).

## 🤝 How Can I Contribute?

### 🐛 Reporting Bugs

Before creating bug reports, please check [existing issues](https://github.com/Metaphor-ReFantazio-Offline/metaphor-refantazio-offline-setup-assistant/issues) to avoid duplicates.

**Great bug reports include:**
- Clear, descriptive title
- Exact steps to reproduce
- Expected vs actual behavior
- Screenshots/GIFs if applicable
- System information (OS, game version, etc.)
- Configuration files (if relevant)

**Use our bug report template when creating issues.**

### 💡 Suggesting Features

We love new ideas! Before suggesting features:

1. Check if it already exists in [issues](https://github.com/Metaphor-ReFantazio-Offline/metaphor-refantazio-offline-setup-assistant/issues)
2. Consider if it fits the project's scope
3. Think about how it benefits the gaming community

**Great feature requests include:**
- Clear problem statement
- Proposed solution
- Alternative solutions considered
- Additional context/mockups

### 🔧 Code Contributions

#### Areas where you can help:
- **UI/UX Improvements**: Make the interface more intuitive
- **Performance Optimization**: Faster loading, better resource usage
- **New Features**: Configuration options, offline modes
- **Bug Fixes**: Resolve reported issues
- **Documentation**: Improve guides and help text
- **Testing**: Platform compatibility, edge cases
- **Localization**: Multi-language support

## 🚀 Getting Started

### Prerequisites

- **Development Environment**: [List specific requirements]
- **Game Access**: Metaphor: ReFantazio for testing
- **Tools**: Git, appropriate IDE/editor

### Setting Up Development Environment

1. **Fork the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/metaphor-refantazio-offline-setup-assistant.git
   cd metaphor-refantazio-offline-setup-assistant
   ```

2. **Install dependencies**
   ```bash
   # Add specific installation commands
   npm install  # or pip install -r requirements.txt
   ```

3. **Set up configuration**
   ```bash
   # Copy example config
   cp config.example.json config.json
   # Edit with your settings
   ```

4. **Run tests**
   ```bash
   # Add test commands
   npm test  # or python -m pytest
   ```

5. **Start development server**
   ```bash
   # Add dev server command
   npm run dev  # or python app.py
   ```

## 🔄 Development Process

### Branch Strategy

- `main`: Stable, production-ready code
- `develop`: Integration branch for features
- `feature/feature-name`: New features
- `bugfix/issue-description`: Bug fixes
- `hotfix/critical-fix`: Emergency fixes

### Workflow

1. **Create Issue**: Discuss changes before starting
2. **Create Branch**: From `develop` for features, `main` for hotfixes
3. **Develop**: Make your changes with tests
4. **Test**: Ensure all tests pass
5. **Document**: Update relevant documentation
6. **Submit PR**: Against appropriate base branch

## 📝 Style Guidelines

### Code Style

#### General Principles
- **Readability**: Code should be self-documenting
- **Consistency**: Follow existing patterns
- **Performance**: Consider gaming performance requirements
- **Cross-platform**: Ensure compatibility across OS

#### Naming Conventions
```python
# Variables and functions: snake_case
game_config = load_configuration()
def setup_display_mode():
    pass

# Classes: PascalCase
class GameConfigManager:
    pass

# Constants: UPPER_SNAKE_CASE
DEFAULT_RESOLUTION = "1920x1080"
```

#### Comments
- Explain **why**, not what
- Use docstrings for functions/classes
- Add TODOs for future improvements

```python
def optimize_graphics_settings(hardware_info):
    """
    Automatically configure graphics settings based on hardware.
    
    Args:
        hardware_info (dict): System hardware information
        
    Returns:
        dict: Optimized graphics configuration
        
    Note:
        This function prioritizes stability over maximum quality
        to ensure smooth gameplay on various hardware configurations.
    """
    # Use conservative settings for older GPUs
    if hardware_info['gpu_year'] < 2020:
        return conservative_settings()
```

### Documentation Style

- Use clear, concise language
- Include examples where helpful
- Consider different skill levels
- Test all instructions

## 📋 Commit Guidelines

### Commit Message Format

```
<type>(<scope>): <subject>

<body>

<footer>
```

#### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding/updating tests
- `chore`: Maintenance tasks

#### Examples
```
feat(ui): add dark mode theme option

- Added toggle switch in settings panel
- Implemented dark theme CSS variables
- Updated all UI components to support themes
- Added user preference persistence

Closes #123
```

```
fix(config): resolve controller detection on Linux

- Fixed udev rule parsing for game controllers
- Added fallback detection method
- Improved error messaging for unsupported devices

Fixes #456
```

## 🔍 Pull Request Process

### Before Submitting

- [ ] Code follows project style guidelines
- [ ] Tests added/updated for changes
- [ ] Documentation updated if needed
- [ ] All existing tests pass
- [ ] Changes tested on multiple platforms (if applicable)
- [ ] Issue referenced in PR description

### PR Template

When creating a pull request, use our template:

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Refactoring

## Testing
- [ ] Tested on Windows
- [ ] Tested on macOS
- [ ] Tested on Linux
- [ ] Added unit tests
- [ ] Manual testing completed

## Screenshots/GIFs
(If UI changes)

## Checklist
- [ ] Code follows style guidelines
- [ ] Self-review completed
- [ ] Documentation updated
- [ ] Tests pass
```

### Review Process

1. **Automated Checks**: CI/CD must pass
2. **Code Review**: At least one maintainer approval
3. **Testing**: Manual testing if significant changes
4. **Merge**: Squash and merge for features

## 🌟 Recognition

Contributors are valued members of our community! We recognize contributions through:

- **Contributors List**: README acknowledgment
- **Release Notes**: Feature attribution
- **Community Highlights**: Social media recognition
- **Special Roles**: Discord contributor roles

## 💬 Community

### Getting Help

- **Discord**: [Join our server](https://discord.gg/metaphor-refantazio) for real-time chat
- **Discussions**: [GitHub Discussions](https://github.com/Metaphor-ReFantazio-Offline/metaphor-refantazio-offline-setup-assistant/discussions) for longer conversations
- **Issues**: [GitHub Issues](https://github.com/Metaphor-ReFantazio-Offline/metaphor-refantazio-offline-setup-assistant/issues) for bugs and features

### Community Guidelines

- **Be Respectful**: Treat everyone with kindness
- **Be Patient**: Remember that everyone has different experience levels
- **Be Constructive**: Provide helpful feedback
- **Stay On Topic**: Keep discussions relevant
- **Have Fun**: We're all here because we love gaming!

## 📈 Project Roadmap

Check our [roadmap](https://github.com/Metaphor-ReFantazio-Offline/metaphor-refantazio-offline-setup-assistant/projects) to see what we're working on and where you can help!

---

Thank you for contributing to the Metaphor: ReFantazio community! Together, we're making gaming more accessible and enjoyable for everyone. 🎮✨ 