# Data-Communting-Zones
Commuting zones (CZs), the concept for the local labor market, were developed by Tolber and Sizer (1996).
They use county-level commuting data from 1990 Census data, and there are 741 clusters of counties. There are only 722 CZs in the entire mainland United States. 

The CZs are not included in my paper because of duplication or other issues; I drop:
1. drop #10600 keep #10700: they have the same largest cities in their CZs, Birmingham city, AL. #10700 is larger than #10600 in terms of population size.
2. drop #11304: District of Columbia has a very different character than other CZs.
3. #20402: no fiscal data in suburbs in Nantucket County, MA
4. #27704: no fiscal data in central city in year 1992 and before
5. #30605: no fiscal data in suburbs in Culberson County, TX
6. #31304: no fiscal data in suburbs in Mason County, TX
7. #31503: no fiscal data in suburbs before 1992
8. #32306: no fiscal data in suburbs in Maverick County, TX
9. #32603: no fiscal data in suburbs in Baylor County, TX
10. drop #34101 - #34115: CZs are in AK state
11. #34701 ,34702 ,34703 ,35600: CZs are in HI state
12. #34306: no fiscal data in suburbs in 30033 (fips_state_county) Garfield County, MT
13. #34307: no fiscal data in central city in year 1997 and before
14. #37902: no fiscal data in suburbs in 32021 (fips_state_county) Mineral County, NV
15. #39301: no fiscal data in suburbs in 53055 (fips_state_county) San Juan County, WA
