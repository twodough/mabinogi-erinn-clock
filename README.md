# 瑪奇愛爾琳時鐘與鬧鈴

A small static Mabinogi Erinn time clock with browser alarms.

- Real-world 36 minutes = 1 Erinn day
- Real-world 1 second = 40 Erinn seconds
- Alarms are stored in `localStorage`
- Refresh rate is user configurable from 1 to 10 times per second
- Analog hands use sub-second Erinn time for smoother movement
- Alarm volume is user configurable
- Test button plays sound and sends a real browser notification when permission is granted
- Preset alarms include mushroom time and part-time job start/report reminders
- Default baseline uses Taiwan time (Asia/Taipei), which keeps weekday calculations correct for Taiwan Mabinogi
- Optional extra offset calibration: `?offset=120` means add 120 real seconds before converting to Erinn time

## Deploy

This repo is deployed with GitHub Pages from the `main` branch root.
