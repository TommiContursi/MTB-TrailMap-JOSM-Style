# MTB Trailmap - Map Style for JOSM
*Easily visualize path or trail difficulty, uphill difficulty, trail width, visibility, and surface type while editing maps with JOSM editor. Inspired by the popular Trailmap map service, this style enhances your mapping experience by providing clear, color-coded indicators and text labels for various trail attributes, helping you make accurate and detailed edits.*

![Trailmap Inspired Style](JOSM-style-trailmap.png)
Example how the map style looks combined with the Potlatch2 map style.

## Introduction

The Trailmap Inspired Style for JOSM brings the look and feel of the popular [Trailmap.fi](https://web.trailmap.fi) map service into the JOSM editor. This style is particularly beneficial for users, especially in Finland, who frequently contribute to OpenStreetMap (OSM) and want to ensure their updates will reflect accurately on the Trailmap platform. By replicating the visual style of Trailmap, users can immediately see how their edits and updates will appear, maintaining consistency and accuracy in map data.

While this style draws heavy inspiration from Trailmap.fi, it is important to note that it is not an exact copy nor created based on their code. All visual aspects have been approximated through visual inspection to best match the appearance of Trailmap.fi. Consequently, certain elements may be rendered differently, and users should not expect a perfect one-to-one replication. Despite these differences, this style aims to provide a close approximation that will be helpful for many map editors.

In addition to mimicking the visual style, this JOSM style includes extra features not found on Trailmap.fi, such as the uphill difficulty scale, text labels for MTB difficulty, and surface information. These enhancements offer additional functionality for users to visualize more detailed aspects of trail data, providing a comprehensive view of the trail conditions.

This style is designed to work seamlessly with JOSM's default styles, such as the [JOSM Standard](https://josm.openstreetmap.de/browser/trunk/resources/styles/standard/elemstyles.mapcss) and [Potlatch 2](https://josm.openstreetmap.de/wiki/Styles/Potlatch2) styles, ensuring it can be used alongside other popular styles without conflicts.

### Purpose and Benefits

The primary purpose of this style is to provide a familiar visual environment for Trailmap users within JOSM. It helps users to:

- **Visualize the MTB difficulty scale of trails**: Easily distinguish trails by their difficulty levels using color-coded indicators.
- **Identify access restrictions and obstacles**: Quickly recognize paths with restricted access or potential obstacles.
- **See trail visibility and width variations**: Understand the visibility and width of trails at a glance with varied dash patterns and opacities.
- **Utilize customizable settings for a tailored mapping experience**: Adjust the display of various trail attributes to suit individual mapping needs, enhancing the overall user experience.
- **Surface Information**: Display detailed surface type information directly on the paths, aiding in better trail assessment and editing decisions.

### Key Features

- **MTB Difficulty Scale**: Indicates MTB difficulty scale with color coding, making it easy to distinguish trails at a glance.
- **MTB Difficulty Scale Uphill**: Displays a secondary line next to the path for the uphill difficulty scale, providing detailed information for mountain bikers.
- **Text Display**: Shows text labels next to paths for MTB difficulty scale and uphill difficulty scale, providing clear, on-map information about trail difficulty.
- **Surface Information**: Displays surface information with color coding and text labels next to paths, indicating the type of surface (e.g., paved, gravel, dirt).
- **Toggle Options**: Users can easily toggle the visibility of various elements such as the MTB difficulty scale, uphill difficulty scale, and surface information, allowing for a cleaner map view based on individual preferences.
- **Compatibility**: This style is designed to work seamlessly with JOSM's default styles, such as the [JOSM Standard](https://josm.openstreetmap.de/browser/trunk/resources/styles/standard/elemstyles.mapcss) and [Potlatch 2](https://josm.openstreetmap.de/wiki/Styles/Potlatch2) styles, ensuring it can be used alongside other popular styles without conflicts.
- **Access Restrictions**: Visually indicates paths with restricted access, such as those that are private, permissive, or not accessible to bicycles, helping users quickly identify paths with access limitations.

## Installation

1. Open JOSM editor.
2. Go to `Edit` > `Preferences` > `Map Settings` > `Map Paint Styles`.
3. Click on `+` to add a new style.
4. Paste the URL of this style's raw content or use the local file path if you've downloaded it.
5. Apply and restart JOSM.

## Usage

### Toggle Options in JOSM

This style includes settings that allow you to toggle the visibility of certain elements such as the MTB difficulty scale, uphill difficulty scale, and surface information. To access and modify these settings:

1. Open JOSM editor.
2. Load the style by following the installation instructions.
3. Go to `View` > `Map Paint Styles`.
4. In the Map Paint Styles panel, find the Trailmap Inspired Style.
5. Click on the wrench icon next to the style name to open the style settings.
6. Here, you can see various toggle options:
   - **Display MTB Difficulty Scale**: Toggle the display of MTB difficulty scale color coding on paths.
   - **Display Difficulty Text**: Toggle the display of MTB difficulty scale text next to the paths.
   - **Display MTB Uphill Difficulty Scale**: Toggle the display of MTB uphill difficulty scale color coding on paths.
   - **Display Surface Information**: Toggle the display of surface information for paths and tracks.

By default, all these options are enabled. You can disable any of these options based on your preference.
---

## Contribution

I welcome contributions from the community to help improve this style. If you have suggestions, find any issues, or want to contribute code, please feel free to open issues or submit pull requests on our [GitHub repository]([https://github.com/TommiContursi/JOSM-Style](https://github.com/TommiContursi/MTB-TrailMap-JOSM-Style)). Your feedback is invaluable in helping us refine and enhance this style.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Visual Guide

### MTB Difficulty Scale

Paths are color-coded based on their MTB difficulty scale:
- `mtb:scale=0-`: Light Blue `#50d6eb`
- `mtb:scale=0`: Green `#75e009`
- `mtb:scale=1`: Yellow `#e3e800`
- `mtb:scale=2`: Orange `#feb13e`
- `mtb:scale=3`: Red `#ff4454`
- `mtb:scale=4`: Magenta `#f20bab`
- `mtb:scale=5`: Purple `#bf1cf5`
- `mtb:scale=6`: Dark Purple `#8100ac`

### MTB Difficulty Scale Uphill

Paths are color-coded based on their MTB uphill difficulty scale, displayed as a secondary line next to the path:
- `mtb:scale:uphill=1`: Yellow `#e3e800`
- `mtb:scale:uphill=2`: Orange `#feb13e`
- `mtb:scale:uphill=3`: Red `#ff4454`
- `mtb:scale:uphill=4`: Magenta `#f20bab`
- `mtb:scale:uphill=5`: Purple `#bf1cf5`

### Visibility Based Styles

Paths with varying visibility are displayed with different dash patterns and opacity levels:
- `trail_visibility=excellent`: Dash pattern `8, 5`
- `trail_visibility=good`: Dash pattern `8, 5`
- `trail_visibility=intermediate`: Dash pattern `6, 5`, reduced opacity
- `trail_visibility=bad`: Dash pattern `6, 5`, further reduced opacity
- `trail_visibility=horrible`: Dash pattern `6, 5`, even more reduced opacity
- `trail_visibility=no`: Dash pattern `6, 5`, lowest opacity

### Access Restrictions

Paths with restricted access are displayed with red color and specific dash patterns:
- `bicycle=no`, `bicycle=private`, `access=no`, `access=private`: Dash pattern `4, 4`
- `bicycle=permissive`, `access=permissive`: Dash pattern `2, 15`

### Surface Information

Paths are color-coded based on their surface type, with text labels displaying the surface information:
- `surface=paved`: Dark Gray `#555555`
- `surface=asphalt`: Darker Gray `#333333`
- `surface=gravel`: Light Gray `#cccccc`
- `surface=dirt`: Brown `#a52a2a`
- `surface=grass`: Green `#7cfc00`
- `surface=sand`: Sandy Brown `#f4a460`
- `surface=wood`: Burlywood `#deb887`
- `surface=concrete`: Gray `#808080`
- `surface=cobblestone`: Saddle Brown `#8b4513`
- `surface=pebblestone`: Dark Gray `#a9a9a9`
- `surface=compacted`: Dark Goldenrod `#b8860b`
- `surface=fine_gravel`: Light Gray `#d3d3d3`
- `surface=grass_paver`: Green `#7cfc00`
- `surface=paving_stones`: Sienna `#a0522d`
- `surface=metal`: Light Steel Blue `#b0c4de`
- `surface=bricks`: Firebrick `#b22222`
- `surface=earth`: Brown `#a52a2a`
- `surface=clay`: Chocolate `#d2691e`
- `surface=mud`: Saddle Brown `#8b4513`
- `surface=ground`: Saddle Brown `#8b4513`
- `surface=rock`: Gray `#808080`
---

## Changelog

### [1_2024-07-30] - 2024-07-30

#### Added
- **MTB Difficulty Scale Display**: 
  - Color-coded MTB difficulty scale based on `mtb:scale` tag.
  - Text display next to paths indicating MTB difficulty scale with color coding.
  - Toggle option `mtb_scale_text_display` to enable or disable MTB difficulty scale text display.
- **MTB Uphill Difficulty Scale Display**:
  - Color-coded MTB uphill difficulty scale based on `mtb:scale:uphill` tag.
  - Text display next to paths indicating MTB uphill difficulty scale with color coding.
  - Toggle option `mtb_uphill_display` to enable or disable MTB uphill difficulty scale display.
- **Surface Information Display**:
  - Color-coded surface information display based on `surface` tag.
  - Text display next to paths indicating surface type with color coding.
  - Toggle option `surface_display` to enable or disable surface information display.
  - Added new surface types with appropriate colors: wood, concrete, cobblestone, pebblestone, compacted, fine_gravel, grass_paver, paving_stones, metal, bricks, earth, clay, mud, ground, rock.

#### Changed
- **Code Organization**:
  - Improved readability and organization by consolidating repeated logic and structuring code more efficiently.
- **Path and Track Styles**:
  - Updated the text offset for `mtb:scale` and `mtb:scale:uphill` to avoid overlapping with surface information text.
  - Ensured that the styles work seamlessly with JOSM default styles like [JOSM Standard](https://josm.openstreetmap.de/browser/trunk/resources/styles/standard/elemstyles.mapcss) and [Potlatch 2](https://josm.openstreetmap.de/wiki/Styles/Potlatch2).
- **Access Restrictions Display**:
  - Implemented display for restricted access (no, private, permissive) for tracks and paths with specific color coding and dash patterns.

#### Fixed
- **Text Overlapping Issues**:
  - Corrected text offset issues to ensure clear and non-overlapping text displays for different path attributes.
- **String Comparison Issues**:
  - Addressed issues with string comparisons in the MapCSS `eval` function to ensure proper rendering based on tag values.
