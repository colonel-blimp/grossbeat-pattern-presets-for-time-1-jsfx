# grossbeat-pattern-presets-for-time-1-jsfx
Gross Beat patterns, translated to the TIME-1 and GATE-1 JSFX plugins


# TIME-1 jsfx presets

A bank of 166 Gross Beat patterns, adapted as presets for the JSFX TIME-1 (https://forum.cockos.com/showthread.php?t=286951)

Currently provides all patterns from the Gross Beat banks:

- Pattern (35 patterns)
- Repeater (35 patterns)
- Stutter (29 patterns)
- Turntablist (33 patterns)
- Momentary (34 patterns*)

Notes:

- TIME-1 has a limit of 12 patterns per preset, so each 36-pattern bank has been broken up into three sets each.
- Patterns follow the same order as their original bank. Any empty or "mute" patterns are left empty at the same location in the TIME-1 presets. As a result, each preset has been saved to start on its first non-empty pattern.
- Some pitch bending curves in the Chaos patterns sound slightly off compared to the original patterns, and wave curves sound noticeably smoother. It's possible this could be adjusted by using different settings (tilr suggested the anti-clicking algorithms may different); I haven't checked because they still sound good.
- Some Gross Beat patterns (mostly in the Turntablist presets) can't be entirely recreated, either because they require an accompanying volume automation pattern or because TIME-1's grid doesn't go as far down as Gross Beat (-3 vs -7 beats). The patterns with missing volume automation still sound great imo, and so far the only pattern affected by the grid depth is Turntablist 2 pattern 5.0 (Backspin), where the original went all the way down to -7 beats(!).
- The original Turntablist scratch patterns include very quick and often "humanized" rhythms that use grids much smaller than 32 and/or drift slightly on either axis. I've done my best to recreate these without access to exact measurements in TIME-1, and as far as I can hear the timing along both axes is practically identical.
- * = In the TIME-1 version of the Momentary patterns, the `Bar Scratch` and `Scratch` presets are identical
 
# GATE-1 jsfx presets

A bank of 35 Gross Beat volume (gate) patterns, adapted as presets for the JSFX GATE-1 (https://forum.cockos.com/showthread.php?t=286951)

Currently provides all patterns from the Gross Beat banks:

- Pattern (35 patterns)

Notes:

- GATE-1 has a limit of 12 patterns per preset, so each 36-pattern bank has been broken up into three sets each.
- Patterns follow the same order as their original bank. Any empty or "mute" patterns are left empty at the same location in the GATE-1 presets. As a result, each preset has been saved to start on its first non-empty pattern.
- Gross Beat gate patterns often go down to -7 on the y-axis, while GATE-1 has a limit of -4. In practice, I don't hear much of a difference. 
