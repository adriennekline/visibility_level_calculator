# visibility_level_calculator
Visibility Level Calculator App

The purpose of this application is to allow traffic engineers, vision scientists, or human factors to given a numerical quantity to how well (visibility level) a human with 20/20 vision can see a object based on distance, contrast, glare sources and their age.

Several parameters must be defined for the calculator to generate the visibility level (VL) for any given target with up to 5 glare sources. Specifically:

1. Target area (m^2) and distance (m) from the eye of the observer
2. The luminance of the target (cd/m^2) and the target background (cd/M^2)
3. Assessment of the disability glare illuminance (lux). Glare acts to increase the background luminance and to increase the contrast threshold. Its luminance in (lux), angles (deg) from the glare sources to the observer's eye, observer's age (yrs) and iris color (black, brown, light, very light) all feed into the calculation of the correction for disability glare.
4. The observer's age
5. Duration (s) over which the observer could view the target The VL calculator will use the preceding to calculate the VL contrast ratio

Created by Adrienne, Don, Theresa Kline
