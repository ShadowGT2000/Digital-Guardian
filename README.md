# Digital-Guardian
# Here is a collection of Jamf Pro scripts to assist in the Management of Digital Guardian in your enviroment:

/EA

[DG-Binary-Build] & [DG-Kernel-Build]
What: Provides you with the build numbers for Digital Guardian.
Why : The Kernel and the Binary build must match or your agents will not report properly.
Note: Only the build is captured here when building smart groups make sure you have [DG-Version]

[DG-Binary-Load] & [DG-Kernel-Load]
What: Informs you if the agent and kernel is loaded for Digital Guardian.
Why : Both the Binary and the Kernel need to be loaded for the agent to work properly and communicate.
Note: Best for use with a remediation script or workflow, will submit a scrubbed version at a later date.

[DG-Version]
What: Provides you with the version number for the agent for Digital Guardian.
Why : Provides you with the version number for the agent for Digital Guardian. :)
Note: Because :)

/Scripts

[Digital Guardian - Health Check]
What: Automates the check and repair of a Digital Guardian agent. 
Why : Because doing it manually is tedious
Note: Will have to create a scrubbed version for GitHub, will come later.

