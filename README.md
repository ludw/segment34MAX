# Segment34 MkII
A watchface for Garmin watches with a 34 Segment display

![Screenshot of the watchface](screenshot.png "Screenshot")

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
https://apps.garmin.com/apps/aa85d03d-ab89-4e06-b8c6-71a014198593

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


## Change log
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