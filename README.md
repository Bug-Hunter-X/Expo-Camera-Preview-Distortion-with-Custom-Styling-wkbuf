# Expo Camera Preview Distortion Bug

This repository demonstrates a bug in Expo's Camera component where custom styling can lead to preview image distortion. The issue primarily affects devices with varying aspect ratios, resulting in stretched or incorrectly sized previews.  The `bug.js` file showcases the problem, while `solution.js` provides a corrected implementation.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the app on different devices or emulators.
4. Observe the distortion in the camera preview (bug.js).
5. Compare the corrected preview in solution.js

## Solution

The solution involves careful management of the aspect ratio and dimensions of both the Camera component and its parent container. Using `flex` and `aspectRatio` properties effectively prevents distortion.