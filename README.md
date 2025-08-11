# UV Irradiance Simulation App

## Description
Interactive browser app to simulate UV irradiance in a rectangular chamber. Users can adjust lamp wavelength, radiant flux, chamber geometry, exposure duration, and other parameters to visualize irradiance and dose. The app displays a real-time heatmap, numerical statistics, and includes a unit converter.

## How to Use
1. **Select Lamp Wavelength**  
   Choose between 222 nm and 275 nm lamps.

2. **Adjust Radiant Flux per Lamp**  
   Use the slider or input box to set the lamp output (1–1000 mW).

3. **Set Chamber Dimensions**  
   Define length, width, and height in centimeters.

4. **Set Exposure Duration**  
   Adjust the exposure time in seconds to calculate dose.

5. **Lamp Layout and Attenuation**  
   Select lamp arrangement (center or corners) and adjust attenuation coefficient (α) and reflection factor.

6. **Choose Analysis Plane**  
   Move the Z-plane slider to inspect irradiance at different heights.

7. **Probe Measurement**  
   Click on the heatmap to set a probe and read local irradiance and dose.

8. **View Statistics**  
   See mean, min, and max irradiance for the current plane, plus chamber-wide mean values.

9. **Use Unit Converter**  
   Convert between common irradiance (W/m², mW/cm², etc.) and dose units (J/m², mJ/cm², etc.) using the dedicated panel.

## Requirements
- Any modern web browser (Chrome, Firefox, Edge, Safari)
- No installation or server required

## Author
Developed for UV chamber irradiance simulation and visualization.
