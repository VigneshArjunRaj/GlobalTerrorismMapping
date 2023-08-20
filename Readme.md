# Carto DB Map Readme - Web Analysis and Mapping

## Overview

This repository contains a Carto DB map that provides an insightful visualization of global terrorism incidents. It enables users to explore and analyze various dimensions of terrorist events worldwide. The map showcases multiple layers, each offering a unique perspective on the data.

## Dataset: Global Terrorism Database (GTD)

The data for this map is sourced from the Global Terrorism Database™ (GTD). This open-source database contains information on terrorist events spanning from 1970 to 2020. It encompasses over 200,000 cases of terrorism, featuring detailed data points for each incident, including date, location, weapons used, targets, casualties, and responsible entities.

The GTD dataset has the following characteristics:
- Covers domestic, transnational, and international incidents.
- Contains data on more than 88,000 bombings, 19,000 assassinations, and 11,000 kidnappings.
- Provides insights into over 45 variables for each case, with more recent incidents having data on more than 120 variables.
- Relies on credible open media sources for information.
- Facilitates the study and understanding of terrorist violence through comprehensive data.

## Layers

### Layer 1: Global Terrorism

This layer serves as the primary visualization, depicting global terrorism incidents across various zoom levels. The incidents are color-coded based on the type of weapon used (weaptype1_txt). The following weapon types are represented:
- EXPLOSIVES
- FIREARMS
- UNKNOWN
- INCENDIARY
- MELEE
- CHEMICAL
- OTHERS

The size of each incident's representation is determined by the number of reported fatalities (nkill), ranging from 0 to a maximum of 1700 fatalities.

### Layer 2: Location Widgets

This layer introduces location-specific widgets that offer valuable insights into terrorism incidents in different countries. The widgets include:
- **Sucide Bombers:** Displays the count of incidents involving suicide bombers.
- **Successful Attempts:** Shows the total count of successful terrorism attempts.
- **Country Breakdown:** Presents statistics for selected countries:
  - Iraq: 24.3k incidents
  - Afghanistan: 16.5k incidents
  - Pakistan: 13.5k incidents
  - India: 11.7k incidents
  - Colombia: 8.24k incidents
  - Others: 111k incidents

### Layer 3: Casualty Breakdown

This layer provides insights into casualty counts based on different attack types:
- **Killed:** Breakdown of fatalities for different attack types.
- **Wounded:** Breakdown of wounded individuals for different attack types.

## Usage

This Carto DB map is designed for web analysis and mapping purposes, allowing users to delve into global terrorism incidents and trends. Users can navigate, explore, and analyze data points to gain a better understanding of the distribution of incidents, the types of weapons used, and the resulting casualties.

To effectively use the map:
1. **Navigation:** Zoom and pan to explore incidents at varying levels of detail.
2. **Color and Radius:** Observe the color-coded incidents and the radius representing the severity of each incident's impact.
3. **Location Widgets:** Utilize the widgets to understand terrorism-related statistics for specific countries.
4. **Casualty Breakdown:** Analyze the casualty breakdown to comprehend the impact of different attack types.

## Attribution

This Carto DB map is powered by CARTO and utilizes data from the Global Terrorism Database. The dataset is sourced from credible open media reports, providing an accessible and informative visualization of global terrorism trends and patterns.

---

Please note that the information and data presented in this Carto DB map are based on the available dataset and context as of the last update. For the most up-to-date and accurate information, refer to the original data sources provided by the Global Terrorism Database.
