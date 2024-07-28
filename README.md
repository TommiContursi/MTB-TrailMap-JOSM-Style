# Trailmap Inspired Style for JOSM

## Description
This is a JOSM style inspired by the Trailmap service, designed to visualize the `mtb:scale` of objects. It helps to distinguish the difficulty levels of mountain biking trails based on the `mtb:scale` and other attributes like path width, visibility, and obstacles.

## Features
- **Basic Geometry**: Sets the background color of the canvas.
- **Node Styles**: Defines styles for nodes at different zoom levels.
- **Highway Styles**: Customizes the appearance of highways, including cycleways, tracks, and paths.
- **MTB Scale Styles**: Colors paths based on the `mtb:scale` attribute.
- **Width-Based Styles**: Adjusts path width based on the `width` attribute.
- **Visibility-Based Styles**: Uses dash patterns to indicate the trail visibility.
- **Obstacle-Based Styles**: Uses casing colors and dash patterns to indicate obstacles like vegetation and mud.
- **Uphill Scale Styles**: Adds casing and dash patterns for paths with uphill scales.
- **Minor Roads**: Styles minor roads like unclassified, residential, tertiary, and service roads.
- **Regional and Major Roads**: Styles for motorways, trunks, primary, and secondary roads.
- **Waterways**: Styles for waterway features.
- **Bicycle Route Relations**: Adds underlays for bicycle route relations.
- **Text Display**: Displays `mtb:scale` and `mtb:scale:uphill` values along the paths.

## Installation
1. Download the `trailmap_style.mapcss` file from this repository.
2. Open JOSM.
3. Go to **Edit** > **Preferences**.
4. Select the **Map Settings** tab.
5. Click on the **Map Paint Styles** icon.
6. Click the **+** button to add a new style.
7. Select the `trailmap_style.mapcss` file and click **Open**.
8. Ensure the style is checked to enable it.

## Usage
- The style will automatically apply to the map view in JOSM.
- Paths will be color-coded based on their `mtb:scale`.
- Width and dash patterns will indicate the trail's width and visibility.
- Additional information like obstacles and uphill scale will be displayed using casings and dash patterns.

## Author
- **Tommi Contursi**
