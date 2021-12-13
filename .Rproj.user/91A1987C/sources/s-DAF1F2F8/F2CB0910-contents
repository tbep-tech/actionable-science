library(tbeptools)
library(here)
library(tidyverse)

# get wq epc data ---------------------------------------------------------

# file path
xlsx <- here('data/epcdata.xlsx')
epcdata <- read_importwq(xlsx, download_latest = T)

save(epcdata, file = here('data/epcdata.RData'))

file.remove(xlsx)

# get phyto epc data ------------------------------------------------------

# file path
xlsx <- here('data/phyto_data.xlsx')
phydata <- read_importphyto(xlsx, download_latest = T)

save(phydata, file = here('data/phydata.RData'))

file.remove(xlsx)
