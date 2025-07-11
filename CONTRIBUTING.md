# Contributing to TinyQ

Thank you for your interest in contributing to TinyQ! This document outlines the process for contributing to this project.

## Getting Started

1. Fork the repository
2. Clone your fork:
```bash
git clone https://github.com/afondiel/TinyQ.git
cd TinyQ
```
3. Install dependencies:
```bash
# Create and activate conda environment
conda create -n qenv python=3.8
conda activate qenv

# Install dependencies
pip install -r requirements.txt
```

## Development Process

1. Create a new branch:
```bash
git checkout -b feature/your-feature-name
```

2. Make your changes
3. Test your changes:
```bash
# Run the example script
python examples.py --model_path "Salesforce/codegen-350M-mono" --qm w8a32
```

4. Commit your changes:
```bash
git add .
git commit -m "Add: brief description of your changes"
```

## Pull Request Process

1. Update documentation if needed
2. Push to your fork and submit a pull request
3. Wait for review and address any feedback

## Coding Standards

- Follow PEP 8 style guide
- Add docstrings for new functions/classes
- Include type hints where appropriate
- Keep functions focused and single-purpose

## Adding New Features

- Focus on one feature per PR
- Add tests for new functionality
- Update README.md if needed
- Maintain backward compatibility

## Bug Reports

Please include:
- Python version
- PyTorch version
- Model being quantized
- Steps to reproduce
- Expected vs actual behavior

## Feature Requests

- Check roadmap first
- Describe use case clearly
- Explain benefits
- Consider implementation complexity

## License

By contributing, you agree that your contributions will be licensed under the MIT License.