# YouTube Video View Predictor

An interactive, AI-powered tool that estimates the number of views a YouTube video might receive based on its title, metadata, and engagement metrics.

## Overview

With millions of videos published daily, it's difficult to predict what will gain traction. This project helps content creators and analysts understand the early view potential of a video—before it's even published.

## What It Does

- Predicts expected views using a combination of:
  - Video title (via TF-IDF keyword extraction)
  - Likes and comment count
  - Category and upload hour
- Outputs a **Virality Score**: Low / Medium / High
- Allows real-time testing of both custom and real YouTube titles
- Built entirely in Google Colab — no file uploads, no API keys required

## Business Relevance

**For Content Creators and Brands**
- Forecast content success before launch
- Improve title and metadata strategy
- Prioritize content ideas with higher projected reach

**For Agencies and Platforms**
- Pre-screen videos for promotion or paid media
- Automate early-stage content evaluation
- Benchmark creative ideas based on historical performance

## Features

| Component         | Description                                 |
|------------------|---------------------------------------------|
| Data Source       | YouTube Trending Videos (Kaggle)            |
| Model             | Random Forest Regressor                     |
| NLP Technique     | TF-IDF on video titles                      |
| Input Parameters  | Title, Likes, Comments, Category, Hour      |
| Output            | Predicted View Count + Virality Score       |
| Interface         | Google Colab + ipywidgets                   |
| Visualization     | Feature Importance Breakdown                |

## How to Use

1. Open the notebook in Google Colab.
2. Run all cells to initialize.



