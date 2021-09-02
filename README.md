# Electrical Template Symbol Library

<figure>                                                                                                                                                                                                                                                                                                                                                                              
  <img src="https://raw.githubusercontent.com/Gondolindrim/file_hosting/main/acheron_graphics/acheron_long.svg" width="600" align="middle"/>
</figure>

Electrical Templates is a symbol library used to make good-looking and uniformized electrical circuit schematics in a vectorized software. The original source is from Inkscape and all sources are developed in Inkscape SVG format which should be natively supported by most vector editors like Illustrator, CorelDRAW *et cetera*.

## Development conventions

In order to ensure scalability and reproductibility, certain aspects are enforced and uniformized throughout the symbols:

- Points use a milimmeter grid and all points should snap to the grid;
- In order for the images to be compatible throughout all systems, the font used is *sans-serif* which is an open-source adaptation of Helvetica;

![example pnp](./readme/bjt_example.png)

In order to keep the grid fixed, the page size is set to A4 size and **should not be changed**, as doing so will move the grid and mess with the formatting of the symbols.

## How to use

If you want to add a component to your drawing, simply copy the drawing from the source file and paste into your circuit file or import the source file SVG. Avoid modifying the source drawings.
