# blackhole-Schwarzschild-
a Schwarzschild black hole, showing how light bends around it and how orbiting objects precess. It uses only NumPy, SciPy, and Matplotlib.

1. Light bending: it traces rays past a Schwarzschild black hole. Rays with an impact parameter below about 5.2 M fall in, and the rest curve around it.

2. Orbit precession: it follows a particle orbiting the black hole, and the orbit's ellipse rotates a little each lap. This is the relativistic effect behind Mercury's orbit.

How it works: for every pixel we shoot a light ray backwards from the camera. Gravity bends the ray; we follow it until it (a) falls into the horizon (black pixel), (b) crosses the accretion disk (glowing pixel, with Doppler brightening so one side of the disk looks brighter), or (c) escapes to the starfield.

Units: G = c = M = 1 (horizon at r = 2, disk from r = 6 to 18).
