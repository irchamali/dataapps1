# Streamlit App Preview

Live preview: https://ircham1.streamlit.app/

## Overview

This repository hosts a Streamlit app demo with interactive plotting, mapping, and DataFrame exploration.

### Features
- Plotting examples (`pages/1_📈_Plotting_Demo.py`)
- Mapping examples (`pages/2_🌍_Mapping_Demo.py`)
- DataFrame examples (`pages/3_📊_DataFrame_Demo.py`)
- Simple starter script (`hello.py`)
- Uber pickups sample dataset demo (`uber_pickups.py`)

## Run locally

1. Create a virtual environment:

   ```bash
   python -m venv .venv
   source .venv/bin/activate
   ```
2. Install requirements:

   ```bash
   pip install streamlit
   ```
3. Start app:

   ```bash
   streamlit run hello.py
   ```
4. Or run specific page:

   ```bash
   streamlit run pages/1_📈_Plotting_Demo.py
   ```

## Deploy

- Deployed to Streamlit Community Cloud at: https://ircham1.streamlit.app/
- Push to GitHub and link with Streamlit Cloud for automatic deploys.

## Notes

- Works on macOS, Linux, Windows (with proper venv activation path).
- Update `requirements.txt` as needed for additional dependencies.
