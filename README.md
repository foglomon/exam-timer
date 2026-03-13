# Minimal Exam Stopwatch

A minimal, dark-themed exam stopwatch designed to help you track time per question and manage your overall exam duration. Aesthetically pleasing and functionally focused.

## Features

- **Per-question timer** — A large display shows the elapsed time for the current question.
- **Total exam timer** — A smaller display tracks total elapsed time for the entire session.
- **Configurable exam limit** — Set an end condition by total minutes or total number of questions (each question budgets 3 minutes).
- **Strict Mode (Distraction Tracking)** — Detects when you switch away from the window and counts distractions, flashing the background red as a warning.
- **Per-question statistics** — Tracks and displays average, highest, and lowest time per question.
- **Warning at 3 minutes** — The per-question timer turns red and plays a soft beep when a question exceeds 3 minutes.
- **Pause support** — Hold Space for 1 second to pause the timer; tap Space again to resume.
- **Progress bar** — A subtle top bar fills while holding Space to pause.
- **Fullscreen mode** — Automatically enters fullscreen when the exam starts and exits on pause or exam end.
- **Leave protection** — Prompts before closing or navigating away during an active exam.

## Usage

1. Open `index.html` in any modern browser.
2. Configure your exam settings at the bottom of the screen:
   - **End Exam After** — Enter a number and choose *Minutes* or *Questions*.
   - **Strict Mode** — Toggle to enable or disable distraction tracking.
3. Press **Space** to start the exam.
4. Press **Space** again after finishing each question to record it and reset the per-question timer.
5. To pause, **hold Space for 1 second**. Press Space again to resume.
6. The exam ends automatically when the configured time or question limit is reached.

## Keyboard Controls

| Action | Key |
|---|---|
| Start exam / Next question | `Space` (tap) |
| Pause timer | `Space` (hold 1 second) |
| Resume timer | `Space` (tap while paused) |

## Stats Panel

| Stat | Description |
|---|---|
| **Average Time** | Mean time spent per question |
| **Highest Time** | Longest time spent on a single question |
| **Lowest Time** | Shortest time spent on a single question |
| **Questions Done** | Number of questions completed |
| **Distractions** | Number of times focus left the window (Strict Mode only) |

## Requirements

- A modern web browser with JavaScript enabled (Chrome, Firefox, Safari, Edge).
- No dependencies or build step required — it is a single self-contained HTML file.

## License

See [LICENSE](LICENSE).
