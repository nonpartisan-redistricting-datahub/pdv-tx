# pdv-tx
Partner data validation for Texas. Data Partners: PGP / MGGG. 

[Final Report](https://docs.google.com/document/d/1QFsWiIAIpEUsXorbExAe_T93_dSbkYjtE7XaeSXTbiY/edit?usp=sharing)

Note: The MGGG and PGP replication files are the same (they are duplicated to reflect the fact that the data is shared).

**Raw from source:**
- TX Shapefile (2016 General Election VTDs):
  - Online: https://data.capitol.texas.gov/dataset/archived-precincts
  - AWS: `vtd16g.zip`
- US Congressional Map (115th Congress):
  - Online: https://catalog.data.gov/dataset/tiger-line-shapefile-2016-nation-u-s-115th-congressional-district-national
  - AWS: `tl_2016_us_cd115.zip`
- TX House Map (PlanH407): 
  - Online: https://data.capitol.texas.gov/dataset/planh407
  - AWS: `planh407.zip`
- TX Senate Map (PlanS172): 
  - Online: https://data.capitol.texas.gov/dataset/plans172
  - AWS: `plans172.zip`
- TX Election Results (reported by 2016 VTDs): 
  - Online: https://data.capitol.texas.gov/dataset/historical_elections
  - `ftp_election_data_16g.zip`
- Census Data (reported by 2016 VTDs): File not publically available, posted on AWS
  - Online: n/a
  - AWS: `Pop2010_VTD_2016G.xlsx`  
  
**File Processing:**
- MGGG / PGP  File: https://openprecincts.org/tx/
- Processing and Validation Steps: `PGP_TX_replication.ipynb`
- Notes / Methodology: Comments on `PGP_TX_replication.ipynb`
