Entities
<ul>
  <li>Developer-A member of the Developer class of employee</li>
  <li>Manager-A member of the management class of employee</li>
</ul>
Processes
<ul>
  <li>Manage Software Package for License and Vulnerability-Scans the License Repository, then sends the results to the Results Store</li>
  <li>Scan for Licenses-Checks for current licenses</li>
  <li>Get Vulnerability Information-Checks current licence vulnerabilities</li>
  <li>Software Project License Information Request- Gets the sofware license and vulnerability request from the developer or manager and returns the software package</li>
  <li>Create and Change of License Information- Creates new license information policy or changes the current license policy</li>
  <li>Process for Create/Update- Creates new license information policy or updates the current license policy</li>
  <li>Request Policy- The Developer requests the status of the current license policy</li>
</ul>
Data Flows
<ul>
  <li>Software Package-Package of software to be scanned and stored</li>
  <li>Software Package License Results-The results of the check against the License Repository</li>
  <li>Software Package Name- The name of the software package that is being queried</li>
  <li>Vulnerability Information- Results of the software package name query against the NIST Vulnerability Database</li>
  <li>Software Package License Results- Results of the scan for license process </li>
  <li>License and Vulnerability Information- Information returned to the developer from the Manage Software Package for License and Vulnerability process</li>
  <li>Software Project License and Vulnerability Request- Request for the software project license and vulnerability</li>
  <li>Software Project License and Vulnerability Results- Results for the request of the software project license and vulnerability</li>
  <li>Query to Update Current License Policy- A query against the Policy Repository to either create new license information or update current license information</li>
  <li>Current License Request Results- Results from the Policy Repository</li>
  <li>Software Project License and Vulnerability Request- Request against the Results Store by the developer or the manager</li>
</ul>
Data Repositories
<ul>
  <li>Results Store-Storage for the license results</li>
  <li>Policy Repository-Storage for current license policy information</li>
  <li>NIST Vulnerability Database- Database for storing vulnerabilities in the software package</li>
</ul>
