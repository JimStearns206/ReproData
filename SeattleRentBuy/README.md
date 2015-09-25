# Rent vs Buy in Seattle, 2012:2013:2014

Data Source: [U.S. Census FactFinder](http://factfinder.census.gov)

* Advanced Search, then load 
[search criteria in this project](file:/Users/jimstearns/GoogleDrive/Learning/Courses/DataAnalysisAndInterpretation_Wesleyan/SeattleRentBuy/Data/USCensusACS/SearchCriteriaSeattle.aff)
[relpath alt](file:Data/USCensusACS/SearchCriteriaSeattle.aff)

[relpath alt 2](file:SeattleRentBuy/Data/USCensusACS/SearchCriteriaSeattle.aff)

* Files of interest:
    * B25118 for 2012 and 2013, metadata and data:
        * ACS_12_1YR_B25118_metadata.csv (column descriptions)
        * ACS_12_1YR_B25118_with_ann.csv (the actual data)
        * ACS_12_1YR_B25118.txt (discussion)
        * ACS_13_1YR_B25118_metadata.csv (column descriptions)
        * ACS_13_1YR_B25118_with_ann.csv (the actual data)
        * ACS_13_1YR_B25118.txt (discussion)
        
    * Did a manual compare of the metadata for the two years. Binary compare equality.
    
    * Columns of Interest:
        * GEO.id (should be 1600000US5363000 for Seattle)
        * Estimate; Owner occupied: - *
        * Estimate; Renter occupied: - *
        * Aggregate the following into:
            * > $150K
            * $100K - $150K: 1
            * $75K - $100K: 1
            * $50K-$75K: 
            * < $50K: 7
            
        
    
    


