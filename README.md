# ECON860_midterm
//.............Part 1.............//
I. Requesting and Parsing//

//Requesting html page from the given webpage.//
//Using the beautiful soup to get into the html of the page for parse.//
//df_login: creates a column based on defined headings-login id,Repo cout, follower count, and member since.//
//For requesting the desired information, we will locate the place at higher level by find_all(class_='grid-cols-4').//
//Then we run a loop to locate <div> to get the required information//
//Hence, we create a dataframe with the pre-defined column and will keep adding the infomraiton for all the users.//

//II. Validating//
//For vlaidating: we will summarize the data to get a general informaitons.//

//Also, we cross check with orginial webpage infomraiton//

//Dropping all duplicates//

//Also, removing the invalid login id based on the observation that some Repos count has -1 along with follower. Also, the date is alo in 00000 fomrat. We also drop this from our final dataset.//

//Finally,
Saving the file into CSV format//


//.................Part 2.................///

//First, we import different packages required for us.//
//Second, we use githiub personal token. We are storing the id and token in different files. We recall these information by using f.() .// 
//We use this to extend our limit in accessing the infomration from the web page//

//Third, //
//I have created a loop to get into each user github page and extract the required information.//
//I have used the csv file obtained from part to extract the 'Login id'.
We use json to get a dictionary so that we can extract the required dataset.//

//Finally, We are saving this information to csv file//





.........Part 3.................
//We have used the describe commad to generate max,min,mean ,count and standard deviation.//
//For correlation, we have used Scatter plot.//
//For plot, we have created dataset by using .tolist .//
//Few varibales are chosen based on intuition which will be explained in detail in word file uploaded in exam folder.//
