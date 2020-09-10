# The Louver Carousel

This is a variation on the [Slide Carousel](https://github.com/teochewthunder/slidecarousel). Stuff still slides from right to left (or left to right), but instead of having it happen in one shot, we want it to happen in louvers, like the blinds on a window.

## HTML/CSS
Within the viewport, we now have 10 containers instead of 1. Each one takes up 10% of its parent's width, and acts as a viewport on its own. The content background image still maes up the background of the `content` divs, but the position will be offset using the `nth-of-type` pseudoselector. This provides the illusion that it's one big picture, when in reality it's 10 small ones.

## JavaScript
Largely unchanged, though no HTML content can be embedded easily.
