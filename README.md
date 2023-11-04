# personal_fun
Just some random mini projects that I decided to explore!
Check out the interactive maps I made for the child marriage Notebook:
https://nbviewer.org/github/d-billups/personal_fun/blob/main/child_marriage%20%281%29.ipynb 

Check out the cool visualizations I made for my own personal netflix data analysis I did!
Find it here: https://nbviewer.org/github/d-billups/personal_fun/blob/main/analyzing_netflix.ipynb
For this project, I used pandas, to put the netflix file into a dataframe, regex to grab specific information based on certain patterns in order to isolate show information, and plotly express to visualize the data using bar and pie charts. The goal was to simply analyze some of what I have been watching: how much time I spent watching specific shows, looking at days of the week, and time of day with increased viewing, etc.

With the scrape_cloud program, I did some webscraping on tripadvisor --looking at customer reviews for the Royal Sonesta hotel in Puerto Rico. I ended up getting blocked by tripadvisor so my requests were minimal (didn't request every page containing reviews) at this point because I was afraid of constantly getting blocked (I didn't feel like rotating ips). Anyway, I used the packages: requests, BeautifulSoup, and matplotlib for this exercise. I used a function to go through ~20 pages of reviews, pulled the reviews out by finding their tag location, and then isolated the text-only data (no tags) and put it in a list. I transformed the list to a string, to prepare it for the wordcloud. Lastly I imported matplotlib because I wanted to create a wordcloud based on the reviews. I used STOPWORDS from the wordcloud library, but I added additional stop words that were more tailored to hotel reviews.
