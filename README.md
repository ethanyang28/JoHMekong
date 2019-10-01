# JoHMekong
The repository is for shapefile data used in the Mekong River paper published in the Journal of Hydrology.

Yang, J, Yang, Y. C. E., Chang, J., Zhang J. and Yao. J. 2019. Impact of Dam Development and Climate Change on Hydroecological Conditions and Natural Hazard Risk in the Mekong River Basin, Journal of Hydrology, 579:124177.
https://www.sciencedirect.com/science/article/pii/S0022169419309126

Dataset:
1. Mekong-dams-baseline:
Dam_name->Name of the dam;
Latitude->Latitude of the dam;
Longitude->	Longitude of the dam;
Country->	Country of the dam;
Scenario->	Same with the scenario division in the Table S2;
Comm_year->	Commission year of the dam;
Agent_D->	Agent number of the dam;
Agent_Name->	Agent name of the dam;
Dam_height->	Height of the dam (in m);
SWAT_InSub->	Subbasin of the dam in the SWAT model;
Total_sto->	Total storage of the dam (in MCM);
Active_sto->	Active storage of the dam (in MCM).

2. Mekong-dams-development:
Meaning of each column in the attribute table is same with that in the “Mekong-dams-baseline” data.

3. Mekong-ecosystem-hotspots:
Name->	Name of the ecosystem hotspot;
Alphabet->	Same with the ecosystem hotspot alphabet shown in Figure 1 and Table S1.

4. SWAT-agent-sub-boundary:
GRIDCODE->	Necessary SWAT column;
Subbasin->	Subbasin ID;
Area->	Subbasin area (in m^2);
Lat->	Centroid Latitude of the subbasin;
Long_->	Centroid Longitude of the subbasin;
Elev->	Mean elevation of the subbasin (in m);
ElevMin->	Minimal elevation of the subbasin (in m);
ElevMax->	Maximal elevation of the subbasin (in m);
HydroID->	Necessary SWAT column;
OutletID->	Necessary SWAT column;
Agent_ID->	Agent ID;
Agent_name->	Agent name;

5. SWAT-mekong-river:
ARCID->	Necessary SWAT column;
GRID_CODE->	Necessary SWAT column;
FROM_NODE->	Necessary SWAT column;
TO_NODE->	Necessary SWAT column;
Subbasin->	Necessary SWAT column;
SubbasinR->	Necessary SWAT column;
