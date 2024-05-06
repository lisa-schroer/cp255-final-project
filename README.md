# Bike- and pedestrian-related collisions along Berkeley's bike boulevard network
### Lisa Schroer | May 6, 2024 | CYPLAN 255 Final Project

![bblvd_pic](https://github.com/lisa-schroer/cp255-final-project/assets/157168522/c1f9f7fa-c059-49f4-b327-6ac8cc7ff707)

## 01 Research Question
#### For the purpose of this project, I chose to answer the question, "are bike boulevards equitable?" through an analytical safety lens. The following analysis uses bike and pedestrian collision data to understand how collision density varies along Berkeley's bike boulevard network. Bike boulevards are often lauded by planners as safe and comfortable facilities for all ages and abilities. However, given the historical disadvantagement of West Berkeley and the lack of robust intersection improvement recommendations in Berkeley's 2017 Bicycle Master Plan, my hypothesis is that some segments of the bike boulevard network are more safe than others.  

## 02 Data
#### - Bike network data from the Berkeley Bicycle Plan Update (in-progress, expected in 2023 but plan is delayed) // shapefile
<img width="251" alt="Picture2" src="https://github.com/lisa-schroer/cp255-final-project/assets/157168522/b7c0c183-cd41-4537-8500-d4b03d0fc389">

#### - Collision data from UC Berkeley TIMS over a 5-year period from January 2018 to December 2022 // csv
![Picture3](https://github.com/lisa-schroer/cp255-final-project/assets/157168522/8f5f4970-88cd-4093-99cf-6c7f3745a288)

## 03 Methodology
The following graphic outlines the steps I took to answer my research question. I first cleaned both data sets to isolate my variables of focus, then I performed a spatial join between mapped bike and pedestrian collision points and buffered 300 foot long bike boulevard line segments. Following the spatial join, I then calculated the ratio of bike and pedestrian collisions compared to total collisions for each segment, and then normalized the ratio per foot of bike boulevard. 
![1714928801772-de66315a-d321-4e58-8239-b4e1aa2b9087_4](https://github.com/lisa-schroer/cp255-final-project/assets/157168522/d5bf9182-43b0-45fd-b87b-6e11062e549b)

## 04 Key Findings
The map below shows bike and pedestrian collision density along Berkeley's bike boulevard network. As shown through the clustering of higher density segments (darker blue), we can see that bike and pedestrian collisions are not evenly distributed along the network. Rather, some areas of the bike boulevard network experience higher rates of collisions compared to others. Notable locations with higher densities on the map below include: California Street north of University Avenue, the intersection of Russell Street and Adeline Street, Channing Way between Sacramento Street and MLK Jr Way, and the intersection of Hillegass Avenue and Dwight Way.  
![Picture4](https://github.com/lisa-schroer/cp255-final-project/assets/157168522/2325ec35-b3ee-4e09-9838-a17958a90c52)

<img width="287" alt="picture7" src="https://github.com/lisa-schroer/cp255-final-project/assets/157168522/01ddc454-500a-4a01-8f6d-3727b752ee86">

![Picture6](https://github.com/lisa-schroer/cp255-final-project/assets/157168522/19c20b79-6d4d-4388-afd7-f5eb52df8cd7)
![Picture5](https://github.com/lisa-schroer/cp255-final-project/assets/157168522/98f190f2-0370-4ef8-a3f9-58f8f26513c6)

## 05 Implications


## 06 Limitations


