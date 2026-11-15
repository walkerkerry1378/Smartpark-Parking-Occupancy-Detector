# Smartpark-Parking-Occupancy-Detector
Computer Vision project for detecting occupied and available parking spaces

## Team Members
Kerry Walker

## Project Tier
Tier 1 - Core
SmartPark uses one pretrained YOLO11 model to detect vehicles and determine parking availability.

## Problem Statement
Drivers often spend unnecessary time searching for available parking spaces in crowded parking lots. This can cause frustration and contribute to traffic congestion. SmartPark aims to help drives and parking lot operators identify available parking spaces more efficently.

## Solution Overview
SmartPark will use YOLO11 object detection to identify vehicles in parking lot images. The system will compare detected vehicles with parking-space location to determine which spaces are occupied or available. The results will show parking availability to help users find open spaces.

## Technical Approach

- CV Technique: Object Detection
- Model Architecture: Convolutional Neural Network
- Model: YOLO11
- How I Will Use It: Pretrained model
- Framework: Ultralytics and PyTorch
- Programming Language: Python

Why This Approach:
YOLO11 can detect vehicles in parking lot images.
I selected it because I used YOLO11 in Lab 6 and
am familiar with its object detection capabilities.


## Dataset

- Name: PKLot Parking Lot Dataset
- Source: Federal University of Paraná, Brazil
- Size: 12,417 parking lot images
- Labels: Occupied and vacant parking spaces
- Link: https://web.inf.ufpr.br/vri/databases/parking-lot-database/


## Success Metrics

- Primary Metric: Parking-space occupancy accuracy
- Target: At least 85% accuracy
- Secondary Metric: Image processing speed
- Target: Under 2 seconds per image


## Milestone Plan

- Week 10: Blueprint submitted
- Week 11: First working demonstration using YOLO11
- Weeks 12–13: Add parking lot data and occupancy logic
- Week 14: Test accuracy and processing speed
- Week 15: Complete final demonstration and presentation


## Resources

- Compute: Google Colab
- Programming Language: Python
- Model: YOLO11
- Cost: $0


## Risks and Mitigation

| Risk | Probability | Plan B |
|---|---|---|
| YOLO11 misses vehicles | Medium | Test confidence thresholds and review incorrect detections |
| Incorrect parking-space occupancy results | Medium | Review predictions and adjust parking-space comparison logic |


## Demo Video

To be added for the final project.


## AI Usage Log

See docs/AI_usage_log.md


## Current Status

- [x] Repository created
- [ ] Proposal submitted
- [ ] First working demo
- [ ] System works on project data
- [ ] Metrics measured
- [ ] Final submitted
