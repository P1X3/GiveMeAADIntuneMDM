# GiveMeAADIntuneMDM
All-in-one script that can be executed remotely to join device to:
* Enroll device into IntuneMDM if device is already AzureAD joined and AzureAD user is logged in (required for user context)
* Re-join device to AzureAD, and subsequntly enroll into IntuneMDM, using provisioning package
* Join device to AzureAD, and subsequntly enroll into IntuneMDM, using provisioning package

## Origin
Long ago there were 400 remote devices that were not IntuneMDM enrolled, or AzureAD joined, but did have RMM software to use this script. There was no desire to have hand-on with each of those devices.
