# Changelog

### **April 7, 2025**
1. Fixed: Unable to apply material on walls in 3D.
2. Enabled Gyroscope for render tours and 360 renders
    - Render tours can now be navigated via gyroscope in mobile devices.

3. Implemented multiselect in Layoutplanner
    - Multiple objects can now be selected in floor plan via `CTRL + right click`.
    - Selected objects can be justified or aligned in horizontal and vertical directions
      via edit panel.
    - Multiple object can be copied/deleted/moved together in floor plan.

4. Experiment with lighting preview in 3D directly
    - Lighting can now be previewed in 3D directly by pressing and holding the `L` key in 3D page.
    - Lights with different presets (spot, panel etc.) glow differently when the light mode is
      toggled.

5. Added 'feet and inches' input to model upload
6. Fixed: Curved meshes were not showing up as smooth in renders
7. Added water-filter under kitchen in modular
    - Water purifier can now be added as a furnishing component within the woodwork customization page.
8. Fixed: Bug with bathroom walls
9. Added horizontal rafters
    - Horizontal rafters can now be added in woodwork customization page as well.
10. Enable auto save for entire project.
    - Can be toggled from global settings.
11. Implemented Palettes
    - Palettes are available under material tab in 3D. Users can select any palette from the
      palette gallery and find all the associated materials used within that palette.
12. Fixed: curved ledges are not composing properly, missing edge cases
    - The ledges were not composed properly in some cases like while setting the left front
      and right back simultaneously, etc.
13. Implemented Staircase Generator
    - Straight, L-shaped and U-shaped staircases can now be added from floor plan directly.
    - Multiple profils available for different types.
    - Glass and concrete railing can be set for any type of stair.
    - Railing position can be straight, flush etc.
14. Added option for render gallery in projects page
    - Render gallery can now be directly accessed for any project from the `/projects` page as well.


### **March 20, 2025**
1. Set a combined door model for custom woodwork doors
    - Users can now set a door model for the entire section.

2. Implemented: Utility for removing skirts of partitioned boxes.
    - Skirts of already partitioned boxes can be removed via shortcut
      or the toggle button.

3. Fixed: Variable height walls showing strip over the shorter of the intersecting walls.

4. Show only 'in progress' renders.
    - In the render reel, only last 1 hour renders and renders which are currently in
      progress are shown.
    - In progress: queued/started/pending.

5. Added more woodworks.
    - Added multipurpose, partition, paneling.
    - Added PoP option in woodworks page.


### **March 07, 2025**

1. Extended status for furnishings in modular and added active updates
    - The status of uploaded furnishings will now be shown for modular, similar to the furnishings gallery.
    - Uploaded furnishings are actively added to their respective galleries.

2. Implemented L-shaped doors
    - For joined sections, the door type can now be set as **L-shaped** or **Double (Unsupported)**.
    - These door types won’t have a support stick to rest on.
    - The handle type and handle position are set simultaneously for L-shaped sections.

3. Added double door options in fittings
    - Double doors (4ft by 7ft) can now be added directly from **Fittings > Doors**.

4. Windows appear dark in daylight renders
    - Updated the background image for daylight renders.

5. Disabled room locking when furnishings are inside the room
    - Occupied rooms can now be selected, moved, and scaled without holding the `SHIFT` key.

6. Implemented snaps for room scaling
    - Rooms will now snap to the boundaries of other rooms when scaled.
