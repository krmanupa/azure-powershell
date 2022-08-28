# Overall
This directory contains the service clients of Az.Automation module.

## Run Generation
In this directory, run AutoRest:
```
autorest.cmd README.md --version=v2
```

### AutoRest Configuration
> see https://aka.ms/autorest

``` yaml
csharp: true
clear-output-folder: true
reflect-api-versions: true
openapi-type: arm
azure-arm: true
license-header: MICROSOFT_MIT_NO_VERSION

title: AuotmationHWGManagementClient
```


### 
``` yaml 
input-file:
  - https://github.com/Azure/azure-rest-api-specs/blob/main/specification/automation/resource-manager/Microsoft.Automation/stable/2022-02-22/hybridRunbookWorkerGroup.json 

output-folder: Generated

namespace: Microsoft.Azure.Management.Automation
```