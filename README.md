# Welcome to Connect 4!
🔥 GET READY TO DROP IT LIKE IT’S HOT—STRATEGICALLY, OF COURSE! 🔥
This isn’t just a game of colorful discs…

It’s a high-voltage battlefield where every second counts and every drop can shatter your opponent’s dreams!

Stack like a boss. Block like a legend. Outsmart, outmaneuver, and CRUSH the grid as you race to forge FOUR IN A ROW—horizontally, vertically, or diagonally—before they even see it coming!

Ridiculously easy to learn.

Brutally addictive to master.

Guaranteed to ignite epic trash-talk and heart-pounding friendly rivalries that’ll have you both yelling at the board!

So grab your discs, lock onto that grid, and UNLEASH YOUR MOVE.
Four connects = TOTAL VICTORY. LET THE SHOWDOWN EXPLODE!  🔴🟡


## Game Strategy
🔥 Connect Four Strategies: Dominate Fast 🔥
Core: 1st player wins perfect play.
- Win with: Center control + Forks.
- Center King: Drop Column 4 first. Then fight 3 & 5. (One disc = 13 lines!)
- Block or Die: Opp has 3-in-row (open both ends)? Block NOW.
- Fork = Win: One move creates 2 threats. Opp blocks 1 → you win. Build in rows 3-4.
- Every Move: Win now / Block / Create threat. Master diagonals.
- Checklist: Win? Block? Fork? Center stronger?
- Avoid: Edge starts, ignoring diagonals.
Drop center. Force forks. Crush them. 🚀

## Technical Summary
Core: Full Minimax + α-β pruning on fast 64-bit bitboards.

Fidelity: Exact gravity rules, win/draw detection, smooth animations, menus + 3 modes (HvH, HvAI, AIvAI).

### Key Upgrades:
- Depth-adjusted scoring: (42−depth)×100 → hunts early wins, delays losses.
- Dynamic column ordering (center-first) → massive pruning, 8–10 plies in <50 ms.
- Window-based heuristic (aspiration search) counting 3-in-rows, forks & center control.

Result: Instantly blocks threats, sets up strategic forks, plays near-perfect on Hard.

## Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-feature`.
3. Make changes and add tests where appropriate.
4. Open a pull request describing your changes.

Please include descriptive commit messages and keep changes focused.

## Tests

If you add unit tests, include instructions to run them here (for example, using pytest):

```bash
pip install pytest
pytest
```

## License

MIT License.

## Contact

If you have questions or suggestions, open an issue or submit a pull request. Mention @santakd for visibility.
