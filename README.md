# Bridge-Deterioration-Model

## Sponsor: Illinois Department of Transportation (IDOT)

 
## Overview:
The United States has 614,387 bridges (also referred to as structures). Almost four in ten of our bridges are 50 years or older. The average age of our bridges keeps going up and many of our bridges are approaching the end of their design life. In Illinois we have 26,775 bridges of which 4,527 are in poor condition. In Champaign County we have 723 bridges of which 61 are in poor condition.

## Sponsor’s Representative
Hugh Gallivan, a member of the Associated General Contractors of Illinois, will represent IDOT to introduce the use case and be available to answer questions. Hugh will be on site at PYGHACK from Noon to 3:00 pm on Saturday and available by email (hgallivan@maccgroup.net) or cell phone (217-202-2597) until the event closes at Noon on Sunday. 

## Problem Statement:
IDOT has been inspecting bridge elements (e.g. steel column or pile extensions; unpainted steel floor beams) since 1995. Bridge elements are described in IDOT’s Bridge Element Inspection Manual. Historical inspection data for each bridge element for each bridge is stored in SQL tables in an Access Database. 

IDOT needs to develop deterioration curves based on this historical data. IDOT needs four deterioration curves developed for each bridge element by environment as follows:
 
Benign: Neither environmental factors nor operating practices are likely to significantly change the condition of the element over time or their effects have been mitigated by the presence of highly effective protective systems.

Low: Environmental factors and/or operating practices either do not adversely influence the condition of the element or their effects are substantially lessened by the application of effective protective systems.
 
Moderate: Any change in the condition of the element is likely to be quite normal as measured against those environmental factors and/or operating practices that are considered typical by the agency.

Severe: Environmental factors and/or operating practices contribute to the rapid decline in the condition of the element. Protective systems are not in place or are ineffective.
 

For example, how fast will steel column or pile extensions (Bridge Element #8409) deteriorate in a benign, low, moderate and severe environment? How fast will unpainted steel floor beams (Bridge Element #8151) deteriorate in a benign, low, moderate and severe environment?

## Evaluation criteria
* Which solution generates the most accurate/reasonable deterioration curves for each bridge element for each of the four environments? 

* Does the solution have the ability to display the deterioration curves graphically? 

* Has the solution analyzed the historical inspection element data to determine what data shall be included to produce reasonable deterioration curves? For example: 
* The element may have been repaired or replaced over the past 20-years which could skew the results.
* Bad inspection data could skew the results (key typing errors, small sample size, etc.). 
* Etc.


## Datasets

| Data | Content|
| -----|--------|
|**Illinois Bridge Element Level Inspections Table**| This table contains Element Level Inspections back thru January of 1995 for all bridges (also referred to as structures) including bridges that have been replaced.|
|**Illinois Construction History Table**| This table contains the Original Year of Construction plus Reconstruction Year (if applicable) for all bridges including bridges that have been replaced.|
|**Illinois Structure Information System (ISIS) Summary State and Local2 Table**| This table contains an inventory/inspection record for each bridge (does not include bridges that have been replaced).|
|**National Bridge Inventory Data**| In addition, there are a series of queries that list the “National Bridge Inventory Datasets”. These use the ISISSummaryStateandLocal2 Table as the source data and they can easily be exported to Excel if needed:
* Bridge condition by year built
* Bridge condition by county
* Bridge condition by highway system
* Bridge condition by owner
* Bridge condition by posting status
* Count of bridges by functional classification
* Length of bridges by functional classification
* Area of bridges by functional classification
* Average daily traffic of bridges by functional classification|
 
 
Please refer to the Structure Information & Procedures Manual  for use in interpreting the data.  Please note that the field names in the tables provided are included in the title block of each manual page manual in the “SIMS Field Name” box.  Lastly, we are unable to provide you with Bridge Replacement Unit Costs at this time for a variety of reasons.  Mainly, due to the wide range in costs between the different Main Structure Types.


Notes:
The term Functionally Obsolete is no longer used.
Structurally Deficient has been redefined as Poor (effective 2018).
