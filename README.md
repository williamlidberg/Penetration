# Soil bearing capacity

## Summary
Soil disturbance near streams and lakes entails a significant risk to contaminate and impair the water quality. The risk of affecting the quality of the water is associated with soil moisture content of the soil.  Increase of soil moisture content entails increased risk of rutting damage. From a biological perspective, perennial streams are particularly sensitive. This constitutes difficulties for the forestry, especially during deforestation when soils wet up. These difficulties are expected to increase as a consequence of the prediction that, via global warming, the future will hold shorter winters and increased rainfall. Newly produced wet-area-maps might give managers a tool to avoid soil damage. Field data was collected across different regions of Sweden to try to investigate if the new wet area map can be used to predict soil bearing capacity.

## Research questions
 Is there a significant difference between the field estimated soil moisture (soil_class in the table) and the SLU soil moisture map (Classified in the table)?
Is soil bearing capacity significantly different in the different soil classes?
Can the wet area maps be used to plan forestry operations to avoid rutting near streams?

## Data
Sample plots were laid out along transects crossing streams and ground soil bearing capacity, along with other parameters correlated to ground bearing capacity, were collected for each sample plot. Field data were linked to the WAM via GPS-coordinates belonging to the respective sample plot. This data can be downloaded here: https://github.com/williamlidberg/Penetration (Links to an external site.)

These are the most relevant columns to look at: 

Soil_class

O_horizon

Kpa5

Kpa10

Kpa15

Prob

Classified




Name = Plot ID
Northing = Y coordinate in Swereff 99 TM
Easting = X coordinate in Swereff 99 TM
Elevation = Elevation from GPS unit. Not very accurate
Waypoint = Same as plot ID
Soil_moist = Messured soil moisture. Not accurate
Average_so = Average penetration
F5cm = Penetration depth after 5 bonks
F10cm = Penetration depth after 10 bonks
F15 = Penetration depth after 15 bonks
Soil_class = Soil moisture classified in the field based on vegetation patterns. 1: Dry, 2: Mesic, 3:Mesic-Moist, 4: Moist, 5: Wet
O_horison = Messured O horizon in cm
Kpa5 = Cone Penetration index based on 5 bonks
Kpa10 = Cone penetration index after 10 bonks
Kpa15 = Cone penetration index after 15 bonks
Prob = Probability from SLU Soil moisture map. 0 % is dry and 100 % is wet.
Classified = Values extracted from the classified version of the SLU Soil moisture map.
Kpa5, Kpa10 and Kpa15 are the most relevant data collected in the field. These are what we want to investigate. you can either use Kpa15 or average them together.

p Ground pressure [Pa]

W Weigth [N] (40.45N)

h Height [cm] (40 cm)

n number of drops 5, 10 and 15

Q Weight of probe [N] (14,17 N)

A Basal area of cone [m2] (40 mm)

More maps can be found here: https://maps.slu.se (Links to an external site.)




## References
Bodin, A., 1999. Development of a tracked vehicle to study the influence of vehicle parameters on tractive performance in soft terrain. Journal of Terramechanics, Volym 36, pp. 167-181.

Anneli M.Ågren Johannes Larson Siddhartho Shehar Paul HjalmarLaudon WilliamLidberg. 2021.Use of multiple LIDAR-derived digital terrain indices and machine learning for high-resolution national-scale soil moisture mapping of the Swedish forest landscape. https://www.sciencedirect.com/science/article/pii/S0016706121003608
