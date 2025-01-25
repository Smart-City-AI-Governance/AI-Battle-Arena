# AI Models

This directory contains pre-trained AI models used in AI Battle Arena to provide dynamic and adaptive gameplay experiences.

## Contents:
- **agent_model_v1.pth** - Initial AI model version.
- **future_model.pth** - Experimental features for advanced decision-making.

## Usage:
To load a model, use the following command:

```python
import torch
model = torch.load('src/ai_agents/models/agent_model_v1.pth')
