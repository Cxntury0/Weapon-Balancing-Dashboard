## Games Weapon Balancing by Weapon Rarity

Interactive Tableau Dashboard Project

## Live Dashboard (Tableau Public):
https://public.tableau.com/app/profile/nico.h.chler/viz/GamesWeaponBalancingbyWeaponRarity/GamesWeaponBalancingbyWeaponRarity

## Project Overview

This project analyzes weapon balancing across rarity tiers in a fictional game dataset.

The objective was to evaluate whether weapon attributes such as Attack Power, Range, and Durability scale consistently with rarity and to identify potential balancing inconsistencies that could impact gameplay fairness and player progression.

The dashboard was built in Tableau Public and designed to simulate a real-world game analytics scenario where design teams evaluate stat distribution across item tiers.

## Analytical Goals

This analysis aims to answer the following game design questions:

Do higher rarity weapons consistently provide stronger stats?

Is there proportional scaling between Attack Power and Range?

How does weapon durability compare across rarities?

Are certain rarity tiers over- or under-represented?

Does material type significantly influence weapon damage output?

## Dashboard Features
View Toggle: Dumbbell ↔ Bar Chart

Users can switch between:

Dumbbell Chart
Used to visually compare Average Attack Power vs Average Range per rarity tier.

Bar Chart
Displays the same metrics in a traditional comparative format for clearer numeric interpretation.

This dual-view approach allows both intuitive visual comparison and precise value analysis.

## Number of Weapons by Rarity

A distribution breakdown showing how many weapons exist in each rarity tier.
This helps contextualize whether balancing issues may be influenced by item volume.

🔥 Average Damage by Material (Heatmap)

Displays damage output across:

Weapon materials

Rarity tiers

The heatmap enables quick identification of:

High-performing material/rarity combinations

Potential material scaling imbalances

🛡 Average Weapon Durability (Treemap)

Provides a high-level comparison of durability by rarity tier.
This visual emphasizes structural balance beyond raw damage.

## Interactive Filtering

Users can:

Filter by rarity

Highlight specific tiers

Switch between visualization modes

## Key Insights

Common weapons display disproportionately high attack power relative to certain mid-tier rarities, suggesting potential early-game balancing inconsistencies.

Mythical weapons show the highest durability, but not always the highest attack power, indicating differentiated stat design.

Uncommon tier contains the highest number of weapons, potentially affecting balancing perception due to volume.

Material type significantly impacts damage output, even within the same rarity tier.

Some rarity tiers exhibit stronger range scaling than attack scaling, indicating non-linear stat progression.

## Tools & Technologies

Tableau Public

Kaggle dataset

Data visualization best practices

Dashboard UX design principles

No extensive data cleaning was required, allowing the project to focus primarily on analytical reasoning and visualization design.

## Dataset

Source: Kaggle

Dataset contains weapon attributes including:

Rarity

Attack Power

Range

Durability

Material

Data represents a fictional game scenario used for analytical demonstration.




















### Dataset License

The "Modern Weapons Dataset" used in this project is licensed under the 
[Database Contents License (DbCL) 1.0](LICENSE.txt). 
Use of the dataset is subject to the [Open Database License (ODbL) 1.0](https://opendatacommons.org/licenses/odbl/1-0/).

Original dataset source: [Kaggle – Modern Weapons Dataset](https://www.kaggle.com/datasets/bhadramohit/modern-weapons-dataset)
