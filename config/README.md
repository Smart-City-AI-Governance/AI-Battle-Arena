# Configuration Files

The `config/` directory contains configuration files required for AI Battle Arena's operations.

## Files:

- **settings.json** - General project settings.
- **ai_config.yaml** - AI model parameters and training configurations.
- **blockchain_config.json** - Settings for smart contract interactions.

## Usage:

Ensure that all configurations are properly set before running the project. To modify configurations, edit the respective files:

Example to change AI settings in `ai_config.yaml`:

```yaml
model:
  learning_rate: 0.001
  batch_size: 64
  epochs: 50
