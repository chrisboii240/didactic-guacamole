# Chrisboii's Mini Handheld: Shopping List

Prices were seen in search results on Nov 27, 2026, so check them before buying. Core build total: about $420–460 before the case, tax and shipping.
Full plan (sizes, mounting, cables, build stages): https://claude.ai/artifact/65VU4GMzGoXpAZYVt8pLfn

| # | Part | Pick | Size (mm, approx) | Price seen | Where |
|---|---|---|---|---|---|
| 1 | Pi kit | CanaKit Pi 4 4GB Starter MAX (Pi, power supply, fan, heatsinks, 64 GB card with Pi OS, HDMI cables) | Pi: 85 × 56 × ~17 | $189.99 | [Micro Center](https://www.microcenter.com/product/615270/canakit-raspberry-pi-4-starter-max-kit-4gb-sdram) |
| 2 | Main screen | Waveshare 7" HDMI LCD (C), 1024×600, ~2.5 W | 164.9 × 107 × 8 | check Amazon | [Waveshare specs](https://www.waveshare.com/wiki/7inch_HDMI_LCD_(C)) |
| 3 | Keyboard | 10" wireless keyboard with touchpad (Vilros) | measure | ~$16 | [Vilros](https://reach.dog/shop/vilroscom/products/vilros-2-4ghz-10-inch-wireless-keyboard-with-touchpad-great-for-raspberry-pi) / Amazon |
| 4 | Status screen (top) | Pimoroni Display HAT Mini 2" | ~65 × 30 board | $23.90 | RobotShop |
| 5 | AI screen (side) | 3.5" HDMI 640×480: Waveshare (E) with touch, or Newhaven sunlight-readable | measure | $44–60 | Waveshare / [Newhaven](https://newhavendisplay.com/3-5-inch-ips-high-resolution-hdmi-tft-module/) |
| 6 | Battery | Anker A1259 10,000 mAh, built-in USB-C cable | ~105 × 52 × 26 | $49.99 | [B&H](https://www.bhphotovideo.com/c/product/1917544-REG/anker_a1259h11_nano_power_bank_with.html) |
| 7 | On/off button | 16 mm panel-mount momentary button → GPIO3 + GND (`dtoverlay=gpio-shutdown`) | 16 mm hole | ~$5–8 | Amazon / Micro Center |
| 8 | Full power cut | Inline USB-C cable with on/off switch (battery → Pi) | – | ~$8 | Amazon |
| 9 | Cables | Flat micro-HDMI ribbon ×2, right-angle USB-A→micro-USB (screen touch), right-angle USB-A→USB-C **data** (Flipper), 40-pin GPIO extension | – | ~$30–40 | Amazon |
| 10 | Screws | M2.5 heat-set inserts + screws + standoffs kit | – | ~$12–15 | Amazon / Micro Center |
| 11 | Tool | Digital calipers | – | ~$20 | Micro Center |

## Items you asked about
- **CM4 aluminum heatsink (55 × 40 × 5 mm): don't buy.** It's for the Compute Module 4 and won't fit a Pi 4 Model B.
- **3.5" HDMI TFT, 640×480, sunlight-readable: yes, as the AI screen.** It uses the Pi's second HDMI port, so it doesn't share GPIO pins. The bright version uses more battery.
- **GeeekPi Arduino UNO R4 WiFi kit: later.** The Pi can't read the analog joystick, so it would need a second board. Use panel-mount buttons for now.

## Flipper Zero upgrades (top-left dock)
| Upgrade | Price seen | Where |
|---|---|---|
| WiFi Devboard | $34.99 | [Micro Center](https://microcenter.com/product/704152/wifi-devboard-for-flipper-zero) |
| Video Game Module | $48.99 | [Micro Center](https://microcenter.com/product/704156/video-game-module-flipper-zero) |
| Silicone case | $15.00 | [Flipper shop](https://flipper.net/products/flipper-zero) |
| Screen protectors | $7.50 | [Flipper shop](https://flipper.net/products/flipper-zero) |
