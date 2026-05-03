# VIQRC-Fusion

A (best effort) collection of all the VIQRC-Legal Parts for Autodesk Fusion (neé Fusion 360).

## Release History & Roadmap

- v1.0.0 - 2025-12-15: Initial Public Release
- v1.1.0 - 2026-05-03: Added in Uncommon structural parts, Level Up elements, and pre-assembled Traction and Intake Wheels

## Folder Structure

The organization of parts here is reflective of the way we've organized parts at our home club. It should be fairly straightforward, but there are edge cases that could probably fit in several different places. Please search the repository using the name and/or part number found in the [VIQRC Legal Parts Appendix](https://content.vexrobotics.com/docs/25-26/viqrc-mix-and-match/documentation/legal-parts-rev21.pdf), [VIQRC Illegal Parts Appendix](https://content.vexrobotics.com/docs/25-26/viqrc-mix-and-match/documentation/illegal-parts-rev13.pdf), or the [VEX Robotics Website](https://vexrobotics.com) before reporting anything as missing (and know that apart from game elements, we're unlikely to include many if any illegal parts here).

- VIQRC Parts - A container to keep the top level of this repo clean and to ease importing a bit
  - Connectors - Parts for joining parts to other parts
    - Ball Links - Parts that interface using a ball and socket joint
    - Corner Beams - The right- and left-handed angled beams new in the last handfull of years
    - Corner Connectors - They all have at least one integrated pin and one hole
    - Pins
    - Standoffs
  - Electronics - If it's electrically-powered and isn't pneumatics-related, it's here
  - Game Elements - Fields & Scoring Objects from VIQRC games past and present
    - 2026-2027 - Level Up
    - 2025-2026 - Mix & Match
    - 2024-2025 - Rapid Relay
  - Motion - If it has a square hole, goes into a square hole, or is mostly used with those things, it's here
    - Accessories - Washers, spacers, shaft collars and all the other motion things that don't belong elsewhere
    - Gears
      - Flat Gears - Run-of-the-mill gears
      - Hybrid Gears - Gears that can be used as either flat or beveled gears
      - Special Gears - All other gears
    - Linear Motion - If it's meant to help things slide in a straight line (and isn't pneumatics related), it's here
    - Lock Structure - If it's got a square hole *and* regular round holes, it's here
    - Pulleys & Belts
    - Ratchets
    - Shafts
      - Metal
        - Capped Shafts
        - Motor Shafts
        - Plain Shafts
      - Plastic
        - Capped Shafts
        - Motor Shafts
        - Plain Shafts
    - Spools & Rope
    - Sprockets & Chain
    - Turntables
    - Wheels & Tires
  - Pneumatics
  - Structure
    - 1x Beams
    - 2x Beams
    - Angle Beams - If it has a bend and it's called a beam by VEX, it's here
    - Other (Common) - Common things that don't fit elsewhere: license plates, cable clips, PET sheets, etc.
    - Plates - 3x, 4x, 6x, 12x, 14x parts that VEX call "plates"
    - Uncommon - All the other VIQRC-legal parts. There's a lot of stuff in here from VEX retail and Hexbugs sets.

## Installation

1. Open the data panel in Fusion (usually on the left).
2. Navigate to or create a project where you want this collection to live.
3. Click the "Upload" button and select the "VIQRC Parts" folder.
4. Upload and wait for things to process.

## Part Collection Notes

- There are some models with filenames starting like 0_5 (a number, an underscore, another number). These are mostly parts that had a period character in their original names because Fusion cut off everything after the first dot so that "
2.5x Pitch Capped Shaft (228-2500-2220)" turned into "2". It is, as of writing, the year 2025 and I'm using Fusion on a UNIX OS (macOS) where periods have never mattered like they did in DOS/Windows, and even Windows knows that there can be more than one period in a filename! *Dismounts soapbox...*
- For parts that are more assemblies rather than discrete parts, I've got a few different versions:
  - For the Omni Wheels, there are 4 total versions: one where it's a single rigid group and one where the rollers are fully jointed, and then each of those both with and without the Center Lock Beam and its 1x1 pins and shaft collar (because I basically never use an omni wheel without the Center Lock Beam).
  - For each pneumatic cylinders there are 3 versions: one with a jointed & movable rod/head, one that's fixed in the retracted position, and one that's fixed in the extended position.
- I have not been able to find models for the 1x6 and 1x8 Linear Motion Beams (Under `Motion > Linear Motion`).
- I've included some potentially duplicate models for completeness, including:
  - Parts with "weak" versions that generally don't have cosmetic differences to the standard variant.
  - Parts (like the 3x3 Wye Lock Beam in `Motion > Lock Structure`) where there are two part numbers listed for what appears to be a single, un-changed part.

----

This work is licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) based on original and transformative effort. Original models Copyright VEX Robotics, Inc.

[Disclaimer](https://kb.vex.com/hc/en-us/articles/360044338912-CAD-Resources-for-VEX-IQ): VEX IQ CAD models and 3D printing specifications are made freely available for personal and educational use. Commercial use of 3D printed VEX IQ parts is strictly prohibited. Using custom components on a VEX IQ robot design has the potential to cause unexpected behavior for which VEX Robotics is not responsible. Parts created using 3D printing technology are not eligible for use in the VEX IQ Robotics Competition.
