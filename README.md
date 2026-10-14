# JSS University Noida – 3D Virtual Campus Tour

An interactive 3D model of the JSS University campus (C-20/1, Sector 62, Noida) built with Three.js, with a 10-stop guided tour.

## Features
- Dusk-lit 3D campus you can orbit, zoom and pan
- 10 tour stops: Main Gate, Administration, Academic Blocks, Central Library, College of Pharmacy, Research & JSS STEP, Sports Grounds, Boys' Hostel, Girls' Hostel, Student Services
- Click any building or numbered pin to fly to it; Auto tour mode
- Fact panel with sourced data for every stop
- Works on desktop and mobile

## Run
Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000. Three.js r128 loads from a CDN.

## Deploy with GitHub Pages
Settings → Pages → Deploy from branch → `main` / root.

## Note
Building positions are a schematic approximation; no public site plan was available. Facts come from Careers360, jssaten.ac.in, TopUniversities, CollegeBatch and the university's 2026 faculty notice.
