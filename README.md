# Sportsmen Dataset Analysis – Summary

Objective:
To clean a multi-sheet sports dataset, standardize player information, and generate analytical insights regarding performance, category, and location data.

**Key Tasks Performed**

* Cleaned data across multiple sheets (SPORTSMEN, SPORT, LOCATION, etc.).
* Standardized data entries such as Player Names, Cities, Sports Categories.
* Created relationships between sheets using lookups.
* Built PivotTables to summarize players by sport, region, medals, and performance criteria.
* Created a final analytical report and dashboard.

**Important Formulas Used**

* Standardizing Text	=PROPER(), =TRIM(), =CLEAN()
* Mapping Location or Sport	=XLOOKUP(lookup_value, lookup_array, return_array)
* Traditional Lookup	=VLOOKUP(A2,SPORT!A:B,2,FALSE)
* Multi-criteria Count	=COUNTIFS(SportRange, Sport, CityRange, City)
* Multi-criteria Sum	=SUMIFS(SumRange, CriteriaRange, Criteria)
* Checking Errors	=IFERROR(formula, "Not Available")
* Assigning Categories	=IF(Condition1,Result1, IF(Condition2,Result2, "Others"))
* Extracting codes from mixed text	=LEFT(), =RIGHT(), =MID(), =FIND()
* Date cleaning work	=DATEVALUE(), =TEXT()

**Excel Tools/Techniques Used**

* Power Query for transformation (if applicable)
* PivotTables for comparison & ranking
* Slicers for interactive dashboards
* Relationship building across sheets
* Conditional Formatting (Top 10, Color Scales, Icons)
* Data Validation lists
* Sorting and filtering for analysis
