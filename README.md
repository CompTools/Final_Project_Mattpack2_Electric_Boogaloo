# Final_Project_Mattpack2_Electric_Boogaloo


## People in Project

1. Vanessa Muhl
2. Juan H Piloto
3. Rebecca Molina
4. Danielle Bovie

Everyone in this group has participated in this repository

## Dataset

This project focuses on the flight dataset used for Problem Set2: /ufrc/bsc4452/share/Class_Files/data/flights.May2017-Apr2018.csv

## Project info

This project focuses on the flight dataset used for Problem Set2: /ufrc/bsc4452/share/Class_Files/data/flights.May2017-Apr2018.csv

The codes/functions focuse on the information provided in the column of 'WHEATHER DELAY.'

The codes for the functions will show how many total flights of the whole dataset were delayed, on time, or had no data available due to wheather delay. It will also allow for the user to input a desired airport code (LAX, SFO, GNV.....) to retrieve the number of wheather related delayed flights, on time flights, and the number of flights that have no data provided for the specific airport. 
Further more, graphs will be created. One graph plots the data from all of the wheather related delayed-, on time-, and no data flights. The other graph plots the same data but only from the desired (input) airport.   

The script includes the following flow control elements:
- for loop is used to read lines within the file and isolte the column needed to extract late flights, on time flights, and no data flights, which is found by using
- if statement is used primarily for the float command in order to find numbers within the data that are representative of being late, on time, or no data.
- two functions are used to define analyzing airports and flight delays.
- the module pandas and matplotlib are used for creating graphs.
- two graphs represents the data inputted from our code.
- a print command that allows the graphs to be saved as a PDF
