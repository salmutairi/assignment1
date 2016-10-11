
#Data Flow

**Software Package-** It is the set of apllications and files sent by the developer to manage packages.

**Software Package License and Vulnerability Results-** The resultant package that contains the license and vulenrability information from manage packages to the developer.

**Vulnerabilites for Package-** The data store for NST vulnerability can send this package to manage packages which contains information about different packages.

**Software Package Name-** The information from manage package sent to the NST Vulnerability datastore contains the software package name.

**Software Package License Information-** The Scan license send the this information to manage packages.

**Software Package-** The manage package sends this package details to for scanning the license to scan license.

**Software Package License and Vulnerability Results-** From the manage packages to software package license and vulnerability datastore.

**Data Request-** Summerized project data sends this request to software package license and vulnerability datastore.

**Summarized Information-** The Software package license and vulnerability datastore sends this information to the summerized project data.

**Project Information Request-** Developer can request this to the summerized project data.

**Summarized Project Information-** Summerized project data sends it to developer for any request.

**Policy Data Request-** Developer asking for the data to policy issues.

**Summarized Policy Information-** Policy issues gives the requested data to developer.

**Summarized Policy Information-** Policy issues gives the requested information to manager.

**Policy Information Request-** Manager sends the request for the information to policy issues.

**Project Information Request-** Manager sends to summerized project data.

**Summarized Project Information-** Summerized project data sends to Manager for each request.

**Policy Database Request-** The policy issues asks for the database details to policy database.

**Granular Line Items-** Policy database gives details of the database to policy issues.

**Data Operations-** The Policy operations send to the policy database for operations

**Data Operations Submits-** Policy database sends to policy operations to happen.

**Policy Data Change Request-** Manager send to the policy operations.

**Policy Data Change Confirmation-** The policy operations confirms the change to manager.


#Porcesses

**Manage Packages-** Manages the vulnerability and license infrimation for each software package.

**Scan For Licenses-** Check for licenses for the software packages sent to it by manage packages.

**Summarize Project Data-** Contains the information about the project, software packages used and the license and vulnerability details for each software package.

**Policy Issues-** It handles all the requests sent by developer or manager to policy database and sends back the information accordingly.

**Policy Operations-** It tackes all the operations taking place over the data in policy database.

#Entities

**Developer-** Responsible for creating, maintaining the system.

**Manager-** Responsible for organizing and managing the project and system within the limit of resources.

#Database Store

**Policy Database-** Conatins all the information regarding the policy.

**Software Package License and Vulnerability Database-** Contains the information about the licenses and vulnerability for software packages.

**NST Vulnerability DB-** The vulnerability data with reference to each software package.
