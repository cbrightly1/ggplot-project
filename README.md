# Quentin Tarantino + ggplot

This project involved replicating a FiveThirtyEight visualization using R's ggplot package. I chose to recreate a multiple dot plot visualization that utilized data from Quentin Tarantino movies. You can view the original article and plot [here.](https://fivethirtyeight.com/features/complete-catalog-curses-deaths-quentin-tarantino-films/)

### The Data Set
Quentin Tarantino movies are known for being full of swear words and lots of blood. This data set quantifies
the amount of profanity and death by stating when a character said a swear word and when someone died
throughout Tarantino’s most popular movies. The data set includes 7 movies, every swear word you could
think of, and the minute time in that movie when the death or swear word occurred.

### Project Highlights
* The dot plot was surprisingly difficult to manipulate due to some technical errors with the geom() function. The dot plot does not give a count of the dots as a y-axis as expected so text labels were used instead.
* Because of the erros with the geom() function, writing annotations was extremely difficult. The less desirable text labels with ggdraw() were used as a replacement.  

### Plot Comparison
Original on Left, Recreation on Right
![image](https://user-images.githubusercontent.com/47046823/120385634-abcc4880-c2f5-11eb-80d3-dac4cdd3834f.png)

