# Data-for-social-good-project
My project for AP comp sci A - Unit 3
# Unit 3 - Data for Social Good Project 

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need. 

## Requirements 

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program: 
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors. 
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about. 
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs. 
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset). 
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions. 

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

> As an [Journalist], <br> 
> I want to [find out cancellation rates for airlines], <br> 
> so that I can [find the best airline to get to my events on time ]. 

## Dataset 

Include a hyperlink to the source of your dataset used for this project. Additionally, provide a short description of each column used from the dataset, and the data type. 


Dataset: https://www.kaggle.com/datasets/umeradnaan/flight-delays-dataset/data
- **Cancels** (String) - Indicates whether a flight was cancelled true or not
- **Delay Minutes** (double) - Represents the delay time (in minutes) for each flight
- **Total flights** (int) - total number of flights analyzed based on the delayMinutes array length


## UML Diagram 

Put and image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one work, otherwise it might not properly get display on this README. 

![UML Diagram for my project] https://docs.google.com/drawings/d/14NajWU75T3YCCwAhL4mt8fdQxjVdy3k6MtBEwUEQVjk/edit

## Description 

Write a description of your project here. In your description, include as many vocab words from our class to explain your User Story, the chosen dataset and how your project addressed that users goals. If your project used the Scanner class for user input, explain how the user will interact with your project

Our project is about data for social good. We had to crete a program that outputs data that could possiby help people around us. We decided to create a program that outputs flights with cancellation rates. The data structure in airlines.java traverses through the data with an enhanced for loop. Each time it found a “true” for a flight cancellation in the delays.txt file, it added a count to the int trues. The method then returns a statement showing the flights that were cancelled out of the total number of flights. This is done by looking at the value the variable trues holds and the length of the delayMinutes 1D array. To add up the average minutes of delyas, in airlines.java, a code calculates the average delay time, in minutes, by adding up all the values within the delayMinutes array under a total delay double and dividing by the delayMinutes array’s length. This outputs the average delay time in minutes.This program would help a user if they have a job that requires to travel often to for example, important meetings that would help them know how high the cancelation rates are for each airline and helps choose the airline with the least cancelation rates to ensure there are no delays.  