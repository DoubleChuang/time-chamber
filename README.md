# Pause Breathe — Freediving Breath Training Timer

[繁體中文版](README_TC.md)

A breathing timer designed for freediving training: customizable sequences, precise timing, and video recording.

---

## Features

| Feature | Description |
|---------|-------------|
| Custom Training Sequences | Drag and drop modules to build CO2 tables, O2 tables, stretch routines, and more |
| Precise Timing | Independent countdown for each phase with pause, skip, and stopwatch modes |
| Sound Cues | Phase transition tones + English voice prompts (start, finish, countdown) |
| Video Recording | Record camera feed with timer overlay during training |
| Example Programs | 5 built-in presets, load and adjust in seconds |
| Share Links | Compress your sequence into a URL, share and restore instantly |
| Calendar Export | Export ICS file or add to Google Calendar after training |
| Bilingual | Traditional Chinese / English |
| Dark / Light Theme | Ocean Night (dark) / Ocean Day (light) |
| PWA Install | Install to home screen, works offline |

---

## Interface Overview

### Top Toolbar

Fixed at the top of the screen:

- **Logo** — Click to refresh the page
- **Version Tag** — Shows current version
- **Settings Button** — Opens settings panel (language, theme, sound, recording)

### Summary Bar (Hero Panel)

Real-time statistics of your current sequence:

- **Steps** — Total number of steps after flattening loops
- **Total Duration** — Sum of all step durations

### Tool Modules (Left Panel)

Drag or tap to add training modules:

| Module | Purpose | Description |
|--------|---------|-------------|
| **Inhale** | Set inhale or recovery duration | Default 90 seconds, customizable |
| **Hold** | Set breath-hold duration | Default 75 seconds, supports stopwatch mode |
| **Top (Competition Countdown)** | Simulate competition countdown | 120s countdown + 30s overtime with full voice cues |
| **Loop** | Repeat a sequence multiple times | Supports nested loops (loops inside loops) |

### Example Programs (Left Panel)

5 built-in presets, load with one click and fine-tune:

| Example | Description |
|---------|-------------|
| Competition Countdown | Simulates a competition countdown flow |
| CO2 Table | 8 rounds, fixed 1:00 hold, rest reduced by 15s each round |
| Full Breath CO2 Table | 8 rounds, single full breath recovery, 75s hold |
| Full Lung Stretch | 8 sets: 10s full breathing → 30s stretch hold → 10s recovery |
| Empty Lung Stretch | 8 sets: 10s full exhale → 20s stretch hold → 20s recovery |

### Sequence Builder (Center Panel)

Main workspace for assembling your training flow:

- Drag modules from the left panel
- Configure duration, mode, and repeat count for each module
- Nested loops support unlimited depth (5 levels recommended)
- Builder locks during execution to prevent accidental edits
- Mobile: tap the "+" button to insert modules quickly

#### Hold Module Special Features

- **Stopwatch Mode** — Counts up instead of down, press "Finish" to end
- **Reminders** — Set reminder points in stopwatch mode, voice announces elapsed time

#### Loop Module

- Set repeat count (1-100 times)
- Contains other modules (inhale, hold, or even another loop)
- Shows progress during execution (e.g., round 3 of 8)

### Training Runner (Right Panel)

Controls training execution:

- **Start** — Begins with a snapshot of the current sequence
- **Pause / Resume** — Pause and continue at any time
- **Skip** — Skip the current phase
- **Stop** — End training and reset

Runner displays:

- Current phase (Inhale / Hold / Competition Countdown)
- Countdown or stopwatch timer
- Step progress (Step X of Y)
- Status description

### Share Panel (Right Panel)

Share your sequence with others:

- Automatically generates a compressed URL
- Copy the link and send to friends
- Recipients can load the exact same sequence by opening the link

### Video Recording

Enable recording in settings:

1. Camera and microphone permissions are requested when training starts
2. Records camera feed + training overlay (timer, phase name, progress)
3. Automatically converts format after training (WebM → MP4 if needed)
4. When complete:
   - Download video
   - Share video (mobile)
   - Export ICS calendar file
   - Add to Google Calendar

A floating preview window appears during recording — drag to reposition, tap to expand/minimize.

---

## Use Cases

### Case 1: Daily CO2 Table Training

1. Open the app
2. Load the "CO2 Table" example
3. Adjust durations to your pace
4. Press "Start"
5. Export to calendar after training

### Case 2: Pre-Competition Simulation

1. Load the "Competition Countdown" example
2. Adjust countdown start seconds (120s / 90s / 60s)
3. Enable sound cues (includes full English voice countdown)
4. Enable recording to capture the session
5. Download video and share with your coach

### Case 3: Full / Empty Lung Stretch

1. Load "Full Lung Stretch" or "Empty Lung Stretch" example
2. Loop is preset to 8 repetitions
3. Adjust breathing and stretch durations per set
4. Start training

### Case 4: Custom Training Flow

1. Drag "Inhale", "Hold", and "Loop" modules from the tool panel
2. Place multiple inhale and hold modules inside a loop
3. Set duration for each module
4. Adjust loop repeat count
5. Save the share link for friends

### Case 5: Stopwatch Challenge

1. Add a Hold module
2. Switch to "Stopwatch" mode
3. Set reminder times (e.g., 1 min, 2 min, 3 min)
4. Start — timer counts up, voice announces at each reminder
5. Press "Finish" when done

---

## License

BSD-3-Clause
