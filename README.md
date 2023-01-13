# MLB Pitch Count Project

Baseball Pitch Count Project - Data Club 2022
Vivek Divakarla, Suhaib Iqbal


Our project was revolved around baseball pitch count statistics. We found the data from baseball-reference.com and used python to try to analyze player performance on different pitch counts. In our findings, we found out that most players do better on favorable counts such as 2-0, 3-0 and 3-1, but struggled on the 2 strike counts. However, there were some differences between the best players compared to the average, as they had stronger averages in the pressure situations

<img width="661" alt="Screen Shot 2023-01-12 at 7 19 10 PM" src="https://user-images.githubusercontent.com/11672096/212208329-ceb09033-b405-4159-ace2-62897e2556b8.png">
Our first step was to import the data. We did this by exporting the baseball-reference data to CSVs for each MLB team, then reading it into Pandas. 

# Preliminary Graphs
<img width="774" alt="Screen Shot 2023-01-12 at 7 20 27 PM" src="https://user-images.githubusercontent.com/11672096/212208476-1496247c-e5b9-4ea2-8f98-99fb48eafe0d.png">
<img width="759" alt="Screen Shot 2023-01-12 at 7 21 05 PM" src="https://user-images.githubusercontent.com/11672096/212208556-5e5833bd-f534-4655-94ad-3e72e002eaf0.png">
We ran some preliminary graphs to look at some differences in pitch counts across the whole league, but not many major differences were found there. 

<img width="602" alt="Screen Shot 2023-01-12 at 7 22 28 PM" src="https://user-images.githubusercontent.com/11672096/212208681-8cdf5052-07f1-4b70-8137-776804eb8b5e.png">
Next, we have sorted the data set to then Yankees who are eligible, comparing them to see their different success rates on each pitch count. As we can see, they all take a dip on 2 strike counts, but perform well on 2-0 and 3-0. Looking at the individual players, Stanton is consistently above average until the 2 strike counts, but Sanchez is a bit of a wildcard, as he is the best in some categories but the worst in others, including a .100 average at first pitch

# Comparing the best and worst in the MLB
We wanted to find out if player performance changed based on the pitch count. Are the best players the best on all counts, or do they only separate themselves from the league on the more favorable counts?

<img width="587" alt="Screen Shot 2023-01-12 at 7 23 06 PM" src="https://user-images.githubusercontent.com/11672096/212208748-259dba94-3d34-4883-9c86-1897df4aa32d.png">
This graph shows 6 of the best MLB players, and how they perform on each count. The league average OPS is .740, a mark these players clear on every count except 0-2, 1-2 and 2-2. They make the most of their opportunities on the early count and on even counts, but like the rest of the league, they are human and struggle on 2 strike counts. 

<img width="602" alt="Screen Shot 2023-01-12 at 7 23 35 PM" src="https://user-images.githubusercontent.com/11672096/212208788-15e1cf15-4875-4905-b952-f3b49e36c10a.png">
This graph shows 10 of the worst players in the MLB, and graphs their OPS for each count. The best hitters graph went up to 3 OPS while this graph only goes to 1.4, clearly showing the lack of top end potential any of these players have. Not only that, but they are even worse when it comes to 2 strike counts. However, one similarity that can be made is the trend going through each count. For both sets of players, 2-0, 3-0 and 3-1 had the highest OPS. 

<img width="582" alt="Screen Shot 2023-01-12 at 7 24 08 PM" src="https://user-images.githubusercontent.com/11672096/212208854-8a5ed084-1b5d-4ccb-bea4-a9a56fa2b3dc.png">
When looking at the OPS of the hitters on different counts, we wanted to compare them together to see if the league’s best were just dominating early and advantageous counts, or could do it on all counts. Looking at this graph, with the exception of 2-0, the star hitters were consistently at the top end of the box plot, while the worse hitters stayed near the bottom. Even though the 2 strike counts are closer, there is still a difference between the two different sets of players

#Conclusion
In conclusion, we determined that even though all players do better on more favorable counts in comparison to the less favorable ones, there are still clear differences between the best and worst players on all counts. It’s interesting how the jumps between counts are pretty consistent between the entire league. 
