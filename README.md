# SmartPark – Parking Occupancy Detector

Computer vision project for detecting occupied and available parking spaces.

## Team Members
Kerry Walker

## Project Tier
Originally proposed as Tier 1 – Core using YOLO11. The final implementation uses OpenCV and Canny edge detection.

## Problem Statement
Drivers often spend unnecessary time searching for available parking spaces in crowded parking lots. SmartPark aims to help drivers and parking lot operators identify available parking spaces more efficiently.

## Solution Overview
SmartPark analyzes overhead parking lot images and classifies manually mapped parking spaces as occupied or available using computer vision.

## Technical Approach
- CV Technique: Edge detection and image processing
- Algorithm: Canny edge detection
- Library: OpenCV
- Programming Language: Python
- Development Environment: Google Colab
- Parking Space Mapping: Rectangular coordinates

## Dataset
- Two overhead parking lot images
- Image 1: 51 parking spaces
- Image 2: 28 parking spaces
- Total: 79 parking spaces
- Labels: Occupied and available
- Original image sources and usage permissions require verification.

## Success Metrics
- Target accuracy: At least 85%
- Image 1 accuracy: 90.20%
- Image 2 accuracy: 100.00%
- Combined accuracy: 93.67%
- Correct classifications: 74 out of 79
- Incorrect classifications: 5 out of 79
- Processing speed target: Under 2 seconds per image
- Processing speed result: Not yet verified

The project exceeded its accuracy target on the two evaluated images.

## Repository Structure
- data/ – Dataset documentation
- docs/ – Project documentation and AI usage log
- notebooks/ – Project notebook
- results/ – Detection images and accuracy results

## Resources
- Google Colab
- Python
- OpenCV
- GitHub

## Risks and Mitigation

| Risk | Mitigation |
|---|---|
| Incorrect occupancy classification | Adjust detection thresholds |
| Shadows and lighting variations | Improve image preprocessing |
| Incorrect parking space mapping | Review and adjust coordinates |
| Limited dataset | Evaluate additional parking lot images |

## Demo Video
To be added.

## AI Usage Log
See docs/AI_usage_log.md.

## Current Status
- [x] Repository created
- [x] Working implementation
- [x] System tested on project data
- [x] Accuracy measured
- [x] Results uploaded
- [ ] Demo video added
- [ ] Final project submitted
