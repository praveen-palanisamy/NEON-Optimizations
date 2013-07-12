NEON-Optimizations
==================

NEON optimized image processing/ Computer vision algorithms.

####What's the need when FastCV is around?
NVIDIA and Itseez decided to create a Tegra-optimized version of OpenCV , which is available as a pre built library for
smartphone application developers. But FastCV is not an open source project unlike OpenCV and also it's aimed mainly at 
Android and the support is only available on windows platform.

####So, what's my Idea?

I would like to make real time image processing possible with embedded processors mainly the recent ARM based SOCs. OpenCV
is available on all embedded platforms (linux, android) but it's not optimized for SIMD on ARM processors like how
it is for Intel processors (using SSE). For this reason i would like to contribute to make an ARM optimized computer vision
library available either by optimizing the existing OpenCV libraries or by creating a new one, an Open Embedded CV library
Though this project seems to be too ambitious, i guess i'll get hands from people around willing to contribute.
