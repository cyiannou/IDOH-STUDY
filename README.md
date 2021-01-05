"# IDOH-STUDY" 
in-census.csv: Indiana census data
ind.pop.tot.csv: Counts of Indiana state population by district used in sampling
time_series_covid19_confirmed_US.csv: Hopkins data 12/9/2020
ISDH_compact3.csv: Indiana Department of Health compact version of testing data 
  testXresult: testresult, X=1--> PCR test, X=2--> antibody test
  testlabname: PCR test processing lab
    1=Eli Lilly Clinical Diagnostics Laboratory, 0=IU Health Pathology Laboratory
  race: 1=Non-white, 2=White
  ethnicity: 1=Hispanic, 2=Non-Hispanic
  sex (not used): 1=Female, 2=Male
  age (not used): "1=<40", 2="40-59", 3=">=60"
  totcount: frequency of testlabname/test1result/test2result combination
