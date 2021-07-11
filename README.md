# Descriptive-analysis-of-demographic-data
The International Data Base(IDB) provides accurate and timely demographic measures of over 200 countries and regions that are recognized by the US Department of State and have a population of 5,000 or more that is collected by the United States Census Bureau. The Census Bureau has produced international population estimates and projections since 3 the 1960s, and the IDB has been available on census.gov since 1966. Data included in the IDB [Bureau, 1960-2100] consists of indicators from Censuses, surveys, administrative records, and special measures of HIV/AIDS-related mortality. Through evaluation and adjustment of data from these sources, the Census Bureau estimates measures of population, mortality, fertility, and net migration for the current and past years and then projects trends forward to 2100. In this project, a subset of the IDB was compiled by the instructors of the course Case Studies at TU Dortmund University in the summer term of 2021. It includes life expectancy and fertility rates for 228 countries from 2000 and 2020. These countries are divided geographically into 5 regions and 21 subregions. Hence, the data set has 456 rows and ten columns. Country is a unitless categorical variable that represents the name of each country or territory in the data set(Nominal scale variable). FIPS Federal Information Processing Standards (FIPS), now known as Federal Information Processing Series, are country codes assigned by the National Institute of Standards and Technology (NIST). It’s unitless ( Nominal scaled variable.). GENC Geopolitical Entities, Names, and Codes (GENC) country codes values that are used in the IC (Nominal scaled variable). Subregion is a unitless categorical variable that represents the geographical sub-region to which each country belongs to (Nominal scaled variable). Region is a unitless categorical variable that represents the geographical region to which each country or territory belongs to (Nominal scaled variable). Year is a unitless continuous variable that represents the year to which the indicator refers to. Units: none. Interval scaled variable. Total fertility is a continuous variable that represents the average number of children per women according to a given set of age-specific fertility rates. its unit is children per women and its ratio scaled variable. Life expectancy of both sexes is a unitless continuous variable that represents the average number of years that people is expected to live (Ratio scaled variable). Life expectancy of Males is a unitless continuous variable that represents the average number of years that males are expected to live (Ratio scaled variable). Life expectancy of Females is a unitless continuous variable that represents the average number of years that females are expected to live (Ratio scaled variable). Out of 456 records, 9 of them present missing values. Seven rows have missing values for fertility and life expectancy variables including Honduras, Libya, Puerto Rico, South Sudan, Sudan, Syria and the United States. These seven rows are excluded from the data. Nambia has 2 missing values for GENC in the following 2 years 2000 and 2020 but, these two records are kept in the analysis. So, the total number of records after dropping out missing values is 449 observations
