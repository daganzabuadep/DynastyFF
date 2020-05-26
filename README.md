# DynastyFF
Home of Jupyter-Notebook for FF Analysis!

Hi fellas,
from playing with different scoring and league settings (some with 1st Down, PPRush and yardage bonuses and large starting rosters), I wanted to see how value of positions and players change. Contrary to Excel spreadsheets, I started compiling a jupyter notebook (Python) in my spare time in order to make some investigations. For those unfamiliar with jupyter: it's a really easy tool to let you run code that others have written. The notebook that I will share once I am no longer embarrassed about my hacky code downloads NFL data from past years from pro-football-reference.com for you and then let's you enter your league's scoring settings and calculates Fantasy points for those settings. The queries/filters are not too different from other database structures.
I'm currently going through to satisfy my own curiosities, but I want to add some more features that will allow you to plug in your roster(s) and use expert projections for the 2020 season to give you an idea where each team in your league is projected to land, points-wise. I found some initial projections that are freely available but I would happily take recommendations of experts that were successful in the past.
The jury on some of the questions I had is still out and I will share them once they are presentable. With this post, I wanted to ask for ideas/trends on what the sub would find interesting to scope out. Hope I haven't scared anyone off with deviating from the common Spreadsheet approach (I have some CS background but must say: Python Dataframes are really similar and easy to learn!) and am looking forward to some ideas from you. Stuff that's already working:
-Calculate FP and points per game for every player based on your scoring settings and just about any query you can imagine (Top 12 WRs under 25 every year,  the WRs on their team for that season etc.), Top 100 Board per season, follow player scores over the years
-Comparing customable tiers (Top 8/10/12, Top 24) to one another and plotting some shabby graphs (Known spoiler: TE and RB dropoffs were pretty big for my TE Premium, PPRush and PP 1st Down league, WR was really flat)
Things I plan to take on:
-Incorporate some measure of value over replacement to really find advantages when constructing rosters or drafting startups -->  there have been posts on this before
-Incorporate expert projections for 2020 and reason about likely fantasy production, feature to pull in roster data easily

SETUP:
The notebook should be good to run right away as soon as you specify a valid folder location in the frames that download the databases. Happy to get input/contributions from others. Cheers!
