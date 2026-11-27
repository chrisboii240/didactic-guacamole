# Chrisboii's Mini Handheld

A handheld Raspberry Pi 4 build with a 3D-printed case that every part drops or clicks into.

## Who's who
- The builder is **Chrisboii**. Handoff PDFs labelled "Kylie's Mini Laptop" come from Kylie's Claude chat, but they're Chrisboii's project. Use "Chrisboii" for names and titles.

## Current design (sketch: design/sketch.jpg, 3D mockup: design/handheld-mockup.html)
- One-piece handheld, not folding. The screen section leans back about 8° from the keyboard section.
- 7" 1024x600 main screen (Waveshare HDMI LCD (C)). Keyboard: a 9-10" wireless keyboard with touchpad, which makes the body ~10-11" wide.
- On top: Flipper Zero in a removable cradle (top left), 2" status screen box (Pimoroni Display HAT Mini, top right), antenna (decoration).
- Right side: a 3.5" HDMI "AI" screen (640x480) in its own small case, on the Pi's second HDMI port.
- Inside: Pi 4 behind the screen with USB ports facing up toward the Flipper, battery (Anker A1259) in a click-in tray beside it, 30 mm 5 V fan, cable channels.

## Links
- 3D mockup: https://claude.ai/artifact/TdSzdJcM2RjNwRsfqEmoqq
- Case fit plan: https://claude.ai/artifact/65VU4GMzGoXpAZYVt8pLfn

## Working rules
- Keep add-ons optional until Chrisboii picks one. Before changing the parts list, check the connector, power draw and mounting space.
- Pi 4 USB ports share 1.2 A in total; watch the screen and Flipper together.
- Bench-test in stages before designing or printing the case. Measure real parts with calipers.

## Open decisions
- Shopping list: SHOPPING_LIST.md. Battery chosen: Anker A1259. Power: GPIO3 button + inline USB-C switch.
- Still open: Waveshare (E) vs Newhaven 3.5" AI screen; exact keyboard; 3D printer access; USB power budget check.
