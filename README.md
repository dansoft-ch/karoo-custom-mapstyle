# Karoo Map Style – MTB Optimized

I've noticed that the default map on the Karoo has various inconsistencies and bugs. It's simply not ideal for mountain biking. That's why I've created this improved version.
This custom map style for the Hammerhead Karoo improves clarity, visibility, and usability for mountain biking.

## Usage

1. Copy the `icons-dan` folder and the `offline_v14.xml` file to the root directory of your Karoo device.
2. Reopen the map view.
3. Enjoy. 

> [!TIP]
> Some Karoo software updates may require a different filename for the style XML file.  
> After copying the file, make sure to **rename it according to your Karoo software version**.  
> For example:
> - Software version **14** → `offline_v14.xml`
> - Software version **15** → `offline_v15.xml`

## Improvements

### More Visible Settlements
- Smaller towns and villages are now more prominently displayed, improving overview at lower zoom levels.

<img width="1000" height="800" alt="CityName" src="https://github.com/user-attachments/assets/8f28daac-7637-46f8-95a1-cb38a38d4b1f" />

### Enhanced Terrain Readability
- Forests have been colored in a darker green tone to improve contrast with meadows and fields.

### Added Gondola and Narrow-Gauge Railways
- Cable cars and narrow-gauge mountain railways are now visible, aiding navigation in alpine terrain.

<img width="1000" height="800" alt="Gondola-NarrowGauge" src="https://github.com/user-attachments/assets/30ff4a26-a9cd-4922-9549-b9daca606ac8" />

### Improved POI Icons
- Default black icons were hard to see while riding.
- The following POIs are now more visible and highlighted for cyclists:
  - **Bakery, Bank/ATM, Bike Shop, Grocery Store, Toilet, Café, Pharmacy, Hospital**
 
<img width="1000" height="800" alt="Icons" src="https://github.com/user-attachments/assets/3f9253cb-4b30-4d2b-aeec-8fff12fe1aa9" />

### Improved Residential Road Visibility
- Paved residential streets now appear more clearly, helping with orientation.
- Contour lines have been toned down to a subtle brown – inspired by Locus Map and Swisstopo.

<img width="1000" height="800" alt="Quartierstrasse" src="https://github.com/user-attachments/assets/1bdbd491-38af-402c-b3bc-f4c1a74e9752" />

## Bug Fixes

### Town Names Overwritten by Smaller Settlements
- Smaller settlements no longer overwrite the name of the capital city.  
  **@Hammerhead Developers:** Please note, the higher the value of `priority`, the higher the display priority (priority 1 is the lowest).

<img width="1000" height="800" alt="CityName" src="https://github.com/user-attachments/assets/9a76ef4a-64c8-4df9-a8a5-a42b68eda8d2" />

### Town Names Overwritten by Elevation Labels
- Elevation labels no longer replace town names.  
  **@Hammerhead Developers:** Again, higher `priority` = higher display priority.

<img width="1000" height="800" alt="CityName-Elevation" src="https://github.com/user-attachments/assets/2a27741a-b7c8-4b3f-b362-6b9d136a3e10" />

### Confusion Between Trails and Unpaved Roads
- Trails and unpaved roads were previously hard to distinguish.
  - Unpaved roads are now shown as solid dark gray lines.
  - Trails are now all shown in the same color (**pink**), instead of mixed styles (brown-white, white dashed).
  - Paved sections that were temporarily shown in yellow, green, blue, or brown outlines have been cleaned up for consistency.

<img width="1000" height="800" alt="Trails-Forrestroad" src="https://github.com/user-attachments/assets/5876db96-630c-4296-a155-2f8d56afa60a" />

### Hospitals Were Not Displayed
- Hospitals are now properly shown on the map – helpful in emergencies.

<img width="1000" height="800" alt="Hospital" src="https://github.com/user-attachments/assets/de25cd99-7e67-469e-9fb8-b8c057e7aee8" />

## Inspiration
- [www.openandromaps.org](https://www.openandromaps.org/)
