# The 3D Printer That Fits in a Billy: Solving Space Constraints in a small apartment

## Introduction
The struggle to balance my passion for 3D printing with the limited square footage of my apartment led to an innovative solution that maximized space and seamlessly integrated into my living environment. It all began with one of my favorite hobbies—3D printing. However, the constant battle for space in my apartment left me searching for a way to accommodate a 3D printer without sacrificing precious room. That’s when inspiration struck: I decided to design a 3D printer that would perfectly fit into one of the most ubiquitous pieces of furniture—the Ikea Billy bookcase.

## History
In 2016, I bought a Chinese 3D printer kit. After printing several upgrades, it transformed into a solid, albeit not very fast, machine with a 200x300x200 mm build volume. This size was sufficient for most of my projects. However, in 2020, with the arrival of a new family member, I lost my hobby room in our apartment, and finding space to store the printer became impossible. During the pandemic, it found a temporary home in the living area, where it printed face mask components to help meet the high demand.

## The Initial Solution
My initial solution was to design and create a small 3D-printed 3D printer that could be neatly stored in an Ikea Billy bookcase when not in use. This allowed me to disassemble and store my old, larger printer. While this compact printer, with its 10x10x10 cm build volume, was ingenious in terms of space-saving, its limited size made it suitable only for smaller projects.

## The Need for a Larger Solution
As time went on, I found myself needing to print larger items, some even exceeding the capacity of my original printer. This led me to design and build a new printer with specific characteristics: it had to fit in a Billy bookcase, reuse material from my old printer, have a minimum build volume of 200x400x200 mm, require minimal cabinet space, be corexy and Klipper-based, and feature a direct drive instead of a Bowden setup.

## The Innovative Design
The design I came up with is a fixed bed, moving/flying gantry core xy printer with an impressive build volume of 500x200x400 mm. The power supply and electronics are neatly located under the heated bed, which can be hinged like the hood of a car or easily removed by disconnecting just two connectors. With the bed fixed, the build volume can be utilized to store my small printer, resin printer, and filament dryer when not in use. This clever design means that the net space it occupies when not in use is just 10 cm from the bottom, 5 cm on each side, and 4 cm from the top of the cabinet.

## The Main Structural Elements
The main structural elements of my design are 2020 aluminum profiles, most of which are standard lengths to keep costs down and make sourcing easier. The bed is composed of two MK3S 200x280 aluminum beds, one of which came from my old printer. I created slicer profiles to use and heat the left, right, or both beds depending on the size of the object to be printed.

The gantry is upheld by four threaded rods connected to four stepper motors, allowing me to take advantage of the four-corner leveling built into Klipper. I opted to use linear rails for all axes: four MGN9 rails for the Z axis, two MGN9 rails for the Y axis, and one MGN12 rail for the X axis. This setup allows me to use toolheads designed for the VORON, although I am currently using a Chinese Ender 3 upgrade part. All printed parts were small enough to print on my mini printer, though many parts were later reprinted on the new printer to strengthen some components or redesign them for better clearance.

## Sharing the Design
After printing more than 20 kg of material over the last six months, I believe the design is solid enough to share with the community. I hope it can help others who, like me, love 3D printing but lack space for a typical 3D printer. I'm currently uploading the design files and instructions to my GitHub: [https://github.com/rjacobs1969/Fabricator/Build/Frame/BOM.md](https://github.com/rjacobs1969/Fabricator/Build/Frame/BOM.md).
