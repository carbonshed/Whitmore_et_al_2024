# Carbon Evasion Dynamics in a Tropical, High-Elevation, Peatland Catchment are Mediated by A Threshold in Watershed Area

## Authors: Keridwen M. Whitmore, Amanda G. DelVecchia, Elizabeth Farquhar, Gerard Rocher-Ros, Esteban Suárez, and Diego A. Riveros-Iregui


This repository serves to host data and analyses used in the research supporting the work in *Carbon Evasion Dynamics in a Tropical, High-Elevation, Peatland Catchment are Mediated by A Threshold in Watershed Area*, submitted to *Water Resources Research*.

## Purpose  
  To provide access to the data and make analyses reproducible for others. Figures 2 through 7 presented in the paper were created using R statistical software. Figure 1 is a site map created in Arc Pro (ESRI 2023) All scripts and data files for creating our figures are provided within this repository. If you have Rstudio installed on your computer, you should be able to 'fork' this repository and run it on your local computer to reproduce the anlayses in this paper without any alterations.
  
## Instructions to run this code
You can fork or simply download this repository to your local computer and open the project file *Whitmore_et_al_2024.Rproj*. We use the [here package](https://github.com/jennybc/here_here) to ensure that the code will run on any computer without having to change any file paths. 
  
## Guide to files  

### Data

- File name: **Data.csv**

*these data are used to create figures 2,3,6, & 7*

| Column Name | Description |
| :--- | :---------- |
| lon_fit | longitude corrdinate of sample, predicted by fitting a spline to GPS collected corrdinates (decimal degrees)|
| lat_fit | latitude corrdinate of sample, predicted by fitting a spline to GPS collected corrdinates (decimal degrees) |
| ele_fit | elevation of sample, predicted by fitting a spline to GPS collected corrdinates (meters)  |
| width | width of stream at sample location (centimeter) |
| depth | depth of stream at sample location (centimeter) |
| dist | sample distance from most upstream measurment (meter) |
| Wetland | name of sampled reach  |
| Wetland_2 | name of sampled reach, all tribs combined  |
| Wetland_3 | name of sampled reach, gavilan river network combined |
| Wetland_4 | name of sampled reach, mainstem split between outlet and inlet  |
| Wetland_5 | name of sampled reach, mainstem split between outlet and inlet, gavilan tribs combined |
| CatchmentSize_ha | catchment size at sample point (hectar)  |
| Date | Date of sample collection |
| pCO2_ppm | dissolved co2 (parts per million)  |
| F_CO2_umol_m2_s | co2 evasion flux, average of 2-3 measurments (umol/m2/s) |
| WaterTemp_c | Water Temperature (celcius)  |
| AirTemp_c | air temperature (celcius) |
| air_pressure_hpa | air pressure (hectopascals) |
| surface_area | surface area of stream represented by sample point (square meter)  |
| pCO2_air_ppm | CO2 concentration in the air (parts per million) |
| air_pressure_atm | air pressure (atmospheres) |
| water_pressure_atm | water pressure (atmospheres) |
| pCO2_w_atm | dissolved CO2 concentration (atmospheres)  |
| pCO2_air_atm |  CO2 at saturation (atmospheres |
| KH_mol.l.atm |  Henry's constant adjusted for water temperature (mole/L/atm) |
| KH_mol.m3.atm | Henry's constant adjusted for water temperature (mole/m3/atm)  |
| Flux_mol_m2_d | CO2 evasion flux (mole/m2/day) |
| k_m_d | CO2 gas transfer velocity (meter/day) |
| Sc | schmidt's constant |
| K600 | CO2 gas transfer velocity adjusted to the schmidt's constant of 600 (meter/day) |


<strong>______________________________________________________________________</strong>

- File name: **Slope_Data.csv**

*these data are used to create figures 4 & 5
  
  | Column Name | Description |
  | :--- | :---------- |
| lon_fit | longitude corrdinate of sample, predicted by fitting a spline to GPS collected corrdinates (decimal degrees)|
| lat_fit | latitude corrdinate of sample, predicted by fitting a spline to GPS collected corrdinates (decimal degrees) |
| ele_fit | elevation of sample, predicted by fitting a spline to GPS collected corrdinates (meters)  |
| width | width of stream at sample location (centimeter) |
| depth | depth of stream at sample location (centimeter) |
| dist | sample distance from most upstream measurment (meter) |
| Wetland_4 | name of sampled reach, mainstem split between outlet and inlet  |
| CatchmentSize_ha | catchment size at sample point (hectar)  |
| pCO2_ppm | dissolved co2 (parts per million)  |
| F_CO2_umol_m2_s | co2 evasion flux, average of 2-3 measurments (umol/m2/s) |
| Ele_sample | elevation of sample pulled from DTM (meter) |
| Ele_upstream | elevation upstream of sample from DTM (meter) |
| reach_length | gas travel distance (meter) |
| slope_m.m | slope upstream of sample point (meter/meter) |
| k_m_d | CO2 gas transfer velocity (meter/day) |
| Sc | schmidt's constant |
| K600 | CO2 gas transfer velocity adjusted to the schmidt's constant of 600 (meter/day) |
  
<strong>______________________________________________________________________</strong>

- File name: **Fig7_dataframe.csv**

*these data are used to create figure 7
  
  | Column Name | Description |
  | :--- | :---------- |
  | Eos# | EosFd unit no. |
  | Date | date of collection |
  | Flux | Carbon dioxide flux (umole per m^2 per sec) |
  | Distance From 35 | distance from the outlet of the wetland (meters) | 
  | Syn7-18 | synoptic site number, collection date July 18th | 
  | Syn7-25 | synoptic site number, collection date July 25th | 
  | Syn7-31 | synoptic site number, collection date July 31th | 
  | Syn8-6 | synoptic site number, collection date August 6th | 
  | Syn8-12 | synoptic site number, collection date August 12th | 

<strong>______________________________________________________________________</strong>
  
## script

| File Name | Type | Description |
| :------- | :--: |:---------- |
| figure_02.R | R code | figure 3 |
| figure_03.Rmd	| R markdown | figure 3 |
| figure_03.html | html | figure 3 image rendered in html |
| figure_04.R |	R code | figure 04 |
| figure_05.R |	R code | figure 04 | 
| figure_06.R |	R code | figure 07 |
| figure_07.R |	R code | figure 07 |
| figure_08.R |	R code | figure 08 |

<strong>______________________________________________________________________</strong>
  
## Points of contact  

Direct **questions about the paper** to Keridwen M Whitmore: <keridwen@email.unc.edu> or to Dr. Diego Riveros-Iregui: <diegori@email.unc.edu>

Direct **questions about the code** to:

Keridwen M Whitmore: <keridwen@email.unc.edu> 

