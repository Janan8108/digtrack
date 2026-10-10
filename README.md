# DigTrack: Public Works Transparency and Coordination

**Team Groundwork** | CivicTech track | IIITDM Kancheepuram 24-Hour Web Development Hackathon

**Live demo:** https://janan8108.github.io/digtrack/

## Problem
Roads, drains and pipelines are dug by different departments and contractors. Residents cannot see what is being done, who is responsible or when it will end. Departments do not know each other's plans, so the same road is often dug repeatedly.

## Solution
DigTrack is a single public map of all ongoing and planned public works.
- **Project map:** colour-coded pins (red = delayed, yellow = ongoing, green = completed)
- **Project details:** purpose, department, contractor, timeline, delay reason
- **Citizen reports:** residents report whether work is ongoing, stalled or poorly done
- **Department form:** officers add new projects by clicking a location on the map
- **Conflict detector:** warns when a new project is within 500 m of active work with overlapping dates

## Tech stack and open-source disclosure
- HTML, CSS, JavaScript (single-page app)
- Leaflet 1.9.4 (via cdnjs) for maps
- OpenStreetMap tiles for map data
- Hosted on GitHub Pages
- All project data is simulated for demonstration.

## Setup
1. Open the live link above, or
2. Download `index.html` and open it in any browser (internet needed for map tiles).

## Current limitations and future scope
- Citizen reports are stored in the browser (localStorage). Next step is a shared database (Supabase) with authentication for officers.
- Photo uploads for reports and progress updates
- SMS or email alerts for residents of an affected area
- Integration with municipal open-data feeds

## Demo video
See the demo video added to this repository.
