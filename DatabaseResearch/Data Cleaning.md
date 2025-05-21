Making sure that data adheres to 
- desirable quality (?) 
	- practical, domain-specific characteristics that make data trustworthy, usable, and meaningful for a given purpose
- integrity constraints

Two Step:
- error detection
	- violations of integrity constraints
	- duplicates
	- outlier detection
- data repairing 
	- [[Data Cleaning#Data repair using integrity constraint!]]]
	- [[Data Cleaning#Data repair using external data]]]
	- quantitative statistics, using statistics to find outliers


### Data repair using integrity constraint!

assume majority of data is  ok
tries to find minimum number of change to make the data consistent
"Minimum" doesn't always mean correct

### Data repair using external data

To match dataset 1 from external dataset (dataset 2), there has to be some type of rule (Matching Dependencies)
Like, if a city's ziplock from dataset 1 matches with dataset 2 then dataset 2's city name should also match to dataset 1's city name