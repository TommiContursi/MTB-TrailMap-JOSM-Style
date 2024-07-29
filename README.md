# MTB Trailmap - Map Style for JOSM
*Easily visualize path or trail difficulty, uphill difficulty, trail width, visibility and surface while editing maps with JOSM editor*

![Trailmap Inspired Style](JOSM-style-trailmap.png)
## Introduction

The Trailmap Inspired Style for JOSM brings the look and feel of the popular [Trailmap.fi](https://web.trailmap.fi) map service into the JOSM editor. This style is particularly beneficial for users, especially in Finland, who frequently contribute to OpenStreetMap (OSM) and want to ensure their updates will reflect accurately on the Trailmap platform. By replicating the visual style of Trailmap, users can immediately see how their edits and updates will appear, maintaining consistency and accuracy in map data.

While this style draws heavy inspiration from Trailmap.fi, it is important to note that it is not an exact copy nor created based on their code. All visual aspects have been approximated through visual inspection to best match the appearance of Trailmap.fi. Consequently, certain elements may be rendered differently, and users should not expect a perfect one-to-one replication. Despite these differences, this style aims to provide a close approximation that will be helpful for many map editors.

In addition to mimicking the visual style, this JOSM style includes extra features not found on Trailmap.fi, such as the uphill difficulty scale and text labels for MTB difficulty. These enhancements offer additional functionality for users to visualize more detailed aspects of trail data.

This style is designed to work seamlessly with JOSM's default styles, such as the [JOSM Standard](https://josm.openstreetmap.de/browser/trunk/resources/styles/standard/elemstyles.mapcss) and [Potlatch 2](https://josm.openstreetmap.de/wiki/Styles/Potlatch2) styles, ensuring it can be used alongside other popular styles without conflicts.

### Purpose and Benefits

The primary purpose of this style is to provide a familiar visual environment for Trailmap users within JOSM. It helps users to:
- Visualize the MTB difficulty scale of trails.
- Identify access restrictions and obstacles.
- See trail visibility and width variations.
- Utilize customizable settings for a tailored mapping experience.

### Key Features

- **MTB Difficulty Scale**: Indicates MTB difficulty scale with color coding, making it easy to distinguish trails at a glance.
  
- **MTB Difficulty Scale Uphill**: Displays a secondary line next to the path for the uphill difficulty scale, providing detailed information for mountain bikers.

- **Text Display**: Shows text labels next to paths for MTB difficulty scale and uphill difficulty scale, providing clear, on-map information about trail difficulty.

- **Toggle Options**: Users can easily toggle the visibility of various elements such as the MTB difficulty scale and uphill difficulty scale, allowing for a cleaner map view based on individual preferences.

- **Compatibility**: This style is designed to work seamlessly with JOSM's default styles, such as the [JOSM Standard](https://josm.openstreetmap.de/browser/trunk/resources/styles/standard/elemstyles.mapcss) and [Potlatch 2](https://josm.openstreetmap.de/wiki/Styles/Potlatch2) styles, ensuring it can be used alongside other popular styles without conflicts.

- **Access Restrictions**: Visually indicates paths with restricted access, such as those that are private, permissive, or not accessible to bicycles, helping users quickly identify paths with access limitations.
- 

### Contributions and Feedback

We welcome contributions from the community to help improve this style. If you have suggestions, find any issues, or want to contribute code, please feel free to open issues or submit pull requests on our [GitHub repository](https://github.com/TommiContursi/JOSM-Style). Your feedback is invaluable in helping us refine and enhance this style.

### License

This project is licensed under the MIT License. For more details, please refer to the [LICENSE](LICENSE) file in the repository.

---

## Installation

1. Open JOSM editor.
2. Go to `Edit` > `Preferences` > `Map Settings` > `Map Paint Styles`.
3. Click on `+` to add a new style.
4. Paste the URL of this style's raw content or use the local file path if you've downloaded it.
5. Apply and restart JOSM.

## Usage

### Toggle Options in JOSM

This style includes settings that allow you to toggle the visibility of certain elements such as the MTB difficulty scale and uphill difficulty scale. To access and modify these settings:

1. Open JOSM editor.
2. Load the style by following the installation instructions.
3. Go to `View` > `Map Paint Styles`.
4. In the Map Paint Styles panel, find the Trailmap Inspired Style.
5. Click on the wrench icon next to the style name to open the style settings.
6. Here, you can see various toggle options:
   - **Display MTB Difficulty Scale**: Toggle the display of MTB difficulty scale color coding on paths.
   - **Display Difficulty Text**: Toggle the display of MTB difficulty scale text next to the paths.
   - **Display MTB Uphill Difficulty Scale**: Toggle the display of MTB uphill difficulty scale color coding on paths.

By default, all these options are enabled. You can disable any of these options based on your preference.

## Contribution

Feel free to open issues or submit pull requests if you have suggestions for improvements or find any bugs. Contributions are welcome and appreciated.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

## Examples

### MTB Difficulty Scale

Paths are color-coded based on their MTB difficulty scale:
- `mtb:scale=0-`: Light Blue
- `mtb:scale=0`: Green
- `mtb:scale=1`: Yellow
- `mtb:scale=2`: Orange
- `mtb:scale=3`: Red
- `mtb:scale=4`: Magenta
- `mtb:scale=5`: Purple
- `mtb:scale=6`: Dark Purple

### MTB Difficulty Scale Uphill

Paths are color-coded based on their MTB uphill difficulty scale, displayed as a secondary line next to the path:
- `mtb:scale:uphill=1`: Yellow
- `mtb:scale:uphill=2`: Orange
- `mtb:scale:uphill=3`: Red
- `mtb:scale:uphill=4`: Magenta
- `mtb:scale:uphill=5`: Purple

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
