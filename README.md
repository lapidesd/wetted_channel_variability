# wetted_channel_variability

Code supplement for Lapides et al. (2021). Publication explores how flow regime and network hydraulic scaling co-determine temporal variability in the surface expression of wetted channels. Data for this project are stored in a HydroShare repository: https://www.hydroshare.org/resource/b5e17ec502154fc5ac06cfe2a65b1267/. This repository includes the code generated for this work and the streamflow data for the study sites. Files include:

*  catchment_metadata.csv: Metadata about study sites. Columns include gauge_sta_ID (station ID for the site), gauge_sta_name (name of the site), gauge_sta_data_stew (data steward agency for site), gauge_sta_lat (Latitude of streamflow gage for site), gauge_sta_lon (Longitude for streamflow gage for site), study_name (name of publication where wetted channel data is presented), study_yr, studyauthors, catch_name (name of catchment), catch_data_end (end of wetted channel data), catch_data_start (start of wetted channel data), catch_area_study, catch_area_data_stew, catch_Bedrock, catch_Veg, chat_cli (Koppen_Geiger climate time for catchment site), catch_precip_an, catch_alpha (alpha in power law relating streamflow and wetted channel length), catch_beta (beta in power law relating streamflow and wetted channel length), batch_beta_se, bluelinepersist_intermit_len (length of intermittent stream in catchment from USGS blue line map), blueline_persist_intermit_dd (drainage density of intermittent stream in USGS blue line map), blueline_persist_intermit_dd, blueline_persist_lenE, blueline_persist_ddE.
*  hydrographs: directory containing streamflow data for study sites
*  Wetted_Channel_Analysis-github.ipynb: Jupyter Notebook with code to reproduce figures and analyses in study


Lapides, Dana A., et al. "Variability of stream extents controlled by flow regime and network hydraulic scaling." Hydrological Processes 35.3 (2021): e14079.
