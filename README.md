I started by reading in and outputing the file, using the ifstream function discussed in lectures. Intially I tried to seperate the data types using the spaces as a delimiter, but ran into issues with the course names being split up. To get
around this I used the erase function to make three strings for each line and then combine each catergory into a vector and convert to the proper data type. Next I worked on my mean and standard deviation functions, which I then used to
output the statistical data. I also made a year function which outputs all the data for a given year if requested, and also has the option to end the program by entering 0. I used a while loop to ask the user if they want to repeat the code, so the year function will only be called if the Repeat='y' and Year =! 0, since inputing the year as 0 is the option to terminate the program. Finally, I tried to add the option to sort the outputs by course name, but my method didnt
work so is left out

AI use: 

I used AI on a few occasions to help identify where my code was running into issues
