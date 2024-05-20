# mlb_2024_re24
A short blog post about the RE24 statistic in baseball using Pandas

As the 2024 season kicks off its first couple months, players are still in the rhythm of finding their swing. Baseball analysts know that OPS is the main measurement of value in hitters. However, there is another statistics that I'd like to highlight in this post, known as 'RE24'. It is represented as a matrix of run probability for every situation a hitter faces. The advantage of this stat is that it measures a hitters ability to increase or add on to run probability, even if they aren't slugging at an elite rate yet or directly getting the RBI. In short, the stat is calculated by this formula:

*** RE24 = RE End State - RE Beginning State + Runs Scored ***

RE End State and RE Beginning state are the average runs scored based on the situation after the at-bat and before. 

The FanGraphs matrix will be provided in the notebook, and the player data is provided by Baseball Reference. 
