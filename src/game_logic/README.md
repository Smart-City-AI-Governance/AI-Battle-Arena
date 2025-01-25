# Game Logic

This directory contains the core game mechanics and logic that define the AI Battle Arena experience.

## Main Components:
- **game_engine.py** - The core engine that manages the game state and interactions.
- **battle_manager.py** - Handles AI agent interactions and combat logic.
- **scoring_system.py** - Implements the scoring and ranking logic for matches.

## How It Works:
1. The `game_engine.py` initializes the game environment.
2. AI agents interact through the `battle_manager.py` module.
3. The scoring system tracks performance and rankings.

## Running the Game Logic:

```bash
python src/game_logic/game_engine.py --config config/game_config.yaml
