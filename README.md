# districting
A data visualization of the effects on districting on the results of the 2016 congressional elections. Check it out at [https://inewell.github.io/districting/](https://inewell.github.io/districting/).

I did this in my CSC630: Data Visualization class at Phillips Academy for my maps project. I selected the topic, found the data, and came to all the conclusions about it.

I chose to examine this topic as gerrymandering has become an increasingly important national dilemma. Cases in North Carolina and Wisconsin have captivated the nation's attention, as the Supreme Court prepares to make a landmark decision regarding partisanship. Driving much of the increased importance of gerrymandering is the advancement of gerrymandering algorithms; we now have very advanced ways to attempt to maximize wasted votes for the opposite party and skew states in a favorable direction for the governing party. At the same time it presents a difficult problem, because it is hard to prove that gerrymandering occurred, and harder to prove exact intent.

This project is not really a large-scope, insightful political science endeavor. I went into it hoping to uncover how districting affected the results of the 2016 Congressional elections, not looking to prove the existence of gerrymandering in certain parts. Mostly, it doesn't reveal many striking conclusions or anything; however it does still take a worthwhile angle that does just scratch the surface of the issue.

In this project, I looked at districting through two seperate angles. The first was looking at margin of victory patterns across districts in states, with the idea that gerrymandered states would pack opposition voters into a few large-majority districts while preserving many small-majority districts for the governing party, or crack opposition voters acorss districts. The second angle looked at the shape of districts, with the hypothesis that less "compact" districts are more likely to be gerrymandered. Quite obviously, neither approach can claim to show any cause and effect, nor prove the presence of gerrymandering or nefarious intent. Nonetheless, they can, in certain places, illuminate some areas that might be suspect, and promote further investigation. That was my aim, at least.

## Table of Contents
* `index.html`: The HTML code the renders the visualization.
* `election_results_cleanup.ipynb`: Jupyter notebook that cleans and collects the data from the election results.
* Data:
  * `cb_2015_us_cd114_20m.json`: 114th Congressional District map path data.
  * `cb_2016_us_state_20m.json`: State map path data.
  * `house_general_election_2016.csv`: The raw election results data.
  * `congressional_results_2016.txt`: The cleaned election results data. Outputted by the Jupyter notebook listed earlier.

## Authors
* Isaac Newell
