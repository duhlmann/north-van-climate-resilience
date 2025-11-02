# North Vancouver Climate Resilience Score

**Goal:**  
Score every neighbourhood in the City and District of North Vancouver on climate resilience, using open data and a transparent scoring system. The final results will be shown on an interactive Streamlit dashboard with maps, rankings, and recommendations.

## What contributes to "climate resilience"?
- Heat exposure (tree canopy, cooling spaces, surface temperature)
- Flood and landslide risk
- Wildfire interface exposure
- Social vulnerability (seniors, low income, housing type)
- Park and green space access

## Project Structure
- **data/raw/**  
  Original downloaded files (from municipal open data + StatsCan)
- **data/processed/**  
  Cleaned and merged datasets used for analysis
- **notebooks/**  
  Jupyter or Colab notebooks for cleaning, scoring, and visualization
- **app/**  
  Streamlit dashboard code
- **docs/**  
  Images, screenshots, project explanation

## High-Level Steps
1. Gather open data for the City + District of North Vancouver
2. Clean and merge by neighbourhood
3. Create scoring indicators (heat, flood, social vulnerability, etc.)
4. Build a resilience score (0–100)
5. Visualize results with maps and charts
6. Publish Streamlit dashboard

*Status:* Project setup ✅
