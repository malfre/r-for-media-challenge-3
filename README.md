# r-for-media-challenge-3

## Challenge III
* Load both the 2020 election results ('wahlergebnisse.rds') and stadtteil_profile ('stadtteil_profil.rds').
* Calculate each parties' election result per district (valid ballots are basis for this calculation).
* Hint: investigate the function `across()` for applying calculation on multiple columns at once.
* Calculate the ratio of people with a migration background in the total population of each district.
* Compare migration ratio to results of the AfD
* Compare the voter turnout to both other variables.
* Join the two data sets.
* Arrange by the AFD's results in descending order. 
* Prepare to discuss in the next session!
* Hint: the final table must have the following columns: stadtteil, mig_ratio, turn_out, afd.
