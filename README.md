# Ray_Tracing_Engine
Implemented a GPU accelerated Ray Tracer in CUDA C++ which can simulate effect of light on different shapes and materials.
like dielectric, metal and Lambertian and is able to produce videos of moving objects 12.7x faster than its CPU based counterpart.

This is a CUDA based Ray Tracing Engine.

Usage

Clone this repo and run make to compile. Use ffmpeg to compile the frames.

Current Capabilities

The engine can currently be used to simulate geometric objects with material types like Lambertian, metal, dielectric and diffuse light.

Requirements
Ensure CUDA toolkit 11.1 is used for compilation.

Motivation
Im creating this project to get more familiar with ray-tracing.

Reference
Peter Shirley's Ray Tracing Guide
