# Subway's Yelp-Reviews Analysis and Data Visualization

This project aimed to assist Subway CEO John Chidsey in addressing the Subway Reviews Problem by analyzing Yelp's review data and creating informative visuals tailored to address the concerns of each level of management. The project was conducted as part of the Cornell University MSBA BANA 5440 Statistical Programming Course.

![alt text](https://github.com/dl754/Subways-Yelp-Reviews-Analysis-and-Data-Visualization/blob/main/Visualizaiton/Fig1_Rating_Trends.png)

## Table of Contents
1. [Demonstrated Skills](#Demonstrated&#32;Skill)
2. [Background](#Background)
3. [Usage](#Usage)
4. [Results](#Results)
5. [License](#License)

## Demonstrated Skills
* Data Cleaning using Pandas
* Data Visualizaiton using Matplotlib


## Background

Subway CEO John Chidsey received a report from his field officer that customers are unhappy with one of its stores in Milford, CT, where Subway is headquartered. Upon checking the online reviews for this store, he finds that the average rating received by the store is 3.2/5. John is concerned that if a store next to the headquarters is at 3.2/5, stores farther away might be performing even more poorly. 
John calls for an urgent meeting of the Head of Customer Service, the Head of Store Operations, the Head of Social Media, and the Chief Data Scientist (your boss). He expresses his concern and urges the team to take measures to improve the average ratings received across all stores in the U.S. to 4.5/5.
His team tells him not to worry by making the following statements: 

* Head of Customer Service: “Our ratings are gradually improving, and we will soon reach 4.5/5.”
* Head of Store Operations: “Sandwiches are a tricky business. All sandwich chains suffer from poor customer ratings.”
* Head of Social Media: “The goal of 4.5/5 is unreasonable for national chains like us. Only small, local, and boutique restaurants can achieve such high ratings.”
*	Chief Data Scientist: “It is well known that customers make the effort to give a rating only when they are either extremely angry or absolutely delighted with the     service. So online ratings are not reliable.”


## Usage

To run the simulation, simply input Command:
  simul = 1000
  ps = ProfitStimulation(simul)
  ps.loop_manufactured(). 
  
This will create an instance of the ProfitSimulation class with simul number of simulations, and then call the loop_manufactured method to perform the simulation and plot the results. You can adjust the value of simul to increase or decrease the number of simulations performed. Additionally, you can modify the parameters passed to the __init__ method of the ProfitSimulation class to simulate different scenarios.


## Results

![alt text](https://github.com/dl754/Newsvendor-with-Monte-Carlo-Simulation--Optimal-Production-Level/blob/main/output.png)


Optimal Production Units: 169, Maximized Profit: $17365.719

## License

MIT License

Copyright (c) [2023] [Konstantin Liu]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
