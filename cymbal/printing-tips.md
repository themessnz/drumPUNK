# E-Drum Cymbal - Printing Tips
These are merely "suggestions" that may change in the future with learning and feedback. Using the appropriate material for each part may help ensure it lasts for more than a day getting smashed with wooden sticks over and over again...

## 3D Printing
### General
- I printed everything with a layer height of 0.2mm and a 0.4mm nozzle. I used 1.75mm dia, black filament of various materials (see below). 
- The cymbal body has a diameter of about 260mm. If you're reading this, I (or someone else) haven't made the cymbal body itself small printer friendly... But PrusaSlicer and other slicing tools these days have built-in tools to split the model and generate connectors for post-printing assembly. 

### `cymbal-mount-plug.3mf`
Material: TPU

This part provides a small flexible layer between the mounting equipment of the cymbal, to the `cymbal-body` itself, a slightly softer layer between the `cymbal-sensor-body`, and the `cymbal-body` for modest shock absorbtion, and the "dome" that sits pivots on the `cymbal-pole-mount`.

General:
- I printed with the concave surface face-down to minimise the support structures needed. TPU is pretty difficult to remove from itself...

### `cymbal-sensor-body.3mf`
Material: PLA

General:
- I printed this upside-down, as the side with the hollow for the electronics doesn't need to look nice. 
- This part doesn't have much direct load transferred to it, and is also in the "shade" being under the cymbal body, so PLA should be sufficient. 

### `cymbal-pole-mount.3mf`
Material: PLA (PETG may be a good alternative)

General:
- Remains to be seen if PLA is robust enough. It's going to be transferring the load from the cymbal to the mount pole. Ensuring there is minimal movement between the object and the mounting pole (e.g. using the correct sized pole, 8mm dia), should help.

### `cymbal-body.3mf`
Material: PETG

General:
- PETG (theoretically) provides a better chance at longevity due to its more flexible nature, and stability over time than PLA. 
- Printed with an infil of 20%, adaptive cubic (PrusaSlicer).
- No raft - printed directly on the print-bed, but I used painters tape arranged in a square so 4 edges of the circle would have great adhesion 
to the bed.
- Printed slowly and hot to ensure good layer adhesion, with minimal cooling (no cooling for the first 5 layers).

### `cymbal-shock-pad.3mf`
Material: TPU

General:
- I printed upside-down directly on the print bed. In other words, the bit that curles around the rim of the cymbal body was printed last.
