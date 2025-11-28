---
title: "SABR Taiwan Founding Talk: Introduction to Sabermetrics"
collection: talks
type: "Talk"
permalink: /talks/2018-01-19-sabr-taiwan
venue: "SABR Taiwan"
date: 2018-01-19
location: "Taipei, Taiwan"
---

This talk was given at the founding press conference of the Society for American Baseball Research (SABR) Taiwan Chapter (美國數據棒球學會台灣分會).

![SABR Taiwan Founding](/images/talks/sabr-taiwan-1.jpg)

The event marked the official establishment of the SABR Taiwan chapter on January 19, 2018. SABR was originally founded in the United States in 1971, and after 47 years, Taiwan finally established its own chapter, joining other countries like Japan, Korea, Venezuela, and the Dominican Republic. The goal is to catch up with Japan and Korea in baseball analytics within three years.

Professor Huang Chih-Hao (黃致豪) from the Department of Sports Information and Communication at National Taiwan Sport University (NTSU) spearheaded the effort. He introduced the military-grade "Trackman" radar system to NTSU's baseball stadium in 2016—the first of its kind in Taiwan. This system, widely used in MLB as part of "Statcast," captures detailed data such as spin rate, exit velocity, and launch angle.

![SABR Taiwan Event](/images/talks/sabr-taiwan-2.jpg)

Key attendees included former Brother Elephants player and current Philadelphia Phillies scout Wang Jin-yong (王金勇), as well as representatives from the Fubon Guardians and Chinatrust Brothers. Wang noted that while data analysis is crucial for scouting and player development, it also helps pitchers find ways to improve and answer questions about their performance.

![SABR Taiwan Group Photo](/images/talks/sabr-taiwan-3.jpg)

My presentation, titled "Introduction to Sabermetrics," introduced the fundamental concepts of modern baseball analysis. I discussed how data can be used to objectively evaluate player performance and strategy, moving beyond traditional "impression-based" evaluation. The full content of my talk is summarized in the article below.

---

## Beyond Batting Average: Unveiling the Truth of Baseball through Sabermetrics

### Introduction: The Limitations of Traditional Statistics

*   **Defining Sabermetrics**: The empirical analysis of baseball, focusing on objective evidence to evaluate performance.
*   **The Dilemma of Traditional Stats**: While metrics like Batting Average (AVG), On-Base Percentage (OBP), and Slugging Percentage (SLG) are ubiquitous, they possess inherent flaws:
    *   **Batting Average (AVG)**: A crude measure that ignores the value of walks and treats all hits (singles, doubles, home runs) as equal.
    *   **On-Base Percentage (OBP)**: While better than AVG, it treats every time on base equally (a walk is valued the same as a home run).
    *   **Slugging Percentage (SLG)**: Although it accounts for total bases, the standard 1:2:3:4 weighting for hits lacks a rigorous mathematical justification.

### Part 1: Offense – Redefining Offensive Value

Sabermetrics employs **wOBA (Weighted On-Base Average)** to provide a comprehensive assessment of a player's offensive contribution.

*   **The Core of wOBA**: Derived from the **Run Expectancy Matrix**, wOBA assigns precise run values to every offensive outcome (hits, walks, outs) based on the historical probability of scoring runs from various base-out states.
*   **Insights from Weights**: Analysis of 2017 CPBL data reveals that a home run (weight ~2.0) is worth slightly more than double a single (~0.9). Crucially, a walk (~0.78) holds nearly the same value as a single, highlighting the often-underrated importance of on-base ability.
*   **Advanced Metrics**:
    *   **wRAA (Weighted Runs Above Average)**: Converts wOBA into a counting stat, showing the number of runs a player contributes above the league average.
    *   **wRC+ (Weighted Runs Created Plus)**: A standardized metric that adjusts for park factors and league averages. A wRC+ of 100 is average; 196 indicates a player created 96% more runs than the league average.

### Part 2: Application – Separating Skill from Luck

**BABIP (Batting Average on Balls In Play)** measures the frequency at which balls hit into play (excluding home runs and strikeouts) result in hits.

