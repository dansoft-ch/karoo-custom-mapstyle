# Karoo Map Style – MTB Optimized

I've noticed that the default map on the Karoo has various inconsistencies and bugs. It's simply not ideal for mountain biking. That's why I've created this improved version.
This custom map style for the Hammerhead Karoo improves clarity, visibility, and usability for mountain biking.  

## ✨ Improvements

### More Visible Settlements
- Smaller towns and villages are now more prominently displayed, improving overview at lower zoom levels.

### Enhanced Terrain Readability
- Forests have been colored in a darker green tone to improve contrast with meadows and fields.

### Added Gondola and Narrow-Gauge Railways
- Cable cars and narrow-gauge mountain railways are now visible, aiding navigation in alpine terrain.

### Improved POI Icons
- Default black icons were hard to see while riding.
- The following POIs are now more visible and highlighted for cyclists:
  - **Bakery, Bank/ATM, Bike Shop, Grocery Store, Toilet, Café, Pharmacy, Hospital**

### Improved Residential Road Visibility
- Paved residential streets now appear more clearly, helping with orientation.
- Contour lines have been toned down to a subtle brown – inspired by Locus Map and Swisstopo.


## 🐞 Bug Fixes

### Town Names Overwritten by Smaller Settlements
- Smaller settlements no longer overwrite the name of the capital city.  
  **@Hammerhead Developers:** Please note, the higher the value of `priority`, the higher the display priority (priority 1 is the lowest).

### 1. Town Names Overwritten by Elevation Labels
- Elevation labels no longer replace town names.  
  **@Hammerhead Developers:** Again, higher `priority` = higher display priority.

### 1. Confusion Between Trails and Unpaved Roads
- Trails and unpaved roads were previously hard to distinguish.
  - Unpaved roads are now shown as solid dark gray lines.
  - Trails are now all shown in the same color (**pink**), instead of mixed styles (brown-white, white dashed).
  - Paved sections that were temporarily shown in yellow, green, blue, or brown outlines have been cleaned up for consistency.

### Hospitals Were Not Displayed
- Hospitals are now properly shown on the map – helpful in emergencies.
