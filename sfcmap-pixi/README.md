# SfcmapPixi

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.2.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Goals

- Get a map to show
- Zoom and Pan with a mouse drag, mouse wheel, keyboard + and -
- Calibrate the map to pixels per distance
- Ruler
- Add the grid


Appl
Layers
- Image
- Grid
- Sprits
- Graphics

Interaction


# Maps
- Showed that PixiJS is problably better than leaflet for my use case.
- All Maps are in native resolution and have a PPM 
- Maps can be dragged with the mouse and zoomed with mouse wheel
- Need to figure out fog of war
- Layers

    Fog Of War / Lighting
    Grid
    Annotation
    Characters
    Items
    Map / Page
    Viewport
    Background
- Need to figure out mouse over annotations
- Need to figure out Distance Meter

# Tool Bar
- DIV element (not part of pixijs)

## Ruler Tool
- User clicks on tool, clicks on start point and end point(s) 

# Work on
- Understand the viewport plugin more. 
- Add a character sprite and try to move it with a mouse.

## Character / Monster design
- Primarily the image (sprite) (Z 100)
- Attach bars to that  (z200)
- Auras z90
- FIgure out how to scale the size. (PPM * Size)
- Selection indicator (Use the glow filter)