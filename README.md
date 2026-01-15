# Odoo NFC Attendance Kiosk

Turn a Raspberry Pi + Waveshare NFC Hat into a professional attendance terminal for Odoo.

## Features
- Real-time feedback via WebSockets.
- Double-tap protection.
- Auto-recovery (Systemd services).
- Automatic "Forgot to clock out" handling.

## Setup
1. Clone this repo to your Raspberry Pi.
2. Run `./install_kiosk.sh`.
3. Edit the `.env` file and add your Odoo Webhook URL.
4. Reboot or start the services: `sudo systemctl start attendance_app`.

## Hardware
- Raspberry Pi (3, 4, or 5).
- Waveshare PN532 NFC HAT.
