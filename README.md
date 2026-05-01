# BER Prediction in Dual-Hop UWOC System

## Overview
This project uses Machine Learning to predict Bit Error Rate (BER) in a dual-hop Underwater Optical Wireless Communication (UWOC) system using Random Forest Regression.

---

## Features
- BER prediction from channel parameters
- Handles underwater effects (SNR, bubble, water type, fading coefficients)
- Data-driven modeling approach
- Visualization of Actual vs Predicted BER

---

## Machine Learning Model
- Random Forest Regressor
- Train-Test Split (80/20)
- Evaluation using:
  - Mean Squared Error (MSE)
  - R² Score

---

## Input Features
- SNR
- Bubble effect
- Water type (fresh/salty)
- Channel fading parameters (\omega, \lambda, a,b,c etc.)

---

## Output
- Predicted BER values
- Comparison graph (Actual vs Predicted BER)
