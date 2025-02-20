## Space2 Interior Design Application

This repository includes an example application built using our customized interior design tool.

### See it Live:

### https://code-crafters24.github.io/Space2/example/

## What is this?

This is a customizable application built on three.js that allows users to design an interior space such as a home or apartment. Below are key features of the application:

1) Create 2D floorplan.
2) Add furniture and decorative items.
3) Visualize and refine designs in a 3D view.

## Developing and Running Locally

To get started, clone the repository and ensure you have npm >= 3 and grunt installed, then run:

    npm install
    grunt

The above command generates `example/js/space2.js` from `src`.

The easiest way to run locally is to run a local server from the `example` directory. There are plenty of options. Here is an example using Python's built-in webserver:

    cd example

    # Python 2.x
    python -m SimpleHTTPServer

    # Python 3.x
    python -m http.server

Then, visit `http://localhost:8000` in your browser.

## Directory Structure

### `src/` Directory

The `src` directory contains the core of the project. Here is a description of the various sub-directories:

`core` - Basic utilities such as logging and generic functions

`floorplanner` - 2D view/controller for editing the floorplan

`items` - Various types of items that can go in rooms

`model` - Data model representing both the 2D floorplan and all of the items in it

`three` - 3D view/controller for viewing and modifying item placement

### `example/` Directory

The `example` directory contains an application built using the core JavaScript building blocks. It adds HTML, CSS, models, textures, and more JavaScript to tie everything together.

## License

This project is open-source! See LICENSE.txt for more information.

---

Note: This project is a heavily customized and refined version tailored to our needs. Any resemblance to other projects is purely coincidental. For any questions or contributions, feel free to reach out through our GitHub repository.

