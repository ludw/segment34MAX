# Segment34 MAX
A watchface for Garmin watches with a 34 Segment display

The watchface features the following:

- Time displayed with a 34 segment display
- Phase of the moon with graphic display
- Heartrate or Respiration rate
- Weather (conditions, temperature and windspeed)
- Sunrise/Sunset
- Date
- Notification count
- Configurable: Active minutes / Distance / Floors / Time to Recovery / VO2 Max
- Configurable: Steps / Calories / Distance
- Battery days remaining (or percentage on some watches)
- Always on mode
- Settings in the Garmin app


## Frequently Asked Questions
https://github.com/ludw/Segment34mkII/blob/main/FAQ.md

## IQ Store Listing
https://apps.garmin.com/apps/3261679c-602d-457d-81a2-27e3c39ad5c3

## Buy me a coffee (if you want to)
[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/M4M51A1RGV)

## Contributing (code)
Pull requests are welcome, but please follow the following guidelines:
- For larger changes, **please open an issue first** and discuss what you have in mind.
- Keep PRs small, don't do a lot of different changes at once.
- Explain what you have changed and why.
- Only submit code you have actually run and tested (on all supported screen sizes).
- Remeber that watch faces has to be performant and memory efficient.
  Changes that significantly increase memory use or degrade performance will be rejected.
- For optimizations, please provide memory and profiler comparisons.
- Try to keep the code in the same style as the rest of the project.
   - Indent with four spaces.
   - local variables with snake_case.
   - function and global variables names with camelCase.
   - cache all properties.
   - use comments only when they add value.
     Explain things that look strange or values that has to be looked up to be understood.

 ## TODO / Things people have asked for
- Localization
- Adjustable font size
- Goal completion marker
- Pressure trend
- Race predictions
- Weather caching
- Monthly run/bike distance
- Font options for bottom fields as well (lines, blended, dots)

## Change log
2026-02-03 v1.8.0
- Improvements when field width is 2
- New field size option: 3, 2, 3
- Experimental support for CGM data from CGM Connect Widget
- Larger battery icon

2025-09-30 v1.7.2
- Support for Venu 4

2025-09-12 v1.7.1
- Support for Fenix 8 Pro

2025-09-01 v1.7.0
- AOD mode that shows all the fields (must be enabled in settings)

2025-06-10 v1.6.3
- Fixed issue with sunset

2025-06-08 v1.6.2
- Fixed crash

2025-05-29 v1.6.1
- Support for fr570
- Fixed bug with press to toggle night theme

2025-05-21 v1.6.0
- Fixed issue with weather not always updating properly
- Support for Fr970

2025-05-18 v1.5.1
- Added support for Descent G2

2025-05-18 v 1.5.0
- Custom themes replaced with a online theme designer, all colors can now be customized. If you have usef custom color themes 1-4 you must unfortunately recreate the theme you want at https://ludw.github.io/designer and then copy over the color codes to the watchface settings after you have updated.

2025-05-04 v 1.4.0
- Option for smaller font size on bottom fields

2025-04-30 v 1.3.1
- Minor layout adjustments on some watches

2025-04-26 v 1.3.0
- Clip issue for seconds on MIP
- Added UV Index as option


2025-04-26 v 1.2.0
- More compact weather data to avoid overflow
- More choices for text lines

2025-04-25 v 1.1.0
- Weather caching for offline viewing
- Clip issues with seconds in inactive mode on some MIP devices
- Condensed weather conditions as option (and as default)
