# Cricket All-Rounder Analysis

A Python data analysis project using Pandas to analyze cricket all-rounders.

## Features
- Lists the top 50 all-rounders
- Highest wicket taker
- Highest run scorer
- Best batting average
- Best bowling average
- Best strike rate
- Least economy
- Top 5 all-rounders using a custom scoring system

## Technologies Used
- Python
- Pandas
- Jupyter Notebook

## Dataset

The dataset contains the following attributes:

- Player
- Country
- Runs
- Wickets
- Batting Average
- Bowling Average
- Strike Rate
- Economy
- Bowling Type
- Batting Hand

## Scoring System

The project calculates an overall score using weighted batting and bowling statistics.

The score is calculated using:

Score =
(Runs × 0.01)
+ (Wickets × 0.35)
+ (Batting Average × 0.20)
− (Bowling Average × 0.15)
− (Economy × 0.15)
+ (Strike Rate × 0.14)

Higher scores indicate better all-round performance.

## Limitations

This project uses a custom scoring formula and has some limitations:

- The weights are chosen manually and may not match official cricket rankings.
- Raw career statistics are used instead of normalized values, so players with exceptionally high career totals may receive an advantage.
- Match conditions, opposition strength, era, and match format (Test, ODI, T20) are not considered.
- The ranking is intended for educational purposes and should not be considered an official ranking of all-rounders.

## Future Improvements

- Normalize all statistics before calculating scores.
- Create separate rankings for Test, ODI, and T20 cricket.
- Add visualizations using Matplotlib.
- Build an interactive dashboard using Streamlit.
- Include additional metrics such as catches, match-winning performances, and ICC rankings.

## Author
Kishan A S
