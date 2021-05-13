# vest-tx-2016

Our final validation report for this dataset is available [here](https://redistrictingdatahub.org/dataset/vest-2016-texas-precinct-and-election-results/). 

We do not have the raw data sources available on this Github due to file constraints, but we are happy to share them if needed. 

Please reach out to info@redistrictingdatahub.org to reach our support team if you have any questions.

## Raw from source:
- VEST file (2016): 
  - Online: https://dataverse.harvard.edu/file.xhtml?fileId=3184154&version=53.0 
  - AWS: `tx_2016/` (available upon request)
- TX Shapefile (2016 General Election VTDs):
  - Online: https://data.capitol.texas.gov/dataset/archived-precincts
  - AWS: `vtd16g/` (available upon request)
- TX Election Results (reported by 2016 VTDs): 
  - Online: https://data.capitol.texas.gov/dataset/historical_elections
  - `ftp_election_data_16g/`
  
## File Processing:
- Processing and Validation Steps: `VEST_TX_2016_replication.ipynb`
