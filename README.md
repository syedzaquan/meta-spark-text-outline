# Meta Spark Text Outline
Since Meta Spark does not offer the capability to directly apply outlines to 2D Text components, I have implemented a workaround by incorporating an outline through a render pass.

## Requirements:
1. Sobel Filter Patch
2. Tritone Color Patch

## Scene
Before we begin, make sure you have the following object in the scene:
- Face Tracker
	- 3D Text (z-index scale: 0)
	- Canvas
		- Rectangle (Full width, full height)
