# Sketch2Room

Sketch2Room is a tool for turning a simple room sketch into a clear digital room concept. The project aims to help users quickly explore a room's layout and visualize how a rough idea could look before moving to detailed design or construction.

## Project goal

Build an accessible workflow that accepts a hand-drawn or digital room sketch, identifies the main room geometry and objects, and produces an editable room representation with a useful visual preview.

## First version (MVP)

The first version will focus on one complete, reliable path:

1. Upload a single room sketch as an image.
2. Detect or manually confirm the room boundary, doors, windows, and major furniture.
3. Convert the confirmed sketch into a simple structured floor plan.
4. Generate a basic 2D preview and a simple 3D room view.
5. Export the result as an image and save the project data for later editing.

The MVP will support one rectangular room at a time. Multi-room plans, photorealistic rendering, automatic material selection, and precise construction drawings are outside the first-version scope.

## Roadmap

- [ ] Define the project data model and choose the application stack.
- [ ] Build sketch upload and image preprocessing.
- [ ] Add room-boundary and object detection.
- [ ] Add manual correction tools for detected geometry.
- [ ] Generate the 2D floor-plan preview.
- [ ] Generate the basic 3D room view.
- [ ] Add project save/load and image export.
- [ ] Test the MVP with varied sketch styles.
- [ ] Extend to multi-room layouts and higher-quality visualization.

## Setup

> Setup instructions will be added after the initial technology stack and dependencies are selected.

```bash
# Clone the repository
git clone https://github.com/iparkrgb/Sketch2Room.git
cd Sketch2Room

# TODO: install dependencies
```

## Run

> Development and production run commands will be documented when the first executable prototype is added.

```bash
# TODO: start the application
```

## Status

Early planning and prototyping.
