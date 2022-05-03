# SEB PLOTTER TD / ZOIS


Why TD? Is it for visualisation, or just because you like it?

Would we still just use the SVG print or drive the plotter directly?

## Ways of plotting
https://plotify2d.com/blog/4-ways-to-generate-a-plottable-svg-from-a-raster-image

## SOP to SVG
https://github.com/raganmd/touchdesigner-sop-to-svg

## on the SVG TOP
https://matthewragan.com/2016/02/10/the-mysterious-svg-top-touchdesigner/

### steps
1) decrease noise, increase brightness (important elements) / edge?
2) trace, transform etc
3) sop to svg
4) print



---
# Libs

Uses TD-PIP for external python
https://olib.amb-service.net/component/td-pip

TD-PIP is then used to install svgwrite with
*op('td_pip').Import_Module("svgwrite", pip_name = "svgwrite")*

SOP to SVG is then used to generate a SVG for printing
https://github.com/raganmd/touchdesigner-sop-to-svg

