# OpenWindow
LAHacks 2025
## Inspiration
During the COVID-19 lockdown, I was struck by how isolated we felt behind our screens—and how online relationships can blur comfort and control.

## What it does
 I wanted to capture that tension in a small, self-contained Roblox experience: a teenage heroine confined to her room, seeking lighthearted connection but finding something unsettling instead. The title “Open Window” nods to both digital “windows” and the literal window that never fully closes, symbolizing privacy lost.

## How we built it
- Modeled a single bedroom in Studio
- DayManager ModuleScript that tracks the current day
- Designed a multi-tab ScreenGui with Zoom, Messaging, fully functioning Roblox “dress-up” minigame
- Scripted timed dialogue sequences

## Challenges we ran into
- Infinite Yields when using WaitForChild, UI elements not found
- Event Timing: Rapidly queuing multiple delay() calls risked overlapping dialogues
- UI Lock/Unlock: Balancing mouse lock for GUI interaction versus free camera

## Accomplishments that we're proud of
- Implementing mock Zoom interface
- Fully functional dress up game
- Thrilling dialogue and story line 
- Immersive bedroom design

## What we learned
- First time making Roblox game! Huge learning curve.
- Roblox Studio, Roblox Lua Scripting, State Management, GUI Flow & Timing, Narrative Pacing

## What's next for Open Window
Expanded Narrative: Flesh out more days with more events and optional player choices.
Player Agency: Allow players to type custom replies in chat, influencing subsequent dialogue or endings.
Sound and Environment: Allow players to interact with room more, and make a soundtrack.

