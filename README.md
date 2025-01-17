## pandas-challange-JDAP

---

## Pandas Homework - Pandas, Pandas, Pandas

### Intention of the Repository

This Repository has been made to summit the homework assignment for my Data Science Bootcamp at Northwestern University

Pandas

Student: Jorge Daniel Atuesta

March, 2021

---

### Inside of this repository

The reader will encounter my solution to the homework assignment Pandas-challange. The repository is organized in folders and a README.md (The file you are currently reading). Please specifically look at the analysis portion of the excercise. Here is the list of the folders and its contents so you can navigate through them.

1. Images: In this folder you will find the images for the instructions provided by the institution. *You can skip this folder if you want*.
2. HeroesOfPymoli: In this folder you will find all the solutions for the HeroesOfPymoli excercise. Insided the folder you will find two other folders and one ipynb file:
   * 1. Folder ''Resources'': This fodler contains the CSV files I used.
   * 2. Folder ".ipynb_checkpoints": This folder holds the check points to my file. *You can skip this folder if you want.*
   * The FinalMain.ipynb file contains my script solution to the excercise. Please download it before checking it, as in GitHub .ipynb files tend to not display properly when it comes to the style of the doc.
3. PyCitySchools In this folder you will find all the solutions for the PyCitySchools. Insided the folder you will find two other folders and one .ipynb file:
   * 1. Folder ''Resources'': This fodler contains the CSV files I used"analysis"": This folder holds my text file that has the results from my analysis.
     2. Folder'.ipynb_checkpoints': This folder holds the check points to my file. *You can skip this folder if you want.*
   * The FinalMain.ipynb file contains my script solution to the excercise. Please download it before checking it, as in GitHub .ipynb files tend to not display properly when it comes to the style of the doc.

I hope you find my work to not only be complete but displaying all the knowledge learned throughout this portion of the Data Science Bootcamp at Northwestern University.

---

## Heroes Of Pymoli Excercise

### Project's Aim

Using Pandas I was tasked with analyzing the data for the recent fantasy game Heroes of Pymoli. As a first task, I had to generate a report that breaks down the game's purchasing data into meaningful insights

---

### Project Analysis

From the data analysis portion, the following data trends emerged:

The first trend observed in the data is the game is attracting more male players than other genders. As shown in the data, 84.03% of the players identify as male.

The second trend is interesting when it comes to the spending portion by gender. Suppose you look closely at the average spending per individual divided by gender. In that case, you can see that the people who identify as others spend an average of $4.56, individuals who identify themselves as females spend an average of $4.47, and individuals who identify themselves are as men spend an average of $4.07. With this said, it's important to note that more users identify as male forcing the spending average to diminish compared to the other genders. The critical part of this data trend is to let the company know of its success and potential customers behaviors (by gender), so they can decide if they want to target them as potential users or focus on users that identify themselves as male, knowing the revenue that each gender can provide.

The third data trend that is significant to point out is the user's average age. From the analysis, it is clear that most of the game's users fall within 20 – 24 years. Even though the game doesn't attract as many users from ages ten and under, this is a potential category as these users tend to spend more money on average per user than other classes ($ 4.54), making it a key target for income when it comes to in-game purchases. Another age group to look at when it comes to revenue is the age group 35-40, as they have the highest average spent per person ($4.76).


The last data trend observed is related to the most purchased items and most profitable items for the game. This is key for a company to see where the profit comes from and potentially increase its sales from them. Understanding that the item "final critic" is popular amongst the users and the most profitable, the company can increase its price as it is in high demand. The company can also make the item "nirvana" a profitable item that becomes more popular amongst users to generate more revenue.

---



### Project Results Summary

Original df screenshot

![df](Images/1df.png)

1. Player Count

   * ![df](Images/2totalplayers.png)
2. Purchasing Analysis (Total)

   * Number of Unique Items
   * Average Purchase Price
   * Total Number of Purchases
   * Total Revenue
   * ![df](Images/3.uni.png)
3. Gender Demographics

   * Percentage and Count of Male Players
   * Percentage and Count of Female Players
   * Percentage and Count of Other / Non-Disclosed
   * ![df](Images/4genderdf1.png)
4. Purchasing Analysis (Gender)

   * The below each broken by gender
     * Purchase Count
     * Average Purchase Price
     * Total Purchase Value
     * Average Purchase Total per Person by Gender
     * ![df](Images/5genderdf2.png)
