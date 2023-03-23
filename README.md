# digital-fuesim-manv-public-test-scenarios

Public test scenarios for the Digital Fuesim MANV project.

The subfolder migration-test-scenarios contains test scenarios that should be migratable. Please only put folders in that folder. Theese folders should contain the state version of the exports in that folder. The folder may only contain exercise exports as JSON files with the state version that is stated in the folder. Files named starting with EXCLUDE-FROM-TEST will not be tested.
Please use a name that describe what happened in the scenario and add a -complete or -current at the end depending on whether the 
export was a full export or an export of the current state.
