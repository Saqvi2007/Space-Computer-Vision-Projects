# Project 1: Vision-Based Robot Navigation for Planetary Rovers

## Problem Statement
Autonomous Mars/Lunar rovers require visual navigation to estimate position and movement across unknown planetary terrains without GPS.

## Objective
Implement Feature Detection and Keypoint Matching (ORB Visual Odometry) to track surface features across sequential rover images.

## Dataset
- **Source:** Martian/Lunar Crater Detection Dataset
- **Format:** Grayscale crater images (`frame_00.jpg`, `frame_01.jpg`)

## Methodology
1. Convert input images to Grayscale.
2. Extract invariant features using ORB algorithm.
3. Match descriptors across frames using Brute-Force Matcher.

## Tools & Libraries
- Python 3
- OpenCV (`cv2`)
- NumPy

## Results
- Successfully tracked crater surface features across consecutive navigation frames.
- Output visualization saved in `outputs/matched_craters.png`.
- Keypoints detected: 1000 per frame.
- Total matches found: 279.