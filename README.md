Lucas Feliciano, Brandon Reinoso, Dennis Dong, Jennifer Muy
CIS 2300
Professor Jairam
May 20, 2025	
Introduction: To see if collegiate-level varsity swimmers are generally taller than collegiate-level varsity volleyball players. Web scraping college athletic roster data from publicly available databases, and graduated collegiate heights to come to a factual conclusion based on this assumption.

Techniques Used: Web scraping was conducted in Python with libraries like BeautifulSoup and requests. Minor projects were constructed with Pandas data frames for data manipulation and basic data cleaning adjustments, which we'll comment on later.

How Data was Collected/Processed Data was collected from roster overviews from official college athletics pages. The male and female volleyball roster and the male and female swimming roster were parsed from over 30 different colleges. All parsed data was compared across each roster, meaning heights and names were compared to eliminate duplicates. Then the final summation was converted to include a men's swimming category, a women's swimming category, etc. Averages across subgroups were compared for the tallest and shortest males and females (top 5), and each of the groups was accrued.
Average heights are as follows:
Men's Swimming Average Height: 71.6 inches
Men's Volleyball Average Height: 74.2 inches
Women's Swimming Average Height: 65.8 inches
Women's Volleyball Average Height: 68.4 inches


Results/Conclusion: The results imply that volleyball players are taller than swimmers. However, this is just an aggregate across relative microcosm leagues and does not represent all collegiate abilities and options nationwide. Additionally, this could cause private universities or other means of collegiate support systems to be missed without proper access online. Further, volleyball is one of those sports that requires height for blocking/spiking gameplay moves that may lend itself to teams recruiting higher, taller athletes/more natural talents. This could instead represent something that has nothing to do with the swimming sport, but with extended wingspans/efficiency of stroke/open turns—either way, something more representative would need to be completed to find definitive value.

Overall Takeaway: This indicates that average volleyball players are taller than swimmers based on the collegiate version. This makes sense from a sports perspective for its physical gameplay nature. Overall, this project gave me a good opportunity for web scraping and showed how valuable it can be for real-life sports data. On a personal note, this helped solidify my understanding of operator overloading this week because when attempting to exclude and filter heights from multiple checks across our project, we overloaded comparative functions to get them to sort better.
