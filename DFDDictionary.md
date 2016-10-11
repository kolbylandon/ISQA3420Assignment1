Entities
*Developer-A member of the Developer class of employee 
*Manager-A member of the management class of employee

Processes
*Manage Software Package for License and Vulnerability-Scans the License Repository, then sends the results to the Results Store
*Scan for Licenses-Checks current 
*Evaluate Results-Employee evaluates the results 
*Deletion of Results-Deletion of results whe the store is too full
*Change of Licese Information-Changes made to current licenses

Data Flows
*Software Package-Package of software to be scanned and stored
*Software Package License Results-The results of the check against the License Repository
*Current Licenses-Up to date information about the licenses held by the company

Data Repositories
*Results Store-Storage for the license results
*Policy Repository-Storage for current license policy information
