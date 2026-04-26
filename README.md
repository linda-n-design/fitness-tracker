# Fitness Tracker v1.0

A desktop fitness tracker that runs offline in your web browser on your computer. Single HTML file - no accounts, no cloud, no tracking.

## Table of contents

- [About this project](#about-this-project)
- [How it works](#how-it-works)
- [Font](#font)
- [My fitness setup](#my-fitness-setup)
- [Future plans](#future-plans)
- [Quick start](#quick-start)
- [Data export/import](#data-exportimport)
- [License](#license)
- [Version history](#version-history)

## About this project

I created this for myself and decided to share it with others. It's designed around my personal fitness routine and the equipment I have access to, but it's open source - so fork it and modify it to work for you.

**Platform:** Designed and tested on Mac/Safari. Other platforms untested.

## How it works

**Complete privacy. Zero internet required.** All data stays on your computer in your browser's local storage. No cloud sync, no servers, no accounts, no tracking. Just you and your fitness data.

The entire app is a single HTML file - open it in Safari and start logging. Export your data as timestamped Excel files (.xlsx) for backup. Import them back if you clear your browser data.

**Don't have Excel?** The .xlsx files work in LibreOffice and other spreadsheet apps.

## Font

The font used is the free **Atkinson Hyperlegible**, designed and created by the nonprofit Braille Institute for legibility: https://www.brailleinstitute.org/freefont/

The app first tries to use Atkinson Hyperlegible if you have it installed on your computer. If not, it falls back to your system font (San Francisco on Mac, Segoe UI on Windows) or any generic sans-serif font.

## My fitness setup

The exercises in this tracker are based on what's doable for me today, which may be considered too easy or difficult for others. Here's what I have to support my fitness routine:

### Equipment
- **Apple Watch** - To track steps and time various exercises.
- **Weights** - A pair of 20-pound and 3-pound dumbbells. If the day comes when the 20-pounders become easy, I'll probably get a gym membership or heavier weights and update this Fitness Tracker web app.
- **Weightlifting gloves** - Protect my hands during dead hangs, minimizing the grip pain that comes from prolonged hanging.
- **Jump rope** - Can only be used outdoors with rubber-like ground that makes jumping easier on the joints than hard concrete.
- **Shoulder door pulley** - Hooks to the top of the door and when shut, it works almost like a Gyrotonic pulley tower. I love Gyrotonic but owning the tower or regularly attending classes is outside my budget. Plus the goal of this is to not be tethered to an external fitness class or gym.
- **Resistance bands** - The cheapest gear I own.
- **Exercise mat** (not yoga mat) - An inch thick, the sort used in Pilates mat classes. I like using it for burpees and planks instead of doing those exercises on the hardwood floor.
- **Vibrating foot plate** - The most expensive gear in this list (not including the watch). Feels good for loosening up my knees and hips, and makes balance exercises like single-leg stands and squats more challenging.

### Outdoor access
- **Monkey bars** - Where I can do a dead hang.
- **Outdoor staircases** - All over my area, many of them hidden from people driving around and unfamiliar with the neighborhoods.

### Fitness resources
Part of my fitness budget includes a subscription to NYTimes.com, which has a lot of exercise tutorials. I link to them in the app as reminders for the exercises I chose. The digital subscription is cheaper than many US-based online fitness classes. I prefer their instructions over the free YouTube content, many riddled with commercials.

## Future plans

I may modify the tracker with different exercises - add some, remove some, modify some (like heavier weights eventually). Each update will be released as a new version using semantic versioning, with the complete version history documented in this GitHub repository.

Possible future improvements:
- Data visualizations to see fitness progress at a glance.
- Support for iPad.
- Cloud sync for Excel files (Mac/iPad).
- Different exercises based on new equipment.
- More challenging fitness exercises, like heavier dumbbells.

## Quick start

1. Download `fitness-tracker.html` from this repository.
2. Save it anywhere on your Mac (Desktop, Documents, wherever).
3. Double-click to open in Safari.
4. **Bookmark it** for easy access (⌘D on Mac).
5. Start logging your exercises.

**That's it.** No installation, no setup, no account.

## Data export/import

- **Export** - Downloads your data as a timestamped Excel file (.xlsx).
- **Import** - Upload a previously exported Excel file to restore your data.

Export regularly to back up your data!

## License

MIT License - See LICENSE file for details.

This is open source - fork it, modify it, make it work for you.

## Version history

### v1.0 (2026-04-26) - Initial Release
First public release. Designed for personal use on Mac/Safari.

**Features:**
- Offline fitness logging with localStorage.
- Excel export/import with timestamps.
- 10+ exercise types (cardio, strength, balance).

---

**Made for personal use, shared with others who might find it useful.**

**Find this useful? I like coffee** - [buy me a coffee](https://buymeacoffee.com/lindadesign) ☕

