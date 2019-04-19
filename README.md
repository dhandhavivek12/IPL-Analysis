# IPL-Analysis
IPL Analysis and Winner predictions using various ML algorithms
Indian Premier League Data Analysis
Project Goals:
• To analyze the Indian Premier League (IPL) data over all the seasons (2008-2017) till
date and find insights from it.
• To find ’Top 10 Most Valuable Players’ in IPL using most valuable player index (MVPI)
calculation strategy.
• To apply machine learning algoruthm to it and predict the
Project Problem Description:
Board of Control for Cricket in India (BCCI) started a T20 cricket league named Indian Premier
League (IPL) in 2008. From a pool of available players which are selected by BCCI according
to their rules, the franchises select their players through competitive bidding. Every year BCCI
has been organizing the IPL tournament. 11 tournaments have been held till date.
The main objective of the project is to come up with a list of top players IPL history. This will
be achieved by using MVPI strategy. MVPI is in general an index calculated for a player. It
is nothing but a wishful proposition to quantify some of the metrics of that player depending
on its type (i.e. Batsmen/Bowler). This index shows the potential value of that player to the
team.
Approach for solution to the problem:
The heart of the solution to this problem is the MVPI index calculation. This index will be
calculated in step by step manner as follows:
1. Identify the metrics for each player.
2. Calculate absolute values for matrics and normalize them to remove any metric bias.
3. Carry out feature selection on these matrics by using recursive feature elimination technique. This technique retains features by recursively narrowing down to smaller and
smaller sets of attributes. Now, calculate weights for each and every selected feature.
4. The last step involves multiplying the importance (weight) of each feature with its value
and then aggregating the weighted value set for each player.
This way, we find index for each player which are then sorted in decreasing order to get the top
10 Most Valuable Players.



Some basic analysis:

Total number of matches : 636.

Total number of deliveries : 150460.


Different Venues matches were played at:
Dubai International Cricket Stadium, Himachal Pradesh Cricket Association Stadium, Sardar Patel Stadium, Motera, Punjab Cricket Association Stadium, Mohali, Barabati Stadium,
Punjab Cricket Association IS Bindra Stadium, Mohali, Nehru Stadium, Maharashtra Cricket
Association Stadium, Eden Gardens, OUTsurance Oval, M Chinnaswamy Stadium, Feroz Shah
Kotla, Rajiv Gandhi International Stadium, Uppal, Brabourne Stadium, Vidarbha Cricket Association Stadium, Jamtha, Green Park, Holkar Cricket Stadium, Shaheed Veer Narayan Singh
International Stadium, Sheikh Zayed Stadium, Sharjah Cricket Stadium, St George’s Park,
Wankhede Stadium, Newlands, JSCA International Stadium Complex, Saurashtra Cricket Association Stadium, Dr DY Patil Sports Academy, Buffalo Park, New Wanderers Stadium, SuperSport Park, Sawai Mansingh Stadium, Dr. Y.S. Rajasekhara Reddy ACA-VDCA Cricket
Stadium, MA Chidambaram Stadium, Chepauk, De Beers Diamond Oval, Kingsmead, Subrata
Roy Sahara Stadium.



Different Cities matches were played in:
Bangalore, Kochi, Chennai, None, Centurion, Ranchi, Mumbai, Ahmedabad, Durban, Kolkata,
Cape Town, Dharamsala, Sharjah, Pune, Johannesburg, Kimberley, Delhi, Raipur, Chandigarh,
Nagpur, Abu Dhabi, Bloemfontein, Kanpur, Hyderabad, Rajkot, Port Elizabeth, Indore, Cuttack, East London, Jaipur, Visakhapatnam.



Teams :
Sunrisers Hyderabad, Chennai Super Kings, Rising Pune Supergiant, Deccan Chargers, Kochi
Tuskers Kerala, Rajasthan Royals, Gujarat Lions, Royal Challengers Bangalore, Kolkata Knight
Riders, Rising Pune Supergiants, Kings XI Punjab, Pune Warriors, Delhi Daredevils, Mumbai.
Indians


Total umpires used in IPL till now : 45.

Detailed Analysis Using Spark:
Using pyspark, analysis has been carried out and visualized as specified below :
1. Number of matches played at a venue.
2. Win percentage at a venue batting first.
3. Win percentage at a venue bowling first.
4. Teamwise comparative analysis of win/loss/tie if a team bats first.
5. Percentage wins by a team when it wins toss
6. Percentage wins by a team when it loses toss
7. Teams most and least affected by the event of winning/losing toss.
Please find sample screenshots for the analysis below. Kindly refer to the attached notebook
and pdf file for detailed visualization of the analysis.
