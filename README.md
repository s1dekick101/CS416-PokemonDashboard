# Description
A data visualization of all Pokémon from Generations 1 - 6

## Content
All work used to create the visualization can be found in the "Dashboard" folder and within that directory there are the following:

* Datasets - Has the .csv files used for creating the Pokedex as well as another folder (Dataset-Merger) that contains the code used to merge and clean the Pokedex.csv 	and Pokemon.csv into the Pokemon_All.csv Pokemon_All.csv columns explained:
  * '#' - The unique Key value assigned to each Pokémon and its variant if applicable
  * Name - The name of the Pokémon 
  * Type 1 - The typing for the Pokémon 
  * Type 2 - The typing for the Pokémon and can be "NULL" 
  * Total - The total accumulation of the HP, Attack, Defense, Sp.Atk, Sp. Def, Speed values
  * HP, Attack, Defense, Sp.Atk, Sp. Def, Speed - A value that represents a Pokémon stat for that particular attribute 
  * Generation - The Pokémon generation in which the Pokémon belongs too
  * Legendary - A Boolean that’s tied to a Pokémon if it is legendary or non-legendary
  * CatchRate - The value associated with how difficult a Pokémon is catch (Side Note: The higher the catch rate the easier it is for the Pokémon to be captured)
* Tableau-Data-Source - Contains a ready to go Tableau workbook for anyone wanting to configure the data as they see fit        
* PokeDexVisualization - The Tableau workbook that was used for the visualization of the dataset 

## Link to Pokémon Dashboard 
https://public.tableau.com/app/profile/nicholas.o.brown/viz/PokeDexVisualization/Dashboard

## Data Set Sources 
https://www.kaggle.com/datasets/abcsds/pokemon 

https://bulbapedia.bulbagarden.net/wiki/List_of_Pok%C3%A9mon_by_catch_rate
