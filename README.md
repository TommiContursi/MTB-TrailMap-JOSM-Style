# MTB Trailmap - Map Style for JOSM
*Easily visualize mountain bike trail difficulty, uphill difficulty, trail width, visibility, and surface type with color-coded indicators and text labels while editing OpenStreetMaps with JOSM Editor. The map style includes toggle options that allow you to choose which trail attributes are displayed on the map layer. This style allows users to see how their edits will appear on platforms dedicated to mountain biking trails, ensuring accuracy and consistency in the map data for mountain biking enthusiasts worldwide.*

![JOSM-style-trailmap](https://github.com/user-attachments/assets/8833d127-f0b9-4850-b588-903e973cc64d)
*Example of how the map style looks on JOSM editor combined with the Potlatch2 map style.*

## Introduction
The **MTB Trailmap Style for JOSM** is designed to help [OpenStreetMap (OSM)](https://www.openstreetmap.org/) contributors visualize mountain biking (MTB) trail data within the [Java OpenStreetMap editor (JOSM Editor)](https://josm.openstreetmap.de). Inspired by the Finnish [Trailmap.fi](https://web.trailmap.fi) service, this style allows users to see how their edits will appear on platforms dedicated to mountain biking trails, ensuring accuracy and consistency in the map data. This style is also useful for other MTB mapping platforms like [mtbmap.no](https://mtbmap.no) which use similar data.

### Project Background

As an OSM contributor since 2010, I have focused on mapping natural features and trails suitable for mountain biking. In 2024, I recognized the need for a tool to better visualize MTB trail data in JOSM. JOSM is a powerful editor, but it can be challenging to get a clear overview of trail conditions and difficulty without switching between different map layers or external services that can visualize trail data.

To address this need, I developed the MTB Trailmap Style using the MapCSS language. Despite its complex and poorly documented nature, this project marks my first attempt at utilizing MapCSS. There may be some logical inconsistencies or errors, but I hope the end result provides significant value to map editors.

This project aims to replicate the visual style of Trailmap.fi within JOSM. Although it is not an exact copy or based on Trailmap.fi's code, this style has been developed through visual inspection to closely match its appearance. The goal is to provide immediate visual feedback on map edits, making it easier to ensure that trail data is accurately represented. While some map elements may be rendered differently, this style serves as a valuable tool for map editors, offering a close approximation of the Trailmap.fi visual style. Users should not expect a perfect one-to-one replication, but rather a practical and useful representation for OSM editing purposes.

This MTB Trailmap Style includes features such as color-coded trail difficulty levels, indicators for uphill difficulty, text labels for MTB difficulty and surface information, and visualization of trail width and visibility. These enhancements provide a comprehensive view of trail conditions directly within JOSM, streamlining the mapping process and improving accuracy for platforms like Trailmap.fi, MTBmap.no and other MTB mapping services that use similar OSM data.

With this map style, map contributors can see real-time previews of their map edits, avoiding the need to wait for updates on external services, which can take hours or even days. This tool aims to be invaluable for anyone involved in mapping MTB trails, ensuring that edits are consistent and accurately reflected across different platforms. The global applicability of this style means that it can be beneficial for MTB mapping efforts worldwide, supporting various platforms and communities dedicated to mountain biking.

### Key Features and Benefits

This JOSM style replicates the visual elements of Trailmap.fi, such as color-coded trail difficulty levels ja trail visibility. In addition to mimicking the visual style, this JOSM style includes extra features not found on Trailmap.fi, such as the uphill difficulty scale, text labels for MTB difficulty, and surface information. These enhancements offer additional functionality for users to visualize more detailed aspects of trail data, providing a comprehensive view of the trail conditions. 

- **MTB Difficulty Scale**: Color-coded indicators based on the `mtb:scale` tag, which rates trails on a scale from 0 to 6. This scale indicates how difficult the trail is to ride, with 0 being the easiest and 6 being the most challenging. This helps in distinguishing trails by their difficulty levels at a glance. [Learn more about the `mtb:scale` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:mtb:scale).
- **Uphill Difficulty Scale**: Adds a secondary line to indicate uphill difficulty using the `mtb:scale:uphill` tag. This helps mountain bikers prepare for steep or difficult uphill segments. [Learn more about the `mtb:scale:uphill` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:mtb:scale:uphill).
- **Trail Visibility**: Dash patterns based on the `trail_visibility` tag, showing how visible and well-marked the trail is. This ranges from excellent visibility to no visibility. [Learn more about the `trail_visibility` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:trail_visibility).
- **Trail Width**: Variations based on the `width` tag, indicating the physical width of the trail. This information is useful for understanding how wide a trail is and whether it can accommodate different types of users or activities. [Learn more about the `width` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:width).
- **Surface Information**: Color-coded based on the `surface` tag, indicating the type of surface, such as paved, gravel, or dirt. This helps users anticipate the trail conditions and choose the right equipment. [Learn more about the `surface` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:surface).
- **Identify Access Restrictions and Obstacles**: Indicators based on `access`, `bicycle`, and `obstacle` tags, helping users recognize paths with restricted access or potential obstacles like vegetation or mud, ensuring safer and more informed route planning.
- **Customizable Toggles**: Options to toggle the visibility of MTB difficulty, uphill difficulty, trail visibility, width, and surface information for a tailored mapping experience.
- **Compatibility**: Seamlessly integrates with JOSM's default styles, such as [JOSM Standard](https://josm.openstreetmap.de/browser/trunk/resources/styles/standard/elemstyles.mapcss) and [Potlatch 2](https://josm.openstreetmap.de/wiki/Styles/Potlatch2), ensuring it can be used alongside other popular styles without conflicts.

Each of these features helps to draw trails and paths in the JOSM editor with varying styles and colors, making it easier to interpret the map data and make informed decisions while mapping or navigating.

---

## Installation

### Method 1: JOSM Style Database

1. Open [JOSM Editor](https://josm.openstreetmap.de).
2. Go to `Edit` > `Preferences` > `Map Settings` > `Map Paint Styles`.
3. In the list of available styles, search for **MTB Trailmap**.
4. Select the style and click `Activate`.
5. Apply the changes.

### Method 2: Manual Installation

1. Open JOSM editor.
2. Go to `Edit` > `Preferences` > `Map Settings` > `Map Paint Styles`.
3. Click on `+` to add a new style.
4. Paste [the URL of this style's raw content](https://raw.githubusercontent.com/TommiContursi/MTB-TrailMap-JOSM-Style/main/MTB-Trailmap-JOSM-map-style.mapcss) or use the local file path if you've downloaded it.
5. Apply the changes.

## Usage

Once the style is applied, you can enable or disable the visibility of various elements such as MTB difficulty scale, uphill difficulty scale, and surface information. See the section below for detailed instructions on using the toggle options.

### Toggle Options in JOSM

![how-to-style](https://github.com/user-attachments/assets/70326628-9501-4be0-86fb-1d7261852034)

This style includes settings that allow you to toggle the visibility of certain elements such as the MTB difficulty scale, uphill difficulty scale, and surface information. To access and modify these settings:

1. Open JOSM editor.
2. Load the style by following the installation instructions.
3. Go to `View` > `Map Paint Styles`.
4. In the Map Paint Styles panel, find the MTB Trailmap Style.
5. Click on the wrench icon next to the style name to open the style settings. Optionally, you can right click the style name and find the menu from there. 
6. Here, you can see various toggle options:

- **Display MTB Difficulty Scale**: Toggle the display of color-coded MTB difficulty scale on paths.
- **Text for MTB Difficulty**: Toggle the display of MTB difficulty scale text over the paths.
- **Display MTB Uphill Difficulty Scale**: Toggle the display of the color-coded MTB uphill difficulty scale next to the paths.
- **Text for MTB Uphill Difficulty**: Toggle the display of MTB uphill difficulty scale text next to the paths.
- **Display surface on a separate path**: Toggle the display of surface information on a separate path layer next to the paths.
- **Display surface on paths**: Toggle the display of surface information directly on the paths. Note that the surface coloring can't be seen if the MTB Difficulty Scale option is enabled.
- **Text for surface**: Toggle the display of surface-type text next to the paths.
- **Display path opacity**: Toggle path opacity based on trail visibility.

By default, all these options are enabled except `Display surface on a separate path`. You can disable any of these options based on your preference.

---

## Contribution

I welcome contributions from the community to help improve this style. If you have suggestions, find any issues, or want to contribute code, please feel free to open issues or submit pull requests on our [GitHub repository]([https://github.com/TommiContursi/JOSM-Style](https://github.com/TommiContursi/MTB-TrailMap-JOSM-Style)). Your feedback is invaluable in helping us refine and enhance this style.

## License

This project is licensed under the MIT License. Please take a look at the [LICENSE](LICENSE) file for more details.

---

## Visual Guide

### MTB Difficulty Scale

Paths are color-coded based on their MTB difficulty scale, making it easy to distinguish trails at a glance. More information on MTB difficulty can be found on the [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:mtb:scale) and the [Trailmap tag wiki](https://wiki.trailmap.fi/fi/kartoitus/tagit):
- `mtb:scale=0-`: Light Blue `#50d6eb` - **Very Easy Path**: Smooth outdoor paths and forest roads, etc. Does not require any off-road skills and can be ridden with a city bike or road bike.
- `mtb:scale=0`: Green `#75df08` - **Easy Path**: Needle-covered path or similar smooth easy track, with few stones or roots. Does not require special off-road skills, pleasant even for beginners, and can be easily ridden with a cyclocross bike.
- `mtb:scale=1`: Yellow `#d8dc00` - **Intermediate Path**: Small stones or roots. Obstacles can mainly be crossed with a mountain bike without bypassing. Mostly easy to ride with basic skills on a mountain bike, but a beginner may occasionally need to dismount. Still rideable with a cyclocross bike for a skilled rider.
- `mtb:scale=2`: Orange `#feb13e` - **Difficult Path**: Larger stones and roots. There may be smaller drops. Requires concentration even from more experienced riders and is not easy for most, especially uphill and when wet. Cyclocross bike needs to be carried on the shoulder.
- `mtb:scale=3`: Red `#ff4355` - **Very Difficult Path**: Many large stones, roots, and other obstacles. Large drops and challenging climbs. Almost impossible to ride uphill. Requires tight concentration from experienced riders and is slow to ride. Beginners often need to push their bikes frequently.
- `mtb:scale=4`: Magenta `#e410dd` - **Extremely Difficult Path**: Extremely difficult due to large obstacles and height differences, requires exceptional trials-type skills to ride even very slowly. Very slow to run for trail runners as well.
- `mtb:scale=5`: Purple `#9600c8` - **Almost Impossible Path**: Practically unridable for almost everyone due to large obstacles, height differences, and winding paths. Theoretically rideable with sufficient skills.
- `mtb:scale=6`: Dark Purple `#8101ad` - **Unridable Path**: Not rideable regardless of skills due to, for example, long vertical drops or large, densely located obstacles. Requires concentration even on foot.

### MTB Difficulty Scale Uphill

Paths are color-coded based on their MTB uphill difficulty scale, displayed as a secondary line next to the path. More information on MTB uphill difficulty can be found on the [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:mtb:scale:uphill):

- `mtb:scale:uphill=0`: Green `#75df08` - **Easy Uphill**: Graveled or hardened earth with good grip, typically a highway=track. Even unskilled mountain bikers can easily ride up these paths. Average incline is less than 10%, with a maximum incline of less than 15%. There are no obstacles.
- `mtb:scale:uphill=1`: Yellow `#d8dc00` - **Moderate Uphill**: Similar to easy uphill but slightly steeper. The path is gravel or hardened earth, with good grip to prevent wheelspin. Average incline is less than 15%, with a maximum incline of less than 20%. Some loose objects may be present but are avoidable.
- `mtb:scale:uphill=2`: Orange `#feb13e` - **Challenging Uphill**: The path is mostly stable but unsurfaced and partly washed out. Requires steady pedaling and balance. Average incline is less than 20%, with a maximum incline of less than 25%. Expect fist-sized loose rocks, roots, or a rocky underground.
- `mtb:scale:uphill=3`: Red `#ff4355` - **Difficult Uphill**: The surface varies with tight corners and small steps, composed of rocks, earth, or grass. Very good balance and steady pedaling are needed. Without advanced skills, mountain bikers will need to push their bike. Average incline is less than 25%, with a maximum incline of less than 30%. Contains fist-sized loose rocks, roots, and branches or a rocky surface.
- `mtb:scale:uphill=4`: Magenta `#e410dd` - **Very Difficult Uphill**: Very steep or in poor condition for pedaling. Features steps, trees, roots, and tight corners. Even skilled and strong mountain bikers will have to push or carry their bike for parts of the way. Average incline is less than 30%, with a maximum incline of less than 40%. Expect big loose rocks, big branches across the trail, and a rocky or loose surface.
- `mtb:scale:uphill=5`: Purple `#8101ad` - **Extremely Difficult Uphill**: Too steep and/or difficult to ride uphill. This level indicates to other mountain bikers that they will need to push and carry their bike on this part of the trail.

### Path Visibility Based Styles

Paths with varying visibility are displayed with different dash patterns and opacity levels. More information can be found on the [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:trail_visibility):
- `trail_visibility=excellent`: Clearly visible path with a long dash pattern of 10 pixels followed by a gap of 6 pixels.
- `trail_visibility=good`: Good visibility with the same long dash pattern of 10 pixels followed by a gap of 6 pixels.
- `trail_visibility=intermediate`: Moderate visibility, slightly harder to follow, with a short dash pattern of 2 pixels followed by a gap of 2 pixels.
- `trail_visibility=bad`: Poor visibility, difficult to follow, also with a short dash pattern of 2 pixels followed by a gap of 2 pixels.
- `trail_visibility=horrible`: Very poor visibility, very difficult to follow, with the same short dash pattern of 2 pixels followed by a gap of 2 pixels.
- `trail_visibility=no`: No visible path, extremely challenging, with a short dash pattern of 2 pixels followed by a gap of 2 pixels.

### Path Width

Paths are displayed with varying widths based on their `width` tag, including casing. More information can be found on the [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:width):

- `width < 0.6`: Narrow paths displayed with a total width (including casing) of 6 pixels (2 pixels for the path, 2 pixels for the casing on each side).
- `width < 0.9`: Slightly wider paths displayed with a total width (including casing) of 8 pixels (2 pixels for the path, 2 pixels for the casing on each side).
- `width < 1.8`: Moderately wide paths displayed with a total width (including casing) of 12 pixels (3 pixels for the path, 4.5 pixels for the casing on each side).
- `width > 1.8`: Wide paths displayed with a total width (including casing) of 14 pixels (4 pixels for the path, 5 pixels for the casing on each side).

### Access Restrictions

Paths with restricted access are displayed with red color and specific dash patterns. More information can be found on the [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:access):
- `bicycle=no`, `bicycle=private`, `access=no`, `access=private`: No bicycle access or private access. Dash pattern `4, 4`.
- `bicycle=permissive`, `access=permissive`: Permissive access, with some restrictions. Dash pattern `2, 15`.

### Surface Information

Paths are color-coded based on their surface type, with text labels displaying the surface information. More information can be found on the [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:surface):
- `surface=paved`: Dark Gray `#555555`
- `surface=asphalt`: Darker Gray `#333333`
- `surface=gravel`: Light Gray `#cccccc`
- `surface=dirt`: Brown `#a52a2a`
- `surface=grass`: Green `#006400`
- `surface=sand`: Sandy Brown `#f4a460`
- `surface=wood`: Burlywood `#deb887`
- `surface=concrete`: Gray `#808080`
- `surface=cobblestone`: Saddle Brown `#8b4513`
- `surface=pebblestone`: Dark Gray `#555555`
- `surface=compacted`: Dark Goldenrod `#b8860b`
- `surface=fine_gravel`: Dark Gray `#555555`
- `surface=grass_paver`: Green `#006400`
- `surface=paving_stones`: Sienna `#a0522d`
- `surface=metal`: Light Steel Blue `#b0c4de`
- `surface=bricks`: Firebrick `#b22222`
- `surface=earth`: Brown `#a52a2a`
- `surface=clay`: Chocolate `#d2691e`
- `surface=mud`: Saddle Brown `#8b4513`
- `surface=ground`: Saddle Brown `#8b4513`
- `surface=rock`: Gray `#808080`
  
---

## Change Log

### 2024-07-30

**Added:**

- **Icon Support:** Added an icon to the meta section for better visualization in JOSM.
- **Toggle Options:** Introduced multiple new toggle settings for various trail attributes including surface display, MTB scale display, surface display path, MTB uphill display, MTB scale text display, and surface display text. These toggles allow users to customize the display of different elements based on their preferences.
- **Width and Visibility Adjustments:** Implemented width and visibility settings for trails based on `width` and `trail_visibility` tags. These adjustments help in visualizing the trail conditions more accurately.
- **Surface Information:** Added detailed color coding for various surface types, such as paved, gravel, dirt, and more. This includes both on-path and separate path displays.
- **Text Labels:** Enhanced text display for surface types and MTB scales, providing clear on-map information about trail attributes.
- **Obstacle Visualization:** Introduced styles for different types of obstacles like vegetation and mud to help identify challenging sections.
- **Uphill Difficulty:** Added color-coded and dashed patterns for `mtb:scale:uphill` tag to indicate uphill difficulty levels.
- **Compatibility Enhancements:** Ensured seamless integration with JOSM's default styles, like JOSM Standard and Potlatch 2.

**Changed:**

- **Path Styling:** Updated the styling of paths and tracks with more accurate and visually appealing representations, including changes in dashes, casing colors, and widths.
- **Meta Information:** Updated the meta information to provide a more comprehensive description and versioning.
- **Node Styling:** Adjusted node styles for different zoom levels to improve visibility and map readability.
- **Access Restrictions:** Refined the visual indicators for paths with restricted access based on `access` and `bicycle` tags, making it easier to recognize paths with access limitations.

**Fixed:**

- **Text Overlapping Issues:** Corrected text offset issues to ensure clear and non-overlapping text displays for different path attributes.
- **String Comparison Issues:** Addressed issues with string comparisons in the MapCSS `eval` function to ensure proper rendering based on tag values.
- **Opacity Settings:** Improved opacity settings for paths to reflect trail visibility more accurately, enhancing the overall map readability.

### 2024-07-29

**Initial Release:**

- **Basic Path Styles:** Implemented basic styles for paths, tracks, cycleways, and footways.
- **Surface Information:** Introduced surface information display for tracks and paths with toggle options.
- **MTB Scale Display:** Added MTB difficulty scale display with color-coded indicators based on the `mtb:scale` tag.
- **Text Labels:** Included text labels for MTB scales and surface information to enhance map readability.
- **Basic Road Styles:** Implemented basic styling for unclassified, residential, tertiary, and service roads.
- **Waterway Styles:** Added basic styles for waterways.
- **Route Relation Underlay:** Introduced visual underlays for bicycle and MTB route relations.
- **Obstacle Styles:** Implemented basic visualization for obstacles like vegetation and mud.
