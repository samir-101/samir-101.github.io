---
title: "tRIPSy - Sound Source Localizing Tri-copter"
excerpt: "Short description of portfolio item number 1<br/><img src='/images/portfolio1.jpg' height=\"300\" width = \"500\">"
collection: portfolio
---

### tRIPSy

Sound source localization tri-copter is our ME 366 project. It uses a 4 array microphone arranged
in a circular pattern to detect noise sources and their direction of arrival(DOA). We used an
open source library “Open embeddeD Audition System(ODAS)” in order to detect noise sources
and their direction relative to the UAV. There are three fundamental duties of our UAV, 1.
Detecting noise sources and their direction. 2. Moving towards that direction 3. Taking photos
and keeping a database of the noise sources. For detecting noise sources, the quietness of our
UAV was our first criterion for selection of frame, so we chose tri-copter because of their lower
noise level and higher efficiency.

The tri-copter can automatically detect the loudest sound source that resides within its range of
coverage area and moves towards it until it succeeds in reaching its waypoint which is
specifically above that source. A single board computer with an integrated microphone array is
used for this purpose.

An onboard camera takes a picture of the sound source upon reaching the target waypoint and
extracts text from that image using various image processing algorithms and sends that data to
the server. And the whole process repeats.