Build a Hierarchy

Hierarchies allow business users to drill down
into categorical data on Power BI visuals. It works
extremely well in conjunction with visuals such as treemaps

Steps involved
- Load 2_1_build_hierarchy_pbix from the Exercise folder
- Create a hierarchy on SUBSECTOR in the NAICS code dimension
- Rename the hierarchy to NAICS Code hierarchy
- Add on the following columns in this order to the hierarchy: Industry group and 2017 NAICS Code
- Navigate to the Report view and create a new page called   Summary Stats.
- Add a new Treemap visual, with the values of Number of employees from the Summary Statistics for Manufacturing dataset split by the NAICS Code heirarchy
- Add a Slicer for Year(from Summary Statistics for Manufacturing) and set to 2018
- Enable "Drill down" on the treemap by selecting the down arrow marked "Click to turn on Drill down". Try and click on a category on the treemap to drill into

QUESTION
- How many employees were hired in manufacturing sector with 2017 NAICS Code "325510" in the year 2018?

ANSWER
- 35569
