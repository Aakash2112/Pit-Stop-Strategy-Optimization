# Pit-Stop-Strategy-Optimization

In Formula 1 motorsport racing, a pit stop refers to a scheduled stop during the race where a driver pulls into the team’s pit box for services such as tire changes, minor repairs, or front wing adjustments. While necessary, pit stops cause a temporary loss of track position as the car slows down, stops, and then rejoins the race. Therefore, the timing of a pit stop can have a critical impact on a driver's race outcome. A well-timed pit stop not only minimizes time loss but can also create strategic opportunities for overtaking and gaining positions on track.

On circuits like Monaco where overtaking is notoriously difficult due to the narrow, twisting street layout — optimizing pit stop timing becomes even more crucial. Track position is often determined more by pit stop strategies than by raw on-track pace, making race strategy a key battleground for gaining or defending positions. The motivation for this project stems from the significant strategic impact of a precisely coordinated and effectively managed pit stop: even a small advantage gained during the pit window can be the difference between achieving a strong finish or becoming trapped behind slower competitors, severely limiting a driver’s race potential.

To address this challenge, this project uses machine learning models trained on historical race data from the Monaco Grand Prix (2018–2024) for drivers from Ferrari, Mercedes, Red Bull, and McLaren — four of the top-performing teams in Formula 1. The provlem this project addresses is twofold:

1. ***Optimal Pit Lap Prediction:*** Estimating the most advantageous lap for executing a pit stop based on tire wear patterns, stint dynamics, and race conditions.

2. ***Short-Term Position Gain Prediction:*** Classifying whether a pit stop at a given lap will result in a net positional gain within a 5-lap window after the stop.

By leveraging features such as tire degradation, stint progression, compound type, lap pace trends, and safety car periods, the models aim to provide data-driven support for pit stop decisions. Focusing on immediate post-pit track position changes enables teams to maximize clear-air opportunities, avoid traffic, and gain critical race advantages which is a valuable strategy at a circuit like Monaco, where even a single position gain can significantly impact the final outcome..
