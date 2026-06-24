# ROXA ( DriveSkills: AI-Based Driving Evaluation System)🚗 
[Open Project](https://roxa.vercel.app/)
[DEMO](https://www.youtube.com/watch?v=tsPAnppxqkI)
## Overview

DriveSkills is a web-based intelligent platform designed to support the evaluation of practical driving license examinations using Artificial Intelligence, Computer Vision, and Deep Learning technologies.

The system analyzes driving test videos and assists examiners by providing objective, evidence-based assessments of a candidate's driving performance. Instead of replacing the human examiner, DriveSkills acts as a decision-support system that improves consistency, transparency, and fairness during practical driving evaluations.

---

## Problem Statement

Traditional practical driving examinations depend heavily on human observation. Although experienced examiners play an essential role, the evaluation process may be affected by:

* Subjective judgments
* Examiner fatigue
* Inconsistent scoring
* Limited observation capabilities
* Differences in interpretation between examiners

As a result, candidates with similar driving performance may receive different evaluations.

DriveSkills addresses these challenges by integrating AI-based video analysis with human evaluation.

---

## Features

### Road Analysis API

Analyzes the road environment and evaluates:

* Lane keeping
* Traffic sign recognition
* Vehicle detection
* Pedestrian detection
* Traffic light detection
* Safe driving behavior
* Road awareness

---

###  Parking Evaluation API

Evaluates parking performance by analyzing:

* Parking alignment
* Vehicle position
* Parking cone detection
* Parking accuracy
* Parking completion

---

###  Driver Monitoring API

Monitors driver behavior and safety compliance:

* Seatbelt detection
* Driver attention monitoring
* Head movement analysis
* Driver behavior assessment

---

### Examiner Dashboard

* Manual score entry for evaluation criteria not covered by AI.
* Review of AI-generated scores.
* Video evidence support.
* Final score calculation.

---

### Candidate Dashboard

* View examination results.
* Display detailed score breakdown.
* Access final evaluation report.

---

## Scoring System

| Component                 | Marks |
| ------------------------- | ----- |
| AI Evaluation             | 65    |
| Human Examiner Evaluation | 35    |
| Total                     | 100   |

The final score is automatically calculated and stored in the database.

---

## System Architecture

DriveSkills consists of four major components:

1. Frontend Web Application
2. Backend API Service
3. AI Models hosted on Hugging Face Spaces
4. Supabase PostgreSQL Database

### AI Services

* Road Analysis API
* Parking Evaluation API
* Driver Monitoring API

---

## Technologies Used

### Frontend

* HTML
* CSS
* JavaScript
* Bootstrap

### Backend

* Python
* Flask / FastAPI

### Artificial Intelligence

* OpenCV
* YOLO
* Deep Learning Models
* Computer Vision

### Database

* Supabase PostgreSQL

### Deployment

* Hugging Face Spaces
* GitHub

---

## Workflow

1. Examiner uploads driving test videos.
2. Videos are sent to AI APIs.
3. AI models analyze the videos.
4. Scores are generated automatically.
5. Examiner enters remaining marks.
6. Final score is calculated.
7. Results are stored in Supabase.
8. Candidate can view the final report.

---

## Project Objectives

* Improve fairness in driving examinations.
* Reduce subjectivity in evaluations.
* Provide evidence-based scoring.
* Digitize examination records.
* Support examiners with intelligent tools.
* Increase transparency and consistency.

---

## Future Improvements

* Real-time video analysis.
* Mobile application support.
* Advanced driver behavior analytics.
* Arabic and English interfaces.
* Integration with governmental licensing systems.
* Automatic report generation.

---

## Authors

**Sadeen Mahmoud Abu Khadra**
Data Science and Artificial Intelligence Student
Jordan University of Science and Technology

---

## License

This project is developed for educational and research purposes.
