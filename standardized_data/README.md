# Spatiotemporal patterns of salmon winter habitat usage in the Northeast Pacific uncovered by environmental DNA

Dataset DOI: 10.5061/dryad.c2fqz61nn

## **Files and variables**

File: ASV.csv

Variables: 

* sample_id(_tech_rep): Sample ID to match the metadata. "_A" , "_B" suffix denotes technical replicates
* asv: Amplicon sequence variant sequence
* occurrence_count: Number of occurrences of asv in sample
* forward_primer: Forward primer used to amplify the amplicon
* reverse_primer: Reward primer used to amplify the amplicon
* taxon: Operational taxonomic unit assigned to the asv
* reads_amplicon_sample: Total number of reads generated in sequencing for this amplicon and sample combination

File: sample_metadata.csv

Variables:

* sample_ID: Sample ID
* vessel: Sampling vessel
* doy: Day of year 2022
* method: Collection method
* method_detail:  Collection method detail
* collection_system: Collection method system
* filt_sys: Filtration system
* sample_depth_m: Sampling depth
* latitude: Latitude
* longitude: Longitude
* filt_material: Material of filtration membrane
* filter_type: Filter type
* filter_pore_size_u: Filter pore size in micron
* cruise_program: Cruise program
* sst: Sea surface temperature (C); NA values due to cloud cover obstructing satellite observations or for control samples
* ssta: Sea surface temperature anomaly (K); NA values due to cloud cover obstructing satellite observations or for control samples
* sla_sla: Sea level anomaly (m); NA values due to cloud cover obstructing satellite observations or for control samples
* sla_u: Currents: absolute geostrophic velocity : Zonal Component, m s-1; NA values due to cloud cover obstructing satellite observations or for control samples
* sla_v: Currents: absolute geostrophic velocity : Meridian Component, m s-1; NA values due to cloud cover obstructing satellite observations or for control samples
* chl_prod: Productivity (Net Primary Productivity Of Carbon, mg C m-2 day-1); NA values due to cloud cover obstructing satellite observations or for control samples
* sla_eke: Eddy Kinetical Energy, m2 s-2; NA values due to cloud cover obstructing satellite observations or for control samples
* is_field_control: Sample is a field control
* is_lab_control: Sample is a lab control

### Access information

Data was derived from the following sources:

[https://coastwatch.pfeg.noaa.gov/erddap/griddap/jplMURSST42.html](https://coastwatch.pfeg.noaa.gov/erddap/griddap/jplMURSST42.html)

[https://coastwatch.pfeg.noaa.gov/erddap/griddap/nesdisSSH1day.html](https://coastwatch.pfeg.noaa.gov/erddap/griddap/nesdisSSH1day.html)

[https://coastwatch.pfeg.noaa.gov/erddap/griddap/productivity_viirs_snpp_daily.html](https://coastwatch.pfeg.noaa.gov/erddap/griddap/productivity_viirs_snpp_daily.html)
