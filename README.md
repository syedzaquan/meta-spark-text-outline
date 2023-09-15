
# Meta Spark Text Outline
Since Meta Spark does not offer the capability to directly apply outlines to 2D Text components, I have implemented a workaround by incorporating an outline through a render pass.

## Example:
![example](https://github.com/syedzaquan/meta-spark-text-outline/assets/47650227/eed4934d-28f3-4d19-b3df-e4ba102ea843)

## Overview:
![overview](https://github.com/syedzaquan/meta-spark-text-outline/assets/47650227/261a4942-c503-4f7e-b398-9db7f3b0d814)


## Requirements:
1. Sobel Filter Patch
2. Tritone Color Patch

## Scene
Before we begin, make sure you have the following object in the scene:

└─── Face Tracker<br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;├───3D Text (z-index scale: 0) <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└───Canvas <br />
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;└───Rectangle (Full width, full height)
