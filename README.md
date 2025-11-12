# 🎵 Spotify Hit Predictor

Machine learning project that predicts song popularity using Spotify audio features.

## 📊 Overview

- **Binary Classification**: Predicts hit songs (top 25% popularity)
- **Dataset**: 114,000+ Spotify tracks
- **Model**: Logistic Regression with class balancing
- **Accuracy**: 56% (vs 50% baseline)

## 🔍 Key Insights

**Top Predictors of Hit Songs:**
1. **Loudness** (+23% impact)
2. **Acousticness** (-19% impact) 
3. **Energy** (+15% impact)

## 🚀 Quick Start

```bash
cd spotify-hit-predictor
pip install -r requirements.txt
jupyter notebook spotify_analysis.ipynb
