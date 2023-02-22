# car-analysis-power-BI-
This is project on car price analysis on the basis of car model 
About dataset:
          The dataset of car_price we get on car selling websit. dataset contains price, model , make ,mileage,cylender .
        
   
Problem statement:
             - create a visualiztion using power BI dashboard to analys the car prices for various car models , also find more aspects which is impact the car price .
             - Create a decomposition tree for each car model .
         
Approch to solve the Problem:
               - dataset contians soo many missing values , spelling mistakes  for the handling spelling mistakes and missing values we clean dataset using pandas .
               - after handling the missing values we saved this cleaned dataset in new csv file for power BI analysis
               - for the first problem statement we try to visualize mileage of each car make using 'Pie chart'
               - to visualize the car prices by car_make we used 'bar_plot'
               - to find impact of mileage , make and car model on car price we used 'waterfall_chart'. waterfall_chart clearly show the impact of given feature on car                    price
               - for sencond problem statement we used decompositon tree for each  car model.
               
