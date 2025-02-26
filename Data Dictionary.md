---
title: "FIFA 21 Data Dictionary"
---

# FIFA 21 Data Dictionary

This document provides an overview of the variables in the FIFA 21 dataset, including their definitions and data types.

| **Category**         | **Column Name**        | **Data Type** | **Description** |
|----------------------|----------------------|--------------|----------------|
| **Player Information** | ID                  | int          | Unique identifier for each player |
|                      | Name                | string       | Full name of the player |
|                      | Nationality         | string       | Country of origin of the player |
|                      | Age                 | int          | Age of the player in years |
|                      | Club                | string       | Current football club of the player |
|                      | Positions           | string       | The positions the player can play on the field |
|                      | Best Position       | string       | The primary playing position of the player |
|                      | Preferred Foot      | string       | Dominant foot of the player (e.g., Left, Right) |
|                      | Joined              | string       | Date when the player joined the current club |
| **Physical Attributes** | Height             | float        | Player height in centimeters |
|                      | Weight              | float        | Player weight in kilograms |
| **Ratings**         | ↓OVA                 | int          | Overall rating of the player |
|                      | POT                 | int          | Potential rating of the player |
|                      | BOV                 | int          | Best overall rating of the player |
| **Financial Information** | Value         | float        | Estimated market value of the player in Euros (€) |
|                      | Wage                | float        | Weekly wage of the player in Euros (€) |
|                      | Release Clause      | float        | Buyout clause for the player in Euros (€) |
| **Skill Ratings**   | Attacking           | int          | Overall attacking capability |
|                      | Crossing            | int          | Ability to deliver crosses |
|                      | Finishing           | int          | Shooting accuracy for scoring goals |
|                      | Heading Accuracy    | int          | Ability to score using headers |
|                      | Short Passing       | int          | Ability to make short passes accurately |
|                      | Volleys             | int          | Skill in striking a ball before it hits the ground |
|                      | Dribbling           | int          | Ball control and maneuverability |
|                      | Curve               | int          | Ability to curve shots or passes |
|                      | FK Accuracy         | int          | Accuracy in free kicks |
|                      | Long Passing        | int          | Accuracy in making long-distance passes |
|                      | Ball Control        | int          | Overall ball control ability |
| **Movement & Physical Attributes** | Acceleration | int | How quickly the player reaches top speed |
|                      | Sprint Speed        | int          | Maximum running speed |
|                      | Agility             | int          | Quickness and flexibility in movement |
|                      | Reactions           | int          | Responsiveness to game situations |
|                      | Balance             | int          | Stability while running or turning |
|                      | Shot Power          | int          | Power behind a shot |
|                      | Jumping             | int          | Ability to jump high |
|                      | Stamina             | int          | Endurance to sustain performance over time |
|                      | Strength            | int          | Physical strength |
|                      | Long Shots          | int          | Ability to score from long distances |
| **Defensive Attributes** | Defending       | int          | Overall defensive capability |
|                      | Marking             | int          | Ability to track opponents |
|                      | Standing Tackle     | int          | Effectiveness of standing tackles |
|                      | Sliding Tackle      | int          | Effectiveness of sliding tackles |
|                      | Interceptions       | int          | Ability to read and intercept passes |
| **Goalkeeping Attributes** | GK Diving   | int          | Ability to dive for saves |
|                      | GK Handling         | int          | Ability to catch and control the ball |
|                      | GK Kicking          | int          | Distance and accuracy of goal kicks |
|                      | GK Positioning      | int          | Ability to position correctly in goal |
|                      | GK Reflexes         | int          | Speed of reactions to shots |
| **Additional Attributes** | Total Stats  | int          | Sum of all player attribute ratings |
|                      | Base Stats          | int          | Sum of key base attribute ratings |
|                      | W/F                 | string       | Weak foot rating (1-5 stars) |
|                      | SM                  | string       | Skill moves rating (1-5 stars) |
|                      | A/W                 | string       | Attacking work rate (e.g., Low, Medium, High) |
|                      | D/W                 | string       | Defensive work rate (e.g., Low, Medium, High) |
|                      | IR                  | string       | International reputation (1-5 stars) |
|                      | Hits                | int          | Number of times the player’s profile has been viewed |

This dictionary serves as a reference to understand the structure and meaning of the dataset used in FIFA 21 player analysis.

