# VBA_Challenge
 
Overview of Project

The purpose of this analysis was to compare the perforfance of 12 stocks in the green energy sector by the average daily volume and the year-over-year return. Two scripts were written with the same ouput to analyze the performance of the code. The conclusion can be made that the code runs more effieciently with the refractored script.  
 
 Results
 
  <img width="248" alt="Screen Shot 2022-09-07 at 9 41 02 AM" src="https://user-images.githubusercontent.com/111692952/188893176-44be46c5-f027-4a6a-b751-d2ee1f7fc441.png"> <img width="248" alt="Screen Shot 2022-09-07 at 9 42 01 AM" src="https://user-images.githubusercontent.com/111692952/188893397-f29a6aef-d873-455f-b704-92de602932f1.png">

Looking at the stock performance between 2017 and 2018, it is clear that the green energy sector performed significantly better in 2017 with 11 out of 12 stocks giving positive returns and 4 out of 12 with returns higher than 100%. This level of perfromance is indicitive of a bubble and prices came back to ground in 2018 with only 2 out of 12 stocks with positive returns and all others performing very poorly. 
If I were to give the client advise on building a diversified portfolio based on our findings I would suggest putting 20% in ENPH, 20% in RUN, 20% in AY, 20% in SEDG, and 20% in VSLR as these stocks showed the highest returns for the two years with the lowest volatility in price swings. 

Original Code:

<img width="261" alt="Screen Shot 2022-09-07 at 9 52 37 AM" src="https://user-images.githubusercontent.com/111692952/188895740-c8d31a3e-6bfd-471c-896f-a535b0ee207e.png"> <img width="262" alt="Screen Shot 2022-09-07 at 9 53 21 AM" src="https://user-images.githubusercontent.com/111692952/188895854-8964beca-0140-4483-919b-abeeac46129d.png">

Refractored Code:

<img width="260" alt="Screen Shot 2022-09-07 at 9 54 02 AM" src="https://user-images.githubusercontent.com/111692952/188895998-fdde9e74-11d3-470b-b31d-23b06a636f69.png"> <img width="261" alt="Screen Shot 2022-09-07 at 9 54 22 AM" src="https://user-images.githubusercontent.com/111692952/188896096-bd4dd300-d224-4246-9f3f-312f2ec27b0e.png">

Looking at the code performance between the original code and refractored code, it is clear that the refractored code performs significatly better, with a run time of 0.08 seconds on average versus 0.3 seconds for the original code. The refractored code using for loops seperately, while the original code used one for loop with nested loops inside which caused the program to iterate the data over and over again causing higher run times. 

Summary 

The advantaged of refractoring code is to make the code run more efficient, make the code more readable, add comments, remove unneccessay code, and fix any issues that may be in the code. The main disadvantages are the extra time involved in going through the entire code and changing it and it may cause unwanted errors in the code that were not there before. 

The original code had nested loops that were not needed and a bit disorganized, our refractored code was able to make the program run faster and create a more readable code that looks better to present to the client. 




