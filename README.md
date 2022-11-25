# Pokemon_EDA
Data Visualization Assignment MDSC-303

> 21231  
> MDSC-303 (Data Visualization)  
> Assignment  

# Data
The dataset contains the varied stats(attack, defense, special attacks,..,japanese name,pokedex_number,generation,..,capture_rate,abilities,etc) of pokemons till generation 7.  
It is taken from kaggle: [The Complete Pokemon Dataset](https://www.kaggle.com/datasets/rounakbanik/pokemon)

# Features
- **abilities:** A stringified list of abilities that the pokémon is capable of having.
- **against_?:** Eighteen features that denote the amount of damage taken against a particular type of pokémon.
- **attack:** The base attack of the pokémon.
- **base_egg_steps:** The number of steps required to hatch an egg of the pokémon.
- **base_happiness:** Base happiness of the pokémon.
- **base_total:** Sum of hp, attack, defense, sp_attack, sp_defense and speed.
- **capture_rate:** Capture rate of the pokémon.
- **classification:** The classification of the pokémon as described by the Sun and Moon pokédex.
- **defense:** The base defense of the pokémon.
- **experience_growth:** The experience growth of the pokémon.
- **height_m:** Height of the pokémon in metres.
- **hp:** The base HP of the pokemon. It is short for Hit Point, which determines how much damage a pokémon can receive before fainting.
- **japanese_name:** The original Japanese name of the pokémon.
- **name:** The English name of the pokémon.
- **percentage_male:** The percentage of the species that are male. Blank if the pokémon is genderless.
- **pokedex_number:** The entry number of the pokémon in the National Pokédex.
- **sp_attack:** The base special attack of the pokémon.
- **sp_defense:** The base special defense of the pokémon.
- **speed:** The base speed of the pokémon.
- **type1:** The primary type of the pokémon.
- **type2:** The secondary type of the pokémon.
- **weight_kg:** The weight of the pokémon in kilograms.
- **generation:** The numbered generation which the pokémon was first introduced.
- **is_legendary:** Denotes if the pokémon is legendary.


# Table of Contents

1. [Load Libraries](#Load-Libraries)
1. [Data](#Data)
    1. [Features](#Features)
1. [Load Dataset](#Loading-the-Dataset)
1. [Data Preprocessing](#Data-Preprocessing)
1. [How Many Generations?](#How-many-generations?)
1. [Stats Summary](#Stats-Summary)
1. [Relationship Between Variables](#Relationship-Between-Variables)
    1. [Is there any correlation between stats?](#Is-there-any-correlation-between-stats?)
    1. [Any relation between hp, defense, attack and speed?](#Any-relation-between-hp,-defense,-attack-and-speed?)
    1. [Scatterplot for Attack vs Defense](#Scatterplot-for-Attack-vs-Defense)
1. [Change Over Time](#Change-Over-Time)
    1. [Pokemons introduced per Generation](#Pokemons-introduced-per-Generation)
    1. [Ranking Primary Types across Generations](#Ranking-Primary-Types-across-Generations)
1. [Comparision of Groups](#Comparision-of-Groups)
    1. [Primary & Secondary pokemons](#Primary-&-Secondary-pokemons)
    1. [Ghost vs Dark type pokemons](#Ghost-vs-Dark-type-pokemons)
1. [Part-to-Whole](#Part-to-Whole)
    1. [Filtering pokemons with best stats](#Filtering-pokemons-with-best-stats)
1. [Comparision between Datapoints](#Comparision-between-Datapoints)
    1. [Top Bests & Pikachu](#Top-Bests-&-Pikachu)
    1. [Comparing the First Three: Giratina, Palkia, Dialga¶](#Comparing-the-First-Three:-Giratina,-Palkia,-Dialga)
1. [Tables](#Tables)
    1. [Top 15 Common Abilities](#Top-15-Common-Abilities)
