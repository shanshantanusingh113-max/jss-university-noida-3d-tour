# JSS University Noida – 3D Virtual Campus Tour

An interactive 3D model of the JSS University campus (C-20/1, Sector 62, Noida) built with Three.js, with a 10-stop guided tour.

## Features
- Layout traced from Google Maps satellite imagery: Main Building, College of Pharmacy, MPR Hall, football and cricket grounds, basketball courts, Academic Block 2, the V-shaped central block, Library & JSS STEP, main gate
- Pink sandstone facades modelled on campus photos: deep-set windows with sunshades, arched ground-floor arcades, parapet lettering, glass atriums, rooftop solar panels
- Day and evening lighting (lit windows and street lamps at night)
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
Footprints are traced from satellite imagery. Hostel and cafeteria positions are estimates because public maps do not label them. Facts come from Careers360, jssaten.ac.in, TopUniversities, CollegeBatch and the university's 2026 faculty notice.