5. Age Demographics

   * The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
     * Purchase Count
     * Average Purchase Price
     * Total Purchase Value
     * Average Purchase Total per Person by Age Group
     * ![df](Images/6agedf1.png)
     * ![df](Images/7agedf2.png)
6. Top Spenders

   * Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
     * SN
     * Purchase Count
     * Average Purchase Price
     * Total Purchase Value
     * ![df](Images/8topspenderdf1.png)
7. Most Popular Items

   * Identify the 5 most popular items by purchase count, then list (in a table):
     * Item Name
     * Item ID
     * Purchase Count
     * Item Price
     * Total Purchase Value
     * ![df](Images/9itemdf.png)
8. Most Profitable Items

   * Identify the 5 most profitable items by total purchase value, then list (in a table):
     * Item Name
     * Item ID
     * Purchase Count
     * Item Price
     * Total Purchase Value
     * ![df](Images/11profitabledf.png)

As a final task I had to include a written description of three observable trend based on the data. This is a .txt file inside the folder.

---

## References

Atuesta, J. D., & ashkangh. (2021, March 11). *Using
Pandas in Jupyter Lab how can I modify the value of a column in a data frame*. Retrieved from stack overflow: https://stackoverflow.com/questions/66552939/using-pandas-in-jupyer-lab-how-can-i-modify-the-value-of-a-column-in-a-data-fram/66553022?noredirect=1#comment117652439_66553022

Devlin, J. (2016, October 12). *28 Jupyter Notebook Tips, Tricks, and Shortcuts*. Retrieved from DATAQUEST: https://www.dataquest.io/blog/jupyter-notebook-tips-tricks-shortcuts/

Sharma, P. (2020, May 12). *Count, Value Count, Unique Functions in Pandas | Python.* Retrieved from YouTube: https://www.youtube.com/watch?v=JINEt8QwkwE

Willems, K. (2019, January 14). *Pandas Tutorial: DataFrames in Python*. Retrieved from datacamp: https://www.datacamp.com/community/tutorials/pandas-tutorial-dataframe-python#question1

**Please note: I am new to .md files and I cant seem to indent the reference following the APA guidelines**

---

## Assignment instructions provided by Northwestern Data Science Bootcamp

### Pandas Homework - Pandas, Pandas, Pandas

#### Background

The data dive continues!

Now, it's time to take what you've learned about Python Pandas and apply it to new situations. For this assignment, you'll need to complete **one of two** (not both)  Data Challenges. Once again, which challenge you take on is your choice. Just be sure to give it your all -- as the skills you hone will become powerful tools in your data analytics tool belt.

Before You Begin

1. Create a new repository for this project called `pandas-challenge`. **Do not add this homework to an existing repository**.
2. Clone the new repository to your computer.
3. Inside your local git repository, create a directory for the Pandas Challenge you choose. Use folder names corresponding to the challenges: **HeroesOfPymoli** or  **PyCitySchools**.
4. Add your Jupyter notebook to this folder. This will be the main script to run for analysis.
5. Push the above changes to GitHub or GitLab.

#### Option 1: Heroes of Pymoli

![Fantasy](Images/Fantasy.png)

Congratulations! After a lot of hard work in the data munging mines, you've landed a job as Lead Analyst for an independent gaming company. You've been assigned the task of analyzing the data for their most recent fantasy game Heroes of Pymoli.

Like many others in its genre, the game is free-to-play, but players are encouraged to purchase optional items that enhance their playing experience. As a first task, the company would like you to generate a report that breaks down the game's purchasing data into meaningful insights.

Your final report should include each of the following:

##### Player Count

* Total Number of Players

##### Purchasing Analysis (Total)

* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

##### Gender Demographics

* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

##### Purchasing Analysis (Gender)

* The below each broken by gender
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Gender

##### Age Demographics

* The below each broken into bins of 4 years (i.e. &lt;10, 10-14, 15-19, etc.)
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value
  * Average Purchase Total per Person by Age Group

##### Top Spenders

* Identify the the top 5 spenders in the game by total purchase value, then list (in a table):
  * SN
  * Purchase Count
  * Average Purchase Price
  * Total Purchase Value

##### Most Popular Items

* Identify the 5 most popular items by purchase count, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

##### Most Profitable Items

