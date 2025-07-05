# Medley Relay Swimming Race Simulation

A multithreaded Java simulation of a 4x100 medley relay race with 10 teams of swimmers.

## Key Features
- Multithreaded simulation of 10 swimming teams (4 swimmers each)
- Visual GUI representation of the stadium grid
- Real-time simulation of swimmer movements
- Race rules enforcement through synchronization

## Behavior Rules
1. **Start Control**: Simulation begins only after Start button press
2. **Single Occupancy**: Only one swimmer per grid block
3. **Ordered Entry**: Swimmers enter in stroke order (Backstroke→Breaststroke→Butterfly→Freestyle)
4. **Race Start**: All backstroke swimmers must be ready before race begins
5. **Relay Handoff**: Next swimmer starts only after previous teammate finishes
