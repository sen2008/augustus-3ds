# Augustus for New 3DS

A port of Augustus (the enhanced Julius fork — a Caesar III engine
reimplementation) to the New Nintendo 3DS.

## Install

1. Scan the QR code (in the repo / project notes) with FBI, or download
   `augustus.cia` and install it with FBI.
2. Copy your Caesar III game files into `3ds/augustus/` on the SD card
   root (the engine reads its data from `sdmc:/3ds/augustus/`).
   Game data is not included in this repo.

## Notes

- New 3DS only: the build uses the extended-memory mode (178 MB),
  804 MHz CPU and L2 cache.
- The UI renders at 640x480 logical and is downscaled to the 400x240
  top screen.
