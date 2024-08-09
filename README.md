# GitBot Config: Streamline GitHub Actions Bot Setup

[![GitHub release](https://img.shields.io/github/release/drengskapur/gitbot-config.svg)](https://github.com/drengskapur/gitbot-config/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Instantly configure Git user as GitHub Actions bot in your workflow, ensuring proper commit attribution and seamless integration.

## 🚀 Quick Start

Add this to your GitHub Actions workflow:

```yaml
steps:
  - uses: drengskapur/gitbot-config@v1.1.2
```

## ✨ Key Features

- **Instant Setup**. Configure Git user in one simple step
- **Bot Identity**. Utilize GitHub Actions bot as the committer
- **Zero Configuration**. No inputs required, works out of the box
- **Proper Attribution**. Ensures commits are correctly associated with GitHub Actions

## 🛠 What It Does

GitBot Config automatically sets:

- Git user name to `"github-actions[bot]"`
- Git user email to `"41898282+github-actions[bot]@users.noreply.github.com"`

This configuration allows for proper commit attribution in GitHub Actions workflows.

## 🌟 Why Use GitBot Config?

- **Simplify Workflows**: Eliminate boilerplate Git configuration code
- **Consistency**: Ensure uniform Git user setup across all your workflows
- **Proper Attribution**: Correctly associate commits with GitHub Actions
- **Time-Saving**: Implement Git configuration in one simple step

## 📚 Background

GitBot Config was inspired by a [GitHub community discussion](https://github.com/orgs/community/discussions/26560) on the correct method to set up the Git user for GitHub Actions. The community-discovered email address enables proper association of commits with the GitHub Actions bot.

## 📖 Documentation

For more detailed information, please refer to our [full documentation](https://github.com/drengskapur/gitbot-config/wiki).

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for more details.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

If you encounter any problems or have any questions, please [open an issue](https://github.com/drengskapur/gitbot-config/issues/new).
