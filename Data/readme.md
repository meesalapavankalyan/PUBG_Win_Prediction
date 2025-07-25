
# PUBG Match Placement Prediction Dataset

## Overview

This repository (or location) contains the pubg.csv dataset, which is used in the [PUBG Win Prediction Project](Link to your main code repository here). This dataset comprises detailed in-game statistics for millions of PlayerUnknown's Battlegrounds (PUBG) matches, designed for predicting a player's final placement percentage.

## Dataset File

* pubg.csv: The main dataset file.
    * *Size*: Approximately 4.45 million rows and 29 columns.

## Data Description

The pubg.csv file contains comprehensive match and player statistics. Each row represents a single player's performance in a specific match.

### Columns

The dataset includes 29 columns with the following types:

* *Identifier Columns (Object)*:
    * Id: Player ID.
    * groupId: Group ID, identifying players who played together.
    * matchId: Match ID.
    * matchType: Type of the match (e.g., solo, duo, squad).
* *Performance Statistics (Integer)*:
    * assists: Number of assists.
    * boosts: Number of boost items used.
    * DBNOs: Number of enemies knocked out.
    * headshotKills: Number of kills via headshots.
    * heals: Number of healing items used.
    * killPlace: Placement in terms of kills.
    * killPoints: Elo-like rating based on kills.
    * kills: Number of kills.
    * killStreaks: Highest kill streak.
    * matchDuration: Duration of the match in seconds.
    * maxPlace: The highest placement possible in that match.
    * numGroups: Number of groups in the match.
    * rankPoints: Elo-like rating based on ranking.
    * revives: Number of times the player revived teammates.
    * roadKills: Number of kills while in a vehicle.
    * teamKills: Number of teammates killed.
    * vehicleDestroys: Number of vehicles destroyed.
    * weaponsAcquired: Number of weapons picked up.
    * winPoints: Elo-like rating based on winning.
* *Performance Statistics (Float)*:
    * damageDealt: Total damage dealt.
    * longestKill: Longest distance of a kill.
    * rideDistance: Total distance traveled by vehicle.
    * swimDistance: Total distance swum.
    * walkDistance: Total distance walked.
    * winPlacePerc: *Target Variable* - This is the player's final placement percentile (0.0 to 1.0).

## Source

This dataset is sourced from the PUBG Finish Placement Prediction competition on Kaggle. For further details and original context, please refer to the Kaggle competition page:

* [PUBG Match Deaths, Kills, and Placement on Kaggle](https://www.kaggle.com/c/pubg-finish-placement-prediction/data) (Ensure this link is current and correct)

## Usage

This dataset is intended for machine learning tasks, particularly for training models to predict player performance and match outcomes in PUBG.
