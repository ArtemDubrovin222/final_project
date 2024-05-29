The final goal of this project is to train a model that can predict the amount of energy produced for each day depending on the weather.
During this project there will be different methods used to collect, to prepare and to visualise data.
The data was loaded from: https://www.kaggle.com/datasets/l3llff/wind-power/data
Some additional data is being scrapped using web scrapping: from: https://en.wikipedia.org/wiki/Wind_power_in_Germany#By_State
Data is being scrapped using API: https://meteostat.net/
A link to my tableau public: https://public.tableau.com/app/profile/artem.dubrovin/viz/final_project_17165459307760/Dashboard1?publish=yes
The idea is to use MW dataset and to combine it with 1 mean dataset, that is build from 3 weather datasets of airports of Cologne, Hamburg and Berling.
The reason of doing it this way is because the highest concentration of turbines is located on the north of Germany and if you draw a line between those places, then you will have the highest concentration of turbines in Germany. (Plus there're also turbines on North and Baltic sea, which makes it more logical to take those north locations for me)