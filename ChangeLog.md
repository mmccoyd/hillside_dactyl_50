# Change Log for the Hillside Dactyl 50 body

## v0.1.0-alpha.3

Better display position and mounting, LED hole, wall grills not open panels.

### Known issues

-   Fully screwing in the display screw pushes up a small bump in the case top
    around the display.
-   The USB holes work with the cables I have,
    but the split one may be too deep for some cables and the rear is inelegant.

### Changes

Breaking change (with respect to the shield)

This moves the bottom LED and LED switch holes to reflect changes made by the
0.1.0-alpha.3 shield. Using the bottom LEDs of an alpha.2 shield would require
cutting some extra holes in the alpha.3 body bottom plate.

The major changes are fixing display mounting and adding a bare LED mount hole.

-   Display
    -   Tilt sideways 10° for visibility and interior mounting space
    -   Move down to not bump up from index home row
-   Display socket
    -   Notch on outside wall for securing display
    -   Four holes for securing display, away from central components
    -   Wider margin before outside wall, though may shorten later
-   Wall
    -   LED hole, round with a slot/open viewing or secondary hole.
    -   Hole grills on the flat areas, instead of open panels.
    -   Smoother front bottom edge and thumb-keywell transition.
-   Key switch socket
    -   Tighter clip-in. Chamfer height reduced to 0.3 mm from 0.5 mm.
-   MCU corner
    -   Rear USB-C hole smaller inner hole, with generous outer hole
        -   Inner: 5 mm tall, 9 mm straight top part
        -   Outer: 9 mm tall, 17 mm wide, 1 mm corners, 2.5 mm recessed
            for the plug's plastic part
        -   (Before that, tested it with -2 mm width and height from alpha.2,
            but plastic plug didn't fit.)
    -   Screw hole for bottom plate moved away from PCB for install clearance.
    -   Taller corner column to strengthen body after putting bigger holes in
        the MCU corner walls.
-   Screw heat insert
    -   Loosen diameter back to 4.1 mm from 4.0 mm.
-   Bottom plate
    -   LED holes moved to the new alpha.3 shield positions
    -   Screw recess add .3 mm depth
    -   Magnetic recess add .1 mm depth to .5 mm.
    -   Grid hole spacing 3.3 mm to avoid thin wall warnings.
-   Neither keywell nor thumb cluster layout changes.
-   Thumbs: reduce the extra front lip


## v0.1.0-alpha.2

Tighter thumb cluster, recess for magnetic mount, reset switch on back.
Not released.

### Known issues

-   Display takes cutting into the wall a little to mount.
-   Base screws stick out a hair.

### Big picture changes

Case

-   Thumb cluster tighter
    -   The reach and center keys are in a grid to be closer, not an arc.
    -   Upper 0.2 mm back, not 1 mm; but still 3 mm up, 10° forward.
    -   Still
        -   10° splay from the single tucked key to the main four
        -   Side caps 5° inward
-   Fit
    -   Thumbs a little higher above key well plane, about 2 mm
    -   Pinkie splay reduced to 1.5° (from 3°)
-   Tented height lowered by moving pinkie case edge inward by 3.5 mm at bottom
-   Wall shroud around keycaps higher
    -   Up 3 mm, to 8 mm from 5 mm
    -   Index column and upper thumb shrouds
-   USB rear has room for 90° plug and cable
    -   Push MCU wall back 3 mm.
    -   Tighten back wall on middle and ring, gaining 1.8 mm
-   MCU corner
    -   Has support shelf for bottom plate in the corner
    -   Wall slants from rear to front instead of straight forward then out
    -   Corner and PCB moved 4 mm inward to give split-USB cable more room
-   Wall magnet mounting holes for a laptop hook or uni-body bridge.
-   Screw insert inside diameter reduced to 4.0 mm from 4.1 mm.
-   Switch socket
    -   Clip-in tighter with chamfer reduced to 0.5 mm from 0.6 mm.
    -   Pushes PCB .36 mm further down for Mill-Max socket lip
-   Bottom plate recess for phone mag mount.
-   Edge on front is softer
    -   Extend middle column's lower guard down
    -   Move lower screw inward and toward the back

Shield

-   USB split uses crossed UART TX/RX data lines
-   Reset is on back for easier grip, and power on side, swapping locations.

### Inner detail changes

-   Column end cap sketches protect key caps and transition to down


## v0.1.0-alpha.1

The original. It worked well but could be improved. Not released.

Alpha.1's thumb cluster setup:

-  Cluster displacements:
    -   5 mm down, 12 mm over to center side edge of tucked
-   Column splay : key well vertical : 10° : tuck : 13 : middle : 15 : reach
-   Tilt: sides 5° inward, upper 10° forward
-   Upper center and side: 3 mm up, 1 mm back
