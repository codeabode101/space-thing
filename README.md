⌨️ 5-Day Python Project: Interactive Status Monitor
Build a program that acts like a control panel, responding to your key presses by changing its display and messages.
---
### Day 1: Basic Alert System
1. Create `monitor.py` and set up a basic Pygame window.
2. Fill the window with a default light gray color.
3. When the `SPACE` key is pressed, change the background color to red.
4. Print "ALERT! Space key pressed." to your console.
---
### Day 2: Multiple System States
1. Keep your Day 1 code.
2. Add functionality: when the `RETURN` (Enter) key is pressed, change the background to green.
3. Print "System OK! Return key pressed." to your console.
4. Add another key: when `ESCAPE` is pressed, change the background back to the default light gray. Print "System Reset."
---
### Day 3: Naming Your Status
1. Keep your Day 2 code.
2. When the `SPACE` key is pressed, in addition to changing the screen to red, also change the window's title to "STATUS: WARNING!".
3. When the `RETURN` key is pressed, change the title to "STATUS: ALL CLEAR".
4. When `ESCAPE` is pressed, change the title to "STATUS: IDLE".
5. **(After core implementation)** Choose two new keys (e.g., 'Q' and 'E'). For each key, pick a unique screen color and window title to display when pressed.
---
### Day 4: Combined Status Reporting
1. Build on your Day 3 code.
2. Introduce new status keys:
   - When the `1` key is pressed, change the screen to a calming blue AND set the window title to "MODE: SLEEP".
   - When the `2` key is pressed, change the screen to a bright yellow AND set the window title to "MODE: ACTIVE".
3. Add a third number key (`3`) to create another unique color and title combination (e.g., purple screen, "MODE: OFFLINE").
---
### Day 5: Custom Control Panel
1. Use your Day 4 code.
2. Implement a toggle feature: When the `TAB` key is pressed, switch between two states:
   - State A: Screen is dark gray, title is "Display: OFF".
   - State B: Screen is white, title is "Display: ON".
   - *Hint*: You'll need a variable to remember which state you are in.
3. **(Open-ended extension)** Add one more key of your choice. When this key is pressed, it should display a new, unique screen color and window title combination, perhaps showing a "special event" status.
