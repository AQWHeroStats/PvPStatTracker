## Project Description
- We have parsed game packets from [this PvP Match](https://hero.pics/PvP/999786) and produced the plots you see below. Note that the code is higly modular and can be repeated for any match played. 
- This is a demonstration, for final deployment the code would need to be deployed to a server and allow users to query games from the frontend.
- We provide a brief sample analysis with each graph.

## Interactability
- We use Plotly, a Python (and JS) based plotting library that allows for interactive visualizations to be made. Click on the legend to isolate traces or click on dropdown menu(s) to change the data displayed. 
- **Hovering over the charts with your mouse will display additional details.**

## Individual Stats Over Time
**Click the dropdown menu to change views**
- Comparing the damage dealt traces of Dragonoid and Axell5, we see that Dragonoid was able to out-damage Axell5 near the end of the match, likely leading to his team winning.
- Redsnake_ was able to stay at or above Zephite's total healing, also contributing to his team winning.

## Individual Target Selection
- Both teams took on a strategy of having thier damage dealer target the enemy healer/bard while thier healer targeted the enemy damage dealer.
- Hus dealt a large share of his damage to mobs, largely indicating that his team dominated mana regeneration.

## Team Stat Share
**Click the dropdown menu to change views**
- The share of damage recieved on both teams was split about evenly between the three players.
- Despite this, both damage classes (Axell5 and Dragonoid) died the majority of times on both teams.

## Team Stats Over Time
**Click the dropdown menu to change views**
- Looking at total team kills, 1150 seconds is a good place for Team A to review the game tape, as they had a 24-17 lead, and let Team B creep back into the game, making it a close ending. 
- Team A consistently had higher mob damage than Team B, suggesting that they controlled the middle room for most of the match. 

## Team Stat Lead Over Time
**Click the dropdown menu to change views**
- Team A was consistently able to deliver more damaget than Team B.

## Damage Distribution
- Although Axell5's maximum damage (4.9K) was higher than that of Dragonoid, Dragonoid's median damage was 30 points higher than Axell5.

## Healing Distribution
- Tystnad's median heal recieved was 1000 points higher than Hus. 
