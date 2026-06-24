# Original Creation Prompt

**Model:** Qwen3.6-27B-Q6_K
**Date:** June 24, 2026

```
Create a single-file modern Tetris web game.

Save it exactly here:
`/mnt/data/Hermes/projects/tetris/qwen3.6-27b_q6_k/index.html`

Constraints:
- One self-contained HTML file only.
- No npm, no build step, no external libraries, no CDN, no separate assets.
- Embed all HTML, CSS, JavaScript, and Web Audio sound code in that one file.
- Create the directory if it does not exist.
- Verify the file exists after writing it.

Game requirements:
- 10x20 board.
- All 7 tetrominoes: I, O, T, S, Z, J, L.
- Move left/right, soft drop, hard drop.
- Rotate clockwise and counter-clockwise.
- Collision detection for walls, floor, and locked blocks.
- Lock pieces after landing.
- Clear completed lines.
- Spawn next piece.
- Game over when a piece cannot spawn.
- Pause/resume.
- Restart.
- Ghost piece.
- Next piece preview.
- Hold piece.

Controls:
- Left/Right arrows: move.
- Down arrow: soft drop.
- Up arrow or X: rotate clockwise.
- Z: rotate counter-clockwise.
- Space: hard drop.
- C or Shift: hold.
- P: pause/resume.
- R: restart.
- Prevent game keys from scrolling the page.

Scoring:
- 1 line = 100 × level
- 2 lines = 300 × level
- 3 lines = 500 × level
- 4 lines = 800 × level
- Level increases every 10 cleared lines.
- Fall speed increases with level.
- Save high score in localStorage.

Design:
- Dark futuristic theme.
- Glassmorphism panels.
- Neon accents.
- Smooth animations.
- Responsive layout.
- Polished grid.
- Glowing rounded tetromino blocks.
- Different visuals for locked blocks, active piece, and ghost piece.
- Start screen.
- Pause overlay.
- Game-over overlay.
- HUD with score, high score, level, lines, next piece, hold piece, controls, and sound toggle.

Polish:
- Line-clear animation.
- Hard-drop feedback.
- Subtle board shake or glow on line clear.
- Button hover effects.
- Optional sound effects via Web Audio API.
- Mute/unmute toggle.
- Handle browser resizing.

Code organization inside the single file:
- Config/constants
- Tetromino definitions
- Board state
- Piece logic
- Rotation
- Collision detection
- Scoring/levels
- Rendering
- Input handling
- UI state
- Audio

After writing the file, report:
- Path written
- Verification result
- Brief feature summary
- Any known limitations
```
