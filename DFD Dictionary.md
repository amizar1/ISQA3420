## Entities
**Corporate Developer:** The person responsible for writing codes and software development

**Corporate Manager:**  The person responsible for managing the software package such as queries the license and vulnerability database, apply and modify the policy of software package

## Processes
**Software Data Management:** Receive the license and vulnerability results from License Scanner and NIST Vulnerability Database and provide the results to Corporate Developer once the request has been made. Also send the results to Licenses and Vulnerabilities Database for storage 
Scanner License: Scan the licenses that are in the software package

**Get License and Vulnerability Information:** Pulls license and vulnerability information from database and provide it to Corporate Developer and Manager
Apply new policy: Process new policy received from Corporate Manager and send it to Policy Database

**Edit or Update Policy:** Modify the policy received from Corporate Manager and send it to Policy Database

**Find Policy:**  Pulls the policy information from the Policy Database and provide the information to the Corporate Manager

## Data Flows
**Software Package:** Package that contain entire files of software codes

**Vulnerability Result:** Result from NIST Vulnerability Database of the software package

**License Result:** Result from the License Scanner of the software package

**License and Vulnerability Info Request:**  Request of license and vulnerability information of software package from Corporate Developer and Manager

**License and Vulnerability Result:**  Result of License and Vulnerability of software package from database

**Policy Info:**  Policy information of software package that has license and vulnerability result

**Policy Info Request:** Request the policy information of software package from Corporate Manager

**Policy Info Response:** Response the policy information of software package to Corporate Manager from Policy Database

## Data Stores
**NIST Vulnerability Database:** Database that maintains the vulnerabilities of all software packages

**License and Vulnerability Database:** Database that stores license and vulnerability information of the software package

**Policy Database:** Database that stores that relevant policy documents of the software package 


