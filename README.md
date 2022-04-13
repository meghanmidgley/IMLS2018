# IMLS2018
Code for analyzing living and dead tree and soil carbon responses to East Woods management (burning and thinning)

Living, standing dead, and downed woody debris data was collected from all 500 IMLS stakes by AES in spring/summer 2018

Soil samples were collected by AES in 2018. Soil bulk density data was created by Michelle Catania and volunteers in 2019. Soil carbon concentration data was created by Resh Mukerjee in 2022. 

Plot locations are from a shapefile: Collections/grid_system/imls_posts. Points were converted into 8.9m radius circle polygons by Meghan Midgley in 2022. 

Burning data is from a combination of two sources: 1) A shapefile managed by Mark McKinney (Collectioned/MarKGIS/Management Unit Plans/Controlled Burn Areas.gdb --> Completed Burned Areas Final_4_5_19) and 2) the 2010 Conservation and Research Management Plan for the East Woods document created by Kurt Dreisilker. Management Units described in the Plan were delineated basted on a shapefile (Collections/Natureal Resources Management/Boundaries/New Management Units). The Plan was used to create burning records prior to 2004, and Mark's GIS was used for burning starting in 2004. Records prior to 2004 can be used for frequency assessments, but not burning season assessments (dates not accurate). These two sorces were occasionally in conflict and I used the Plan as a more reliable source of information for pre-2005 burn history. 

Thinning data is a combination of several sources: Mark's Winter Clearning geodatabase (Collections/Natural Resources/Winter Clearing/Winter Clearing.gdb --> Canopy Thinning), the Plan (details above), the SOWS shapefile (points were made into 8.9m radius circle polygons by Meghan Midgley in 2022), and a Fahey plots shapefile (points were made into 50 x 50 m square polygons by Meghan Midgley in 2022). Metadata for the SOWS project was derived from Dreisilker et al. 2014 and metadata for the Fahey plots were derived from Mary Moses's 2016 masters thesis and documents in Bob Fahey's folder on the S Drive. The geodatabase and Plan were occasionally in conflict and I used the Plan as a more reliable source of information for pre-2005 thinning history. 

**Management data is only applicable to the "woodland" areas** Woodland areas are defined in the 2008 vegetative cover type shapefile (Collections/Natural Resources Management/2008 vegetative cover type). 
