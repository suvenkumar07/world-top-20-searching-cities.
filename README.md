# world-top-20-searching-cities.
# City Visitors Interactive Map Visualization

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Folium](https://img.shields.io/badge/Folium-0.14.0-green)
![Google Colab](https://img.shields.io/badge/Platform-Google_Colab-orange)

An interactive map visualization displaying the top 20 most visited cities worldwide, featuring color-coded markers and an informative legend. Built with Python and Folium, optimized for Google Colab.

## Features

- 🎨 **Color-coded Markers** by rank category:
  - Red: Ranks 1-5
  - Blue: Ranks 6-10
  - Green: Ranks 11-15
  - Purple: Ranks 16-20
- 📍 Interactive markers with popup information:
  - City name
  - Global rank
  - Visitor statistics
- 🗺️ Persistent legend with category explanations
- 🌍 Responsive base map with multiple zoom levels
- 💾 Self-contained HTML export capability

## Requirements

- Google Colab account (free)
- Python 3.8+
- Required packages:
  - `folium`
  - `pandas`
  - `branca`

## Installation & Setup

1. **Open Google Colab**:
   - Create new notebook: `File > New notebook`

2. **Install Dependencies**:
   ```python
   !pip install folium pandas
