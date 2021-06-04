# big-brother-diversity-data
Full dataset containing demographic and gameplay data for every Big Brother US contestant, Season 1 - Season 22

**big_brother_data.csv:** 
Record for every player. Fields include basic demographic information, special demographic information (race/ethnicity, sexual orientation, etc.), and gameplay tallies (total wins, total nominations, days in game, etc).

**big_brother_data_diversity.csv:** 
Contains entropy and ratio calcuations, measuring ethnic diversity.

**Entropy Formula:**

 h<sub>i</sub>= - ∑ <sup>k</sup><sub>j=1</sub> P<sub>ij</sub> ln(P<sub>ij</sub>)
 
 **Full methodology:**
 https://vincedixonportfolio.com/2019/08/29/methodology-behind-big-brother-diversity-data-dive/
 
 **NOTE/UPDATE:**
6/4/21: In previous versions of "big_brother_data" tallies for `total_wins` column for bbus16, bbus21 and bbus22 were mis-calulated, adding 'total_nominations' to the sum. This has been corrected. Names "Steven Moses" and "Jen DiTurno" have also been corrected. Special thanks to Brannon S. for pointing these out.

