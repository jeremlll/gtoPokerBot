# GTO3 Poker Bot
### Submission for PokerHack 2025 by HackMelbourne

This bot was inspired by Game Theory Optimal (GTO) play and it is designed to play in careful consideration of pot size, hand strength and position.

Designed for use with [PyPokerEngine](https://github.com/ishikota/PyPokerEngine).

## Strategy Overview

- **Preflop Evaluation**: Considers hand strength (pairs, suited connectors, high cards).
- **Postflop Strategy**: Evaluates hand potential and board texture.
- **Position Awareness**: Plays tighter in early position, looser in late position.
- **Round-Based Aggression**: Becomes more aggressive as rounds progress.
- **Probabilistic Bluffing**: Occasionally bluffs to stay unpredictable.
- **Pot Odds & Stack Size**: Adjusts behavior based on pot odds and current stack.
