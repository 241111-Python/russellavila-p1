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
