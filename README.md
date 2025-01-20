# Expo Image Component Error: Failed to Load Local Image

This repository demonstrates a common issue when using the `Image` component in Expo applications:  failure to load local images due to incorrect URI paths or asset management problems.

The `bug.js` file shows an example of code that produces this error.  The `bugSolution.js` file provides a corrected version.

## Problem

The `Image` component fails to display local images, throwing an error in the console. This might be due to:

* Incorrect file paths in the `uri` prop.
* Assets not properly configured in your Expo project.
* Issues with asynchronous loading of the image.

## Solution

The solution often involves ensuring the image is located in the correct directory (usually the `assets` folder) and that the path is accurate.  Proper error handling should also be added to catch potential URI failures.