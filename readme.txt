This file contains an overview of the structure of the data which corresponds to the manuscript:

Pollinator Community Assembly Tracks Changes in Floral Resources as Restored Hedgerows Mature in Agricultural Landscapes

Claire Kremen, Leithen K M'Gonigle, Lauren C Ponisio

There are two files:

--------------------------------------------------
1. "date_level.csv" - contains data for data-level analyses

SiteCode - site identifier
Date - sample date
SiteStatus - site status at that date
ypr - years since restoration
sp.abun - species abundance
sp.chao1 - richness using the chao1 estimator
sp.shan - species shannon diversity
sp.evar - species evenness using the evar metric
sp.rich - measured species richness
VegRichness - vegetative species richness
VegDiversity - vegetative species diversity (see manuscript for details)
BareGround - a measure of the abundance of bare ground
DeadWood - a measure of the abundance of dead wood
Natural - natural cover (see manuscript for details)
--------------------------------------------------

--------------------------------------------------
2. "year_level.csv" - contains data for year-level analyses (namely, functional dispersion).

SiteCode - site identifier
Year - sample year
SiteStatus - site status within that year
ypr - years since restoration
sp.abun - species abundance
sp.chao1 - richness using the chao1 estimator
sp.shan - species shannon diversity
sp.evar - species evenness using the evar metric
sp.rich - measured species richness
VegRichness - vegetative species richness
VegDiversity - vegetative species diversity (see manuscript for details)
Natural - natural cover (see manuscript for details)
f.FDis - functional dispersion, as calculated using the "FD" package (see manuscript for details)
--------------------------------------------------
