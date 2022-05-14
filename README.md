# Exploring MLB's 2020 Season with Altered Baseball (using sklearn)


What’s So Interesting About These Baseballs?

Two weeks before the start of the MLB’s 2021 Spring Training campaign. MLB Executive Reporter Mark Feinsand broke that an independent lab reported that official game used baseballs used in the 2020 season had less drag and flew one to two feet shorter on balls hit over 375 feet. The conclusion being inconsistencies in the height of the seams. Rawlings Official Game Used Baseballs are all hand sewn and have a deviation range of .530 to .570. Rawlings has since admitted to loosening the seams on the baseballs which is supposed to slightly reduce drag which in turn should increase overall hitting production. This is all after a groundbreaking discovery by Dr. Meredith Wills who found that the baseballs used in 2019 and the 2020 shortened season were inconsistent with the baseballs used in seasons past. What makes these studies and claims so interesting is that the 2020 season was cut short because of COVID as all these rumors of the ball being different started circling. There is a large gap in data that does not exist because the 2020 was hardly 2 months’ worth of games. We will analyze data from the 2018-2021 seasons and create a regression algorithm that takes in previous season data and predicts stats for a full 162 game 2020 season which we will compare to see how it stacks up to the “juiced” season of 2019 or “normal” season of 2018.


How Will We Analyze and Munge This Data?

pybaseball is a Python package for baseball data analysis. This package scrapes Baseball Reference, Baseball Savant, and FanGraphs so we don't have to. The package retrieves statcast data, pitching stats, batting stats, division standings/team records, awards data, and more. Data is available at the individual pitch level, as well as aggregated at the season level and over custom time periods. Baseball Savant is MLB’s clearinghouse for statcast data (statcast is a high-speed, high-accuracy, automated tool developed to analyze player movements and athletic abilities in Major League Baseball (MLB))
In this project I use a package called pybaseball to analyze original quantitative baseball statistics and sabermetric data to see if we notice a difference in offensive production from season to season. We will also analyze statcast data exported in .csv format from the Baseball Savant website to compare baseball exit velocity and launch angles per season. I also use pandas for our data frames, seaborn and matplotlib for visualization purposes, and sklearn for our linear regression model.[Juiced Baseballs Python Project.pdf]

(https://github.com/rickycamilo/Exploring-MLB-s-2020-Season-with-Altered-Baseball-/files/8693884/Juiced.Baseballs.Python.Project.pdf)
