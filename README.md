# Musa's Colour World

An original, iPad-friendly colouring game built with HTML, CSS and vanilla JavaScript.

## Play it
Open **[index.html](./index.html)** in a browser, or enable GitHub Pages for this repository to publish it as a website.

## Controls
- **Fill:** tap an outlined section to colour only that section.
- **Brush:** choose Brush, then draw inside a section. Brush marks are clipped to that section.
- **Eraser:** use Eraser to restore a section or brush marks to white.
- **Undo / Redo:** step backward and forward through painting actions.
- **Save art:** download the current picture as an SVG file.
- **Brush size:** adjust the brush width with the slider.

## Included original colouring pages
Happy Puppy, Curious Kitty, Garden Butterfly, Wonderful Tree, Little Fish, Space Rocket, Sunny Flower and Dream Castle.

## Design notes
- Responsive layout: picture canvas on the left and colour tools on the right on wide screens; stacked layout on smaller screens.
- SVG-based regions keep fills and brush strokes inside their selected shapes.
- Black outline artwork is rendered above the paint.
- Supports touch, mouse and Apple Pencil input through Pointer Events.

## Next development milestones
Add more original page packs, richer illustrations and sounds, progress/bookmarks, optional guided colouring, and an installable offline PWA build.
