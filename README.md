# 👁️ Iris Detection System

## Introduction
The Iris Detection System is a biometric identification project that uses the unique patterns of the human iris to identify individuals. Since every person's iris pattern is unique and stable throughout life, iris recognition is considered one of the most reliable biometric authentication methods.

This project demonstrates how iris images can be processed to detect and analyze iris patterns for secure identification.

---

## Objective
The objective of this project is to understand the working of an iris recognition system and implement the main stages involved in iris detection.

The project focuses on:
- Image Acquisition
- Iris Localization
- Feature Extraction
- Matching and Authentication

---

## How Iris Recognition Works
Iris recognition works based on the uniqueness of iris patterns.

Key characteristics:
- Every iris pattern is unique
- Iris patterns remain stable throughout life
- The iris is protected behind the cornea, making it difficult to alter

Because of these features, iris recognition is more secure than passwords or PINs.

---

## Algorithm Used

### Daugman's Algorithm

This project uses Daugman's Algorithm for iris detection and recognition.

Steps involved:

1. Segmentation  
   Detect the iris and pupil boundaries from the eye image.

2. Normalization  
   Convert the circular iris region into a rectangular format using the rubber sheet model.

3. Feature Extraction  
   Extract unique texture features from the iris pattern.

4. Matching  
   Compare the extracted iris code with stored iris templates to identify the person.

---

## Dataset

The project uses the CASIA Iris Thousand dataset.

Dataset details:

- Around 20,000 iris images
- Images collected from about 1,000 individuals
- Near-infrared iris images
- High quality and commonly used in biometric research

---

## Methodology

### Step 1: Input Image
Eye images are taken from the dataset.

### Step 2: Preprocessing
- Convert images to grayscale
- Reduce noise
- Enhance iris region

### Step 3: Iris Detection
Detect the iris and pupil boundaries.

### Step 4: Feature Extraction
Extract unique iris texture features.

### Step 5: Matching
Compare extracted features with stored iris templates.

---

## Applications

Iris detection systems are widely used in:

- Airport security
- Military access control
- Banking authentication
- Healthcare patient identification
- Law enforcement identification systems

---

## Advantages

- High accuracy
- Non-contact biometric system
- Fast authentication
- Stable iris patterns over time

---

## Challenges

- Lighting conditions affecting images
- Reflections or occlusions (eyelids, eyelashes)
- Privacy concerns regarding biometric data
- High implementation cost

---

## Future Improvements

Possible improvements include:

- Deep learning based iris recognition
- Improved segmentation algorithms
- Multi-modal biometrics (iris + face recognition)
- Real-time iris detection systems

---

## Project Structure
