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
| lon_fit | Date and Time of collection |
| lat_fit | denotes if data was collected during injection of CO<sub>2</sub> gas  |
| ele_fit | raw partial pressure of CO<sub>2</sub> at Station 1 (ppm)  |
| width | raw partial pressure of CO<sub>2</sub> at Station 2 (ppm)  |
| depth | raw partial pressure of CO<sub>2</sub> at Station 3 (ppm)  |
| dist | raw partial pressure of CO<sub>2</sub> at Station 4 (ppm)  |
| Wetland | Turbidity (NTU)  |
| Wetland_2 | Chlorophylla (ug.L)  |
| Wetland_3 | Colored Dissolved Organic Matter [parts per billion] |
| Wetland_4 | Carbon dioxide flux, unit no 1 (umole per m^2 per sec)  |
| Wetland_5 | Temperature [Celsius] at station 1 |
| CatchmentSize_ha | area draining to sample point in hectars  |
| Date | Date of sample collection |
| pCO2_ppm | Temperature (C) at station:  |
| F_CO2_umol_m2_s | Temperature (C) at station:  |
| WaterTemp_c | Temperature (C) at station:  |
| AirTemp_c | Temperature (C) at station:  |
| air_pressure_hpa | Temperature (C) at station:  |
| surface_area | Temperature (C) at station:  |
| pCO2_air_ppm | Air Temperature (c)  |
| air_pressure_atm | conductivity at station 1 (uS) |
| water_pressure_atm | conductivity at station 2 (uS) |
| pCO2_w_atm | Dissolved Oxygen at station 1 (mg/l)  |
| pCO2_air_atm |  Dissolved Oxygen at station 2 (mg/l) |
| KH_mol.l.atm |  Dissolved Oxygen at station 4 (mg/l) |
| KH_mol.m3.atm | 24-hour total precipitation [mm]  |
| Flux_mol_m2_d | 48-hour total precipitation [mm] |
| k_m_d | 72-hour total precipitation [mm]  |
| Sc | Corrected Water Level- Station 3  in meters |
| K600 | Corrected Water Level- Sensor 425 in meters |


<strong>______________________________________________________________________</strong>

- File name: **Slope_Data.csv**

*these data are used to create figures 4 & 5
  
  | Column Name | Description |
  | :--- | :---------- |
  | Distance | distance from the outlet of the wetland (meters) |
  | Syn1_071819 | Carbon dioxide partial pressure (ppm) collected on 2019-07-18 |
  | Syn2_072519 | Carbon dioxide partial pressure (ppm) collected on 2019-07-25  |
  | Syn3_072919 | Carbon dioxide partial pressure (ppm) collected on 2019-07-29  |
  | Syn4_073119 | Carbon dioxide partial pressure (ppm) collected on 2019-07-31  |
  | Syn5_080619 | Carbon dioxide partial pressure (ppm) collected on 2019-08-06  |
  | Syn6_081219 | Carbon dioxide partial pressure (ppm) collected on 2019-08-12 |
  
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

