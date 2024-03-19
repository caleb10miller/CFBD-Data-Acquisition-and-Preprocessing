# CFBD-Data-Acquisition-and-Preprocessing

## Overview
This project centers on the collection and preprocessing of college football data from the 2022 season. Using the collegefootballdata.com API, we've gathered extensive game and team information, which we then preprocess into a format suitable for analytical purposes. The aim is to explore factors affecting game attendance and excitement, providing insights for sports administration and marketing.

## Team Members
- Caleb Miller: caleb10miller@gmail.com
- Muhammad Hazrat: mh3852@drexel.edu
- Hashim Afzal: ha695@drexel.edu

## Data Collection
Data was sourced from collegefootballdata.com, a comprehensive platform for college football stats. An API key facilitated access to detailed game statistics, player performance, and team data.

## Preprocessing Highlights
- **Formatting**: Converted timestamps into separate date and time variables.
- **Extraction**: Separated box scores for analysis and split team records into distinct columns.
- **Handling Missing Data**: Fields with missing 'Attendance' and 'Excitement Index' were identified as crucial and preserved for analysis.

## Dataset Structure
- GamesData.csv: Individual games, including scores, attendance, and excitement index.
- TeamsData.csv: Team-specific information, including season performance.

## Usage
The project is structured to support a wide range of analyses:

- Sports Analytics for trend analysis.
- Sports Administration for decision-making.
- Academic research on college sports' impact.

## How to Use the Data
- **Install Necessary Tools**: Ensure you have Python and relevant libraries installed.
- **Access the Data**: Download GamesData.csv and TeamsData.csv for your analysis.
- **Run the Notebooks**: Explore ProjectScoping.ipynb and NewPreprocessing.ipynb for insights into our preprocessing steps.

## Access Rights
The dataset is available for educational, research, and analytical use, subject to collegefootballdata.com's terms, which prohibit commercial use without additional permissions.

## Future Directions
We acknowledge certain limitations, such as missing data points and the absence of team rankings or revenue data. Future work will aim to address these gaps for a more comprehensive analysis.

## Contributions
This project was a collaborative effort, with team members contributing to all stages. Data collection and preprocessing were led by Caleb and Hashim, while Muhammad took on the README documentation. The entire team collaborated on the presentation.
