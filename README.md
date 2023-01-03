# Impact of consumers diets on C02 emission and deforestation

## WHAT IS IT?

This model attempts to demonstrate the impact of the food diet choices on carbon dioxide emissions (CO2) and deforestation.

The model focuses on the two scenarios: a world with people having a standard omnivore diet and a world with people feeding exclusively on a plant-based diet.

![Alt text](/model_overview.png)

## HOW IT WORKS

- The model creates an initial land structure composed of forest, farming crop land, and farming livestock (for omnivore diet only).

- Crops and livestock produce food and emit carbon dioxide (CO2s) onto the atmosphere.

- The CO2s travels in either direction.

- Forests capture the CO2s.

- The human population is initialised at 7.5M individuals. The population grows according to time and they consume food.

- We track the food security, which is the difference between the quantity of food produced by the land and the quantity of food consumed by the population.

- If the value of food security is negative the deforestation occurs and the forest is replaced by farming crops and livestock.

## HOW TO USE IT

**Setting up initial map**  
This model can be initialised by clicking one one of the two buttons:  
- ‘setup-omnivore’: this will setup forest, livestock farmed land and crop land.  
- ‘setup-plant-based’ : this will setup forest and crop land.

**go**  
starts and stops the simulation.

**Hide CO2**  
If the model slows down, you can click on ‘Hide CO2’, this will hide the CO2s molecules and make the model faster.

**population-growth-rate**  
Sets the growth rate of the word population.

**Food-security-migitation**  
Selects by which source of food will be produced from the deforestation.  
The forest can be replaced by crops only or by crops and livestock.

## THINGS TO NOTICE

-   Both omnivore diet and plant based diet lead to deforestation. However the speed of the deforestation on an omnivore diet faster.
    
-   A plant based diet leads less CO2 released onto the atmosphere
    

## THINGS TO TRY

1.  Running the model initialising the land based on a plant-based diet and omnivore diet
    
2.  Changing the population growth rate
    
3.  Selecting the forest will be replaced by crops or crops and livestock to sustain food availability
    

## EXTENDING THE MODEL

These are some of the ways to extend this model further:

-   Add land where there is no forest and no farming is possible, with a more accurate representation of the land distribution
-   Make livestock consume crops
-   Set up an accurate food quantity produced based on calories for meat and crops
-   Set up an accurate green of gas emission for livestock and crops
-   Set up an accurate carbon sink by the forest
-   Set up and accurate food quantity consumed based on calories
-   Add a slider allowing to select the average quantity of animal product consumed per week

## CREDITS AND REFERENCES

If you mention this model or the NetLogo software in a publication, we ask that you include the citations below.

For the model itself:

-   Kouidri, A.. NetLogo Climate Change model. Impact of food choices on CO2 emission and deforestation. Data ScienceTech Institute (DSTI), France.

Please cite the NetLogo software as:

-   Wilensky, U. (1999). NetLogo. [http://ccl.northwestern.edu/netlogo/](http://ccl.northwestern.edu/netlogo/). Center for Connected Learning and Computer-Based Modeling, Northwestern University, Evanston, IL.