* Identify the 5 most profitable items by total purchase value, then list (in a table):
  * Item ID
  * Item Name
  * Purchase Count
  * Item Price
  * Total Purchase Value

As final considerations:

* You must use the Pandas Library and the Jupyter Notebook.
* You must submit a link to your Jupyter Notebook with the viewable Data Frames.
* You must include a written description of three observable trends based on the data.
* See [Example Solution](HeroesOfPymoli/HeroesOfPymoli_starter.ipynb) for a reference on expected format.

#### Option 2: PyCitySchools

![Education](Images/education.png)

Well done! Having spent years analyzing financial records for big banks, you've finally scratched your idealistic itch and joined the education sector. In your latest role, you've become the Chief Data Scientist for your city's school district. In this capacity, you'll be helping the  school board and mayor make strategic decisions regarding future school budgets and priorities.

As a first task, you've been asked to analyze the district-wide standardized test results. You'll be given access to every student's math and reading scores, as well as various information on the schools they attend. Your responsibility is to aggregate the data to and showcase obvious trends in school performance.

Your final report should include each of the following:

##### District Summary

* Create a high level snapshot (in table form) of the district's key metrics, including:
  * Total Schools
  * Total Students
  * Total Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

##### School Summary

* Create an overview table that summarizes key metrics about each school, including:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

##### Top Performing Schools (By % Overall Passing)

* Create a table that highlights the top 5 performing schools based on % Overall Passing. Include:
  * School Name
  * School Type
  * Total Students
  * Total School Budget
  * Per Student Budget
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

##### Bottom Performing Schools (By % Overall Passing)

* Create a table that highlights the bottom 5 performing schools based on % Overall Passing. Include all of the same metrics as above.

##### Math Scores by Grade\*\*

* Create a table that lists the average Math Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

##### Reading Scores by Grade

* Create a table that lists the average Reading Score for students of each grade level (9th, 10th, 11th, 12th) at each school.

##### Scores by School Spending

* Create a table that breaks down school performances based on average Spending Ranges (Per Student). Use 4 reasonable bins to group school spending. Include in the table each of the following:
  * Average Math Score
  * Average Reading Score
  * % Passing Math (The percentage of students that passed math.)
  * % Passing Reading (The percentage of students that passed reading.)
  * % Overall Passing (The percentage of students that passed math **and** reading.)

Scores by School Size

* Repeat the above breakdown, but this time group schools based on a reasonable approximation of school size (Small, Medium, Large).

##### Scores by School Type

* Repeat the above breakdown, but this time group schools based on school type (Charter vs. District).

As final considerations:

* Use the pandas library and Jupyter Notebook.
* You must submit a link to your Jupyter Notebook with the viewable Data Frames.
* You must include a written description of at least two observable trends based on the data.
* See [Example Solution](PyCitySchools/PyCitySchools_starter.ipynb) for a reference on the expected format.

##### Hints and Considerations

These are challenging activities for a number of reasons. For one, these activities will require you to analyze thousands of records. Hacking through the data to look for obvious trends in Excel is just not a feasible option. The size of the data may seem daunting, but pandas will allow you to efficiently parse through it.

* Second, these activities will also challenge you by requiring you to learn on your feet. Don't fool yourself into thinking: "I need to study pandas more closely before diving in." Get the basic gist of the library and then _immediately_ get to work. When facing a daunting task, it's easy to think: "I'm just not ready to tackle it yet." But that's the surest way to never succeed. Learning to program requires one to constantly tinker, experiment, and learn on the fly. You are doing exactly the _right_ thing, if you find yourself constantly practicing Google-Fu and diving into documentation. There is just no way (or reason) to try and memorize it all. Online references are available for you to use when you need them. So use them!
* Take each of these tasks one at a time. Begin your work, answering the basic questions: "How do I import the data?" "How do I convert the data into a DataFrame?" "How do I build the first table?" Don't get intimidated by the number of asks. Many of them are repetitive in nature with just a few tweaks. Be persistent and creative!
* Expect these exercises to take time! Don't get discouraged if you find yourself spending  hours initially with little progress. Force yourself to deal with the discomfort of not knowing and forge ahead. Consider these hours an investment in your future!
* As always, feel encouraged to work in groups and get help from your TAs and Instructor. Just remember, true success comes from mastery and _not_ a completed homework assignment. So challenge yourself to truly succeed!
* Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

##### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
