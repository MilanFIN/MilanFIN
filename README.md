Hi,

I work as a software developer mostly on embedded stuff. This page is only for hobby projects.

I've written a bunch of Gameboy & Gameboy Advance games. Those can be found at eg. [itch](https://milanfin.itch.io/)

The onther kind of interesting thing I've worked on with this account is binpacking. It's an NP-hard problem, so the solvers leave some room for some interesting trickery. 

This account has a repo for a reference java implementation of a 3d binpacker that utilizes multiple packing algorithms in addition to a genetic algorithm to attempt finding a decent solution within set parameters. It has some cool tricks like OpenCL based GPU acceleration and packing order mutation tricks such as the ability to preserve the best bin of a packing result for future generations.

I'm working on a wasm demo for this using Rust and WebGPU, but it's still in relatively rough shape.
