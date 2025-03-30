# Physics Adventure Game

## Overview
Physics Adventure is an educational text-based game that teaches real physics concepts through gameplay. Players explore a research center, perform experiments, and study scientific texts to learn about physics principles from basic mechanics to quantum theory.

## Game Objective
Your goal is to make a scientific breakthrough by learning at least 5 physics concepts and completing 3 experiments.

## Installation and Running the Game

### Requirements
- Python 3.6 or higher

### How to Run
1. Save the game code as `physics_adventure.py`
2. Open a terminal/command prompt
3. Navigate to the directory containing the file
4. Run: `python physics_adventure.py`

## Gameplay

### Navigating the World
- Move between rooms using direction commands: `north`, `south`, `east`, `west`
- Each room has a description and may contain items or experiments

### Items and Inventory
- Collect items with `take [item]` (e.g., `take laser`)
- Drop items with `drop [item]`
- View your inventory with `inventory` or `i`
- Use items in your inventory for experiments or to gain knowledge

### Learning Physics
- Study books and journals with `study [item]` or `read [item]`
- Perform experiments with `perform [experiment]`
- Review learned concepts with `concepts`

### Game Mechanics
- Actions consume energy (moving: 5, studying: 10, experimenting: 15)
- Rest to recover energy with `rest` (gives +15 energy)
- Coffee provides a quick energy boost (+20)
- If your energy drops to 0, you'll become exhausted and end the game

### Commands
| Command | Action |
|---------|--------|
| `north`, `south`, `east`, `west` | Move in that direction |
| `look` | Look around the current location |
| `take [item]` | Pick up an item |
| `drop [item]` | Drop an item from your inventory |
| `study [item]` or `read [item]` | Study an item to gain knowledge |
| `perform [experiment]` | Perform an available experiment |
| `inventory` or `i` | Check what you're carrying |
| `concepts` | Review physics concepts you've learned |
| `rest` | Recover energy |
| `help` or `?` | Show game instructions |
| `quit` | End the game |

## Physics Concepts You Can Learn
1. **Basic Physics**: Newton's laws of motion, conservation of energy
2. **Relativity**: Einstein's special and general relativity theories
3. **Current Research**: Quantum computing, dark matter, unified field theory
4. **Pendulum Motion**: Simple harmonic motion, mathematical relationships
5. **Electricity**: Ohm's Law, circuits, conductors, and insulators
6. **Light Properties**: Wave behavior, spectrum, refraction
7. **Quantum Physics**: Wave-particle duality, quantization, double-slit experiment
8. **Quantum Mechanics**: Wavefunctions, measurement, uncertainty principle
9. **Electromagnetism**: Unified electric and magnetic forces, Maxwell's equations

## Experiments
1. **Pendulum Experiment**: Discover relationships between pendulum length and period
2. **Circuit Test**: Verify Ohm's Law using a battery and circuits
3. **Light Refraction**: Use a prism to separate light into its spectrum
4. **Double-Slit Experiment**: Observe wave-particle duality in action
5. **Quantum Measurement**: Demonstrate Heisenberg's uncertainty principle
6. **Magnetic Field Test**: Visualize magnetic fields and electromagnetic connections

## Locations
- **Office**: Your starting point with basic research materials
- **Physics Lab**: General experiments like pendulums and circuits
- **Library**: Books and journals to study
- **Cafeteria**: Where you can find coffee to boost your energy
- **Quantum Room**: Advanced quantum physics experiments
- **Optics Lab**: Experiments with light and waves

## Game Endings
- **Victory**: Successfully learn 5 concepts and complete 3 experiments
- **Exhaustion**: Run out of energy before achieving your goal
- **Quit**: Manually exit the game

## Tips for Success
- Always check which items are needed for experiments before attempting them
- Use the "concepts" command to review what you've learned
- Remember to rest when your energy gets low
- Coffee in the cafeteria provides a good energy boost
- The game shows available actions after each turn - use this to plan your next move
- Some items like the physics textbook and Einstein book provide fundamental knowledge

## Educational Value
This game introduces real physics concepts in an engaging way, from classical physics to modern quantum theory. The experiments are based on real scientific procedures that demonstrated important physics principles throughout history.

Enjoy your scientific journey!
