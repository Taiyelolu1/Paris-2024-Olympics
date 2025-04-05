# Paris 2024 Olympics
I analyzed and visualized the dataset for the Paris 2024 Olympics to generate key insights like the top winning countries, number of athletes by country and number of medals won.
### Step 1: Data Collection
* The data was gotten from wikipedia [Paris 2024 Olympics Dataset](https://en.wikipedia.org/wiki/2024_Summer_Olympics)
### Step 2: Data Cleaning 
* Imported the data from the web into Excel.
* Two tables were imported; the athletes table and the medals table.
* The tables were loaded into power query in Excel and cleaned by removing unwanted symbols.
* I made sure that the columns had appropriate data types assigned to them.
* The tables were then merged into one table to give me a better overview of the dataset.
### Step 3: Data Analysis 
With the use of formulas, I was able to calculate the percentage win by medal for all the countries. 
* The percentage of Gold, Silver and Bronze medal for all the countries were calculated by dividing a medal number by the total number of medals and multiplying by 100.
* Formula 1 = [(No of Gold medals)/(Total medals)] * 100
* Formula 2 = [(No of Silver medals)/(Total medals)] * 100
* Formula 3 = [(No of Bronze medals)/(Total medals)] * 100
### Step 4: Data Visualization
I made use of Tableau in creating the dashboard for this project. After importing my Excel Worksheet into Tableau Public, I made sure to show the connections between the tables before I started visualizing. Visual insights were gotten by using KPIs to show total countries, rank, total athletes, number of gold, silver and bronze medals won by countries. Other visuals include bar charts showing the distribution of various medals by country, a map showing the distribution of number of athletes by country and a table showing the total number of medals won by the various countries. I made use of filter for country to aid extraction of desired information from the visuals. 

* Here is a link to my interactive Tableau Public project:
  [Tableau Public Project](https://public.tableau.com/app/profile/taiye.arokoyu/viz/shared/X27Q3X8Q4)
* Or view a snapshot of the project:
  (https://github.com/user-attachments/assets/e5ef3f88-e264-476a-9fb7-2bcec2ce3ef0)

### Key Insights
1. There were a total of 206 countries that participated in the Paris 2024 Olympics.
2. There were a total of 10,751 athletes who participated in the Paris 2024 Olympics of which United states had the highest number of participants (592).
3. United States had the highest total number of medals won (126) of which Gold (40), Silver (44), and Bronze (42), which were all the highest in their various categories.
4. United States came in ranking first position, China second and Japan Third. 
