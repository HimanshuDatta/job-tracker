# Job Tracker

A simple web app to track job openings from your target companies.

## Features

- Track multiple companies and job roles
- Filter by location and visa sponsorship
- See application deadlines and posting dates
- Smart company autocomplete with 90+ popular companies
- Group jobs by company
- Persistent storage - your data is saved locally

## Setup

### Use on GitHub Pages

1. Fork this repository
2. Go to Settings → Pages
3. Set Source to `main` branch, `/ (root)` folder
4. Your tracker will be live at `https://yourusername.github.io/job-tracker/`

### Run Locally

Just open `index.html` in your browser. No installation needed.

## How to Use

1. Add companies you want to track
2. Add job roles you're interested in
3. (Optional) Add preferred locations
4. Click "Check for New Jobs"
5. Use filters to narrow results

## Note

Currently uses mock data for demonstration. To use real job data, integrate a job board API (LinkedIn, Indeed, Adzuna, etc.) by replacing the `fetchJobs()` function.

## License

MIT