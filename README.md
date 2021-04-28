# EDA-Project-Houses-to-rent
In this repository I did exploratory data analysis of foreign exchange rates

Github link to repository: https://github.com/MadoDoctor/EDA-Project-Houses-to-rent

# Importing

In this exploratory data analysis we worked with packages:

* NumPy;
* Pandas;
* Matplotlib;
* Seaborn;
* CSV.

# Data pre-processing

We taked general info as shape and columns type, then removed the first column as it is repeating the index. By taking general info about columns, we know that several columns has object type. We changed "," to "" so we can get int columns. 

![image](https://user-images.githubusercontent.com/74544370/116436291-13fabb00-a86e-11eb-90c5-5993c2d148b2.png)

We changed the values of the columns that show the amount for digital data and change the column with the city, where 1 means the city. Incluso means inclusive, so we can change its value to 0. Sem info means that there is no information on this line, so we can simply delete these lines.

# Data visualization

We plotted a graph showing the number of houses: located in the city or not; for animals: allowed or not; is there furniture or not.

![image](https://user-images.githubusercontent.com/74544370/116437994-d72fc380-a86f-11eb-9e16-cd19a5f1aae6.png)

Then we plotted a graph showing the number of houses with different indicators. Just counted how many houses have one room etc. After that we plotted a graph of the average amount on whether the house is in the city or not with different indicators. We found the connection between the number of rooms and bathrooms.

## Getting statistical data

We found where the most expensive rental house is located and in total, we will do the same for the cheapest house. Then saw if there is furniture in the most expensive house and if it is possible to live there with animals, we do the same for a cheap house, we found the number of rooms in the most expensive house and the number of bathrooms,number of parking spaces, we do the same for the cheapest house.
