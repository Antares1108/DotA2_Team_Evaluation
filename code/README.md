# DotA2_Team_Evaluation
  1. DESCRIPTION - Describe the package in a few paragraphs.
  In the CODE folder there are three files including index.html, hero_final.json and best4choices.csv. Index.html is the demo website. Hero_final.json contains the attributes of heroes. Best4choices.csv contains the first recommendation based on the user’s first choice. 

  2. INSTALLATION - How to install and setup your code.
  There is no extra need for installation. But we highly recommend using latest Firefox as the browser to open the html file because there would be no further setting needed. For users only have access to safari or google chrome, you may need to setup an HTTP server to run the program correctly. The easiest way is to use simple HTTP server in python (http://www.pythonforbeginners.com/modules-in-python/how-to-use-simplehttpserver/). 

  3. EXECUTION - How to run a demo on your code.
  Keep all three files in the same folder, and you are good to go! Please make sure you have the access to Internet. Then open index.html to use our demo. There are some functions in the demo as below.
	  (a) Hero selection and recommendation: 
		You can select up to 5 heroes by clicking them on the hero rings to form your team. Each ring represents a different type of heroes such as strength agility and intelligence. For each hero you choose, 4 other heroes will be recommended and highlighted with gold edge on the rings. The recommendations are dynamically changing based on current team composition. You can also click the heroes in the center to change your team composition as well. To deselect all heroes, you can use clear button in the center. 
	  (b) Hero searching 
		To find heroes quickly, you can type in the hero’s name (or part of it) and click on search button or hit return on your keyboard to search heroes. The heroes who matches the name will be highlighted on the rings. 
	  (c)Team analysis
		After choosing 5 heroes, you can click on analyse button to enter the analysis page for the entire team. Detailed information of heroes will show in the page along with the team’s score based on the reasonability of team composition. Higher the score means the higher the win rate this team have. There are 5 clusters to demonstrate a hero’s ability including hard carry (Position 1), semi carry (or solo, Position 2), offlaner (Position 3), roaming support (or jungler, Position 4) and hard support (Position 5). To return the hero selection page, hit the return button in the upper left of the page. 
