# RackFrame2D

RackFrame2D is a browser-based 2D elastic frame solver for steel rack frames with welded cantilever arms and configurable support conditions.

## Live app

- GitHub Pages: https://captain-802.github.io/rack/
- Google Sites RackFrame2D page: https://sites.google.com/view/ahmadfayaz/rackframe2d

The original Google Sites RACK page remains the separate legacy rack software: https://sites.google.com/view/ahmadfayaz/rack

## Features

- 2D direct-stiffness frame analysis with 3 DOF per node.
- Fixed welded arm-to-column connections.
- Explicit arm schedule rows for adding more cantilever beams on the column.
- Bottom member end releases for hinged beam-column and beam-support ends.
- Orange release markers in the model view for bottom-member connection hinges.
- Configurable fixed, pin, and roller supports.
- Sway and arm-tip deflection output.
- Interpolated column deflection query at any height along the column.
- Support reactions, member end forces, shear-force data, and bending-moment data.
- Frame3DD-style export and JSON result export.
- UK steel section catalogue imported from local UB, UC, PFC, RHS, and SHS files.

## Files

- `index.html` - the RackFrame2D application.
- `rack-section-catalog.js` - generated steel section catalogue used by the section selectors.

## Engineering note

This is an elastic analysis/design aid. Final rack design should still be checked by a competent structural engineer against the applicable standard, load combinations, connection design, local buckling, lateral torsional buckling, welds, base anchorage, and serviceability limits.
