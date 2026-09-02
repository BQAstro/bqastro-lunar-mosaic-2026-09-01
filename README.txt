BQAstro Lunar Globe — v4.0.34

MOBILE LUNAR FEATURES PANEL
- Reduced the Lunar Features panel width on phones to a compact right-side drawer.
- Reorganized panel controls vertically on mobile.
- Kept buttons at a finger-friendly minimum height.
- Added vertical scrolling inside the panel instead of letting it occupy half the screen.
- Preserved safe-area and visual-viewport handling from v4.0.25.


v4.0.33
- Restored Lunar Features panel to the left/top inside the webpage.
- Added a drag handle so the Features panel can be repositioned with mouse or touch.
- Dragging is constrained to the visible viewport so the panel cannot be moved off-screen.
- Minimize behavior still affects only the panel UI; Moon feature labels remain visible.


v4.0.33
- Lunar Features panel now opens by default at the bottom-right.
- Fixed overlap/clipping between the drag handle and expand button when minimized.
- Added extra collapsed-panel padding so both controls remain fully separated and touchable.
- Dragging remains enabled and constrained to the visible viewport.


v4.0.33
- Fixed clipping of the move and expand controls in the minimized Lunar Features pill.
- Root cause: the controls are absolutely positioned, so their 30 px height did not contribute to the minimized panel's own height.
- Reduced both minimized controls to 24 × 24 px.
- Added an explicit minimized panel minimum height and true vertical centering.


v4.0.33
- Adds a complete global LRO Reference layer from four user-exported LROC WAC tiles.
- Adds Layers panel with independent BQAstro Photo, LRO Reference, and Photo Boundary switches.
- BQAstro photo takes priority where its georeferenced texture has coverage.
- LRO fills the remainder when enabled and can be viewed alone for direct comparison.
- Boundary marks the geographic edge of the BQAstro texture coverage.
- LRO source: USGS/ASU LROC WAC Global Morphology Mosaic 100m, June 2013.


v4.0.34
- Added a persistent live Viewing Layer title card.
- Title card automatically shows Both, BQAstro Photo, LRO Reference, or No imagery as layer switches change.
- Extended the latitude/longitude grid across the complete 360° lunar globe, so the same grid appears on the farside when the Moon is rotated.
- Preserved all v4.0.33 LRO/BQAstro layer controls and existing viewer features.
