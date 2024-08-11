# Configure GitHub Actions Bot

[![GitHub release](https://img.shields.io/github/release/drengskapur/gitbot-config.svg)](https://github.com/drengskapur/gitbot-config/releases)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Quick Start

```yaml
- name: Configure Git Actions Bot
  uses: drengskapur/gitbot-config@00aecab0a790b146951f9e0c48f564eaf26a9df6 # v1.1.2
```

Use this action for pushing changes within a GitHub Actions workflow.

```yaml
- name: Configure Git Actions Bot
  uses: drengskapur/gitbot-config@00aecab0a790b146951f9e0c48f564eaf26a9df6 # v1.1.2

  # Now you can commit changes

- run: |
    git add .
    git commit -m "Automated changes"
    git push
```
