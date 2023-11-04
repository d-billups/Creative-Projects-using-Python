# personal_fun
Just some random mini projects that I decided to explore!
Check out the interactive maps I made for the child marriage Notebook:
https://nbviewer.org/github/d-billups/personal_fun/blob/main/child_marriage%20%281%29.ipynb 

With the scrape_cloud program, I did some webscraping on tripadvisor --looking at customer reviews for the Royal Sonesta hotel in Puerto Rico. I ended up getting blocked by tripadvisor so my requests were minimal (didn't request every page containing reviews) at this point because I was afraid of constantly getting blocked (I didn't feel like rotating ips). Anyway, I used the modules: requests, BeautifulSoup, and matplotlib for this exercise. I used a function to go through ~20 pages of reviews, pulled the reviews out by finding their tag location, and then isolated the text-only data (no tags) and put it in a list. I transformed the list to a string, to prepare it for the wordcloud. Lastly I imported matplotlib because I wanted to create a wordcloud based on the reviews. I used STOPWORDS from the wordcloud library, but I added additional stop words that were more tailored to hotel reviews.
