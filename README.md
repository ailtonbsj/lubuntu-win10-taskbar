# Lubuntu Win10 Taskbar

This is a taskbar of lubuntu with windows theme.

You can reset the taskbar using the keys `[Super] + [Alt] + R`.

The taskbar is available with two monitor too.

## lxhotkey commands

```bash
# List hotkeys from system
lxhotkey global

# List hotkeys from programs
lxhotkey app

# View function associated with hotkey
lxhotkey global "<Super>d"

# View program associated with hotkey
lxhotkey app "<Super>P"

# Add association of command to hotkey
lxhotkey app "leafpad" "<Super>F9"

# Remove all hotkeys association from command 
lxhotkey app "leafpad" --
```