*   **Factors Influencing BABIP**: Originally viewed as a proxy for luck, BABIP is now understood to be influenced by a complex mix of defense, defensive shifts, exit velocity, sprint speed, and batted ball profile (line drives yield the highest BABIP).
*   **Implications for Hitters**: Because BABIP correlates with skill, it should be evaluated against a player's career baseline. Speedsters like Ichiro Suzuki, for instance, consistently maintained a BABIP above .330.
*   **Implications for Pitchers**: A pitcher's BABIP tends to regress to the league average over time. Thus, it serves as a tool to identify whether an ERA is artificially inflated or deflated by defensive performance or luck.

### Part 3: Pitching – Isolating Performance from Defense

**FIP (Fielding Independent Pitching)** addresses the shortcomings of ERA, which is heavily dependent on team defense and luck.

*   **FIP Components**: Focuses solely on outcomes within the pitcher's direct control: Home Runs, Walks, Hit By Pitches, and Strikeouts.
*   **Measuring True Skill**: FIP directly quantifies a pitcher's individual contribution to run prevention by isolating events they control, offering a purer measure of pitching ability than ERA.
*   **Variants**:
    *   **IFFIP**: Adjusts FIP by treating infield fly balls as strikeouts, acknowledging that they are virtually automatic outs.
    *   **xFIP (Expected FIP)**: Normalizes home run rates to adjust for luck and park factors, providing a more stable long-term projection.

### Part 4: Defense – Quantifying Defensive Value

**UZR (Ultimate Zone Rating)** was developed to overcome the limitations of Fielding Percentage, which fails to account for range and play difficulty.

*   **The UZR Advantage**: By dividing the field into 78 distinct zones and analyzing batted ball type, speed, and location, UZR calculates the number of runs a player saves (or costs) compared to an average fielder.
*   **Nuanced Analysis**: UZR can distinguish between a fielder with exceptional range but occasional errors (high UZR) and one with limited range but few errors (negative UZR).
*   **Future Outlook**: With the advent of **Statcast** tracking technology, we can expect the development of even more precise defensive metrics that capture the exact route efficiency and reaction time of fielders.

### Part 5: Synthesis – The Ultimate Metric

**WAR (Wins Above Replacement)** represents the culmination of sabermetrics, synthesizing all contributions into a single figure: wins added to the team.

*   **Definition**: The number of additional wins a player provides compared to a "Replacement Level Player."
    *   **Replacement Level**: Represents a player readily available from the minor leagues or on a minimum salary (baseline set to zero value).
*   **Calculation (Position Players)**: Aggregates Batting (wRAA), Baserunning, and Fielding (UZR), adjusted for position and league context, converting run values into wins.
*   **Calculation (Pitchers)**: Primarily derived from FIP, converted to runs and then to wins.
*   **Interpretation**: WAR is an estimation; differences of less than 1.0 are generally considered statistically insignificant.

### Extra Insight: Objective Evaluation of Pitch Quality (QOP)

**QOP (Quality of Pitch)** seeks to evaluate the intrinsic quality of a single pitch, independent of the umpire's call, the batter's contact, or luck.

*   **Scoring (0-10)**: Utilizes PITCHf/x tracking data to analyze movement, velocity, and location relative to the strike zone borders.
*   **The "Perfect" Pitch**: Higher QOP scores are awarded to pitches that paint the corners of the zone, while pitches down the middle receive lower scores.
*   **Future Outlook**: With Statcast now providing granular data on spin rate and spin axis, we can anticipate even more sophisticated models that quantify the "stuff" of a pitch beyond just velocity and location.

### Conclusion: The Data Revolution

Advanced metrics like wOBA, FIP, and UZR ultimately converge into WAR, providing the baseball world with a high-precision scientific instrument. These tools empower teams and fans to move beyond surface-level statistics and understand the true, objective value of a player's contribution to victory. Looking forward, the granular tracking capabilities of Statcast promise to further revolutionize this landscape, as capturing the precise physical performance of players on the field will undoubtedly fuel the next generation of analytical breakthroughs.
