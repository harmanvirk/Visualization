# Visualization
                        VISUALIZATION OF DAILY DEALS 

Visualization is the technique of the imagination through pictures or mental imagery to create visions of what we want to show and how to make them happen. Means to say we have to play with data. We are provided with huge amount of data, it's upto  us how we represent that data and extract impotant and useful information from that data. As we can't visualize the whole data without using any visualization technique because we are having large amount of data sets from which we can't find the end result which we want to show so we use visualization for that. For visualization we use charts and graphs to display the end result which we want to show.

OBJECTIVE:

To visualize the data set by using d3.js and give informative result from that.
Make charts for visualization

STEPS FOLLOWED:

1. The first step is to analyze the data and try to create an informative analysis on the basis of the data attributes.
2. Next is to querying and storing the data. Here I've used some attributes that are start_date, end_date, state, revenue, num_sold. For this the database used is mongodb.
3. Further I've started making front-end and for that I've used python for buliding a web server using flask and a html page.
4. Generating the charts is the last step. In this I've used d3.js library and a single function called 'dashboard'. This function contain three sub functions called 'histogram', 'piechart' and 'legend'. These sub functions handle all the initiation and interaction needs of the respective component. We will call the function dashboard by passing an id of a div element and data to its parameters.The D3 library creates HTML elements by attching data to them.

RESULT:

This represents the success of daily deals (number of deals sold) as according to the state and number of days a deal is offered. So from here we can know that in which state one day deal (or any number of days deals upto eight) should be offered for more profit. Also represents success (number of deals sold) in each state for number of days deals are offered (one to eight). So we can know that we should provide how much days deal to each state for more profit. Chart is displayed in which one is bar chart of states with number of deals sold in each state. The other is the pie chart which contains the number of days the deal was offered and changes the bar chart according to pie chart that we have selected. The legend displays the total number of deals sold of each state and percentage according to the total.
