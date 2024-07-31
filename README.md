# MTB Trailmap - Map Style for JOSM

**Easily visualize mountain bike trail difficulty, uphill difficulty, trail width, visibility, and surface type with color-coded indicators and text labels while editing OpenStreetMaps with JOSM Editor.** The map style includes toggle options that allow you to choose which trail attributes are displayed on the map layer. This style allows users to see how their edits will appear on platforms dedicated to mountain biking trails, ensuring accuracy and consistency in the map data for mountain biking enthusiasts worldwide.

The **MTB Trailmap Style for JOSM** is designed to help [OpenStreetMap (OSM)](https://www.openstreetmap.org/) contributors visualize mountain biking (MTB) trail data within the [Java OpenStreetMap editor (JOSM Editor)](https://josm.openstreetmap.de). Inspired by the Finnish [Trailmap.fi](https://web.trailmap.fi) service, this style is also useful for map editors of other MTB mapping platforms like [mtbmap.no](https://mtbmap.no), which use similar data. This MapCSS-based style provides real-time visual feedback, which is invaluable for ensuring edits are accurate and consistent.

![JOSM-style-trailmap](https://github.com/user-attachments/assets/8833d127-f0b9-4850-b588-903e973cc64d)
*Example of how the map style looks on JOSM editor combined with the Potlatch2 map style.*

---

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

## How to use the MTB Trailmap Style in JOSM

The **MTB Trailmap Style for JOSM** is designed to help [OpenStreetMap (OSM)](https://www.openstreetmap.org/) contributors visualize mountain biking (MTB) trail data within the [Java OpenStreetMap editor (JOSM Editor)](https://josm.openstreetmap.de). This style allows users to see how their edits will appear on platforms dedicated to mountain biking trails, ensuring accuracy and consistency in the map data. By replicating the visual elements of popular MTB mapping services like Trailmap.fi and MTBmap.no, this style provides an intuitive and familiar environment for MTB trail mapping.

### Enhancing MTB Mapping with JOSM

Mapping MTB trails involves tagging various trail attributes such as difficulty levels, surface types, visibility, and width. Accurate mapping is essential for creating reliable trail maps that bikers can use to plan their routes. The MTB Trailmap Style enhances this process by providing immediate visual feedback on these attributes directly within JOSM. This helps contributors:

- **Visualize Trail Difficulty:** See color-coded trail difficulty levels at a glance, making it easier to ensure the data is accurate and helpful for bikers.
- **Assess Uphill Challenges:** Display uphill difficulty scales, allowing mappers to indicate sections of trails that might be challenging to ascend.
- **Evaluate Surface Conditions:** Show different surface types directly on the map, providing insights into the trail conditions.
- **Understand Trail Width and Visibility:** Visualize trail width and visibility, helping to identify narrow or poorly visible trails that might require special attention.

By using this map style, contributors can see real-time previews of their edits, eliminating the need to wait for updates on external services, which can take hours or even days. This makes the tool invaluable for anyone involved in mapping MTB trails, ensuring that edits are consistent and accurately reflected across different platforms. The global applicability of this style means it can benefit MTB mapping efforts worldwide, supporting various platforms and communities dedicated to mountain biking.

### Toggle Options in JOSM

Once the style is applied, you can enable or disable the visibility of various elements such as MTB difficulty scale, uphill difficulty scale, and surface information. Adjusting these settings can help you manage the visual clutter and focus on the most relevant data for your mapping tasks. See the section below for detailed instructions on using the toggle options.

![how-to-style](https://github.com/user-attachments/assets/70326628-9501-4be0-86fb-1d7261852034)

This style includes settings that allow you to toggle the visibility of certain elements such as the MTB difficulty scale, uphill difficulty scale, and surface information. To access and modify these settings:

1. Open JOSM editor.
2. Load the style by following the installation instructions.
3. Go to `View` > `Map Paint Styles`.
4. In the Map Paint Styles panel, find the MTB Trailmap Style.
5. Click on the wrench icon next to the style name to open the style settings. Optionally, you can right-click the style name and find the menu from there.
6. Here, you can see various toggle options:

- **Display MTB Difficulty on Paths:** Toggle the display of color-coded MTB difficulty scale on paths. This setting shows the trail difficulty levels using different colors based on the `mtb:scale` tag. This feature closely replicates Trailmap.fi.
- **Text for MTB Difficulty on Paths:** Toggle the display of MTB difficulty scale text over the paths. This setting adds text labels indicating the difficulty level of the trails. **Note:** This feature is not available on Trailmap.fi. Disabling this option will provide a more Trailmap-like experience. However, enabling it can help quickly identify trail difficulties with text labels.
- **Display MTB Uphill Difficulty on Separate Paths:** Toggle the display of the color-coded MTB uphill difficulty scale next to the paths. This setting shows uphill difficulty levels using different colors based on the `mtb:scale:uphill` tag on a separate line adjacent to the main path. **Note:** This feature is not available on Trailmap.fi. Disabling this option will provide a more Trailmap-like experience. Enabling it can help mountain bikers prepare for challenging uphill sections.
- **Text for MTB Uphill Difficulty on Separate Paths:** Toggle the display of MTB uphill difficulty scale text next to the paths. This setting adds text labels indicating the uphill difficulty level of the trails on a separate line adjacent to the main path. **Note:** This feature is not available on Trailmap.fi. Disabling this option will provide a more Trailmap-like experience. Enabling it provides clear indications of uphill challenges.
- **Display Surface on Separate Paths:** Toggle the display of surface information on a separate path layer next to the paths. This setting shows surface types such as paved, gravel, or dirt on a separate line adjacent to the main path. **Note:** This feature is not available on Trailmap.fi. Disabling this option will provide a more Trailmap-like experience. Enabling it helps users understand the trail surfaces more clearly.
- **Display Surface on Paths:** Toggle the display of surface information directly on the paths. This setting overlays the surface type information on the same line as the paths. **Note that the surface coloring can't be seen if the MTB Difficulty Scale option is enabled.** **Note:** This feature is not available on Trailmap.fi. Disabling this option will provide a more Trailmap-like experience. Enabling it provides detailed surface information directly on the trails.
- **Text for Surface on Paths:** Toggle the display of surface-type text next to the paths. This setting adds text labels indicating the type of surface (e.g., paved, gravel) along the trails. **Note:** This feature is not available on Trailmap.fi. Disabling this option will provide a more Trailmap-like experience. Enabling it offers clear text indications of the surface type.
- **Display Path Opacity Based on Visibility:** Toggle path opacity based on trail visibility. This setting adjusts the transparency of paths to reflect how visible they are, based on the `trail_visibility` tag. **Note:** This feature is not available on Trailmap.fi. Disabling this option will provide a more Trailmap-like experience. Enabling it helps to quickly assess trail visibility.

> [!IMPORTANT]
> By default, all these options are enabled except `Display Surface on Separate Path`. You can disable any of these options based on your preference. If you have all the options enabled and you are examining a map with many MTB trails, especially those that also include `mtb:scale:uphill` data, the view can become very cluttered. Disabling unnecessary settings is recommended to improve clarity. Adjust the visibility of trail attributes according to your specific needs to create a more manageable and clear map view. This will help you focus on the most relevant information and ensure an efficient mapping process.

---

## Project Background

As an OSM contributor since 2010, I have focused on mapping natural features and trails suitable for mountain biking. My passion for outdoor activities such as mountain biking, gravel riding, road cycling, canoeing, and general nature exploration has deeply influenced my contributions. I am also an enthusiastic map researcher and editor. Combining my love for the outdoors with mapping has made it clear that there is a need for better tools to visualize and edit trail data.

Finally in 2024, I recognized the need for a tool to better visualize MTB trail data in JOSM. Despite JOSM being a powerful editor, it can be challenging to get a clear overview of trail conditions and difficulty without switching between different map layers or external services that can visualize trail data.

Inspired by the detailed and user-friendly visual style of Trailmap.fi, I embarked on a project to create a similar style for JOSM. The goal was to bring the clarity and detail of Trailmap.fi into the JOSM environment, making it easier for contributors to see how their edits would appear on MTB-focused platforms. This project was my first attempt at using the MapCSS language, which presented its own set of challenges due to its complexity and lack of comprehensive documentation. Despite these hurdles, I was determined to create a useful tool for the mapping community.

The development process involved carefully examining maps on Trailmap.fi and manually translating what I observed into MapCSS. I did not have access to Trailmap.fi’s code or any automated tools to assist in this process. Instead, it was a meticulous task of visual inspection and manual coding to ensure that the style closely matched the appearance of Trailmap.fi. This approach means that while the style aims to replicate the visual elements of Trailmap.fi, it is not an exact copy, and some elements may look different.

The main objective of this style is to provide immediate visual feedback on map edits within JOSM, ensuring the accurate representation of trail data. This MTB Trailmap Style includes features such as color-coded trail difficulty levels, indicators for uphill difficulty, text labels for MTB difficulty and surface information, and visualization of trail width and visibility. These enhancements offer a comprehensive view of trail conditions directly within JOSM, streamlining the mapping process and improving accuracy for MTB mapping platforms like Trailmap.fi, MTBmap.no, and other MTB mapping services that utilize similar OSM data.

By using this map style, map editors can see real-time previews of their edits, eliminating the need to wait for updates on external services, which can take hours or even days. This makes the tool invaluable for anyone involved in mapping MTB trails, ensuring that edits are consistent and accurately reflected across different platforms. Its global applicability means it can benefit MTB mapping efforts worldwide, supporting various platforms and communities dedicated to mountain biking.

>[!CAUTION]
>This style is not an exact copy of Trailmap.fi nor based on their code. It has been developed through visual inspection to closely match its appearance. While some elements may be rendered differently, the primary objective is to offer a helpful tool for OSM map editors using JOSM to better visualize their contributions. Users should not expect a perfect one-to-one replication, but rather a practical and useful representation for map editing purposes. Not all elements from Trailmap.fi are rendered the same way. The focus has been on ensuring that mtb:scale is displayed accurately, while trail visibility and trail width are approximations. Additional features such as mtb:scale:uphill, trail surface information and text labels for trails have been added, which are not found in Trailmap.fi.
>
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
