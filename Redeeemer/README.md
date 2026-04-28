# Redeemer

## Methodology
1. Enumeration (Port scanning)
2. Service Identification (Redis)
3. Authentication (unauthorized access)
4. Data Extraction


## Tools Used
1. Nmap
2. Redis CLI
   
## Key Concepts
1. Open Redis service
2. No authentication required
3. Database enumeration
4. Retrieving stored keys


Summary
Redeemer focuses on exploiting an exposed Redis service without authentication. By connecting directly to the service, it is possible to enumerate keys and extract sensitive data, leading to flag retrieval.
