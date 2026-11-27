# Chrisboii's Mini Handheld

A handheld Raspberry Pi 4 build with a 3D-printed case that every part drops or clicks into.

## Who's who
- The builder is **Chrisboii**. Handoff PDFs labelled "Kylie's Mini Laptop" come from Kylie's Claude chat, but they're Chrisboii's project. Use "Chrisboii" for names and titles.

## Current design (sketch: design/sketch.jpg, 3D mockup: design/handheld-mockup.html)
- One-piece handheld, not folding. The screen section leans back about 8° from the keyboard section.
- 7" 1024x600 main screen. Keyboard: Adafruit #922, 152 x 61 x 13 mm, which sets the body width (~180 mm).
- On top: Flipper Zero in a removable cradle (top left), 2" status screen box (Pimoroni Display HAT Mini, top right), antenna (decoration).
- Right side: a 2" "AI" screen in its own small case.
- Inside: Pi 4 behind the screen with USB ports facing up toward the Flipper, battery (Anker A1259) in a click-in tray beside it, 30 mm 5 V fan, cable channels.

## Links
- 3D mockup: https://claude.ai/artifact/TdSzdJcM2RjNwRsfqEmoqq
- Case fit plan: https://claude.ai/artifact/65VU4GMzGoXpAZYVt8pLfn

## Working rules
- Keep add-ons optional until Chrisboii picks one. Before changing the parts list, check the connector, power draw and mounting space.
- Pi 4 USB ports share 1.2 A in total; watch the screen and Flipper together.
- Bench-test in stages before designing or printing the case. Measure real parts with calipers.

## Open decisions
- Which 7" screen (Waveshare (C) or 52Pi from Micro Center)
- Which 2" screen for the AI pod (must share GPIO with the Pimoroni HAT)
- Battery: Anker A1259 tray or GeeekPi UPS Gen 6
- Power button on GPIO3 (conflicts with I2C)
- 3D printer access
