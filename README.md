# ECHO // SHIFT

> A cyberpunk stealth-puzzle game concept built around recording, replaying, and cooperating with your own past actions.

**ECHO // SHIFT** is an original game design project developed as part of a four-week game design and prototyping study. The project explores how a record-and-replay mechanic can be integrated with stealth gameplay, environmental puzzles, level design, and narrative progression.

The central mechanic allows the player to record a sequence of actions and replay those actions through an **Echo** — a temporal copy of the player's previous movement. The active player can then act alongside the Echo, allowing two sequences of actions to occur simultaneously.

## Interactive Prototype

The repository contains the final refined browser prototype developed during Week 4.

The prototype demonstrates the core gameplay loop:

**Plan → Record → Replay → Synchronize → Solve**

The player must record a movement sequence, replay it as an Echo, use the Echo to interact with the environment, and coordinate the active character with the recorded timeline to complete the room.

The final prototype includes:

- Player movement and environmental interaction
- Action recording
- Echo replay
- Pressure-switch and door interaction
- Numbered recorded-route visualization
- Echo replay timeline
- Persistent objective display
- Gameplay-state indicators
- Contextual hints and feedback
- Recording reset controls
- Full room restart
- Success and failure feedback

## Project Development

### Week 1 — Game Concept

The first stage established the overall identity of **ECHO // SHIFT**, including its cyberpunk setting, narrative premise, characters, target audience, gameplay pillars, progression system, and competitive positioning.

The central design question was:

> What if solving a stealth encounter required cooperating with your own previous actions?

This became the foundation of the Echo system.

### Week 2 — Gameplay Mechanics & Prototype

Week 2 transformed the concept into a functional gameplay system.

The initial interactive prototype introduced the core sequence:

1. Navigate the environment.
2. Begin recording.
3. Create a sequence of actions.
4. Stop recording.
5. Replay the sequence as an Echo.
6. Move independently while the Echo repeats the recorded actions.
7. Coordinate both timelines to solve the room.

This stage demonstrated that the core mechanic could work as an interactive puzzle rather than existing only as a theoretical design.

### Week 3 — Level Design

Week 3 expanded the mechanic into a complete level called **The Quiet Archive**.

The level was designed as a secure corporate data archive containing:

- Enemy patrol routes
- Surveillance cameras
- Security zones
- Interactive terminals
- Pressure switches
- Synchronization puzzles
- Optional reward areas
- Alternative routes
- Environmental storytelling
- Extraction objectives

The level was designed around gradually increasing the complexity of Echo-based interactions while maintaining readable player navigation.

### Week 4 — Evaluation & Iteration

The final stage evaluated the prototype through structured self-testing and simulated usability feedback.

Several usability issues were identified, particularly around communicating temporal information to the player.

The prototype was consequently refined with:

- A visible recorded route
- Numbered action indicators
- A replay timeline
- Clearer objective communication
- Improved gameplay-state feedback
- Better error messages
- Contextual hints
- Faster recovery from mistakes
- Separate recording and room-reset controls

These changes focused on making the consequences of the player's recorded actions easier to understand without removing the challenge of planning the solution.

## Core Design Philosophy

ECHO // SHIFT is based around **visible causality**.

The player should be able to understand:

- what they recorded,
- what their Echo will do,
- when an action will occur,
- how the environment responds,
- and why a strategy succeeded or failed.

The challenge should come from planning and synchronization rather than from unclear system behavior.

## Controls

The interactive prototype displays the current controls and objectives directly within the interface.

Follow the on-screen instructions to record a route, deploy the Echo, manipulate the pressure switch, and reach the exit.
