# CTX-ServiceNow-Extended
Additional subtasks to the managed *CTX-ServiceNow* package from the managed Cortex Community

The additional subtasks are:
## Change Requests
### 1. SNOW-CREATE-CHANGE
This subtask allows a Change Request to be created. It returns the Snow SysID and Change Number.
### 2. SNOW-GET-CHANGE-DETAILS
Use this subtask to retrieve information from an existing Change Request. Requires a SysID as input.
### 3. SNOW-UPDATE-CHANGE
Use this subtask to make changes to add Work Notes to existing Change Requests. Requires a SysID as input.
## CMDB CI
### 1. GET-CI-BY-ASSET-TAG
Use this subtask to get CI details by supplying just the Asset-Tag of a CI.
### 2. SNOW-GET-CI-BY-IP-ADDRESS
Use this subtask to get CI details by supplying just the IP-address of a CI.
### 3. SNOW-GET-CI-DETAILS
A more generic retrieve subtask. Requires the CI SysID as input.
### 4. SNOW-GET-CI-LOCATION
A subtask that returns location information of a CI. Requires the CI SysID as input.
## Management
### 1. SNOW-CREATE-USER
A subtask that creates a new user in ServiceNow.

# Installation Instructions
Download the Studio Package file and Import it into your Cortex Environment.
Don't forget to apply rights using the Studio Authorization module.

:thumbsup: Success! :wink:
