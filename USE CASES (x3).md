#Use Case

#Use Case 1:

**Title:** Retrieving the license and vulnerability information for a software package

**Primary Actor:** Developer

**Goal in Context:** Successfully getting information about the software package's license and vulnerability.

**Stakeholders:** Developer, Manager

**Preconditions:** Software package license and vulnerability DB have the information about the licenses and vulnerabilities for the software packages.

**Main Success Scenario:** The developer recieves the information about the software package with licenses and vulnerabilities.

**Failed end Conditions:** Developer does not recieves the information.

**Trigger:** The developer sends request to the manage packages to fetch the information.

#Use Case 2:

**Title:** Get the summarized project information to compare with the policy information.

**Primary Actor:** Manager

**Goal in Context:** Fetch the information from summarized project data and policy database.

**Stakeholders:** Manager, Developer

**Preconditions:** Policy database having all records for the policies and summarized project data contains all information about the project.

**Main Success Scenario:** Manager recieving information from both the end.

**Failed end Conditions:** Manager not recieving information from either one of the database or even from both.

**Trigger:** Manager requesting for policy inforamtion and project information.

#Use Case 3:

**Title:** Operating on the policy data

**Primary Actor:** Manager

**Goal in Context:** To update the data stored in policy database.

**Stakeholders:** Manager, Developer.

**Preconditions:** Policy database contains the data to be updated.

**Main Success Scenario:** Manager successfully able to update the information.

**Failed end Conditions:** Update does not happen.

**Trigger:** Manager sending policy data change request to policy operations.
