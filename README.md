# Stiglers_Diet_Mix

The Stigler diet is an optimization problem named for George Stigler, a 1982 Nobel Laureate in economics, who posed the following problem: For a moderately active man weighing 154 pounds, how much of each of 77 foods should be eaten on a daily basis so that the man’s intake of nine nutrients will be at least equal to the recommended dietary allowances (RDAs) suggested by the National Research Council in 1943, with the cost of the diet being minimal?

The nutrient RDAs required to be met in Stigler’s experiment were calories, protein, calcium, iron, vitamin A, thiamine, riboflavin, niacin, and ascorbic acid. The result was an annual budget allocated to foods such as evaporated milk, cabbage, dried navy beans, and beef liver at a cost of approximately $0.11 a day in 1939 U.S. dollars.

While the name “Stigler Diet” was applied after the experiment by outsiders, according to Stigler, “No one recommends these diets for anyone, let alone everyone.” The Stigler diet has been much ridiculed for its lack of variety and palatability; however, his methodology has received praise and is considered to be some of the earliest work in linear programming.

https://en.wikipedia.org/wiki/Stigler_diet


******************************************************

	UCD MSc Business Analytics Assignment
  	
  	Authors:
  	Eoin Carroll (16202781) 
  	Andy McSweeney (16203177)
  	
  	Module Code: MIS40520
	Module Title: Analytical Business Modelling
	Assessment Title: Assignment 3: Analytical Business Modelling 2017
	Project Title: Food Mix Problem
	Module Co-ordinator: Dr Paula Carroll
	Revision: 0
	Related Filename: MIS40520_ABM_AS3_16202781_16203177.mos
	Date Started: 10/04/2017
	Date Submitted: 18/04/2017
  	
  	References: 
  	Parts of the following class code samples were used:
  	diet.mos
  	part2_subroutine_demo.mos
  	ABM_assignment_2_Team_9.mos
  	
  ******************************************************

	Execution Instructions:
	Select which input file you want to model
	In the input .dat file, select which paramaters you want to use
	Uncomment the input file that you want to model
	Run the model and examine the results on the right
  	
  *******************************************************
  
 input = "Stigler_Full_77_1939.dat"		! Full Stigler Problem 77 Foods, 1939
 input = "Stigler_Reduced_9_1939.dat"		! Reduced Stigler Problem 9 Foods, 1939
 input = "Stigler_Reduced_15_1944.dat"		! Reduced Stigler Problem 15 Foods, 1944
 input = "Everest_trip1.dat"				! Everest Problem 1/3
 input = "Everest_trip2_trip3.dat"			! Everest Problem 2/3
 input = "Everest_summit.dat"				! Everest Problem 3/3
