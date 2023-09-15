# Cars24_used_cars_data_analysis_python

In this Python project, we conducted web scraping on Cars24 to gather data on used cars from five different cities: Hyderabad, Delhi, Mumbai, Bangalore, and Chennai. We extracted information such as Car Name, Model, Gear, Price, EMI, Location, and Features by identifying HTML tags and class names. Afterward, we carried out feature engineering to extract specific attributes like Car Brand and Model Year from the Car Name field and Driven (Kms), Ownership, and Fuel from the Features field. Subsequently, we cleaned the data using regular expressions and saved it in a CSV file. Finally, we conducted data analysis on the dataset to derive insights from the collected information.

### The key findings include:

- The availability of cars in 'Delhi'(1678+) is the highest among other 4 cities.
- Compared to other 4 cities 'Chennai'(554+) has less available cars.
- 'Maruti' brand cars are widely available with a count of around 1919 cars in all the cities, followed by Hyundai(1191), Honda(604).
- Most of the cars runs with 'Petrol' with a count of 4014.
- High budget car among all cities:
   - Tata XZA PLUS GOLD (2212000/-), 2022 Model, available in Bangalore. 
- Low budget car among all cities:
   - Maruti LXI (121000/-), 2010 Model, available in Delhi.
 
<b> Hyderabad City

- Most available brands - Maruti(300+), Hyundai(170+), Honda(55+), Tata(45+), Renault(35+).
- Cars availability - Petrol(593), Diesel(111), CNG(4), LPG(1).
- Recent year models availability - 2010(11), 2011(11), 2012(30), 2013(54), 2014(35), 2015(38), 2016(79), 2017(103), 2018(118), 2019(85), 2020(50), 2021(69), 2022(24), 2023(2).
- Availability based on Gear - Automatic(155), Manual(554).
- High Budget car - Tata XZ PLUS 2.0L (1965000/-), 2022 Model.
- Low Budget car - Hyundai GL (178000/-), 2010 Model.

<b> Delhi City

- Most available brands - Maruti(710+), Hyundai(400), Honda(230+), Renault(80+).
- Cars availability - Petrol(1392), Diesel(112), CNG(164)
- Recent year models availability - 2010(72), 2011(101), 2012(56), 2013(80), 2014(112), 2015(127), 2016(179), 2017(225), 2018(248), 2019(222), 2020(104), 2021(115), 2022(35), 2023(2).
- Availability based on Gear - Automatic(265), Manual(1423).
- High Budget car - Toyota 2.8 ZX AT 7 STR (2010000/-), 2019 Model.
- Low Budget car - Hyundai GLS (154000/-), 2011 Model.

<b> Mumbai City

- Most available brands - Maruti(263), Hyundai(159), Honda(103), Tata(37).
- Cars availability - Petrol(503), Diesel(83), CNG(76).
- Recent year models availability - 2010(7), 2011(13), 2012(27), 2013(33), 2014(48), 2015(75), 2016(87), 2017(123), 2018(71), 2019(69), 2020(39), 2021(49), 2022(21), 2023(0).
- Availability based on Gear - Automatic(190), Manual(472).
- High Budget car - Hyundai PLATINUM 1.5 MT 7 STR (1756000/-), 2021 Model.
- Low Budget car - Honda V MT (227000/-), 2012 Model.

<b> Bangalore City

- Most available brands - Maruti(480+), Hyundai(335+), Honda(140+), Renault(90+).
- Cars availability - Petrol(1059), Diesel(204), CNG(5).
- Recent year models availability - 2010(36), 2011(36), 2012(56), 2013(60), 2014(86), 2015(131), 2016(187), 2017(195), 2018(158), 2019(103), 2020(99), 2021(84), 2022(36), 2023(2).
- Availability based on Gear - Automatic(339), Manual(929).
- High Budget car - Tata XZA PLUS GOLD (2212000/-), 2022 Model.
- Low Budget car - Nissan XL PETROL (234000/-), 2010 Model.

<b> Chennai City

- Most available brands - Maruti(163), Hyundai(126), Honda(71), Tata(45).
- Cars availability - Petrol(467), Diesel(82), CNG(5).
- Recent year models availability - 2010(3), 2011(6), 2012(14), 2013(20), 2014(24), 2015(33), 2016(109), 2017(83), 2018(64), 2019(65), 2020(42), 2021(59), 2022(30), 2023(2).
- Availability based on Gear - Automatic(119), Manual(435).
- High Budget car - Tata HexaVaricor 400 XT (1801499/-), 2019 Model
- Low Budget car - ChevorletSparkLS 1.0 (171799/-), 2011 Model

<b> The above data in conclusion may change upon time to time because the data in the website is not static.
