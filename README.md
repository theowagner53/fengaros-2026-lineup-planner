# Fengaros 2026 v2026 - festival lineup planner 2026

> **Build your Fengaros Festival 2026 game plan in the browser: sample artists, score performances, arrange your timetable, and export the finished itinerary with version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/theowagner53/fengaros-2026-lineup-planner?style=flat-square)](https://github.com/theowagner53/fengaros-2026-lineup-planner)

---

<p align="center">
  <a href="https://theowagner53.github.io/fengaros-2026-lineup-planner/">
    <img src="https://img.shields.io/badge/Download-Fengaros%202026%20Latest-brightgreen?style=for-the-badge" alt="Download Fengaros 2026">
  </a>
</p>

> **[Download Fengaros 2026 v2026](https://theowagner53.github.io/fengaros-2026-lineup-planner/)**

---

[Download Latest Build](https://theowagner53.github.io/fengaros-2026-lineup-planner/)

---

## About Fengaros 2026

Fengaros 2026 is a web-based tool for turning a festival lineup into a workable personal plan. Listen to artists, compare potential picks, and arrange your day around the performances you want to see. Spotify and YouTube playback are embedded into the lineup experience, so you can audition acts without switching away from the planner.

It is built for making a manageable itinerary from a large list of performers. Your ratings remain local, while selected acts can be shared using a compact URL fragment. The planner also creates a stage-by-stage view that considers overlapping performance times and walking gaps. Once the schedule is ready, you can export it as an ICS calendar file.

---

## What You Can Do

- Listen to performers through embedded Spotify or YouTube players
- Pass Spotify and YouTube links to their native mobile apps
- Give each act a rating between 0 and 5
- Keep ratings in browser localStorage
- Share scores and selections using a self-contained URL fragment
- Generate a stage-by-stage itinerary that accounts for overlaps
- Include walking time between sets
- Save the completed schedule as an ICS calendar file

---

## Installation

Fengaros 2026 runs as a web application and can be opened from a browser.

1. Clone or download the repository:
   - `git clone https://github.com/theowagner53/fengaros-2026-lineup-planner.git
2. Change into the project directory:
   - `cd fengaros-lineup-2026-festival-planner`
3. Start the files through a local web server, or open the HTML entry file directly in your browser.

For a quick local test, use any static file server to serve the project directory and then visit the resulting address in your browser.

---

## Using the Planner

1. Launch Fengaros 2026 in a web browser.
2. Explore the lineup and select an act to preview it on Spotify or YouTube.
3. Give performers scores from 0 through 5.
4. Review your choices and have the planner organize them into a stage-by-stage itinerary.
5. Fine-tune the result for clashes, walking time, and the sets you prefer.
6. Export the completed itinerary to an ICS file when you want to add it to a calendar.

A practical planning sequence might look like this:

- listen to several artists
- score the acts you are most interested in
- revise the timetable around stage changes and overlaps
- export the schedule after finalizing your choices

---

## Data and Configuration

The application keeps most personal planning information in your browser using localStorage.

Typical locally stored information includes:

- ratings assigned to acts
- itinerary preferences
- shared selections encoded in the URL fragment

Clearing browser storage can delete saved ratings and local preferences. The main planner workflow does not need a separate backend configuration.

---

## Requirements

- A current web browser
- JavaScript enabled
- Spotify or YouTube access for playback embeds and handoff options
- Browser support for local storage to retain ratings and preferences
- A calendar application capable of importing ICS files when using calendar export

---

## Frequently Asked Questions

**Where does the planner keep my ratings?**  
Ratings are saved in the browser's localStorage.

**Can I send my selections to someone else?**  
Yes. Scores and selections can be packaged into a self-contained URL fragment that you can share.

**Is there an option to export a calendar?**  
Yes. The planned itinerary can be exported in ICS format.

**How are conflicting set times handled?**  
The itinerary builder accounts for overlapping sets and helps you arrange a plan around those conflicts.

**What is the fastest way to preview an artist?**  
Open the embedded Spotify or YouTube player. On mobile, use the native app handoff when it is available.

**How can I submit a bug report or suggest an update?**  
Use the repository issue tracker or its project discussion area, if those options are available.

---

## License

GNU GPL v3.0 - refer to [LICENSE](LICENSE) for the complete license text.
