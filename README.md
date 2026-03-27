# Pit-Stop-Strategy-Optimization

In Formula 1 motorsport racing, a pit stop refers to a scheduled stop during the race where a driver pulls into the team’s pit box for services such as tire changes, minor repairs, or front wing adjustments. While necessary, pit stops cause a temporary loss of track position as the car slows down, stops, and then rejoins the race. Therefore, the timing of a pit stop can have a critical impact on a driver's race outcome. A well-timed pit stop not only minimizes time loss but can also create strategic opportunities for overtaking and gaining positions on track.

In the high-stakes environment of the Monaco Grand Prix, the race is often won or lost on the pit wall rather than the asphalt. Because the narrow, guardrail-lined circuit offers almost zero opportunity for traditional overtaking, the pit window represents the only viable "passing zone" available to a team. This shifts the focus from raw mechanical horsepower to the precision of the strategists' timing, where a single second of hesitation or a poorly calculated release into traffic can result in a permanent loss of track position. Ultimately, optimizing the pit stop is not just a tactical choice but the primary mechanism for navigating the unique constraints of Monte Carlo, ensuring that a driver’s potential is not dictated by the car in front, but by the efficiency of the team behind them.

To address this challenge, this project uses machine learning models trained on historical race data from the Monaco Grand Prix (2018–2024) for drivers from Ferrari, Mercedes, Red Bull, and McLaren — four of the top-performing teams in Formula 1. The problem this project addresses is twofold:

1. ***Optimal Pit Lap Prediction:*** Estimating the most advantageous lap for executing a pit stop based on tire wear patterns, stint dynamics, and race conditions.

2. ***Short-Term Position Gain Prediction:*** Classifying whether a pit stop at a given lap will result in a net positional gain within a 5-lap window after the stop.

By leveraging features such as tire degradation, stint progression, compound type, lap pace trends, and safety car periods, the models aim to provide data-driven support for pit stop decisions. Focusing on immediate post-pit track position changes enables teams to maximize clear-air opportunities, avoid traffic, and gain critical race advantages which is a valuable strategy at a circuit like Monaco, where even a single position gain can significantly impact the final outcome..
