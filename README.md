# personal_fun
Just some random mini projects that I decided to explore!

Here's the viewer for the final version of the employee map: https://nbviewer.org/github/d-billups/personal_fun/blob/main/final_employee_map.ipynb

Take a look at the notebook I created that analyzes shark attacks in California from the 1950s until present day: https://nbviewer.org/github/d-billups/personal_fun/blob/main/shark_attacks.ipynb
I downloaded this daataset from Kaggle, and my goal was exploratory for the most part. After looking at the dataset, I was interested in seeing what species of shark accounted for the most deadly attacks, what mode put individuals at the most risk for shark attacks, what counties had the highest incidence of attacks, and much more. In the end, I created a word cloud based off of the 'Comment' series in the dataset to see which words were being used the most and I put that cloud into an actual shark mask (this was my first time doing so!) I used pandas, matplotlib, regex, and plotly.express.

Take a look at the visuals I created for an interactive map: https://nbviewer.org/github/d-billups/personal_fun/blob/main/emp_map.ipynb
The program itself outlines the purpose of the program and what libraries I used

Check out the interactive maps I made for the child marriage Notebook:
https://nbviewer.org/github/d-billups/personal_fun/blob/main/child_marriage%20%281%29.ipynb 
Packages used: Pandas, plotly.express and plotly.graph_objects. The dataset I used was pulled from kaggle: https://www.kaggle.com/datasets/data855/child-marriage/data 
I wanted to see which countries had higher marriage rates by age group and then provide visualizations to display the results.

Check out the cool visualizations I made for my own personal netflix data analysis I did!
Find it here: https://nbviewer.org/github/d-billups/personal_fun/blob/main/analyzing_netflix.ipynb
For this project, I used pandas to put the netflix file into a dataframe, regex to grab specific information based on certain patterns in order to isolate show information, and plotly.express to visualize the data using bar and pie charts. The goal was to simply analyze some of what I have been watching: how much time I spent watching specific shows, looking at days of the week, and time of day with increased viewing, etc.

With the scrape_cloud program, I did some webscraping on tripadvisor --looking at customer reviews for the Royal Sonesta hotel in Puerto Rico. I ended up getting blocked by tripadvisor so my requests were minimal --I didn't request every page containing reviews because I was afraid of constantly getting blocked (I didn't feel like rotating ips). Anyway, I used the packages: requests, BeautifulSoup, and matplotlib for this exercise. I used a function to go through ~20 pages of reviews, pulled the reviews out by finding their tag location, and then isolated the text-only data (no tags) and put it in a list. I transformed the list to a string to prepare it for the wordcloud. Lastly I imported matplotlib because I wanted to create a wordcloud based on the reviews. I used STOPWORDS from the wordcloud library, but I added additional stop words that were more tailored to hotel reviews.
