This is a roulette wheel simulator which will generate the results of having played 20 spins using different betting strategies to a data file. 
The data itself is meant to demonstrate the statistical risk/reward variances seen in gambling when for example, betting on one number which pays
35 to 1 as opposed to the stability of just betting on black or red which pay 1:1.

#files 
P1roulette.sh	-the main file, run this first.
		after each run, another record will be added to data file. 
		generates data.txt in current directory

analyzer.sh	-after doing P1roulette a few times, run this to 
		analyze which gambler made the most money.

analyzerFun.sh	-helper function for analyzer. 
		no need to be run

suggested use
=============
bash P1roulette.sh 	(a couple times)
bash analyzer.sh
cat data.txt            (see if analyzer correctly identified the most successful gambler)
