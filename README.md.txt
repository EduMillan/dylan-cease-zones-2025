# Dylan Cease (2025): Pitch Location, Command & Whiff Zones

## Objective
This project analyzes the pitch location and command of Dylan Cease during the 2025 MLB season, with a focus on identifying where swings and misses are generated for different pitch types.

## Data
- Source: MLB Statcast (Baseball Savant)
- Accessed via: pybaseball
- Season analyzed: 2025 (in-season)
- Pitcher: Dylan Cease

## Methodology
1. Downloaded pitch-by-pitch Statcast data for the 2025 season.
2. Filtered pitches with valid location data (`plate_x`, `plate_z`).
3. Identified swings and whiffs using Statcast pitch descriptions.
4. Visualized pitch locations and overlaid whiff events to evaluate command and effectiveness by pitch type.

## Results
- The slider generates the majority of its whiffs in the lower, glove-side region of the strike zone and just outside of it, indicating a clear reliance on chase rather than in-zone dominance.
- This location pattern suggests the slider functions primarily as a put-away pitch, where command and late movement are critical.
- The four-seam fastball is predominantly located in the upper portion of the strike zone, often on the outer half.
- The fastball appears to function more as a setup pitch, disrupting the hitter’s visual plane and increasing the effectiveness of secondary offerings.

## Conclusion
Early-season data from 2025 suggests Dylan Cease continues to rely on a vertically separated approach, pairing elevated fastballs with low, glove-side sliders to generate swings and misses. This spatial pitch strategy highlights the importance of command and intentional location over raw velocity alone.

## Tools
- Python
- pandas
- matplotlib
- pybaseball

## Visualizations
### Slider Whiff Zones (2025)
![Slider Whiff Zones](figures/zone_whiff_sl_2025.png)

### Fastball Whiff Zones (2025)
![Fastball Whiff Zones](figures/zone_whiff_ff_2025.png)
