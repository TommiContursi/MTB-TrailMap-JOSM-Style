# MTB Trailmap - Map Style for JOSM

**Easily visualize mountain bike trail difficulty, uphill difficulty, trail width, visibility, and surface type and quality with color-coded indicators and text labels while editing OpenStreetMaps with JOSM Editor.**

![image](https://github.com/user-attachments/assets/43e87e65-d94e-4bf0-84c5-3d065ce6c6aa)
*Example of how the map style looks on JOSM editor combined with the Potlatch2 map style.*

### Introduction

The **MTB Trailmap Style for JOSM** is designed to transform how [OpenStreetMap's (OSM)](https://www.openstreetmap.org/) mountain biking (MTB) trail data is visualized within the [Java OpenStreetMap editor (JOSM Editor)](https://josm.openstreetmap.de). Inspired by popular MTB mapping services like Trailmap.fi and mtbmap.no, this style brings a familiar and intuitive map style to JOSM.

Accurate mapping is essential for creating reliable trail maps that bikers can use to plan their routes. As an MTB trail mapper, you need to tag various attributes such as difficulty levels, surface types, visibility, and width. Without a clear visual representation, it's easy to miss or incorrectly tag these attributes, leading to errors. The MTB Trailmap Style enhances this process by offering **immediate visual feedback** directly within JOSM. With this style, you can easily visualize:

- **[Trail Difficulty](#mtb-difficulty-scale):** See color-coded trail difficulty levels at a glance, ensuring the data is accurate and helpful for bikers.
- **[Uphill Challenges](#uphill-difficulty-scale):** Display uphill difficulty scales to indicate sections that might be challenging to ascend, helping bikers prepare for steep climbs.
- **[Surface Conditions](#surface-information):** Show different surface types directly on the map, such as dirt, gravel, or pavement, providing insights into the trail conditions and helping bikers choose the right equipment.
- **[Surface Quality](#surface-quality):** Visualize the overall smoothness of the trail using color indicators or text. Helps determine how rideable or bumpy a trail segment is, based on the smoothness tag.
- **[Trail Width](#trail-width):** Visualize trail width to identify narrow single tracks or wider paths, ensuring bikers know what to expect and can plan accordingly.
- **[Trail Visibility](#trail-visibility):** Assess trail visibility to highlight well-marked routes or paths that might be harder to follow, improving safety and navigation for all users.
- **[Identify Access Restrictions and Obstacles](#identify-access-restrictions-and-obstacles):** Recognize paths with restricted access or potential obstacles like vegetation or mud, ensuring safer and more informed route planning.
- **[Customizable Toggles](#customizable-toggles):** Control which visual overlays and text labels are active—like trail difficulty, uphill difficulty, surface type, or visibility—to avoid clutter. Useful for focusing on one set of trail data at a time while mapping.

Instead of clicking on each line to view its tags, you can see all relevant information visually represented on the map. This ensures that your edits are accurate and consistent by providing real-time previews, allowing you to see how your changes will appear on dedicated MTB platforms. This eliminates the need to wait for updates from external services, which can take hours or even days.

By using this map style, you can simplify your mapping process, make it more accurate, and reduce errors, helping you create better and more useful maps for yourself and the entire mountain biking community. 

For installation instructions, see the [Installation Guide](#installation).

---

## Latest Changes (v1.2.1 – 2025-05-05)

- Grouped toggle settings for better organization in JOSM UI
- New support for `smoothness=` and `width=` tag rendering
- Text labels now available for `trail_visibility=`
- Improved font sizes, offsets, and overall label layout
- Renamed and clarified setting labels for better usability
- Default setting states updated to reduce clutter on first use

⚠️ **Tip:** For best results, activate only one main overlay (such as trail difficulty, surface, or visibility) at a time. Enabling multiple layers that use the same line coloring may result in visual overlap or conflicting styles. Text labels may also stack or become unreadable if too many are enabled at once.

📄 [See full changelogs and previous releases on the Releases page](https://github.com/TommiContursi/MTB-TrailMap-JOSM-Style/releases).

---

## Installation and Usage

To effectively use the MTB Trailmap Style in JOSM, follow these steps for installation and configuration:

### Installation

**Method 1: JOSM Style Database**

1. Open [JOSM Editor](https://josm.openstreetmap.de).
2. Go to `Edit` > `Preferences` > `Map Settings` > `Map Paint Styles`.
3. In the list of available styles, search for **MTB Trailmap**.
4. Select the style and click `Activate`.
5. Apply the changes.

**Method 2: Manual Installation**

1. Open JOSM editor.
2. Go to `Edit` > `Preferences` > `Map Settings` > `Map Paint Styles`.
3. Click on `+` to add a new style.
4. Paste [the URL of this style's raw content](https://raw.githubusercontent.com/TommiContursi/MTB-TrailMap-JOSM-Style/main/MTB-Trailmap-JOSM-map-style.mapcss) or use the local file path if you've downloaded it.
5. Apply the changes.

**Optional: Installing Additional Styles**

To get the most out of the MTB Trailmap Style, consider also installing the [JOSM Standard](https://josm.openstreetmap.de/browser/trunk/resources/styles/standard/elemstyles.mapcss) and [Potlatch 2](https://josm.openstreetmap.de/wiki/Styles/Potlatch2) styles:

1. **JOSM Standard:**
   - This is the default style provided by JOSM. It can be activated through the Map Paint Styles settings.

2. **Potlatch 2:**
   - Go to `Edit` > `Preferences` > `Map Settings` > `Map Paint Styles`.
   - Search for **Potlatch 2** and activate it.

### How to Use the MTB Trailmap Style in JOSM

1. **Enable the Style:**
   - Go to `View` > `Map Paint Styles`.
   - Ensure the MTB Trailmap Style is activated.

2. **Adjust Display Settings:**
   - Customize the visibility of various trail attributes using the toggle options available in the style settings.
   - Adjust settings to focus on the most relevant data for your mapping tasks, such as trail difficulty, uphill difficulty, surface type, and visibility.
   - Refer to the [toggle options](#customizable-toggles) for more details.

3. **Start Mapping:**
   - Begin tagging trail attributes such as difficulty levels ([`mtb:scale`](https://wiki.openstreetmap.org/wiki/Key:mtb:scale)), uphill difficulty ([`mtb:scale:uphill`](https://wiki.openstreetmap.org/wiki/Key:mtb:scale:uphill)), surface types ([`surface`](https://wiki.openstreetmap.org/wiki/Key:surface)), visibility ([`trail_visibility`](https://wiki.openstreetmap.org/wiki/Key:trail_visibility)), and width ([`width`](https://wiki.openstreetmap.org/wiki/Key:width)).
   - Use the visual indicators provided by the style to get immediate feedback on these attributes, helping you ensure accuracy. For detailed guidance on the style's features, please take a look at the [Key Features and Benefits](#key-features-and-benefits) section, which includes illustrative images and explanations.

4. **Review and Refine:**
   - Continuously review your edits using real-time visual feedback. This allows you to see how your changes will appear on MTB platforms.
   - Refine your tags and attributes to meet the standards required for accurate MTB trail mapping, ensuring the data is detailed and helpful for bikers.

By following these steps, you can effectively use the MTB Trailmap Style to enhance your MTB trail mapping efforts, ensuring that your edits are accurate, consistent, and beneficial to the global MTB community.


## Key Features and Benefits

This JOSM style replicates the visual elements of Trailmap.fi, such as color-coded trail difficulty levels ja trail visibility. In addition to mimicking the visual style, this JOSM style includes extra features not found on Trailmap.fi, such as the uphill difficulty scale, text labels for MTB difficulty, and surface information. These enhancements offer additional functionality for users to visualize more detailed aspects of trail data, providing a comprehensive view of the trail conditions. 

### MTB Difficulty Scale
Color-coded indicators based on the `mtb:scale` tag, which rates trails on a scale from 0 to 6. This scale indicates how difficult the trail is to ride, with 0 being the easiest and 6 being the most challenging. This helps in distinguishing trails by their difficulty levels at a glance. [Learn more about the `mtb:scale` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:mtb:scale) and the [Trailmap tag wiki](https://wiki.trailmap.fi/fi/kartoitus/tagit).

![image](https://github.com/user-attachments/assets/c62d0691-d6fd-4c0e-9ab0-c7ce31725ed7)

### Uphill Difficulty Scale
Adds a secondary line to indicate uphill difficulty using the `mtb:scale:uphill` tag. This helps mountain bikers prepare for steep or difficult uphill segments. [Learn more about the `mtb:scale:uphill` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:mtb:scale:uphill).

![image](https://github.com/user-attachments/assets/25744ade-47e6-4dd3-87bf-1ffab9a70be8)

### Trail Visibility
Dash patterns based on the `trail_visibility` tag, showing how visible and well-marked the trail is. This ranges from excellent visibility to no visibility. When enabled, the trail’s opacity also changes based on its trail_visibility value, helping users spot hard-to-see paths more intuitively.  [Learn more about the `trail_visibility` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:trail_visibility).

![image](https://github.com/user-attachments/assets/3f3f14e9-efa3-4e6f-970b-8e6cb97dc9c0)

### Trail Width
Variations based on the `width` tag, indicating the physical width of the trail. This information is useful for understanding how wide a trail is and whether it can accommodate different types of users or activities. Trail width values can also be shown as text labels next to the paths, depending on the selected settings. [Learn more about the `width` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:width).

![image](https://github.com/user-attachments/assets/d7156dde-33aa-4abb-b991-98abe888d211)

### Surface Information
Color-coded based on the `surface` tag, indicating the type of surface, such as paved, gravel, or dirt. This helps users anticipate the trail conditions and choose the right equipment. When enabled in settings, surface type can also be shown as text labels directly on or next to the trail. [Learn more about the `surface` tag on the OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:surface).

![image](https://github.com/user-attachments/assets/eb0a4ba7-45d7-41ce-b634-57199580b1b2)

### Identify Access Restrictions and Obstacles
Indicators based on `access`, `bicycle`, and `obstacle` tags, helping users recognize paths with restricted access or potential obstacles like vegetation or mud, ensuring safer and more informed route planning.

![image](https://github.com/user-attachments/assets/2a385242-983e-43ae-b80c-10cc5d3dc60d)

### Customizable Toggles

Once the style is applied, you can enable or disable the visibility of various trail attributes such as MTB difficulty, uphill difficulty, surface, visibility, smoothness, and path width. Adjusting these settings can help you manage the visual clutter and focus on the most relevant data for your mapping tasks. Please take a look at the section below for detailed instructions on using the toggle options.

![image](https://github.com/user-attachments/assets/06690b34-9e0a-424d-abb0-38c5f4f2484b)

To access and modify these settings:

1. Open JOSM editor.
2. Load the style by following the installation instructions.
3. Go to `View` > `Map Paint Styles`.
4. In the Map Paint Styles panel, find the MTB Trailmap Style.
5. Click on the wrench icon next to the style name to open the style settings. Optionally, you can right-click the style name and find the menu from there.
7. Here, you can see various toggle options:

#### MTB Difficulty (`mtb:scale`)

- **Color-coded line**  
  Shows the MTB difficulty as a colored line directly on the trail. Matches Trailmap.fi style and is usually the main indicator for trail difficulty.  
  _Default: ON_
- **Text label**  
  Adds a small text label (like `S2`) on the trail, showing the difficulty number. Helpful when colors are hard to distinguish or trails are close together.  
  _Default: ON_

#### MTB Uphill Difficulty (`mtb:scale:uphill`)
- **Separate color-coded line**  
  Adds a second line next to the main trail, showing uphill difficulty with different colors. Makes steep or technical climbs stand out clearly.  
  _Default: ON_
- **Text label**  
  Shows the uphill difficulty as text (like `↑ S3`) beside the trail.  
  _Default: ON_

#### Path Surface Type (`surface`)
- **Color-coded line**  
  Shows the trail surface (like gravel, asphalt, dirt) using color. This only works if MTB difficulty color is disabled.  
  _Default: ON_
- **Text label**  
  Adds the surface name (e.g., `sand`, `compacted`) as text on the trail.  
  _Default: ON_
- **Separate color-coded line**  
  Draws surface type on a second line next to the trail. Works even when MTB or uphill difficulty coloring is enabled.  
  _Default: OFF_

#### Trail Visibility (`trail_visibility`)
- **Color-coded line**  
  Changes the color of the trail to show how visible it is in real life (from excellent to no visible path).  
  _Default: OFF_
- **Text label**  
  Adds trail visibility info (like `intermediate` or `no`) as text next to the trail.  
  _Default: OFF_
- **Opacity based on visibility**  
  Fades out trails that are harder to follow, based on the `trail_visibility` tag.  
  _Default: ON_


#### Surface Quality (`smoothness`)
- **Color-coded line**  
  Shows how smooth or rough the trail is with different colors.  
  _Default: OFF_
- **Text label**  
  Adds the smoothness value (e.g. `intermediate`, `very_bad`) as text on the trail.  
  _Default: OFF_

#### Path Width (`width`)
- **Text label**  
  Adds the trail width (like `1.2 m`) as text on the trail.  
  _Default: OFF_


> [!IMPORTANT]
> Avoid enabling too many overlapping data layers at once, especially those that use the same line colors or label positions. 
> 
> For example, `mtb:scale`, `surface`, `smoothness`, and `trail_visibility` all use the same line coloring. If you enable several at the same time, the colors may overwrite each other or create a misleading impression (e.g., it may look like you're seeing surface info when it's actually MTB difficulty).
> 
> Similarly, if you enable multiple text labels (such as , `surface`, `smoothness`, `trail_visibility`, and `width`) they may overlap and clutter the view, making it harder to read and interpret.
> 
> **Recommendation:**  
> Enable only one of the main line-based overlays (`mtb:scale`, `surface`, `trail_visibility`, or `smoothness`) at a time. Some combinations, like `mtb:scale` and `mtb:scale:uphill`, work well together since they use different lines.  
> 
> You can also enable text labels for more context, but consider showing only the ones that are essential for your current editing task.
---

## Project Background

As an OSM contributor since 2010, I have focused on mapping natural features and trails suitable for mountain biking. My passion for outdoor activities such as mountain biking, gravel riding, road cycling, canoeing, and general nature exploration has deeply influenced my contributions. I am also an enthusiastic map researcher and editor. Combining my love for the outdoors with mapping has made it clear that there is a need for better tools to visualize and edit trail data.

Finally in 2024, I recognized the need for a tool to better visualize MTB trail data in JOSM. Despite JOSM being a powerful editor, it can be challenging to get a clear overview of trail conditions and difficulty without switching between different map layers or external services that can visualize trail data.

Inspired by the detailed and user-friendly visual style of Trailmap.fi, I embarked on a project to create a similar style for JOSM. The goal was to bring the clarity and detail of Trailmap.fi into the JOSM environment, making it easier for contributors to see how their edits would appear on MTB-focused platforms. This project was my first attempt at using the MapCSS language, which presented its own set of challenges due to its complexity and lack of comprehensive documentation. Despite these hurdles, I was determined to create a useful tool for the mapping community.

The development process involved carefully examining maps on Trailmap.fi and manually translating what I observed into MapCSS. I did not have access to Trailmap.fi’s code or any automated tools to assist in this process. Instead, it was a meticulous task of visual inspection and manual coding to ensure that the style closely matched the appearance of Trailmap.fi. This approach means that while the style aims to replicate the visual elements of Trailmap.fi, it is not an exact copy, and some elements may look different.

The main objective of this style was to provide immediate visual feedback on map edits within JOSM, ensuring the accurate representation of trail data. This MTB Trailmap Style includes features such as color-coded trail difficulty levels, indicators for uphill difficulty, text labels for MTB difficulty and surface information, and visualization of trail width and visibility. These enhancements offer a comprehensive view of trail conditions directly within JOSM, streamlining the mapping process and improving accuracy for MTB mapping platforms like Trailmap.fi, MTBmap.no, and other MTB mapping services that utilize similar OSM data.

By using this map style, map editors can see real-time previews of their edits, eliminating the need to wait for updates on external services, which can take hours or even days. This makes the tool invaluable for anyone involved in mapping MTB trails, ensuring that edits are consistent and accurately reflected across different platforms. Its global applicability means it can benefit MTB mapping efforts worldwide, supporting various platforms and communities dedicated to mountain biking.

>[!CAUTION]
>This style is not an exact copy of Trailmap.fi nor based on their code. It has been developed through visual inspection to closely match its appearance. While some elements may be rendered differently, the primary objective is to offer a helpful tool for OSM map editors using JOSM to better visualize their contributions. Users should not expect a perfect one-to-one replication, but rather a practical and useful representation for map editing purposes. Not all elements from Trailmap.fi are rendered the same way. The focus has been on ensuring that mtb:scale is displayed accurately, while trail visibility and trail width are approximations. Additional features such as mtb:scale:uphill, trail surface information and text labels for trails have been added, which are not found in Trailmap.fi.
>
---

## Contribution

I welcome contributions from the community to help improve this style. If you have suggestions, find any issues, or want to contribute code, please feel free to open issues or submit pull requests on our [GitHub repository]([https://github.com/TommiContursi/JOSM-Style](https://github.com/TommiContursi/MTB-TrailMap-JOSM-Style)). Your feedback is invaluable in helping us refine and enhance this style.

## License

This project is licensed under the MIT License. For more details, please see the [LICENSE](LICENSE) file.

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

Paths with varying visibility are displayed with different dash patterns, opacity levels, and casing colors. More information can be found on the [OpenStreetMap wiki](https://wiki.openstreetmap.org/wiki/Key:trail_visibility):

- `trail_visibility=excellent`: Bright Green `#00cc00` – Clearly visible path with a long dash pattern of 10 pixels followed by a gap of 6 pixels.
- `trail_visibility=good`: Light Green `#66cc66` – Good visibility with the same long dash pattern of 10 pixels followed by a gap of 6 pixels.
- `trail_visibility=intermediate`: Yellow `#cccc00` – Moderate visibility, slightly harder to follow, with a short dash pattern of 2 pixels followed by a gap of 2 pixels.
- `trail_visibility=bad`: Orange `#ff9900` – Poor visibility, difficult to follow, also with a short dash pattern of 2 pixels followed by a gap of 2 pixels.
- `trail_visibility=horrible`: Red `#ff3300` – Very poor visibility, very difficult to follow, with the same short dash pattern of 2 pixels followed by a gap of 2 pixels.
- `trail_visibility=no`: Dark Red `#990000` – No visible path, extremely challenging, with a short dash pattern of 2 pixels followed by a gap of 2 pixels.
  
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

### Surface Quality (smoothness)

Paths are color-coded based on the `smoothness=` tag to indicate how smooth or rough a trail is. This helps assess bike suitability and expected comfort level.
- `smoothness=excellent`: Green #00cc00 – Smooth like asphalt, suitable for all bicycles.
- `smoothness=good`: Light Green #66cc66 – Mostly smooth, few irregularities.
- `smoothness=intermediate`: Yellow #cccc00 – Noticeable irregularities, but still rideable.
- `smoothness=bad`: Orange #ff9900 – Rough surface, suitable for mountain bikes only.
- `smoothness=very_bad`: Reddish Orange #ff6600 – Difficult terrain, challenging for most riders.
- `smoothness=horrible`: Red #ff3300 – Extremely rough, mostly unrideable.
- `smoothness=very_horrible`: Dark Red #990000 – Dangerous or impractical to ride.
- `smoothness=impassable`: Black #000000 – Not passable even on foot.
