# Beebei_EvoEco
Below is the code for the Fouilloux et al. (2023) paper about reproductive resource defense in our beloved poison frog Anamoglossus beebei!

On this repo you will find all of the information about the analysis of phytotelmata.

In the **2023_EvoEco_Beebei.Rmd** you will find the annotated code for all of the models for phytotelm choice/tadpole occurence as well as all of the script for the data visalizaiton with these associated data (Fig 2A/B and Fig 3A/B).

In the **Beebei_PoolData2023.csv** is the cleaned data .csv ready for rock and roll. 
The variable descriptions are as follows:
**Bromeliad** Individual entire plant ID
**Pool_ID** Individual ID for plant pool
**Distance** Distance in meters to nearest reference flag.
**Bearing** Orientation in direction to the nearest reference flag.
**Ref_Flag_x/y** Reference flags for grid established in the field site in Kaiteur Falls, Guyana.
**Tad_Count** Number of tadpole in each pool
**YNTad** Binary tadpole peresence
**DO** Dissolved oxygen reading of pool
**Temp** Temperature in C of pool
**PAR** Phytosynthetically active radiation above pool (see paper for measurement details)
**Full_Sun** Measurment of PAR in the full sun to control for changes in PAR with changing weather (see paper for details)
**PercPAR** Percent of PAR = (PAR/Full_Sun)*100
**logPAR** log(PercPAR)
**L_H** Cat. factor assessing leaf height 
**Goop** Cat. factor assessing mucilage in pools
**Goop_Count** Numeric assessment of mucilage in pools (0-3)
**YNGoop** Binary goop presence
**Detritus** Cat. factor assessing detritus in pools
**Water** Cat. factor assessing turbidity of pools (Clear vs. Turbid)
**Depth** Pool depth in cm
**Width** Pool width in cm
**Volume** Volume contained by pool measured in mL

