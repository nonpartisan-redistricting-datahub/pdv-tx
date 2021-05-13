# mggg-tx

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/mggg-texas-precincts-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.


Note: The MGGG and PGP replication files are the same (they are duplicated to reflect the fact that the data is shared).

**Raw from source:**
- TX Shapefile (2016 General Election VTDs):
  - Online: https://data.capitol.texas.gov/dataset/archived-precincts
  - AWS: `vtd16g.zip`
- US Congressional Map (115th Congress):
  - Online: https://catalog.data.gov/dataset/tiger-line-shapefile-2016-nation-u-s-115th-congressional-district-national
  - AWS: `tl_2016_us_cd115.zip` (available upon request)
- TX House Map (PlanH407): 
  - Online: https://data.capitol.texas.gov/dataset/planh407
  - AWS: `planh407.zip` (available upon request)
- TX Senate Map (PlanS172): 
  - Online: https://data.capitol.texas.gov/dataset/plans172
  - AWS: `plans172.zip` (available upon request)
- TX Election Results (reported by 2016 VTDs): 
  - Online: https://data.capitol.texas.gov/dataset/historical_elections
  - `ftp_election_data_16g.zip`
- Census Data (reported by 2016 VTDs): File not publically available, posted on AWS
  - Online: n/a
  - AWS: `Pop2010_VTD_2016G.xlsx` (available upon request)
  
**File Processing:**
- MGGG / PGP  File: https://openprecincts.org/tx/
- Processing and Validation Steps: `mggg-tx.ipynb`, `pgp-tx.ipynb`
- Notes / Methodology: Comments on `mggg-tx.ipynb`, `pgp-tx.ipynb`
